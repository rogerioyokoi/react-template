# React Template

## Sumário

- [React Template](#react-template)
  - [Sumário](#sumário)
  - [Introdução](#introdução)
  - [Tecnologias](#tecnologias)
  - [Instalação](#instalação)
  - [Uso](#uso)
    - [Scripts](#scripts)
    - [Configuração de Depuração](#configuração-de-depuração)
  - [Estrutura do Projeto](#estrutura-do-projeto)
  - [Contribuição](#contribuição)
  - [Licença](#licença)

## Introdução

Este projeto é um template básico de aplicação React, desenvolvido com TypeScript e configurado com uma série de ferramentas modernas para garantir uma experiência de desenvolvimento eficiente e organizada.

**Objetivos**:

- Fornecer uma estrutura inicial para aplicações React com suporte a autenticação.
- Implementar uma arquitetura escalável para facilitar o desenvolvimento de novas funcionalidades.
- Prover uma base de desenvolvimento com scripts de automação para testes, linting e formatação de código.

Este template é ideal para desenvolvedores que desejam criar aplicações React de forma rápida e com uma configuração inicial robusta.

## Tecnologias

As principais tecnologias e ferramentas utilizadas neste projeto incluem:

- **React 18** - Biblioteca JavaScript para criação de interfaces de usuário.
- **TypeScript** - Superset do JavaScript com tipagem estática.
- **Vite** - Ferramenta de build para desenvolvimento rápido com ESBuild.
- **Vitest** - Framework de testes para JavaScript com suporte nativo ao Vite.
- **Tailwind CSS** - Framework CSS para estilização rápida e responsiva.
- **ESLint** - Ferramenta de linting para manter um código consistente e livre de erros.
- **Prettier** - Ferramenta de formatação de código para garantir consistência.
- **Commitizen e Commitlint** - Ferramentas para padronizar mensagens de commit.
- **Lefthook** - Gerenciador de hooks de git, substituindo o Husky para maior simplicidade.

## Instalação

Para instalar e configurar o projeto localmente, siga os passos abaixo:

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/react-authentication-template.git
   cd react-authentication-template
   ```

2. **Instale as dependências**:

   ```bash
   npm install
   ```

3. **Configure os hooks de git com o Lefthook**:
   ```bash
   npx lefthook install
   ```

Após seguir esses passos, você estará pronto para iniciar o desenvolvimento.

## Uso

Para executar o projeto e utilizar os scripts disponíveis, veja abaixo as instruções.

### Scripts

Abaixo estão os scripts que podem ser executados neste projeto, com descrições detalhadas:

- **`npm run dev`**: Inicia o servidor de desenvolvimento usando o Vite.
- **`npm run build`**: Faz o build do projeto para produção, utilizando o TypeScript e o Vite.
- **`npm run build:commit`**: Utiliza o Commitizen para gerar mensagens de commit seguindo um padrão específico.
- **`npm run lint`**: Executa o ESLint para analisar o código, reportando problemas e proibindo quaisquer avisos.
- **`npm run lint:fix`**: Corrige automaticamente os problemas de linting encontrados pelo ESLint.
- **`npm run lint:format:check`**: Verifica a formatação do código com o Prettier.
- **`npm run lint:format:fix`**: Formata o código com o Prettier.
- **`npm run lint:commit`**: Executa o Commitlint para garantir que a última mensagem de commit siga o padrão especificado.
- **`npm run test`**: Executa os testes unitários com o Vitest.
- **`npm run test:staged`**: Executa os testes para os arquivos alterados no último commit.
- **`npm run test:coverage`**: Gera um relatório de cobertura dos testes.
- **`npm run test:ui`**: Abre a interface de usuário do Vitest para execução interativa dos testes.
- **`npm run preview`**: Pré-visualiza a versão de produção gerada pelo Vite.

### Configuração de Depuração

Para configurar a depuração do projeto:

1. Certifique-se de que a extensão de depuração está ativa no seu editor de código.
2. Configure a depuração no Vite, caso o editor exija um arquivo de configuração de depuração específico.
3. Utilize os scripts `npm run dev` para rodar o servidor e `npm run test:ui` para verificar os testes de maneira interativa.

## Estrutura do Projeto

Abaixo está a estrutura de diretórios e arquivos principais do projeto:

```plaintext
react-authentication-template/
├── public/                     # Arquivos públicos estáticos
├── src/                        # Código-fonte da aplicação
│   ├── assets/                 # Arquivos de mídia e estilos
│   ├── components/             # Componentes reutilizáveis
│   ├── hooks/                  # Custom Hooks
│   ├── pages/                  # Páginas da aplicação
│   ├── routes/                 # Configurações de rotas
│   ├── services/               # Serviços para integração de APIs
│   ├── types/                  # Tipos e interfaces TypeScript
│   ├── utils/                  # Utilidades gerais
│   └── main.tsx                # Arquivo principal
├── .eslintrc.json              # Configuração do ESLint
├── .prettierrc                 # Configuração do Prettier
├── tsconfig.json               # Configuração do TypeScript
├── vite.config.ts              # Configuração do Vite
└── README.md                   # Documentação do projeto
```

Cada diretório e arquivo nesta estrutura tem um propósito claro para manter o projeto organizado e modularizado, facilitando a escalabilidade.

## Contribuição

Para contribuir com este projeto, siga estas diretrizes:

1. **Faça um Fork** do projeto.
2. Crie uma **nova branch** para sua feature ou correção:
   ```bash
   git checkout -b feature/minha-nova-feature
   ```
3. **Commit suas mudanças** seguindo o padrão do Commitizen:
   ```bash
   npm run build:commit
   ```
4. **Envie a branch** para o seu repositório forkado:
   ```bash
   git push origin feature/minha-nova-feature
   ```
5. **Abra um Pull Request** explicando as alterações feitas.

O projeto utiliza o padrão de commits convencionais para garantir um histórico de alterações organizado.

## Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE no repositório.

```

```
