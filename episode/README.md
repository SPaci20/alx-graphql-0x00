# Episode GraphQL Queries

This repository contains GraphQL queries to fetch episode information from the Rick and Morty API using specific episode IDs.

## Files

- `episode-id-1.graphql` - Query for episode with ID 1
- `episode-id-1-output.json` - Expected output for episode ID 1
- `episode-id-2.graphql` - Query for episode with ID 2
- `episode-id-2-output.json` - Expected output for episode ID 2
- `episode-id-3.graphql` - Query for episode with ID 3
- `episode-id-3-output.json` - Expected output for episode ID 3
- `episode-id-4.graphql` - Query for episode with ID 4
- `episode-id-4-output.json` - Expected output for episode ID 4

## Query Structure

All queries follow the same structure:
- Use the `episode(id: ID!)` field
- Request the following fields: `id`, `name`, `air_date`, `episode`

## Field Descriptions

- `id`: The unique identifier for the episode
- `name`: The name of the episode
- `air_date`: The air date of the episode
- `episode`: The code of the episode (e.g., "S01E01")

## How to Execute

You can execute these queries against the Rick and Morty GraphQL endpoint: