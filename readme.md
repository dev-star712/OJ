# EduOJ Frontend

This repository back-end and front-end code of EduOJ.

EduOJ is an online evaluation system for teaching, which combines online program evaluation and editing management functions to achieve efficient class and homework management and automatic homework verification.

---

## Deployment

---

### Download & Run

```sh
sudo apt-get update
sudo apt-get install -y git
git clone https://github.com/dev-star712/frontend.git
cd frontend
npm run serve
```

```sh
sudo apt-get update
sudo apt-get install -y git
git clone https://github.com/dev-star712/backend.git
cd backend
go run . [command] (serve , ...)
```

---

### Build

#### Backend
```sh
go run build
```

#### Frontend
```sh
yarn build
```
---

### Configuration

#### Backend
Copy `backend/config.yaml.example` to `backend/config.yaml`. And modify `backend/config.yaml` according to your system configuration.

#### Frontend
Copy `frontend/src/config/config.example.js`, modify `title` and `apiUrl` if necessary

```
cp src/config/config.example.js src/config/config.js
```

---

### Deployment

Deploy `dist` to the `nginx` root directory, and configure the `/api` directory to the backend reverse proxy

---

### Documentation

Our documentation is still under construction.

---