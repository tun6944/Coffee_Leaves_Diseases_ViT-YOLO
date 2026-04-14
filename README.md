### Step 1
Run the pip install command below: 
```
cd run
pip install -r requirements.txt

```
### Step 2
Run the command below to run Uvicorn 
```
uvicorn main:app --host 0.0.0.0 --port 8000 --reload

```
### Step 3
Access localhost webpage
```
http://localhost:8000/
```