![folder](https://github.com/Flavio-Vicentini/gostack-primeiro-projeto-node/blob/master/assets/to_readme/folder_gostack.png)
# Desafio GoFinancesApp
Projeto desenvolvido para treinar os conhecimentos adquiridos do BootCamp GoStack da RocketSeat.A aplicação tem a finalidade consumir uma API desenvolvida no bootcamp GoStack e listar todas as transações financeiras do banco de dados, assim como permitir o envio de arquivos CSV para criação das transações.  

O desafio era implementar as seguintes rotas:

1. Listar as transações da sua API: Sua página Dashboard deve ser capaz de exibir uma listagem através de uma tabela, com o campo title, value, type e category de todas as transações que estão cadastradas na sua API.
2. Exibir o balance da sua API: Sua página Dashboard, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.
3. Importar arquivos CSV: Na sua página Import, você deve permitir o envio de um arquivo no formato csv para o seu backend, que irá fazer a importação das transações para o seu banco de dados.



E assim passar nos testes automatizados:

- *should be able to list the total balance inside the cards*: Para que esse teste passe, sua aplicação deve permitir que seja exibido na sua Dashboard, cards contendo o total de income, outcome e o total da subtração de income - outcome que são retornados pelo balance do seu backend.
- *should be able to list the transactions*: Para que esse teste passe, sua aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do seu backend.
- *should be able to navigate to the import page*: Para que esse teste passe, você deve permitir a troca de página através do Header, pelo botão que contém o nome Importar.
- *should be able to upload a file*: Para que esse teste passe, você deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de import, e que seja possível exibir o nome do arquivo enviado para o input.

---

## Features

*ReactJs* -
*Typescript* -
*Multer* -
*ESLint* -
*Prettier*
