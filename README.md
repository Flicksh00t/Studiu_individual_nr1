## 🧰 Comenzi Git utilizate în cadrul proiectului

Pe parcursul dezvoltării aplicației, am utilizat un set de comenzi Git esențiale pentru
gestionarea fișierelor, actualizarea documentației și publicarea proiectului pe GitHub.

### 1. Inițializarea și configurarea repository-ului
- `git init` – inițializează un repository Git în folderul proiectului.
- `git remote add origin <url>` – conectează repository-ul local la GitHub.

### 2. Gestionarea fișierelor și a modificărilor
- `git add <fișier>` – adaugă un fișier în zona de staging.
- `git add .` – adaugă toate fișierele noi și modificate.
- `git commit -m "mesaj"` – salvează modificările cu un mesaj descriptiv.

### 3. Trimiterea proiectului pe GitHub
- `git push -u origin main` – publică proiectul pe branch-ul *main*.
- `git push` – trimite ulterior commit-urile noi pe GitHub.

### 4. Actualizarea resurselor proiectului
- `git add images/*.png` – adăugarea screenshot-urilor din prototip.
- `git commit -m "Adăugat screenshot-uri ale prototipului"` – commit pentru noile imagini.
- `git add README.md` – actualizarea documentației README.
- `git commit -m "Adăugat link la prototip și descriere comenzi Git"` – commit pentru actualizarea textului.

### 5. Gestionarea branch-urilor și integrarea prin Pull Request
- `git checkout -b prototip-figma` – creare și comutare pe branch-ul dedicat prototipului.
- `git add prototip.md` / `git add .` – adăugarea fișierelor noi (document .md și screenshot-uri).
- `git commit -m "Prototip..."` – salvarea modificărilor în branch.
- `git push -u origin prototip-figma` – publicarea branch-ului pe GitHub.
- **Pull Request** – creat din interfața GitHub pentru a integra branch-ul în *main*.
- **Merge Pull Request** – finalizarea integrării branch-ului în ramura principală.

## 📂 Structura proiectului

Proiectul este organizat în două branch-uri principale: `main` și `prototip-figma`, fiecare conținând documente specifice componentei pe care o reprezintă.

---

### Branch: `main`
Conține documentele principale ale lucrării:

- **Document SRS(Magazin Online de încălțăminte).docx** – Documentul cu cerințele software (SRS).
- **Modulele Aplicatiei.docx** – Descrierea detaliată a modulelor aplicației.
- **RaportStdiv1AplDeckstop.docx** – Raportul general al lucrării.
- **README.md** – Documentația generală a proiectului pe GitHub (descriere, comenzi Git, organizare).

---

### Branch: `prototip-figma`
Conține materialele aferente prototipului interfeței:

- **Prototip.md**  
  – include **link-ul** către prototipul Figma  
  – include **screenshot-urile** prototipului  
  – descriere scurtă a elementelor vizuale
---

### Branch: `diagrame-uml`
Conține documentul DiagrameUML.md cu imaginile ale diagramele UML
- **DiagrameUML.md**
  - include diagramele UML(UseCase + Activity) în format PNG.
 
---

## 📝 Observații
- Branch-ul `main` conține documentele principale de proiectare și raportare.  
- Branch-ul `prototip-figma` este dedicat **designului**, pentru a păstra proiectarea UI separată de documentele tehnice.  
- Integrarea branch-urilor se face prin **Pull Request**, atunci când este necesar.

## 👤 Colaboratori
- Flicksh00t(Bodrug Tudor) - organizator GitHub
- MariusDemian54(Demian Marius-Pavel) - colaborator
- GhergheNicrasov(Nicrasov Gheorghe) - colaborator
- trappy228(Sclear Mihail) - colaborator


