## Código em python para validar a bandeira de uma cartão.

```import re

def validar_luhn(numero):
    numero = re.sub(r"\D", "", numero)
    soma = 0
    reverso = numero[::-1]
    for i, digito in enumerate(reverso):
        n = int(digito)
        if i % 2 == 1:
            n *= 2
            if n > 9:
                n -= 9
        soma += n
    return soma % 10 == 0

def identificar_bandeira(numero):
    numero = re.sub(r"\D", "", numero)
    if not validar_luhn(numero):
        return "Número de cartão inválido"

    if re.match(r"^4", numero):
        return "Visa"
    elif re.match(r"^5[1-5]", numero):
        return "MasterCard"
    elif re.match(r"^3[47]", numero):
        return "American Express"
    elif re.match(r"^6(?:011|5)", numero):
        return "Discover"
    elif re.match(r"^6(?:0[0-5]|6|8)", numero):
        return "Diners Club"
    elif re.match(r"^35(2[89]|[3-8][0-9])", numero):
        return "JCB"
    elif re.match(r"^6062[0-9]", numero):
        return "Hipercard"
    elif re.match(r"^2014|^2149", numero):
        return "EnRoute"
    elif re.match(r"^8699", numero):
        return "Voyager"
    elif re.match(r"^50[0-9]", numero):
        return "Aura"   
    else:
        return "Bandeira desconhecida"

# Exemplo de uso
numero_cartao = input("Digite o número do cartão (com ou sem formatação): ")
print(identificar_bandeira(numero_cartao))```
