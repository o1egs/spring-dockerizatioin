# Spring Dockerization

  Этот проект демонстрирует, как контейнеризовать приложение Spring Boot с использованием Docker.

## Предварительные требования
- Git установлен на вашем компьютере
- Docker установлен на вашем компьютере
- Maven установлен на вашем компьютере

## Что делает build.sh

1. Клонирует репозиторий
   
   git clone https://github.com/o1egs/spring-dockerizatioin.git
   
2. Переходит в каталог проекта
   
   cd spring-dockerizatioin
   
3. Собирает приложение с помощью Maven
   
   mvn clean package

## Запустите build.sh
  build.sh

## Запустите docker-compose
  
  docker-compose up -d
