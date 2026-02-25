# Student API with Gin

A simple RESTful API built with Go and Gin framework.

---

## How to Run

1. Open a web browser and go to  
   👉 https://go.dev/dl
2. Download the **Windows installer (.msi)**  
   Example: `go1.26.0.windows-amd64.msi`
3. Open **Command Prompt**
    - Press **Win + R**
    - Type `cmd`
    - Press **Enter**
4. Run the following command:
    ```bash
    go version
    ```
    Expected Output
    ```test
    go version go1.26.0 windows/amd64
    ```
5. Clone the Repository run the following command:
    ```bash
    git clone https://github.com/6609650434/go-api-gin-lab.git
    ```
6. move into the project directory run the following command:
    ```bash
    cd go-api-gin-lab
    ```
7. Install dependencies
    ```bash
    go mod tidy
    ```

8. Run the application
    ```bash
    go run main.go
    ```

Server will start at:
http://localhost:8080

---

## Available API Endpoints

GET /students  
GET /students/:id  
POST /students  
PUT /students/:id  
DELETE /students/:id