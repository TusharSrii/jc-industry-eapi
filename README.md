# jc-industry-eapi
This is the solution code for the part-1 JC assignment.

The API specification for "jc-industry-eapi" was initially developed in Anypoint Studio, subsequently committed to the Design Center, and then published to the Exchange.

The RAML was crafted with the specific project requirements in mind. To enhance security, all endpoints were equipped with the 'client-id-required' trait, ensuring authentication against the client_id and client_secret. Additionally, 'error-responses' were integrated into all endpoints to handle common error codes effectively.

Data types were meticulously defined based on the provided snippet, ensuring that request payloads are validated against these definitions. Resource types were employed in the specification to streamline and standardize common methods and codes, eliminating redundancy.

The RAML design strictly adheres to best practices, ensuring optimal quality and performance.

Subsequently, a new project named "jc-industry-eapi" was created, and the RAML was retrieved from the Design Center. After optimizing the project for production, externalizing properties, and applying best practices, the API was successfully deployed to CloudHub.

In the API Manager, I implemented the 'client_id enforcement policy' and 'Rate limiting policy' to enhance security and control access. Additionally, the API was synchronized using API autodiscovery.

Attaching the Postman collection for the api which is deployed on cloudhub to test and review.
[jc-mulesoft-industry-eapi-CH.postman_collection.json](https://github.com/TusharSrii/jc-industry-eapi/files/13196107/jc-mulesoft-industry-eapi-CH.postman_collection.json)
