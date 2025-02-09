# Sprint25-Styling-A

/styleem
│── /chatgptstyles
│   │── basiclayout.css
│   │── navbar.css
│   │── ...
│── /deepseekstyles
│   │── basiclayout.css
│   │── navbar.css
│   │── ...
│── /mystyles
│   │── basiclayout.css
│   │── navbar.css
│   │── ...
│── /sandbox
│   │── test.css
│── /html
│   │── basiclayout.html
│   │── navbar.html
│   │── ...



---

### **4. Use Branches for Feature Development**
If you have one repo with multiple projects:
- `main` – Stable code
- `feature/frontend-design` – HTML/CSS/JS work
- `feature/rust-api` – Rust API implementation
- `feature/mongodb-integration` – MongoDB setup

Switch branches using:
```sh
git checkout -b feature/mongodb-integration
