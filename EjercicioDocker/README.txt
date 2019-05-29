Ejercicio Docker 

Magela Carballo

28 Mayo 2019
------------------------------------------------

git clone https://github.com/magelac94/Linux2019.git

cd Linux2019

cd EjercicioDocker

docker build . --tag="apppy"

docker run -p 8080:8080 apppy

curl http://localhost:8080/

--------------------------------------------------


URL: http://localhost:8080/
