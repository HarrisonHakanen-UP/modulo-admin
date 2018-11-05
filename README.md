# modulo-admin

### Rotas

1. Serviço ações:
  - Retorna uma lista de Ações: http://localhost:8091/listar
  - Salva uma Ação: http://localhost:8091/wsa/cadastrar
  - Deleta uma Ação: http://localhost:8091/wsa/deletar/{id}

2. Serviço menu:

  - Retorna uma lista de Menus: http://localhost:8091/wsm/listar
  - Salva um Menu: http://localhost:8091/wsm/cadastrar
  - Deleta um Menu: http://localhost:8091/wsm/deletar/{id}

3. Serviço módulos:

  - Retorna uma lista de Módulos: http://localhost:8091/wsmod/listar
  - Salva um Módulo: http://localhost:8091/wsmod/cadastrar
  - Deleta um Módulo: http://localhost:8091/wsmod/deletar/{id}

4. Serviço usuário:

  - Retorna uma lista de Usuários: http://localhost:8091/wsu/listar
  - Salva um Usuário: http://localhost:8091/wsu/cadastrar
  - Deleta um Usuário: http://localhost:8091/wsu/deletar/{id}
  
  ### Observação
  Serviço Web com Spring Boot + JPA + Web Service Restful
