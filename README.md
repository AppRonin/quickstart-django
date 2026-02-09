# ⚡ quickstart-django

A **pre-configured Django starter template** with PostgreSQL ready to use — so you don’t need to reconfigure the same settings every time you start a new project.

Built to help you go from **clone → run → build features** as fast as possible.

## Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/AppRonin/quickstart-django.git
cd quickstart-django
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
source venv/bin/activate        # linux/mac
source venv\Scripts\activate    # windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Create `.env` file

```env
DEBUG=True
SECRET_KEY=your-secret-key

DB_NAME=your_db
DB_USER=your_user
DB_PASSWORD=your_pass
DB_HOST=localhost
```

### 5️⃣ Run server

```bash
python manage.py runserver
```

## Author

Developed by AppRonin, Full-Stack Developer.
