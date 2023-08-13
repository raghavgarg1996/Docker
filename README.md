# Docker
Learning docker and it's implementation

Steps to Start Container
1. Execute command "docker build .", it will automatically download all the details mention in the Dockerfile
2. Once it is executed will get an hash similar as "sha256:2b6b632799df777bf4c3fc3a32c60e2b14e1e788f1ae39b08aa036c61789e643", now execute command "docker run -p 3000:3000 2b6b632799df777bf4c3fc3a32c60e2b14e1e788f1ae39b08aa036c61789e643"
3. When we see command it stuck, it means it works on background
4. Now hit http://localhost:3000/

Steps to Stop Container
1. Execute "docker ps", will show all the running container
2. Now in the Name section copy the name of the container - and execute command "docker stop NAME". 
