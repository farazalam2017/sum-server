# Sum Server of Harkirat Cohort

A simple Express.js server deployed on Render to provide various API functionalities such as fetching todos, calculating sums, interest, and generating random notifications.

## 🌍 Live Demo

[**Visit the Live Site**](https://sum-server-faraz.onrender.com)

---

## 🚀 API Endpoints

### 📌 Get Random Todos

- **Endpoint:** `/todos`
- **Example:** [Click here](https://sum-server-faraz.onrender.com/todos)
- **Description:** Returns a random set of todos.

### 📌 Get Specific Todo

- **Endpoint:** `/todo?id=1`
- **Example:** [Click here](https://sum-server-faraz.onrender.com/todo?id=1)
- **Description:** Fetches a specific todo item by ID.

### 📌 Get Sum of Two Numbers

- **Endpoint:** `/sum?a=10&b=20`
- **Example:** [Click here](https://sum-server-faraz.onrender.com/sum?a=10&b=20)
- **Description:** Returns the sum of two numbers passed as query parameters.

### 📌 Calculate Simple Interest

- **Endpoint:** `/interest?principal=1000&rate=5&time=2`
- **Example:** [Click here](https://sum-server-faraz.onrender.com/interest?principal=1000&rate=5&time=2)
- **Description:** Calculates simple interest based on given principal, rate, and time.

### 📌 Get Random Notifications

- **Endpoint:** `/notifications`
- **Example:** [Click here](https://sum-server-faraz.onrender.com/notifications)
- **Description:** Generates random numbers for different notification types.

---

## 🛠 How to Use Locally

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-username/sum-server.git
cd sum-server
```

### 2️⃣ Install Dependencies

```sh
npm install
```

### 3️⃣ Start the Server

```sh
node server.js
```

Server will run at `http://localhost:3000`.

---

## 🤝 Contributing

We welcome contributions! If you want to improve the project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Added new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a **Pull Request (PR)**.

---

## ⭐ Support the Project

If you find this project helpful, consider giving it a **star ⭐** on GitHub!

[![Star on GitHub](https://github.com/farazalam2017/sum-server)]

---

Happy Coding! 🚀
