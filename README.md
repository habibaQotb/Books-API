
# Books REST API

A simple REST API built with Node.js and Express that manages an in-memory collection of books on port `5000` for CSE343 Lab 8.

## Getting Started

Follow these instructions to get a local copy up and running on your machine.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your system[cite: 26].

### Installation & Running

1. **Clone the repository**
```bash
git clone [https://github.com/habibaQotb/books-rest-api.git](https://github.com/habibaQotb/books-rest-api.git)

```

2. **Navigate to the project directory**

```bash
cd books-rest-api

```

3. **Install dependencies**

```bash
npm install

```

4. **Start the server**

```bash
node server.js

```

(Or use `node --run dev` if you have a `dev` script configured in `package.json`.)

The server will run at [http://localhost:5000](http://localhost:5000).

## Endpoints

* `GET /books` — Returns all books


* `GET /books/:id` — Returns a single book by `id`, or `404` if not found


* `POST /books` — Adds a new book (`title` and `author` required; returns `400` if missing, or `201` with the created book)


* `DELETE /books/:id` — Removes a book by `id`, or returns `404` if not found



```

### Next Steps
Save this as `README.md` in your repo root, update `<repo-name>` in the clone/directory commands if you chose `books-api` or `cse343-lab8-books-api`, and push it to GitHub.

