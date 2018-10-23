# account-api

## Build with [Go](https://golang.org/) 1.11.1

### Install package dependencies

Navigate to the project folder and execute the following command to install all the external dependencies:

```
go get ./...
```

### Running the project

To initialize the service use the following command.

```
go run main.go
```

By default the service will be listening and serving HTTP on port 8080.

### Building the executable

Please build the executable to the bin folder to avoid commits of the binary files and run them from that folder.

```
go build -o bin/account-api
./bin/account-api
```