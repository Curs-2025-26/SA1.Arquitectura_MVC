# Arquitectura MVC

Aquest projecte segueix el patró Model‑Vista‑Controlador (MVC). Està estructurat en:
- models/: gestió de dades
- controllers/: lògica
- app.js: punt d'entrada de l'aplicació
Ideal per a aplicacions amb separació clara de responsabilitats.

## Funcionament en codespaces

Cal executar en el terminal

**npm install**

**npm start**


### REST Client. 

#### Petició POST per afegir un item

Al fitxer peticions.http, fes clic al botó “Send Request” que apareix damunt la línia POST....
Si no apareix el botó, instal·la l'extensió REST Client des del Marketplace de VS Code dins del mateix Codespaces.

#### Petició GET per llegir els items

Desde el navegador que obri el codespace es pot accedir a la petició GET /item
