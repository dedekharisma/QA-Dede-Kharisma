# QA-Dede-Kharisma

API Testing for CRUD Features

This project contains a set of API tests that verify the CRUD (create, read, update, delete) functionality of a target API. The tests are implemented using the Postman tool and are organized into a Postman collection.
Requirements

    Postman

Set up

    Clone or download this repository
    Open Postman and import the crud-tests.postman_collection.json file from the repository
    Import the environment testing-qa.postman_environment.json from the repository

Running the tests

    In the Postman app, navigate to the "Collections" tab and select the "CRUD Tests" collection
    Click the "Run" button to run all tests in the collection

Test details

The tests in this collection verify the following CRUD functionality of the target API:

    Create a new resource
    Read the newly created resource
    Update the newly created resource
    Delete the newly created resource

Each test includes one or more assertions to verify the correctness of the API's response.
Additional information

    The target API for these tests is https://reqres.in/.
    The tests use HTTP methods and URLs appropriate for each CRUD operation (e.g. POST /api/users to create a new user, GET /api/users/{id} to read a user).
    The tests save and retrieve resource IDs using Postman's global variables feature.
    The tests verify the response status and content for each request.

Contact

For questions or issues related to this project, please contact the repository owner.
