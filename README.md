# Atividade prática: ESLint e Prettier

Projeto referente ao roteiro de configuração de ESLint e Prettier.

## Pré-requisito
Node.js e npm instalados.

## Executar

```bash
npm install
npm run lint
npm run format:check
npm start
```

Para correção automática:

```bash
npm run lint:fix
npm run format
```

O arquivo `codigo-original.txt` conserva o exemplo despadronizado da atividade. O `index.js` contém a versão corrigida. A configuração usa o formato atual `eslint.config.mjs` do ESLint (flat config), no lugar da configuração legada sugerida no roteiro.

Observação: as dependências não puderam ser instaladas neste ambiente de geração; os comandos de lint e formatação devem ser executados localmente depois de `npm install`.
