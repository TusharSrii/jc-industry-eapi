# jc-industry-eapi
This is the solution code for the part-1 JC assignment.

The API specification for "jc-industry-eapi" was initially developed in Anypoint Studio, subsequently committed to the Design Center, and then published to the Exchange.

The RAML was crafted with the specific project requirements in mind. To enhance security, all endpoints were equipped with the 'client-id-required' trait, ensuring authentication against the client_id and client_secret. Additionally, 'error-responses' were integrated into all endpoints to handle common error codes effectively.

Data types were meticulously defined based on the provided snippet, ensuring that request payloads are validated against these definitions. Resource types were employed in the specification to streamline and standardize common methods and codes, eliminating redundancy.

The RAML design strictly adheres to best practices, ensuring optimal quality and performance.

Subsequently, a new project named "jc-industry-eapi" was created, and the RAML was retrieved from the Design Center. After optimizing the project for production, externalizing properties, and applying best practices, the API was successfully deployed to CloudHub.

In the API Manager, implemented the 'client_id enforcement policy' and 'Rate limiting policy' (three requests every six seconds) to enhance security and control access.

Attaching below the Postman collection for the api which is deployed on cloudhub to test and review.<br />
[jc-mulesoft-industry-eapi-CH.postman_collection.json](https://github.com/TusharSrii/jc-industry-eapi/files/13196107/jc-mulesoft-industry-eapi-CH.postman_collection.json)
<br />
<br />


![api-manager](https://github.com/TusharSrii/jc-industry-eapi/assets/60851515/02b770ba-3b7b-4101-9851-599aa5c875bc)
<br />
![Screenshot 2023-10-28 204828](https://github.com/TusharSrii/jc-industry-eapi/assets/60851515/77dbdd31-1e9f-4309-a80b-fcc3b132bde5)
<br />
![Screenshot 2023-10-28 204902](https://github.com/TusharSrii/jc-industry-eapi/assets/60851515/081a0114-5422-4592-bd77-9cc8c7374710)
