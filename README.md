This project showcases Docker containerization of a Django application, packaging the app with all dependencies for consistent, portable, and scalable deployment. It demonstrates modern DevOps practices, simplifying management and ensuring the application runs reliably across different environments.
install docker // #refer Docker Documentation#
Ensure Docker deamon is running //  #refer Docker Documentation#
Go to the Current Directory  cd python-web-app
docker build .
docker run -p 8000:8000 -it docker_image_id
To see the  Docker_image , go to the command "docker images" after build
