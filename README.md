JOIN – Agile Kanban Board App
JOIN ist eine professionelle Task-Management-Anwendung, die nach agilen Prinzipien entwickelt wurde. Sie ermöglicht Teams eine effiziente Zusammenarbeit durch ein interaktives Kanban-Board, Aufgabensteuerung und Kontaktverwaltung.

Live Demo ansehen | Zum Repository

🚀 Kernfunktionen (Core Features)
Interaktives Kanban-Board
Drag-and-Drop: Intuitive Verschiebung von Aufgaben zwischen den Status-Spalten (To Do, In Progress, Awaiting Feedback, Done).

Echtzeit-Suche: Filtern von Aufgaben nach Titeln oder Beschreibungen in Sekundenbruchteilen.

Progress-Tracking: Visualisierung von Subtasks und Fortschrittsbalken direkt auf den Task-Karten.

Task Management
Full CRUD: Erstellen, Bearbeiten und Löschen von Aufgaben.

Personalisierung: Zuweisung von Prioritäten (Urgent, Medium, Low), Fälligkeitsdaten und Teammitgliedern.

Subtasks: Aufbrechen komplexer Aufgaben in prüfbare Checklisten.

Benutzer- & Kontaktverwaltung
Authentifizierung: Sicherer Login, Registrierung und Gast-Login-Funktion.

Adressbuch: Zentrales Management von Kontakten mit individueller Farbkodierung.

🛠️ Tech Stack
Frontend: JavaScript (ES6+), HTML5, CSS3 (SCSS)

Backend/Database: Firebase Realtime Database

Authentication: Firebase Auth

Version Control: Git & GitHub

👨‍💻 Mein technischer Beitrag
In diesem Team-Projekt war ich maßgeblich für die Kernlogik des Kanban-Boards verantwortlich:

Drag-and-Drop Engine: Implementierung der Logik zur dynamischen Verschiebung von DOM-Elementen und gleichzeitiger Aktualisierung der Datenbank-Indizes.

State Management: Sicherstellung, dass der App-Status bei jeder Änderung (z. B. Verschieben einer Karte) konsistent bleibt.

Responsive Design: Optimierung des Boards für Desktop- und Tablet-Ansichten.

👥 Das Team
Hanbit Chang: Lead Developer (Kanban Board, Drag-and-Drop Logic, Task Filtering)

Robin Gerth: Frontend Developer (User Authentication, Login/Sign-up Flow)

Elias Schäfer: Frontend Developer (Contact Management, UI Components)

⚙️ Installation
Repository klonen:

Bash
git clone https://github.com/DeinNutzername/join.git
In das Verzeichnis wechseln:

Bash
cd join
Die index.html im Browser öffnen (oder via Live Server in VS Code starten).
