**Python API application Development**

- Uvicorn or gunicorn is the API server

- FastAPI() function is the Initialize API

- @app.get,put,post("/") #("/") root endpoint
Any def function written will be the function of the endpoint.

```python
def read_root():
return {"helloworld"}
```
