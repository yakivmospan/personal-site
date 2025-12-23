Personal webpage based on MkDocs:
https://www.mkdocs.org/user-guide/deploying-your-docs/


Install python3, then create a virtual env in project folder:
```
python3 -m venv .venv
```

Activate it:
```
source .venv/bin/activate
```

Install all requirements:
```
pip install -q -r requirements.txt
pip install mkdocs mkdocs-material
```

Run local server:
```
mkdocs serve
```
