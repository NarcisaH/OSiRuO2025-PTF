# OSiRuO2025-PTF
## Provizioniranje resursa u oblaku
Jednostavan primjer projekta izrađen u:
- 📖 Flask razvojnom okviru za razvoj web aplikacija u Python programskom jeziku, 
- 📖 Docker za kontejnerizaciju i 
- 📖 Render.com platfomi za hosting statičkih i dinamičkih web aplikacija u jezicima poput Java Script, Python i Ruby.


## Pokretanje u Docker:
- docker build -t flask-svemir .
- docker run -p 5000:5000 flask-svemir


## Deploy na [cloud](https://render.com/):
- Kreirati Web Service i povezai s GitHub repo
- Build command: pip install -r requirements.txt
- Start command: python app.py (Port: 5000)

Render automatski prepozna Dockerfile.

