# Sistema de Controle Financeiro API REST


## Visão Geral

Este é um projeto de API REST que oferece funcionalidades para gerenciar transações financeiras e categorias relacionadas. Ele permite que os usuários se cadastrem, façam login e realizem operações como adicionar, listar, atualizar e excluir transações financeiras, bem como listar categorias e obter um extrato financeiro.

## Recursos 
- Registro de usuário
- Autenticação de usuário
- Operações de transações financeiras:
   - Adicionar uma nova transação
   - Listar todas as transações do usuário
   - Atualizar uma transação existente
   - Excluir uma transação
   - Obter detalhes de uma transação específica
- Listagem de categorias
- Obtenção de extrato financeiro (total de entrada e saída)

##  Tecnologias Utilizadas
- Node.js
- Express.js
- PostgreSQL
- Bcrypt para criptografia de senhas
- JSON Web Tokens (JWT) para autenticação
- Nodemon para desenvolvimento

## Como Usar
#### Pré-requisitos
- Certifique-se de ter o Node.js instalado na sua máquina.
- Configure um banco de dados PostgreSQL e atualize as informações de configuração no arquivo de configuração do banco de dados, se necessário.
#### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/seu-projeto.git
```

2. Navegue até a pasta do projeto:
```bash
cd seu-projeto

```
3. Instale as dependências:
```bash
npm install
```

4. Atualize o arquivo DataBase.js com as informações de acesso do seu banco de dados.

5. Inicialize o servidor de desenvolvimento:
```bash
npm run dev
```

### Uso
- Certifique-se de que o servidor está em execução.
- Use ferramentas como o Postman ou faça solicitações HTTP para a API nos endpoints correspondentes.
- Consulte a documentação da API para obter detalhes sobre como usar cada recurso.
