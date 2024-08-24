# Django Crud (Backend)

Using django crud, you can perform create, read, update and delete operation from user side.

Features included in the module:
- User is able to create username and password.
- User is able to retrieve username and id.
- User is able to update the password.
- User is able to delete own data.

## Features

- [x] This module includes migrations.
- [ ] This module includes environment variables.
- [x] This module requires manual configurations.
- [ ] This module can be configured with module options.


## API Details
List of api's endpoints with params needed for these apis.

| Api Name                       | Param        | Description                                                    |
| ------------------------------ |:------------:|:---------------------------------------------------------------|
| `GET` `/trial/users`| -No Params-  | Returns users list. |
| `POST` `/trial/users`|  object `{username: "", password: ""}`  |Create a new user.|
| `PUT` `/trial/users/{user_id}`|  object `{username: "", password: ""}`  |Update the users detail.|
| `DELETE` `/trial/users/{user_id}`|  -No Payload  |Delete the users detail.|

## Module Specifications
Here is the [Module Specification GitHub LINK](httpshttps://github.com/hatim-javed-99/django-crud), which provides more information about the 
Crud actual intentions.
