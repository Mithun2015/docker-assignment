# Docker Assignment – Flask Application
This project demonstrates containerization of a simple Flask application using Docker and Docker Compose.

The application runs on port 5000 and displays:
"Hello from Docker."
## Application Output

<img width="1280" height="759" alt="image" src="https://github.com/user-attachments/assets/065e9081-83a0-4ea1-97e3-4e376a2781a4" />
<img width="1280" height="761" alt="image" src="https://github.com/user-attachments/assets/00e28b42-fc34-40fa-b0fe-13a1543eff88" />
<img width="1280" height="755" alt="image" src="https://github.com/user-attachments/assets/e4cdc9d2-5ce5-4aeb-b428-770445b54994" />

## Project Structure

docker-assignment/
│── app.py
│── requirements.txt
│── Dockerfile
│── docker-compose.yml
│── .dockerignore
<img width="1290" height="310" alt="image" src="https://github.com/user-attachments/assets/639af1e9-039d-499a-831e-7338a298fd04" />

## Run Locally

pip install -r requirements.txt
python app.py

Open: http://localhost:5000

<img width="1280" height="759" alt="image" src="https://github.com/user-attachments/assets/5aa67e54-08ef-4595-92b3-b708f6f29f54" />

## Build Docker Image

docker build -t flask-docker-app .
<img width="654" height="41" alt="image" src="https://github.com/user-attachments/assets/a5f55be1-921e-44e2-aacc-b9ac0ca454e1" />


## Run Container

docker run -d -p 8080:5000 flask-docker-app


## Check Running Containers

docker ps
<img width="993" height="71" alt="image" src="https://github.com/user-attachments/assets/5f543b1f-452d-46a1-bdb9-3e171741fd40" />

## Run with Docker Compose

docker-compose up -d
<img width="1280" height="490" alt="image" src="https://github.com/user-attachments/assets/08cf4546-d80a-4c0b-91d3-56a86ad03581" />


docker-compose ps
<img width="1280" height="116" alt="image" src="https://github.com/user-attachments/assets/81b7d4a4-23c9-4886-a3d5-d95f50fa70eb" />

docker-compose down
<img width="1280" height="118" alt="image" src="https://github.com/user-attachments/assets/3fd5e275-0dcb-4522-9e9a-c5be11484e64" />





