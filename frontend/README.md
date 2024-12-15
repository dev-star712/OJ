# EduOJ Frontend

This repository stores the front-end code of EduOJ.

EduOJ is an online evaluation system for teaching, which combines online program evaluation and editing management functions to achieve efficient class and homework management and automatic homework verification.

> Currently used in Beijing University of Technology.

---

## Deployment

---

### Download & Build

```sh
sudo apt-get update
sudo apt-get install -y git
git clone https://github.com/EduOJ/frontend.git
cd frontend
yarn build
```

---

### Configuration

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