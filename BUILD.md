# Bella Napoli

**Erstellt:** 03.06.2026 22:01  
**Stadt:** Fulda  
**Branche:** Restaurant  
**Typ:** 📄 Landing Page  
**Basis:** `firma_website_neu`  
**Runden:** 5  
**Score:** 95/100  

## Ausgangslage
- Website: ❌ Keine
- Mobile: ❌
- Social: ❌
  - 🏪 Restaurant — lokaler Betrieb
  - ❌ Keine Website — maximales Potenzial
  - 📞 Nur telefonisch erreichbar — braucht Web!

## Deployment
- **GitHub:** https://github.com/BastianScherzinger/bella-napoli
- **Railway:** https://railway.app/project/fcea0536-170a-4a93-a78f-0ab631fe9048
- **Live:** https://web-production-671c9.up.railway.app

## Start
```bash
cd bella_napoli
pip install -r requirements.txt
cp .env.example .env  # Werte eintragen!
python manage.py migrate
python manage.py runserver
```

## Railway ENV (automatisch gesetzt)
```
SECRET_KEY, DEBUG=False, DATABASE_URL
SITE_NAME=Bella Napoli
SITE_URL=https://...-production.up.railway.app
CLOUDINARY_URL, CLOUDINARY_FOLDER
```

---
*Django Dream Team 🤖*