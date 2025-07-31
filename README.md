## 🗒️ Keeper App

A simple and responsive note-taking application built using **React.js**. Users can add and delete short notes — just like sticky notes — with a clean and intuitive UI.

### 📌 Features

* 📝 Create notes with a **title** and **content**
* ❌ Delete notes with a single click
* 💾 Uses **React state** to manage the note list dynamically
* 💡 Real-time updates of UI using React’s component rendering
* 📦 Clean and modular component structure

---

### 🚀 Live Demo

> *(If deployed)*
> [Click here to view the Keeper App](https://your-demo-link.com)

---

### 🛠️ Tech Stack

* [React.js](https://reactjs.org/)
* HTML5 + CSS3 (inline and external styles)
* JavaScript (ES6+)
* Optional: FontAwesome / Google Fonts for icons & fonts

---

### 📁 Folder Structure

```
src/
├── components/
│   ├── App.jsx
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Note.jsx
│   └── CreateArea.jsx
├── index.js
└── styles.css
```

---

### 🧠 How It Works

* `App.jsx` holds the state and renders all notes.
* `CreateArea` contains the input form and calls `onAdd()` to add a new note.
* `Note` is a reusable component for displaying individual notes with a delete button.
* The `deleteNote` function removes notes based on their index using `.filter()`.

---

### 🧪 Getting Started

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/keeper-app.git
cd keeper-app
```

#### 2. Install Dependencies

```bash
npm install
```

#### 3. Run the App

```bash
npm start
```

> App will run on [http://localhost:3000](http://localhost:3000)

---

### 📸 Preview

![Keeper App Screenshot](https://via.placeholder.com/800x400?text=Keeper+App+Preview)

---

### 🤝 Contribution

Pull requests are welcome! Feel free to open issues and suggest improvements.

---

### 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


