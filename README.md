# FlowTicket 🎟️: Ticket Sales and Management System

[![GitHub Language Count](https://img.shields.io/github/languages/count/Fabio-Menjivar/FlowTicket)](https://github.com/Fabio-Menjivar/FlowTicket)
[![GitHub Top Language](https://img.shields.io/github/languages/top/Fabio-Menjivar/FlowTicket)](https://github.com/Fabio-Menjivar/FlowTicket)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/Fabio-Menjivar/FlowTicket)](https://github.com/Fabio-Menjivar/FlowTicket/commits)

**FlowTicket** is a desktop application designed for the **complete management and sale of tickets** for events like concerts. Developed using **C# Windows Forms**, it offers a robust and user-friendly interface to handle sales, transaction cancellations, and event history tracking.

---

## ✨ Key Features

* **Event Management:** Administration of data for concerts and other events.
* **Ticket Purchase:** Dedicated interface for selecting events and completing ticket purchases.
* **Transaction Cancellation:** Module for voiding transactions and processing refunds.
* **History and Inquiry:** Functionality to review sales history and event dates.
* **Login System:** A login module to ensure secure access and user authentication.
* **Layered Organization:** Code structure utilizing Data Access Objects (DAO) for a clear separation of business logic and database access.

---

## 💻 Technologies Used

| Area | Technology | Purpose |
| :--- | :--- | :--- |
| **Platform** | **C# / .NET Framework** | Main language and development environment. |
| **UI** | **Windows Forms (WinForms)** | Desktop user interface development. |
| **Data Access** | **Data Access Objects (DAO)** | Abstraction layer for database interaction. |
| **Database** | **SQL Server** (or similar) | Data persistence for tickets, concerts, and user information. |

---

## ⚙️ Installation and Configuration

Follow these steps to set up and run **FlowTicket** in your local environment.

### Prerequisites

* **Visual Studio** (Recommended for C# WinForms projects).
* **.NET Framework** (Version compatible with the project, typically 4.x or higher).
* **SQL Server** (or the database system used).

### Detailed Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Fabio-Menjivar/FlowTicket.git](https://github.com/Fabio-Menjivar/FlowTicket.git)
    cd FlowTicket
    ```

2.  **Open the Solution:**
    Open the C# solution file in Visual Studio.

3.  **Configure the DB Connection:**
    * Locate the database connection string (usually in `App.config` or within the data access layer in the `Data Access Object` folder).
    * Adjust the string to point to your local SQL Server instance.

4.  **Build and Run:**
    * Build the solution to resolve all dependencies.
    * Execute the project (Press `F5` or the **Start** button in Visual Studio).

---

## 🤝 Contribution

If you wish to contribute to improving this ticket sales system, you are welcome!

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/new-functionality`).
3.  Make your changes and commits following good practices.
4.  Open a clear and concise Pull Request.
