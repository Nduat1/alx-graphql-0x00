# Character Queries — Rick and Morty GraphQL

This project contains GraphQL queries to retrieve information about specific characters from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql). The queries focus on fetching characters by ID and retrieving a paginated list of characters.

## Files

### 🔍 Query Specific Character by ID

Each `.graphql` file includes a query to fetch details of a single character using the `character(id: ID!)` field. The corresponding `.json` file contains the actual response from the API.

| File Name | Description |
|-----------|-------------|
| `character-id-1.graphql` | GraphQL query for character with ID 1 |
| `character-id-1-output.json` | JSON output of character ID 1 query |
| `character-id-2.graphql` | GraphQL query for character with ID 2 |
| `character-id-2-output.json` | JSON output of character ID 2 query |
| `character-id-3.graphql` | GraphQL query for character with ID 3 |
| `character-id-3-output.json` | JSON output of character ID 3 query |
| `character-id-4.graphql` | GraphQL query for character with ID 4 |
| `character-id-4-output.json` | JSON output of character ID 4 query |

### 📋 Query Paginated List of Characters

These files query the `characters(page: Int)` field to get a list of characters per page.

| File Name | Description |
|-----------|-------------|
| `characters-page-1.graphql` | Fetches characters on page 1 |
| `characters-page-1-output.json` | JSON output for page 1 |
| `characters-page-2.graphql` | Fetches characters on page 2 |
| `characters-page-2-output.json` | JSON output for page 2 |
| `characters-page-3.graphql` | Fetches characters on page 3 |
| `characters-page-3-output.json` | JSON output for page 3 |
| `characters-page-4.graphql` | Fetches characters on page 4 |
| `characters-page-4-output.json` | JSON output for page 4 |

## Fields Queried

### Character by ID

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

### Characters List

- `id`
- `name`
- `status`
- `image`

## GraphQL Endpoint

All queries are run against:
[GraphQL Playground](https://rickandmortyapi.com/graphql)



## How to Run the Queries

1. Open the [GraphQL Playground](https://rickandmortyapi.com/graphql)
2. Paste the contents of any `.graphql` file
3. Run the query to view the output
4. Copy and save the result in the corresponding `*-output.json` file


