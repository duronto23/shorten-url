
# Shorten-URL

A simple URL shortening service built with Go.

This project contains a backend API and database-related code for creating and resolving shortened URLs. A `docker-compose.yml` file is included to support running the application using Docker.

## Project Structure

```
shorten-url/
├── api/               # API-related code
├── db/                # Database-related code
├── docker-compose.yml # Docker Compose configuration
├── go.mod             # Go module definition
├── go.sum             # Go module dependency lock file
```

This structure reflects the visible top-level contents of the repository.

## Technologies

* Go
* Docker (via docker-compose)

## Getting Started

Clone the repository and install Go dependencies:

```bash
git clone https://github.com/duronto23/shorten-url.git
cd shorten-url
go mod tidy
```

Run the application:

```bash
go run ./...
```

If you prefer Docker:

```bash
docker-compose up --build
```


## Contributing

Issues and pull requests are welcome.
