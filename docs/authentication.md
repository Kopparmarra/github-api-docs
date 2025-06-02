# Authentication

To interact with the GitHub API, you need to authenticate using a personal access token.

## Basic Example

```http
GET /user
Host: api.github.com
Authorization: Bearer YOUR-TOKEN
```

## Response

```json
{
  "login": "octocat",
  "id": 1,
  "name": "The Octocat"
}
```

👉 Replace `YOUR-TOKEN` with your actual GitHub token.
