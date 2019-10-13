# Documentation of the REST Endpoints of the Bank User Transaction Application

| Verb   | Resource URI with Request Params | Effect                                   |
| ------ | -------------------------------- | ---------------------------------------- |
| GET | /users/{id}/acounts              | list all accounts belong to the user by user id. Requires, that the current user is the owner of the given account. |
| GET    | /accounts/{id}/transactions      |list all transactions belong to the selected account by account id. Requires, that the current account is the owner of the given transactions.  |                    |
