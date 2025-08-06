# clean-code-api

## GIT

[Convencional Commit](https://www.conventionalcommits.org/en/v1.0.0/)

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

[git-commit-msg-linter](https://www.npmjs.com/package/git-commit-msg-linter)

Garante o padrão 'convencional commit' nas mensagens

## Typescript

Instalação do superset com types para node e tsc-node para npx

```
npm i typescript @types/node tsc-node -D
```

## Husky
[Husky](https://www.npmjs.com/package/husky)

O Husky é uma ferramenta essencial para projetos JavaScript/TypeScript que atua como um "guardião do código", automatizando verificações antes de commits e pushes. Ele ajuda a manter a qualidade do código e evitar problemas comuns
- Git Hooks Automatizados
  - pre-commit: Antes do commit ser criado
  - pre-push: Antes do push para o repositório remoto
  - Entre outros (como commit-msg, post-merge, etc.)
- Aplicação Padrões de Código
  - Executa o ESLint para verificar erros
  - Roda o Prettier para formatar automaticamente
  - Executa testes unitários (npm test)
- Prevenção de Problemas
  - Bloqueia commits com erros de lint ou testes falhando
  - Evita código mal formatado no repositório

