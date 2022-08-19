# DATABASE EXPERIENCE E-COMMERCE
## Projeto pratico com a criacao de um banco de dados relacional desenvolvido como atividade avaliativa do Bootcamp DATA BASE EXPERIENCE DIO.

### Visando tornar o projeto compativel com o conceito de Bancos de Dados, utiliza-se as bibliotecas alembic e sqlalchemy para o deploy automatico e controle de versionamento do modelo fisico do banco de dados.

### Utiliza-se como SGBD padrao o Banco de Dados Postgresql.

 # Representação textual seria:

Tabela Clientes (ID Cliente, Nome, CPF, RG, Email, etc)

Exemplo de Modelo Conceitual
Figura 1. Exemplo de Modelo Conceitual


![image](https://user-images.githubusercontent.com/107506717/185693789-218e3461-165d-4cfe-a52f-61b351f0cbb6.png)

Já na etapa de modelo lógico devemos entrar em detalhes técnicos sobre cada entidade a ser mapeada e relacionada, tais como nomenclaturas, padrões e definições de chaves (primárias e estrangeiras). Nesse modelo, representamos graficamente a estrutura lógica de entidades e seus relacionamentos entre si, como mostra a Figura 2.

![image](https://user-images.githubusercontent.com/107506717/185693910-9104b0fc-26fc-4f2f-b6b3-5b520a6f4738.png)


Exemplo de Modelo Lógico
Figura 2. Exemplo de Modelo Lógico, representando Relacionamentos entre algumas Entidades
Por fim, no modelo físico devemos definir a estrutura final que será utilizada, levando em considerações limitações do SGBD, tipagem de dados a ser utilizada, e as definições campo por campo (atributo). Como resultado, temos a representação do esquema de armazenamento físico das informações, assim como mostra a Figura 3.

Exemplo de Modelo Físico da entidade Cliente


![image](https://user-images.githubusercontent.com/107506717/185693990-a6732558-28cc-42c9-b767-5665a5713436.png)

Figura 3. Exemplo de Modelo Físico da entidade Cliente.
