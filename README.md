docker build -t one .

docker run -p 8081:8081 one

docker build -t eureka .

docker run -p 8761:8761 eureka

docker-compose build

docker-compose up