Testes E2E com Cypress

Este projeto utiliza o **Cypress** para realizar testes end-to-end (E2E) de forma prática e automatizada.

## ✅ Pré-requisitos

Antes de executar os testes, verifique se você possui o **Node.js** instalado na versão correta:
`node -v`
A versão **deve ser igual a `20.x.x`**.
> ⚠️ Versões diferentes podem causar problemas de compatibilidade com o Cypress.

## 📦 Instalação
Instale as dependências do projeto com:
`npm install`

## 🚀 Executando os Testes

Este projeto utiliza o [`ntl`](https://www.npmjs.com/package/ntl) para facilitar a escolha dos scripts NPM.

Execute o comando abaixo para listar os scripts disponíveis:
`npx ntl`
Você verá duas opções principais:
- `cypress:web`: Abre a interface gráfica do Cypress para executar os testes no navegador.
    
- `cypress:headless`: Executa os testes diretamente no terminal, sem interface.
### Usando o Cypress com interface (modo gráfico)

1. Selecione a opção `cypress:web` no menu do `ntl`.
    
2. A interface do Cypress será aberta.
    
3. Vá até a aba **E2E Testing**.
    
4. Selecione um navegador disponível (ex: Chrome, Electron).
    
5. Clique no botão para iniciar os testes.
    

### Usando o Cypress no modo headless (sem interface)

Se quiser executar os testes diretamente no terminal, selecione a opção `cypress:headless` no `ntl` ou execute:

`npm run cypress:headless`

## 📁 Estrutura dos Testes

Os testes E2E ficam geralmente em:

`
cypress/   
  └─ e2e/ 
    └─ meus-testes.cy.js
`

Você pode adicionar novos arquivos de teste dentro da pasta `cypress/e2e`.cc