# Users

Retrieve profile and user data.

## Get a User

```http
GET /users/{username}
```

### Example

```http
GET /users/octocat
```

### Response

```json
{
  "login": "octocat",
  "id": 1,
  "bio": "Just a friendly octopus"
}
```
