# 🏦 Banco Digital - API Simples em Java

📌 **Descrição**  
Este projeto é uma simulação de um **Banco Digital**, desenvolvido como parte de um desafio da **DIO (Digital Innovation One)**. Ele implementa um sistema bancário simples com **contas correntes e poupança**, permitindo operações como depósito, saque e transferência entre contas.

O objetivo do projeto é aplicar os conceitos de **Programação Orientada a Objetos (POO)** em **Java**, incluindo **herança, abstração e polimorfismo**, além da implementação de **interfaces**.

---

## 🚀 **Funcionalidades Implementadas**  

✅ **Criar contas bancárias** (corrente e poupança).  
✅ **Depósitos, saques e transferências** entre contas.  
✅ **Impressão de extratos** detalhados.  
✅ **Gerenciamento de clientes e contas** dentro de um banco.  
✅ **Uso de POO** para organizar melhor as responsabilidades das classes.  

---

## 🛠️ **Tecnologias Utilizadas**  

- **Java 17**  
- **Paradigma de Programação Orientada a Objetos (POO)**  
- **Interface Gráfica:** Nenhuma (execução via console)  
- **IDE:** IntelliJ IDEA / VS Code / Eclipse  

---

## 📁 **Estrutura do Projeto**  

```
📂 src/main/java/com/bancoDigital
 ├── 📂 model
 │   ├── Banco.java
 │   ├── Cliente.java
 │   ├── Conta.java
 │   ├── ContaCorrente.java
 │   ├── ContaPoupanca.java
 ├── 📂 interface
 │   ├── IConta.java
 ├── Main.java
```

---

## 🔧 **Como Executar o Projeto**  

1️⃣ **Clone o repositório**  
   ```sh
   git clone https://github.com/jpncaetano/dio-banco-digital-poo.git
   cd dio-banco-digital-poo
   ```

2️⃣ **Compile o código**  
   ```sh
   javac -d bin src/main/java/com/bancoDigital/*.java
   ```

3️⃣ **Execute o programa**  
   ```sh
   java -cp bin com.bancoDigital.Main
   ```

---

## 📌 **Possíveis Melhorias Futuras**  

🔹 Implementação de um banco de dados para persistência de contas e clientes.  
🔹 Interface gráfica para interação com o usuário.  
🔹 Criação de um sistema de autenticação para os clientes.  
🔹 Relatórios financeiros mais detalhados.  

---

## 📜 **Licença e Uso**  

Este projeto foi desenvolvido para fins educacionais e pode ser utilizado como base para estudos. Sinta-se à vontade para contribuir!  

📩 **Contato:** Caso tenha dúvidas ou sugestões, entre em contato pelo GitHub.  

---

### 🔥 **Resumo Final**  

Este repositório contém um **Banco Digital Simples** implementado em Java, aplicando conceitos de **POO** como herança, abstração e polimorfismo. O sistema permite operações bancárias básicas e pode ser expandido com funcionalidades adicionais no futuro.
