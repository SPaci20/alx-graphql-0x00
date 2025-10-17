# Character GraphQL Queries

This repository contains GraphQL queries to fetch character information from the Rick and Morty API.

## Single Character Queries

- `character-id-1.graphql` - Query for character with ID 1
- `character-id-1-output.json` - Expected output for character ID 1
- `character-id-2.graphql` - Query for character with ID 2
- `character-id-2-output.json` - Expected output for character ID 2
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-3-output.json` - Expected output for character ID 3
- `character-id-4.graphql` - Query for character with ID 4
- `character-id-4-output.json` - Expected output for character ID 4

## Paginated Characters Queries

- `characters-page-1.graphql` - Query for characters page 1
- `characters-page-1-output.json` - Expected output for page 1
- `characters-page-2.graphql` - Query for characters page 2
- `characters-page-2-output.json` - Expected output for page 2
- `characters-page-3.graphql` - Query for characters page 3
- `characters-page-3-output.json` - Expected output for page 3
- `characters-page-4.graphql` - Query for characters page 4
- `characters-page-4-output.json` - Expected output for page 4

## Query Structure

### Single Character Query
- Use the `character(id: ID!)` field
- Request the following fields: `id`, `name`, `status`, `species`, `type`, `gender`

### Paginated Characters Query
- Use the `characters(page: Int)` field
- Request pagination info: `count`, `pages`, `next`, `prev`
- Request character fields: `id`, `name`, `status`, `image`

## How to Execute

You can execute these queries against the Rick and Morty GraphQL endpoint: