# SOAP Project: StringManipulationService

This project demonstrates a SOAP-based web service for string manipulation. Follow the steps below to run the service and access its WSDL.

## Prerequisites

Ensure you have the following installed:
- Java 8 or higher
- IntelliJ IDEA or another Java IDE
- Apache Maven (if using Maven for dependency management)

## Running the Service

1. **Clone the repository** (if applicable) or ensure the project is set up in your development environment.
   
2. **Run the SOAP Publisher:**
   - Open the project in your IDE.
   - Locate the `SoapPublisher.java` class.
   - Right-click the class and choose **Run 'SoapPublisher.main()'** or use the appropriate run configuration.
   - This will start the SOAP service locally.

3. **Access the WSDL:**
   - Open a browser and navigate to:  
     `http://localhost:8080/StringManipulationService?wsdl`
   - This will display the WSDL (Web Services Description Language) for the SOAP service.

## SOAP Operations

Once the service is running, you can interact with the various string manipulation operations defined in the WSDL.

## Troubleshooting

- **Service not starting**: Ensure no other services are using port `8080`. If needed, change the port in the `SoapPublisher.java` file.
- **WSDL not accessible**: Double-check that the service is running and listening on the correct port. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
