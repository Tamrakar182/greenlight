# Greenlight

A JSON API built following the "Let's Go Further" book by Alex Edwards.

## About

This project is called Greenlight — a JSON API for retrieving and managing information about movies.

## Getting Started

### Prerequisites

- Go 1.19 or later

### Installation

1. Clone the repository

2. Run the Development server
```bash
go run ./cmd/api
```

## Project Structure

- `bin` - Compiled application binary
- `cmd/api/` - Application-specific code for the API
- `internal/` - Ancillary non-application-specific code
- `migrations/` - SQL Migrations for database
- `remote` - Configration files and scripts for production server
- `go.mod` - project dependencies, versions and module paths
- `Makefile` - recipes for automating common administrative tasks

Built with Go following the patterns and practices from Alex Edwards' "Let's Go Further" book.