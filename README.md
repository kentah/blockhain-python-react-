**Activate the virtual environment**
```
source blockchain-env/bin/activate
```

**Install all packages***
```
pip3 install -r requirements.txt
```

**Run the tests**

Make sure to activate the venv.

```
python -m pytest backend/tests
```

**Run the application and API**
```
python -m backend.app
```

**Run a peer instance**
Make sure to activate the venv.
```
export PEER=True && python -m backend.app
```

**Run the frontend**

In the frontend directory:
```
npm run start
```

***Seed the backend with data***
Make sure to activate the venv
```
export SEED_DATA=True && python -m backend.app
```
