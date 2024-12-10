# 📖 **Learn Blockchains by Building One**

[![Build Status](https://travis-ci.org/dvf/blockchain.svg?branch=master)](https://travis-ci.org/dvf/blockchain)

This repository contains the source code for the post on [Building a Blockchain](https://medium.com/p/117428612f46) and the book **[Learn Blockchain by Building One](https://www.amazon.com/Learn-Blockchain-Building-Understanding-Cryptocurrencies/dp/1484251709)** available on Amazon.  

---

## 📘 **About the Book**  

The book provides a practical introduction to blockchain by teaching readers how to build one from scratch. It's designed to enhance your understanding of **cryptocurrencies** and **blockchain technology** through hands-on programming.  

📍 **Get the book:** [Amazon](https://www.amazon.com/Learn-Blockchain-Building-Understanding-Cryptocurrencies/dp/1484251709)  
📂 **Source code for the book:** [GitHub Repository](https://github.com/dvf/blockchain-book)  

---

## 🚀 **Quick Start**

### **Python Implementation**

1. **Prerequisites**  
   - Install [Python 3.6+](https://www.python.org/downloads/).  
   - Install [pipenv](https://github.com/kennethreitz/pipenv):  
     ```bash
     pip install pipenv
     ```

2. **Clone the Repository**  
   ```bash
   git clone https://github.com/dvf/blockchain.git
   cd blockchain
   ```

3. **Install Dependencies**  
   ```bash
   pipenv install
   ```

4. **Run the Blockchain Server**  
   ```bash
   pipenv run python blockchain.py
   ```
   Run additional instances with different ports:  
   ```bash
   pipenv run python blockchain.py -p 5001
   pipenv run python blockchain.py --port 5002
   ```

---

### **Docker Implementation**

1. Clone this repository:  
   ```bash
   git clone https://github.com/dvf/blockchain.git
   cd blockchain
   ```

2. Build the Docker container:  
   ```bash
   docker build -t blockchain .
   ```

3. Run the container:  
   ```bash
   docker run --rm -p 80:5000 blockchain
   ```

4. To add more instances, vary the public port number before the colon:  
   ```bash
   docker run --rm -p 81:5000 blockchain
   docker run --rm -p 82:5000 blockchain
   ```

---

### **C# Implementation**

For developers using **C#**, follow these steps:  

1. **Install Visual Studio**  
   Download the [free Visual Studio IDE (Community Edition)](https://www.visualstudio.com/vs/).  

2. **Open the Solution File**  
   Open `BlockChain.sln` using **File > Open > Project/Solution** in Visual Studio.  

3. **Set Up and Run**  
   - Right-click `BlockChain.Console` in Solution Explorer.  
   - Select **Set As Startup Project**.  
   - Press **F5** or click **Start** to run.  

The program runs in a console window and is controlled via HTTP, similar to the Python version.  

---

## 🛠️ **Features**

- Build a basic blockchain from scratch in **Python** and **C#**.  
- Learn core blockchain principles: proof of work, transactions, and mining.  
- Interact with the blockchain using HTTP endpoints.  
- Explore scalability by running multiple blockchain nodes with Docker.  

---

## 🤝 **Contributing**

Contributions are always welcome!  

### Steps to Contribute:  
1. Fork the repository.  
2. Create a feature branch:  
   ```bash
   git checkout -b feature-name
   ```  
3. Commit and push your changes:  
   ```bash
   git push origin feature-name
   ```  
4. Submit a pull request.  

---

## 📬 **Contact**

Have questions or feedback? Feel free to reach out!  
- **GitHub**: [@dvf](https://github.com/dvf)  
- **Twitter**: [@dvf](https://twitter.com/dvf)  

---

This version is structured for clarity and readability, includes icons for better visualization, and offers a professional touch. Let me know if you'd like further refinements! 😊
