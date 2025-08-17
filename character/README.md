# Character Queries – Rick and Morty GraphQL API

This directory contains GraphQL queries and their outputs for retrieving character information from the [Rick and Morty API](https://rickandmortyapi.com/graphql).

## Instructions

- Each `.graphql` file contains a query for a specific character by ID (1, 2, 3, 4).
- Each `.json` file contains the expected output for the corresponding query.

Fields retrieved: `id`, `name`, `status`, `species`, `type`, `gender`.


# Paginated Character Queries – Rick and Morty GraphQL API

This directory demonstrates how to retrieve paginated lists of characters from the Rick and Morty GraphQL API.  
For each page (1–4), a GraphQL query is provided, along with the output returned by the API.

**Fields retrieved for each character:**  
- `id`
- `name`
- `status`
- `image`

**How to use:**
- Use the Rick and Morty GraphQL Playground: https://rickandmortyapi.com/graphql
- Paste the query from the relevant `.graphql` file.
- The corresponding `.json` file shows the expected output.

---

## Example Query (for page 1):

```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
```

---

Repeat for pages 2, 3, and 4!


# Episode Query – Rick and Morty GraphQL API

This directory contains a sample GraphQL query for retrieving episode details from the Rick and Morty API using the episode-page-1.graphql file.

It also includes sample character pagination queries and their outputs for reference.

## Files

- `episode-page-1.graphql`
- `characters-page-1-output.json`
- `characters-page-2.graphql`
- `characters-page-2-output.json`
- `characters-page-3.graphql`
- `characters-page-3-output.json`
- `characters-page-4.graphql`
- `characters-page-4-output.json`

## Usage

- Use the Rick and Morty GraphQL Playground: https://rickandmortyapi.com/graphql
- Paste the query from the relevant `.graphql` file.
- The corresponding `.json` file shows the expected output.

**Episode query example:**

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
