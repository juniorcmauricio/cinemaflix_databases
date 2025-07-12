🎬 Cinemaflix Databases

🚀 How to build the docker containers

1 - Clone the repository

2 - Start the containers:
	docker-compose up -d --build

3 - Check container status:
	docker-compose ps

4 - Access Jupyter Notebook:
	Run: docker-compose logs jupyter

	Look for a line like: http://127.0.0.1:8888/lab?token=abc123...
	Copy and paste the URL into your browser, or hold Ctrl key and click on it.

