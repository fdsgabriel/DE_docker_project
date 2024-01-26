I going to use this repo/project to learn more about Docker and how insert docker into data engineering field. 


The target is download daily files from Kaggle using Selenium, transform this data and load it into a Postgres table in a Docker container. And another conteiner for orchastration all these steps, another words: use airflow with Docker. 

The project is going to be splited in pieces: 

	- Fecth data from Kaggle with Selelinum;
	- Transform this data; 
	- Build up a container for Postgres and insert data into it;
	- Build up DAGs and set a container for Airflow to run it daily