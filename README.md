# 🧪 Exercício Java com Testes

> Praticando Java com foco em qualidade — escrever código que funciona e que pode ser provado.

---

## 🗂️ Sobre

O projeto **Exercício Java com Testes** explora a prática de testes automatizados em Java, utilizando o **JUnit** para validar o comportamento de classes e métodos, garantindo que o código funcione corretamente a cada alteração.

---

## 📖 Conteúdo abordado

- ✅ Introdução ao **JUnit**
- 🧩 Criação de casos de teste (`@Test`)
- 🔍 Asserções (`assertEquals`, `assertTrue`, `assertNotNull`...)
- ⚠️ Testes de exceções esperadas
- 🔄 Ciclo de vida dos testes (`@BeforeEach`, `@AfterEach`)
- 🏗️ Boas práticas de escrita de testes

---

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/Vinizapella/exercicio-java-com-testes.git

# Acesse a pasta
cd exercicio-java-com-testes

# Execute os testes com Maven
mvn test
```

---

## 📦 Dependência Maven (pom.xml)

```xml
<dependency>
    <groupId>org.junit.jupiter</groupId>
    <artifactId>junit-jupiter</artifactId>
    <version>5.10.0</version>
    <scope>test</scope>
</dependency>
```

---

## 📁 Estrutura

```
📦 exercicio-java-com-testes
 ┣ 📂 src
 ┃ ┣ 📂 main
 ┃ ┃ ┗ 📂 java
 ┃ ┃   ┗ 📄 (classes principais)
 ┃ ┗ 📂 test
 ┃   ┗ 📂 java
 ┃     ┗ 📄 (classes de teste)
 ┣ 📄 pom.xml
 ┗ 📄 README.md
```

---

## 👤 Autor

Feito com 🖤 por **Vinizapella** — projeto concluído para fins acadêmicos.

---

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/status-concluído-brightgreen?style=flat-square" />
</p>
