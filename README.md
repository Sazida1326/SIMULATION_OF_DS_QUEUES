# 🏦 SRM Bank – Queue Management System

### A Data Structures-Based Queue Simulation

A web-based **Queue Management System** developed to demonstrate the implementation of the **Queue Data Structure** using the FIFO (First In, First Out) principle.

The application simulates a bank token management system where customers can generate tokens, join a waiting queue, and get served in the order they arrive.

---

## 📌 Project Overview

The SRM Bank Queue Management System provides a simple and interactive way to understand how queues work in real-world applications.

The system uses JavaScript to implement queue operations and HTML and CSS to provide an interactive user interface.

It demonstrates how customers are managed efficiently using the FIFO principle, ensuring that the first customer to enter the queue is the first one to be served.

## ✨ Features

- **Generate Tokens:** Customers can generate unique tokens automatically.
- **FIFO Queue Management:** Customers are served in their arrival order.
- **Serve Next Customer:** Removes the first customer from the waiting queue.
- **Now Serving Display:** Shows the token number currently being served.
- **Waiting Queue:** Displays all customers waiting for their turn.
- **Next Up Preview:** Shows the next customer in line.
- **Live Statistics:** Displays the total number of tokens issued and customers waiting.
- **Queue Capacity:** Supports a maximum of 20 customers in the waiting queue.
- **Interactive Dashboard:** Provides a clean and user-friendly interface.
- **Empty Queue Handling:** Displays appropriate messages when no customers are waiting.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the application |
| CSS3 | Styling and dashboard design |
| JavaScript | Queue implementation and application logic |
| Data Structures | FIFO Queue operations |

## 🧠 Data Structure Used

### Queue – FIFO (First In, First Out)

A Queue is a linear data structure that follows the FIFO principle.

**FIFO means First In, First Out**, where the element inserted first is removed first.

The project implements the following queue operations:

| Operation | Description |
|---|---|
| Enqueue | Adds a new customer to the queue |
| Dequeue | Removes the customer at the front |
| Front | Returns the first customer in the queue |
| isEmpty | Checks whether the queue is empty |
| Size | Returns the number of customers waiting |

### Example

Suppose three customers generate tokens:

```text
T-1 → T-2 → T-3
```

The queue will look like:

```text
FRONT                  REAR
  T-1  →  T-2  →  T-3
```

When the Serve Next button is clicked, T-1 is removed.

```text
FRONT           REAR
  T-2  →  T-3
```

This demonstrates the FIFO principle.

## ⚙️ System Workflow

1. The customer clicks the **Get Token** button.
2. The system generates a unique token number.
3. The token is inserted at the rear of the queue.
4. The waiting count and queue display are updated.
5. The **Serve Next** button removes the token at the front.
6. The Now Serving section displays the served token.
7. The system updates the queue and statistics automatically.

## 📂 Project Structure

```text
SIMULATION_OF_DS_QUEUES/
│
├── index.html       # Application structure
├── style.css        # User interface styling
├── script.js        # Queue implementation and logic
├── settings.json    # Project configuration
└── README.md        # Project documentation
```

## 🚀 How to Run the Project

Follow these steps to run the application locally:

**Step 1:** Clone the repository.

```bash
git clone https://github.com/sazidavelluri/SIMULATION_OF_DS_QUEUES.git
```

**Step 2:** Navigate to the project directory.

```bash
cd SIMULATION_OF_DS_QUEUES
```

**Step 3:** Open the project folder.

**Step 4:** Run `index.html` in any modern web browser.

You can also open the folder using Visual Studio Code and run it with the Live Server extension.

No additional dependencies or installations are required.

## 📊 Applications of Queue Data Structure

Queue data structures are widely used in real-world applications, including:

- Bank customer management systems
- Printer job scheduling
- CPU process scheduling
- Ticket booking systems
- Customer service management
- Network data handling

## 🎯 Learning Outcomes

Through this project, we understand:

- The fundamental concepts of Queue Data Structures.
- Implementation of FIFO operations using JavaScript.
- Enqueue and Dequeue operations.
- Handling empty and full queue conditions.
- Connecting data structures with real-world applications.
- Developing interactive web applications using HTML, CSS, and JavaScript.

## 👩‍💻 Developer

**Velluri Sazida**

B.Tech – Computer Science and Engineering

SRM University – AP

**GitHub:** [@sazidavelluri](https://github.com/sazidavelluri)

## 🔗 Repository

[SIMULATION_OF_DS_QUEUES – GitHub Repository](https://github.com/sazidavelluri/SIMULATION_OF_DS_QUEUES.git)

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with ❤️ to demonstrate the practical implementation of Data Structures.**
