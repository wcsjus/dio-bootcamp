
**Este laboratório tem como objetivo praticar o processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure. Como entregável, o desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações**


Loguei no Portal do Azure e selecionei “Bancos de dados SQL”. Após isso, cliquei em “Criar Banco de dados SQL”
![image](https://github.com/user-attachments/assets/20ae9b4b-7dda-49c4-8331-24f414fa1520)

Na tela que se segue, cloquei em “Apply offer” para usar o Azure SQL Database for free.
Minha assinatura “Azure subscription 1” já estava selecionada.
![image](https://github.com/user-attachments/assets/efe5b352-6637-4ff1-86c1-291eacb568c5)

Selecionei meu grupo de recursos “grupo-01” (criado anteriormente na tarefa de máquina virtual)
![image](https://github.com/user-attachments/assets/84c67d10-0206-43d3-8914-eda5e166b9b1)

Forneci o nome do meu banco de dados e, como não tinha um servidor previamente criada para essa operação, cliquei em “Criar novo” (exemplificado adiante). O nome do servidor criado ficou “srv-bdsql-a”.
![image](https://github.com/user-attachments/assets/d2c98d27-626a-486f-ad41-b4a94a61924f)

Na tela de criação do servidor, precisei entrar com o nome do servidor e a localização, no caso, (US) West US2. 
Obs: **ele não deixou criar na região padrão informando que minha licença não tinha direito.**

Para autenticação, coloquei para usar Autenticação SQL.
![image](https://github.com/user-attachments/assets/ed510fd3-3929-44c3-ace8-8e78132a55d3)

Deixei as demais opções como a padrão.
![image](https://github.com/user-attachments/assets/9d951738-dea7-44d8-84e0-42c246371131)

Cliquei em Revisar e Criar. Após alguns segundos,  a tela informando que a implantação foi concluída apareceu.
![image](https://github.com/user-attachments/assets/ebd8154a-3e0d-48db-b5af-259c2ab0597e)


