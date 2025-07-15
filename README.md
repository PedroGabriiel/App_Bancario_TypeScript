# App_Bancario_TypeScript

# 💰 Dio Bank

Desenvolvido por [Nathally Souza](https://github.com/nathyts)

O **Dio Bank** é um projeto simples e didático desenvolvido com **TypeScript**, com o objetivo de praticar os fundamentos da programação orientada a objetos (POO), como encapsulamento, herança, polimorfismo e controle de acesso a atributos e métodos.

Este projeto simula um sistema bancário com diferentes tipos de contas e operações bancárias como depósito, saque e empréstimo.

---

## 🚀 Tecnologias utilizadas

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

## 📚 Funcionalidades

- Criação de contas bancárias com número e nome do titular
- Controle de saldo com operações de:
  - Depósito
  - Saque (com verificação de saldo e status da conta)
  - Empréstimo (apenas para contas empresariais)
- Implementação de diferentes tipos de contas:
  - Conta padrão (`DioAccount`)
  - Conta empresarial (`CompanyAccount`)
  - Conta especial com bônus no depósito

Todos os atributos das contas são privados e protegidos com modificadores de acesso, garantindo encapsulamento. Os dados sensíveis como nome do titular e número da conta não podem ser modificados após a criação.

---

## 🛠️ Como rodar o projeto

```bash
# 1. Clone o repositório
git clone https://github.com/nathyts/dio-bank.git

# 2. Acesse a pasta do projeto
cd dio-bank

# 3. Abra o projeto no VS Code
code .

# 4. Instale as dependências
npm install

# 5. Execute o projeto em modo desenvolvimento
npm run dev
