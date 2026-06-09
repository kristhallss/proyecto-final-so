[docker-compose.yml](https://github.com/user-attachments/files/28761644/docker-compose.yml)
services:
  nginx:
    image: nginx:latest
    ports:
      - "800:80"
    volumes:
      - ./nginx:/usr/share/nginx/html

  python:
    build: ./python
    ports:
     - "5000:5000"

