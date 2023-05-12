# boot-starter
Descrição do projeto:

O projeto consiste em uma REST API desenvolvida em Spring Boot que fornece recursos para autenticação de usuários, gerenciamento de documentos, telefones e endereços. As APIs serão documentadas usando o Spring-Docs e terão autenticação utilizando o Spring Security com JWT (JSON Web Token) para geração do token de autenticação.

Principais componentes e funcionalidades do projeto:

1. Autenticação de Usuário:
   - Implementação do registro de usuários com informações básicas como nome, e-mail e senha.
   - Validação e verificação de credenciais de login.
   - Geração de token JWT para autenticação.

2. Gerenciamento de Documentos:
   - Criação, leitura, atualização e exclusão de documentos associados a um usuário.
   - Recursos para consultar documentos por ID ou filtrá-los por propriedades específicas.

3. Gerenciamento de Telefones:
   - Criação, leitura, atualização e exclusão de telefones associados a um usuário.
   - Recursos para consultar telefones por ID ou filtrá-los por propriedades específicas.

4. Classe de Endereço:
   - Implementação de uma classe de Endereço que contém informações como rua, número, cidade, estado, etc.
   - Associação do endereço a um usuário.

5. Documentação com Spring-Docs:
   - Utilização do Spring-Docs para gerar documentação automática das APIs.
   - Documentação clara e completa dos endpoints disponíveis, parâmetros esperados e exemplos de uso.

6. Autenticação com Spring Security e JWT:
   - Configuração do Spring Security para proteger as rotas da API.
   - Utilização do JWT (OAuth 2.0) para gerar e validar tokens de autenticação.
   - Autorização baseada em papéis de usuário (roles) para restringir o acesso a determinados endpoints.

7. Dependências:
   - Spring Boot: Plataforma de desenvolvimento rápida e fácil configuração.
   - Spring Security: Framework de segurança para autenticação e autorização.
   - Spring-Docs: Ferramenta para geração automática de documentação.
   - JWT (OAuth 2.0): Biblioteca para geração e validação de tokens JWT.

Essa é uma descrição geral do projeto que atende aos requisitos solicitados. Lembre-se de que implementar todos os detalhes e lógica necessários para cada recurso pode levar algum tempo, pois envolve configurações, classes de modelo, controladores, serviços e integração com as bibliotecas mencionadas.
