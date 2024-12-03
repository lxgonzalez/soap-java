# SOAP using java with Springboot

## Tech Stack

![Spring Icon](https://img.icons8.com/?size=48&id=90519&format=png&color=000000)
![Java_icon](https://img.icons8.com/?size=60&id=13679&format=png&color=000000)
## Deployment

To run the API locally, follow these steps:

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/lxgonzalez/soap-java
cd soap-java
```
### 2. Install Dependencies
```bash
mvn clean install
```
### 4. Run the Application
```bash
java -jar target/soap-java-0.0.1-SNAPSHOT.jar
```
### 5. Other bash connecting 
```bash
curl --header "content-type: text/xml" --data @((Get-Content -Raw -Path "request.xml")) http://localhost:8080/ws
```

### DEMO

## Authors

- [@lxgonzalez](https://github.com/lxgonzalez)