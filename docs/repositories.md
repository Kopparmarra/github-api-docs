# Repositories

Work with public or private repositories using these endpoints.

## List Repositories for a User

```http
GET /users/{username}/repos
Host: api.github.com
```

### Example

```http
GET /users/octocat/repos
```

### Sample Response

```json
[
  {
    "id": 1296269,
    "name": "Hello-World",
    "full_name": "octocat/Hello-World"
  }
]
```
