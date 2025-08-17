# GraphQL Character Retrieval Project

## Overview

This project demonstrates how to use GraphQL to retrieve specific character information from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) using unique character IDs. It is designed as a practical introduction for learners to understand the structure of GraphQL queries and how to fetch targeted data from a public API.

The Rick and Morty API provides rich data about characters, episodes, and locations from the popular animated series. By leveraging GraphQL, users can request only the data they need, making queries more efficient and flexible compared to traditional REST APIs.

## Objective

- To teach learners how to construct GraphQL queries for retrieving detailed information about individual characters.
- To illustrate the process of querying by character ID and selecting relevant fields.
- To provide hands-on examples of both query syntax and the expected JSON output.

## Features

- Example queries for characters with IDs 1, 2, 3, and 4.
- Each query fetches the following key fields: `id`, `name`, `status`, `species`, `type`, and `gender`.
- Example output files show the API's response in JSON format for each query.
- Directory structure designed for clarity and ease of use.

## Why Use GraphQL?

GraphQL is a query language for APIs that allows clients to request exactly the data they need and nothing more. Key advantages include:
- **Precision:** Retrieve only the fields you specify.
- **Efficiency:** Minimize data transfer by avoiding unnecessary information.
- **Flexibility:** Combine multiple related data requests into a single query.

## Repository Structure

- `character/`: Contains all sample queries and outputs related to character retrieval.
    - `README.md`: Instructions and documentation for the character queries.
    - `character-id-X.graphql`: GraphQL query files (`X` is the character ID).
    - `character-id-X-output.json`: Example output files for each query.

## Getting Started

1. Review the queries in the `character` directory.
2. Use the [Rick and Morty GraphQL Playground](https://rickandmortyapi.com/graphql) to run the queries.
3. Compare your results to the provided JSON output files.

## Learning Outcomes

By exploring this project, you will learn:
- How to write GraphQL queries to retrieve specific data by ID.
- How to select specific fields in your query.
- How to interpret and use the JSON output returned by a GraphQL API.
- The benefits of GraphQL in modern API development.

## References

- [Rick and Morty GraphQL API Documentation](https://rickandmortyapi.com/documentation)
- [GraphQL Official Website](https://graphql.org/)
- [GraphQL Introduction for Beginners](https://graphql.org/learn/)

---

Feel free to explore the `character` directory for hands-on examples and start experimenting with your own queries!
