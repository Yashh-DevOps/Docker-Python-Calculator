# 🐳 dOckerized Python Calculator

This project demonstrates how to **containerize a simple Python calculator application using Docker**.
It is a beginner-friendly project to understand **Docker images, containers, and running Python applications inside Docker**.

---

## 📌 Project Overview

The calculator allows users to perform basic arithmetic operations:

* Addition
* Subtraction
* Multiplication
* Division

The Python application is packaged inside a **Docker container**, allowing it to run consistently across different environments.

---

## 🛠 Technologies Used

* **Python 3**
* **Docker**

---

## 📂 Project Structure

```
calculator/
│
├── main.py 	       # Python calculator script
├── Dockerfile         # Docker configuration
└── README.md          # Project documentation
```

---

## ⚙️ Prerequisites

Before running this project, make sure you have installed:

* Docker
* Python (optional if running locally)

Check Docker installation:

```
docker --version
```

---

## 🏗 Build the Docker Image with the custom name and path

Navigate to the project directory and run:

``` 
docker build -t python-calculator .
```

This command will:

* Read the **Dockerfile**
* Build a Docker image
* Tag it as **python-calculator**

---

## ▶️ Run the Docker Container

Run the container interactively:

```
docker run -it python-calculator
```

The calculator program will start inside the container.

---

## 💻 Example Usage

```
Enter first number: 10
Enter operator (+,-,*,/): *
Enter second number: 5

Result: 50
