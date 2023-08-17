# Use a Go runtime as the base image
FROM golang:1.17

# Working directory inside the container
WORKDIR /app/backend

# Backend application
COPY . .

# Build the backend binary
RUN go build -o backend

# Expose the port
EXPOSE 8081

# Running the backend binary
CMD ["./backend"]