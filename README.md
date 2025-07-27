🎬 **Cinemaflix Databases**

Ambiente de desenvolvimento Docker para o projeto de banco de dados do Cinemaflix, contendo Jupyter, MariaDB, Neo4j, MongoDB e Redis.
<br><br><br><br>

🚀 **Guia Rápido**

**1. Clone o Repositório**

git clone https://github.com/juniorcmauricio/cinemaflix_databases.git

cd cinemaflix_databases

<br>

**2. Inicie o Ambiente**

Este comando irá construir e iniciar todos os contêineres em segundo plano.

docker-compose up -d --build

<br>

**3. Acesse o Jupyter Notebook**

Para obter o link de acesso, execute:

docker-compose logs jupyter

Procure por uma URL parecida com http://127.0.0.1:8888/lab?token=... e cole-a no seu navegador.


<br><br>
🛠️ **Comandos Essenciais**

Verificar o status dos contêineres: docker-compose ps

Parar e remover os contêineres: docker-compose down

Parar e remover contêineres E DADOS: docker-compose down -v


<br><br>
📓 **Notebook Principal**

O arquivo principal para interagir com todos os bancos de dados é o ***CinemaFlix_Databases.ipynb***.

Você pode encontrá-lo no navegador de arquivos do JupyterLab no seguinte caminho:

**jupyter/notebooks/CinemaFlix_Databases.ipynb**

Neste notebook, você encontrará:

- A configuração das conexões com todos os bancos de dados.

- Os scripts para criar os schemas e popular as bases com dados.

- As consultas relevantes que foram desenvolvidas para o relatório.

    
<br><br>
🗄️ **Acesso aos Bancos**

Neo4j Browser: http://localhost:7474 (Usuário: neo4j, Senha: strong_password)

MariaDB: Host: localhost, Porta: 3306 (Usuário: cinemaflix_user, Senha: user_password)

MongoDB: URI: mongodb://root:root_password@localhost:27017/

Redis: Host: localhost, Porta: 6379


