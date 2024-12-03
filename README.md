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
### 6. Expected Response
```bash
<SOAP-ENV:Envelope
	xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/">
	<SOAP-ENV:Header/>
	<SOAP-ENV:Body>
		<ns2:getCountryResponse
			xmlns:ns2="http://spring.io/guides/gs-producing-web-service">
			<ns2:country>
				<ns2:name>Spain</ns2:name>
				<ns2:population>46704314</ns2:population>
				<ns2:capital>Madrid</ns2:capital>
				<ns2:currency>EUR</ns2:currency>
			</ns2:country>
		</ns2:getCountryResponse>
	</SOAP-ENV:Body>
</SOAP-ENV:Envelope>
```
### DEMO
![image](https://github.com/user-attachments/assets/e6d942ba-fbe9-407d-927b-202678060168)

## Authors

- [@lxgonzalez](https://github.com/lxgonzalez)
