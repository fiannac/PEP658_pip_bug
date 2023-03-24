To reproduce the bug, follow these steps:
```
1) python -m http.server
2) pip install --trusted-host 0.0.0.0 --index-url=http://0.0.0.0:8000/simple/ zipp -v --force-reinstall --no-cache
 ```