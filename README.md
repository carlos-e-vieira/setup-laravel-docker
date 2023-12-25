### Instalar o Projeto
G:\Programacao\PHP\Laravel\02-Meus-Projetos\Setup-Laravel-Docker

<hr>

### Criar e Configurar o Dockerfile
Criar o arquivo no diretorio raiz do projeto

<hr>

### Criar e Configurar o docker-compose.yml
Criar o arquivo no diretorio raiz do projeto

<hr>

### Configurar as Credenciais do DB no .ENV e docker-compose.yml
#### ENV:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_setup_laravel_docker
DB_USERNAME=root
DB_PASSWORD=root

#### docker-compose.yml
environment:
    - "DB_HOST=db"
    - "DB_DATABASE=db_setup_laravel_docker"
    - "DB_USERNAME=root"
    - "DB_PASSWORD=root"

environment:
      - "MYSQL_DATABASE=db_setup_laravel_docker"
      - "MYSQL_USER=your_database_user"
      - "MYSQL_PASSWORD=root"
      - "MYSQL_ROOT_PASSWORD=root"

<hr>
