# Api_CRUD-REST
 Aplicação CRUD, usando o serviço de rotas da Arquitetura REST.


 Dependências usadas: Nodemon, Express e Border-parser

 Foi utilizada a ferramenta Postman para testar os serviços e manipular as requisições pelas rotas.
 
 
 
 ![Postman-print](https://github.com/mtsgreat/Api_CRUD-REST/blob/master/postan-img.png)



Utilização, baixar e instalar a ferramenta Postman.


Na aba de URL colocar o endereço: http://localhost:3003/produtos.


<br >
<br >
<br >
<br >





Testando o CRUD:

**Adicionando produtos**

1 - Mudar a rota para POST

2 - Selecionar Body

3 - Selecionar o opção x-www-form-urlencoded

4 - Adicionar campos com os seus valores

5 - depois Send (enviar)

<br >
<br >
<br >



**Listando todos os produtos** 

Basta apenas mudar o tipo de requisição para GET, e depois enviar o Send

<br >
<br >
<br >




**Pegar produto com um Id específico**

Tipo da requisição GET, exemplo: http://localhost:3003/produtos/1


<br >
<br >
<br >



**Alterando valor de um Id específico**

Mudar o tipo de requisição para PUT

Especificar o id do produto que quer alterar, exemplo: http://localhost:3003/produtos/1
e preencher os novos valores, sendo o mesmo passo do incluir produto.


<br >
<br >
<br >



**Excluido produto de um Id específico**

Mudar a requisição para DELETE, e informar o ID que deseja apagar, exemplo: http://localhost:3003/produtos/1


