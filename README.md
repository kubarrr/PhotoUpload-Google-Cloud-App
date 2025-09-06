# PhotoUpload

Warsaw Univeristy of Technology Cloud Computing project

The goal of this project is to build a cloud-based application using Google Cloud Platform and Terraform for infrastructure automation.
The application allows users to upload photos (e.g. from vacations) and then uses Google Cloud Vision API and Google Geocoding API to detect landmarks in the photo and retrieve their geographic coordinates. 
Infrastructure is deployed entirely through Terraform, ensuring that the setup process is automated, repeatable and easy to maintain. The architecture follows a microservices pattern where services are loosely coupled and communicate via event triggers and HTTP APIs. The design emphasizes scalability, fault tolerance and operational simplicity.

