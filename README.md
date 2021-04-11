# DV-Commerce

------

- Create a virtual environment: 

```bash
# example
python3 -m venv env
```

- Install all required packages:

```bash
pip install -r requirements.txt
```

- Migrate models

```bash
./manage.py migrate
```

- Create admin account

```
./manage.py createsuperuser
```

- Front-end setup

```
cd frontend
yarn install
```

