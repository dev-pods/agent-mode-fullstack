---
applyTo: "app/frontend/**"
---
# Diretrizes do Frontend React

## Estrutura da App Frontend REACT

Certifique-se de que em todos os comandos apontamos para o diretório `app/frontend`

```bash
npx create-react-app app/frontend --template cra-template --use-npm

npm install bootstrap --prefix app/frontend

# Add the Bootstrap CSS import at the very top of src/index.js:
sed -i "1iimport 'bootstrap/dist/css/bootstrap.min.css';" app/frontend/src/index.js

npm install react-router-dom --prefix app/frontend

```
