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
