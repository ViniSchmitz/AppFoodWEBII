# App Food

# Meu Projeto

## Instalação 

1. Tenha o docker instalado em sua maquina.

2. Clone esse repositorio utilizando o comando` git clone "link do repositorio"`.

3. Utiliza-se o comando` cd "nome do projeto"` para navegar ate o diretorio do projeto.

4. Utiliza-se `npm install`, para instalar as dependências do projeto.

## Configuração do docker 

1. `docker-compose` up-d: Inicia o docker para rodar os contêineres necessarios. 

2.`docker pa`: para certificar-se que os contêineres estejam em execução.


Verifique se todos os contêineres necessários estão listados e em um estado "UP" ou "Running".

3. Se for necessário, ajuste as configurações do Docker no arquivo `docker-compose.yml`.

## Inserindo dados com o Insomnia ou o Postman

1. Abra o Insomnia ou o Postman em sua máquina, caso não tenha instala-os 

2. Crie uma nova solicitação HTTP para enviar os dados para a API.

3. `POST http://localhost:8000/api/dados`
utiliza-se oara definir a URL da solicitação para o endpoint correto.

4. Configure os parâmetros e o corpo da solicitação de acordo com a API

5. Envie a solicitação para inserir dados no aplicativo.

6. Verifique a resposta da API para garantir que os dados foram inseridos certos.

7. Repita os passos 3 e 6, se for necessario inserir mais dados ou testar diferentes endpoinsts da API

8. Podemos usar o Insomnia ou Postman para fazermos solicitações GET, PUT, DELETE ente outros dependendo da funcionalidade da API utilizada.
