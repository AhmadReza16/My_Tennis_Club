Django Project
# 🎾 My Tennis Club

A beginner-level Django web application to manage a tennis club's members.  
This is the **first version** of the project and will be expanded over time.  
It allows admins to **add** and **delete** members through a simple interface.

---

## 🚀 Features

- 🧾 Register new club members  
- ❌ Delete existing members  
- 📋 View list of all members  
- 🧼 Clean and minimal UI (based on w3schools style)  
- 🧠 Easy to understand and build upon

---

## 🛠️ Technologies Used

- [Python 3](https://www.python.org/)  
- [Django Framework](https://www.djangoproject.com/)  
- [HTML & CSS](https://www.w3schools.com/)  
- SQLite (default Django database)

---

## 📂 Project Structure

```
My_Tennis_Club/
├── members/
      └──  templates/        # Django app for managing members
├── my_tennis_club/          # Project settings and URLs

├── manage.py


```

---

## ⚙️ Installation & Setup

1. **Clone the repo**:
   ```bash
   git clone https://github.com/AhmadReza16/My_Tennis_Club.git
   cd My_Tennis_Club
   ```

2. **Create virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install django
   ```

4. **Run migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Start development server**:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and go to:
   ```
   http://127.0.0.1:8000/
   ```


---

Admin login :
User : admin
Password : abcd1234

---

## 📚 Learning Source

This project was built as a learning exercise by following tutorials and documentation on:  
👉 [w3schools Django tutorial](https://www.w3schools.com/django/)

---

## 🧠 Future Improvements

- [ ] Add member detail pages  
- [ ] Implement member editing  
- [ ] Add user authentication for admins  
- [ ] Add member search or filter  
- [ ] Style with Bootstrap or Tailwind

---

## 👤 Author

**AhmadReza**  
GitHub: [@AhmadReza16](https://github.com/AhmadReza16)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
