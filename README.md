## Installation

### Backend - Flask

Install the dependencies
make sure MySql is installed and change the username, password for the db
```sh
cd backend
> py -3 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

For running the app

```sh
flask run
```

### Frontend - Angular

Install the dependencies
```sh
cd ui
npm install
```

For running the app

```sh
ng s -o
```