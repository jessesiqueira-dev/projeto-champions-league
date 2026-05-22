# Projeto Champions

API para gerenciamento de jogadores e clubes de futebol, desenvolvida com foco em aprendizado e estruturação de serviços Node.js.

## Tecnologias Utilizadas
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)

## Pré-requisitos
- Node.js instalado (versão LTS recomendada).
- `npm` instalado.

## Como Rodar
1. Instale as dependências:
   ```bash
   npm install
   ```
2. Configure as variáveis de ambiente:
   Crie um arquivo `.env` na raiz do projeto e defina a porta:
   ```env
   PORT=3000
   ```
3. Inicie o servidor em modo de desenvolvimento:
   ```bash
   npm run start:dev
   ```

## Endpoints

### Jogadores
- `GET /players`: Lista todos os jogadores.
- `POST /players`: Cria um novo jogador.
- `GET /players/:id`: Busca um jogador específico pelo ID.
- `PATCH /players/:id`: Atualiza dados de um jogador.
- `DELETE /players/:id`: Remove um jogador pelo ID.

### Clubes
- `GET /clubs`: Lista todos os clubes.
