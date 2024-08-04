
# BACKEND COM TYPESCRIPT

Este é um projeto básico pré-configurado usando TypeScript e Jest para testes. O projeto inclui configurações iniciais para rotas, variáveis de ambiente, linting, formatação de código e testes.

## Estrutura do Projeto

```
src/
├── routes/
│   └── userRoutes.ts
├── index.ts
└── index.test.ts
```

## Funcionalidades

- Rotas de usuário genéricas configuradas
- Configuração de variáveis de ambiente usando dotenv
- Suporte para TypeScript
- Linting e formatação de código usando ESLint e Prettier
- Testes unitários configurados com Jest e supertest

## Pré-requisitos

- Node.js (versão 14 ou superior)
- npm (versão 6 ou superior)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Lucas-Teodosio/Back-Type.git
   cd Back-Type
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Crie um arquivo `.env` na raiz do projeto e configure as variáveis de ambiente necessárias:
   ```plaintext
   PORT=3000
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```

O servidor estará rodando em `http://localhost:3000`.

## Scripts Disponíveis

- `npm start`: Inicia o servidor de desenvolvimento com nodemon.
- `npm run lint`: Executa o ESLint para verificar problemas no código.
- `npm run format`: Formata o código usando Prettier.
- `npm run test`: Executa os testes unitários com Jest.

## Estrutura de Pastas

- `src/routes`: Contém as rotas da aplicação.
- `src/index.ts`: Arquivo principal que configura e inicia o servidor Express.
- `src/index.test.ts`: Arquivo de teste de exemplo para o servidor Express.

## Contribuição

Se você quiser contribuir com este projeto, por favor, siga estas etapas:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça um push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
