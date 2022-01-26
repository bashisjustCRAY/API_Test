
# Sample API Postman Collection

Postman Collection demonstrating how to perfom various activities using this [Sample](https://swapi.dev/api/planets/3) REST API.
Activities demonstrated here are writing tests for various responses, creating a mock server and also mocking its response, creating a negative test and lastly, creating a GitHub action to automatically run the collection on every push.

## Installation

To use the sample collection, click the following button to import the API as a collection:

[![Run in Postman](https://s3.amazonaws.com/postman-static/run-button.png)](https://www.getpostman.com/collections/1db495c7ba7b1dd2f7b9)

You can also download the collection file from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).

## Usage

The collection is arranged in folders according to the API endpoints and mock endpoint.

The request to perform this test is a GET method (but for the negative test later, a POST method is used).  From the collection (SampleWork), the test tab shows different tests for verifying header response, body response, JSON schema and reponse time in milliseconds. The negative test changes the method to a POST method and therefore inputs a request body, this immediately gives a 405 status code response and from the test tab also the different tests to verify these responses can be seen.

The mock test the name object is changed to something different and this is hosted [here](https://c9e56645-6747-4471-ad8d-e258c4416f18.mock.pstmn.io/api/planets/3). More information on mock servers and tests can also be found [here](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/).

More information on managing Postman environments and variables can be found [here](https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables).
