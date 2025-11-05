# Cloning Amazon site with HTML & CSS

1. Install docker
2. Build the docker image
3. Deploy the container
  cd amazon/
  ll
  docker build -t amazon-app .
  docker images
  docker run -d -p 80:80 amazon-app:latest
  docker ps

4. access the application with your publicip:80
<img width="1919" height="949" alt="image" src="https://github.com/user-attachments/assets/fd37927a-6348-4c88-8976-1fafb9325912" />
