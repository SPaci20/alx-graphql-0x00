# Character GraphQL Queries

This repository contains GraphQL queries to fetch character information from the Rick and Morty API using specific character IDs.

## Files

- `character-id-1.graphql` - Query for character with ID 1
- `character-id-1-output.json` - Expected output for character ID 1
- `character-id-2.graphql` - Query for character with ID 2
- `character-id-2-output.json` - Expected output for character ID 2
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-3-output.json` - Expected output for character ID 3
- `character-id-4.graphql` - Query for character with ID 4
- `character-id-4-output.json` - Expected output for character ID 4

## Query Structure

All queries follow the same structure:
- Use the `character(id: ID!)` field
- Request the following fields: `id`, `name`, `status`, `species`, `type`, `gender`

## How to Execute

You can execute these queries against the Rick and Morty GraphQL endpoint: