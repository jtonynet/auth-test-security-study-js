# Testes em Node.js - Módulo I
[<img src="../../docs/images/icons/nodedotjs.svg" width="25px" height="25px" title="Node.js" alt="Node.js"> <img src="../../docs/images/icons/npm.svg" width="25px" height="25px" alt="npm" title="npm"> <img src="../../docs/images/icons/eslint.svg" width="25px" height="25px" alt="Eslint" title="Eslint"> <img src="../../docs/images/icons/jest.svg" width="25px" height="25px" alt="Jest" title="Jest"> <img src="../../docs/images/icons/github.svg" width="25px" height="25px" alt="GitHub" title="GitHub"> <img src="../../docs/images/icons/nx.svg" width="25px" height="25px" alt="NX" title="NX"> <img src="../../docs/images/icons/visualstudiocode.svg" width="25px" height="25px" alt="vscode" title="vscode">](#carrinho-sample) <!-- icons by https://simpleicons.org/?q=types -->

![Badge Status](https://img.shields.io/badge/STATUS_DO_CURSO-MÓDULO_ENCERRADO-blue)

## :closed_lock_with_key: Testes em Folha de Pagamento
---

### :books: Projeto Com Finalidade Educacional
Projeto faz parte de curso [Testes com Jest](https://www.alura.com.br/curso-online-nodejs-testes-unitarios-integracao). Estrutura PURAMENTE DIDÁTICA sem preocupação com as reais necessidades de um projeto de produção. Foco nos testes.

Um novo projeto mais elaborado usando esses e outros conhecimentos está a caminho, [venda de tickets de cinema](https://github.com/jtonynet/cine-ticket-study)

---

### :computer: Instalando e configurando

Partindo do suposto que existe um ambiente [Node.js `v18.16.0`](https://nodejs.org/en) ou superior funcional em sua máquina

- Instalando:
```
npm install
```

- Rodando:
```
npx eslint index.js --fix
```

- Testando:
```
npm run test
```


---

<details>
  <summary>Configurando eslint em projetos novos</summary>

```
npm install --save-dev eslint@8.16.0 --save-exact
npx eslint --init 
```

```
> To check syntax, find problems, and enforce code style
> JavaScript modules (import/export)
> None of these
> No
> Node
> Use a popular style guide
> Airbnb
> JSON
```
</details>


<details>
  <summary>Configurando Jest em projetos novos</summary>

```
npm instal --save-exact jest@28.1.0 --save-dev
```

</details>

<!-- npm install --force -->
