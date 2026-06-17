### Step 1

Change directory to _run_ folder

```
cd run

```

### Step 2

Run the pip install command below:

```
python -m pip install -r requirements.txt -q

```

### Step 3

Run the command below to run Uvicorn

```
uvicorn main:app --host 0.0.0.0 --port 8000 --reload

```

### Step 4

Access localhost webpage

```
http://localhost:8000/

```
