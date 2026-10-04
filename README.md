# Restful Booker API Testing

API testing project for the Restful Booker API using Postman and Newman.

## Tools

- Postman
- Newman
- JavaScript
- GitHub Actions
- REST API

## Testing Scope

The project covers:

- Authentication
- Create Booking
- Retrieve Booking
- Retrieve Booking IDs
- Update Booking
- Partial Update
- Delete Booking
- Positive and negative scenarios
- Response validation
- Data persistence validation

## Automation

Postman test scripts validate:

- HTTP status codes
- Response structure
- Data types
- Response body values
- Booking persistence
- Authentication
- CRUD operations

## Running the Tests

```bash
newman run restful-booker-api-testing/Restful-Booker.postman_collection.json
