```bash
conda create -p env python==3.7.6 -y
```

```bash
source activate ./env
```

```bash
docker build -t flask-app-sample:latest .
```

```bash
docker run -d -p 8082:8070 flask-app-sample
```

```bash
docker run -d -p 1000:3000 node-app-sample
```