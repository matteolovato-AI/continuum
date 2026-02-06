# continuum - ITS Project

Benvenuti nella repository del progetto! Per mantenere il codice pulito e funzionante, seguiamo queste regole.

## 🛠 Setup Iniziale
1. `python3 -m venv venv`
2. `source venv/bin/activate` (Mac/Linux) o `venv\Scripts\activate` (Windows)
3. `pip install -r requirements.txt`

## 🚀 Come contribuire (Git Workflow)
Il branch `main` è protetto. Segui questi passaggi per ogni modifica:

1. **Aggiorna il locale:** `git pull origin main`
2. **Crea un branch:** `git checkout -b feat/nome-tua-funzione`
3. **Lavora e salva:** `git commit -am "Descrizione di cosa hai fatto"`
4. **Invia il branch:** `git push origin feat/nome-tua-funzione`
5. **Apri una Pull Request:** Vai su GitHub e clicca su "Compare & pull request".

## 📂 Struttura Cartelle
- `/ai_service`: Codice inferenza e Docker
- `/training`: Script per allenare i modelli
- `/src`: Funzioni comuni (Crop, utility)
- `/web`: Frontend del sito

