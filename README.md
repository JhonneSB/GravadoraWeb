# 🎵 GravadoraWeb

Projeto desenvolvido durante o curso técnico em **Desenvolvimento de Sistemas** no Senai.  
Aplicação web para gerenciamento de uma gravadora musical, com cadastro e controle de **artistas**, **álbuns** e **gravadoras**.

---

## 🚀 Tecnologias Utilizadas

- ☕ Java 17  
- 🌱 Spring Boot  
- 🗃️ Spring Data JPA  
- 🔄 Hibernate  
- 🧩 Thymeleaf  
- 🐬 MySQL  
- 📦 Maven  

---

## ✨ Funcionalidades

- ✅ Cadastro, edição e exclusão de **Artistas**  
- ✅ Cadastro, edição e exclusão de **Álbuns**  
- ✅ Cadastro, edição e exclusão de **Gravadoras**  
- 🔗 Relacionamento entre artistas, álbuns e gravadoras  
- 🖥️ Interface web simples e funcional utilizando **Thymeleaf**

---

## ⚙️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/JhonneSB/GravadoraWeb.git
   
   ```

2. Configure o banco de dados MySQL e ajuste as credenciais no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/gravadoradb
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   spring.jpa.hibernate.ddl-auto=update
   ```

3. Execute o projeto via Maven:
   ```bash
   mvn spring-boot:run
   ```

4. Acesse no navegador:
   ```
   http://localhost:8080
   ```

---

## Autor

Carlos Jhonne de Souza dos Santos  
[GitHub](https://github.com/JhonneSB)  

---

## Contato

Para dúvidas ou sugestões, envie um e-mail para: carlosjhonne7@gmail.com

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
