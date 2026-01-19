# JavaScript Unit Tests 🧪📦

Projeto de estudo desenvolvido durante a formação em **Desenvolvimento Web da Trybe**.  
O foco aqui é **escrever testes unitários em JavaScript** usando **Jest** para garantir que funções se comportam como esperado.

---

## 💡 Sobre

Este repositório contém vários exercícios de lógica em JavaScript onde a tarefa principal é **implementar funções** e **escrever testes Jest** que verificam o comportamento dessas funções em diferentes cenários — casos de sucesso, erros e bordas.

Esse projeto ajuda a:

✔️ Entender o que é um teste unitário  
✔️ Verificar entradas válidas e inválidas  
✔️ Dominar Jest para escrever testes robustos  
✔️ Aprender boas práticas de cobertura de testes  

---

## 🛠 Tecnologias utilizadas

- **JavaScript**
- **Node.js**
- **Jest** (framework de testes)
- **ESLint** (estilo de código)

---

## 🚀 Como rodar localmente

### 1. Clone o repositório

```bash
git clone https://github.com/Thaisvc/Project-Js-Unit-Tests.git
cd Project-Js-Unit-Tests
````

### 2. Instale as dependências

```bash
npm install
```

---

## 🧪 Rodando os testes

Todos os testes foram escritos com **Jest**.

Para rodar todos os testes:

```bash
npm test
```

Isso vai executar cada descrição de teste e mostrar:

✔️ Testes que passaram <br>
❌ Testes que falharam <br>
📌 Mensagem de erro detalhada <br>

---

## 📌 Estrutura do projeto

```
Project-Js-Unit-Tests/
├── node_modules/
├── src/               # Funções que você implementa
├── tests/             # Arquivos de teste Jest
├── package.json
├── package-lock.json
└── README.md
```

---

## 📊 Como os testes estão organizados

Cada função tem um arquivo de teste correspondente. Exemplos típicos:

### 🔹 Função `sum`

O teste espera que:

```js
expect(sum(2,3)).toBe(5);
expect(sum('a', 3)).toThrow();
```

---

### 🔹 Função `myRemove`

O teste verifica que uma função que remove item de array:

```js
expect(myRemove([1,2,3], 2)).toEqual([1,3]);
```

---

### 🔹 Função `myFizzBuzz`

Testes cobrem:

* Retorno esperado para números divisíveis
* Retorno para números não divisíveis
* Retorno para casos inválidos

---

## 📚Aprendizado
Com esse projeto praticou:

✔️ Conceitos de testes unitários <br>
✔️ Escrever testes Jest com `describe`, `test` e `expect` <br>
✔️ Verificações de erros e mensagens personalizadas <br>
✔️ Cobrir diferentes fluxos de execução <br>
✔️ Boas práticas de TDD (Test-Driven Development) <br>

Testes são essenciais em qualquer código real para evitar bugs e garantir que mudanças não quebrem sua lógica.

---

