# comex-jpa-alura
Projeto da segunda semana da trilha Boost do Back-End

### Bom dia!
- O seed dos dados está sendo realizado pelo arquivo import.sql na pasta resources.
- Para que a aplicação funcione é necessário:
  - Mudar informações no persistence.xml encontrado na pasta META-INF.
  - As informações a serem modificadas são quanto ao nome do banco de dados e user e password do seu banco de dados.
  - Pode ser necessário, incialmente, criar um banco de dados em seu SGBD para que o seed funcione.

    
 ### Informações para modificar:
  name="javax.persistence.jdbc.url" value="jdbc:mysql://localhost:3306/nomeDoBanco?createDatabaseIfNotExist=true"
  name="javax.persistence.jdbc.user" value="SeuUserNameDoBancoDeDados"
  name="javax.persistence.jdbc.password" value="SuaSenhaDoBancoDeDados"
