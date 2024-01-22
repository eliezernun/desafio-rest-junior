# Desafio de Desenvolvimento - Java Spring Boot e Vue.js

## Contexto
Você está responsável por desenvolver um sistema de manutenção de clientes que requer integração com uma API externa para obter informações adicionais, como o CEP do cliente a partir da API ViaCEP. O backend deve ser construído em Java com o framework Spring Boot, utilizando JDBC para persistência em um banco de dados local, e o gerenciamento de dependências com Maven. O frontend deve ser desenvolvido em Vue.js 3, utilizando o conceito de CRUD para operações na API.

### Backend (Java Spring Boot)
1. Crie uma entidade "Cliente" com os seguintes campos: id (autoincremento), nome, sobrenome, email, telefone e CEP.
2. Implemente um repositório para a entidade Cliente usando JDBC para persistência no banco de dados local.
3. Crie um serviço para realizar as operações CRUD na entidade Cliente.
4. Configure a integração com a API ViaCEP para buscar informações do endereço a partir do CEP fornecido pelo cliente. Utilize a biblioteca `RestTemplate` para fazer a requisição.
5. Adicione validações necessárias nos campos da entidade Cliente, como validação de email e formato do telefone.

### Frontend (Vue.js 3)
1. Crie um formulário para adicionar novos clientes, considerando todos os campos necessários, incluindo a busca do CEP.
2. Implemente uma tabela para exibir a lista de clientes cadastrados, permitindo a edição e exclusão de cada registro.
3. Utilize componentes Vue.js adequadamente para organizar o código e manter a reutilização.
4. Integre a interface do usuário de forma responsiva e amigável, utilizando o Vue Router para navegação entre as páginas da aplicação.
5. Implemente uma página de detalhes do cliente que exiba todas as informações do cliente, incluindo os dados obtidos da API ViaCEP.

### Requisitos Gerais
1. Utilize o Maven para gerenciar as dependências no backend.
2. Utilize o Vue CLI para criar e gerenciar o projeto Vue.js.
3. Utilize JDBC para persistência de dados no banco de dados local.
4. Mantenha um código limpo, organizado e seguindo as melhores práticas de programação.
5. Compartilhe o código-fonte em um repositório no GitHub.
6. Inclua instruções claras sobre como executar a aplicação localmente.

## Avaliação
O desenvolvedor será avaliado com base na implementação funcional do sistema, boas práticas de codificação, a correta manipulação dos dados do cliente, a integração com a API externa, a persistência de dados no banco de dados local e a usabilidade do frontend. Além disso, a capacidade de seguir as instruções e a qualidade geral do código serão consideradas na avaliação.

**Observação:** Este desafio tem como objetivo avaliar o conhecimento e habilidades do desenvolvedor júnior em Java Spring Boot e Vue.js, incluindo a capacidade de integração com APIs externas e persistência de dados em um banco de dados local usando JDBC.
