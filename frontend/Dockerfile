# Set a Go runtime as the base image
FROM golang:1.17

# Working directory inside the container
WORKDIR /simple-fortune-cookie/frontend

# Frontend application
COPY . .

# Build the frontend binary
RUN go build -o frontend

# Expose the port
EXPOSE 8080

# Running the frontend binary
CMD ["./frontend"]