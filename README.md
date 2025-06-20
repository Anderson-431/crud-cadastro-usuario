# CRUD Cadastro de Usuários

Este é um projeto simples de API REST em Java utilizando Spring Boot, que permite realizar operações de **Cadastro, Leitura, Atualização e Remoção (CRUD)** de usuários.

> ✅ Projeto desenvolvido no **IntelliJ IDEA**, como forma de prática com Spring Boot e Lombok.

---

## 📌 Funcionalidades

- ✅ Cadastrar usuário (`POST`)
- ✅ Buscar usuário por e-mail (`GET`)
- ✅ Atualizar usuário por ID (`PUT`)
- ✅ Deletar usuário por e-mail (`DELETE`)

---

## 🚀 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- Lombok
- Maven
- **IntelliJ IDEA (IDE)**
  
## 📂 Estrutura de pacotes
com.javaverso.cadastro_usuario
│
├── business → Lógica de negócio (serviços)
├── controller → Endpoints da API
├── infrastructure
│ ├── entitys → Classe de entidade (Usuario)
│ └── repository → Interface de acesso ao banco

 ## ✅ Testes realizados

- 📫 **Postman** para testes das operações HTTP
- 💾 **Banco H2 (em memória)** para persistência e visualização rápida via console H2
- http://localhost:8081/h2-console

Configurações padrão:
JDBC URL: jdbc:h2:mem:testdb
Username: sa
Password: (deixe em branco)

## 🔧 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/Anderson-431/crud-cadastro-usuario.git

2. Abra o projeto no IntelliJ IDEA (ou outra IDE de sua preferência).

3. Verifique se o plugin Lombok está instalado e habilitado.

4. Rode a aplicação pela classe CadastroUsuarioApplication.




