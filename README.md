# JWT + Refresh Token + RBAC Authentication Backend

This is a Flask-based authentication backend with:
- JWT authentication
- Refresh tokens
- Role-based access control
- PostgreSQL support
- Docker support

##  Run Locally
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
flask db init
flask db migrate -m "init"
flask db upgrade
python run.py
