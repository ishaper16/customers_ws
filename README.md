# customers_ws

The project contains APIRouter KIT generated mule flows with related API Kit generated MUnit test suite.

### Getting Started

Download zip file to machine. Then extract the zip file.
Then import it to Anypoint Studio as "Anypoint Studio" -> "Anypoint Studio Project from External Location", giving the extracted location as "Project Root" in "Mule Import" wizard.

### Prerequisites

Need to have installed Anypoint Studio (3.8) in machine

### Deploying

Run customers_api.xml under src/main/app.

### Unit Testing

Run customers_api-apikit-test.xml under src/test/munit.

### Testing

After the app is deployed,
- APIKit console will be opened in Anypoint Studio.
- Otherwise can invoke the rest services invoking
      - GET request http://localhost:8081/api/customers/ 
      - POST request http://localhost:8081/api/customers/

for more requests check the src/main/api/customers_api.raml file in source.
