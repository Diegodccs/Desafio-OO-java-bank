# 💳 Java-bank

Um sistema bancário simples desenvolvido em **Java** para praticar conceitos de **POO (Programação Orientada a Objetos)**, **coleções**, **exceções personalizadas** e boas práticas de código.  
O projeto simula operações de contas digitais, incluindo transações PIX, histórico de movimentações e gerenciamento de contas.

---

## 🚀 Funcionalidades

✅ Criar contas digitais com chave PIX  
✅ Registrar transações (depósitos, transferências, etc.)    
✅ Agrupamento de movimentações por data/hora  
✅ Tratamento de erros com exceções personalizadas (`AccountNotFoundException`)  
✅ Cálculo de valores em reais a partir de centavos (ex: `2599 -> R$25,99`)

---

## 🛠️ Tecnologias utilizadas

- ☕ **Java 21+**
- 🗂️ **Collections API** (`Map`, `List`, `TreeMap`)
- 📅 **java.time API** (`LocalDateTime`, `DateTimeFormatter`)
- 📝 **Records (Java 21+)** para modelar transações
- 🧪 Testes manuais via console (entrada/saída padrão)

---

## 📂 Estrutura do projeto

java-bank/
├── src/
│ ├── AccountRepository.java
│ ├── Transaction.java
│ ├── AccountNotFoundException.java
│ └── Main.java
├── README.md
└── pom.xml (caso use Gradle)

📌 Próximas melhorias

🔹 Implementar persistência em banco de dados (H2/MySQL)
🔹 Criar interface gráfica com JavaFX
🔹 Exibir relatório de saldo e estatísticas das transações
🔹 Criar testes unitários com JUnit

👨‍💻 Autor

Projeto desenvolvido por [Diego Camargo] 🧑‍💻
📧 Contato: camargosantosch@gmail.com
