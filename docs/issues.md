# Issues

Create, list, or update issues for a repository.

## Create a New Issue

```http
POST /repos/{owner}/{repo}/issues
Content-Type: application/json
Authorization: Bearer YOUR-TOKEN
```

### Example Request Body

```json
{
  "title": "Bug: Unexpected logout",
  "body": "I was logged out after 5 minutes of inactivity.",
  "labels": ["bug"]
}
```

## Response

```json
{
  "id": 1,
  "title": "Bug: Unexpected logout",
  "state": "open"
}
```
