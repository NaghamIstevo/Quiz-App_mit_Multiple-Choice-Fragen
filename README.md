

# Quiz-App mit Multiple-Choice-Fragen
Es wurde eine Quiz-App mit React erstellen, die Multiple-Choice-Fragen anzeigt und die Antworten der Nutzer bewertet.
Anforderungen:
•	Laden der Fragen aus einer JSON-Datei.
•	Bewertung und Anzeige des Ergebnisses.
•	Speichern des Highscores und des Spielerprofil im LocalStorage.
•	Verwendung von Redux zur Verwaltung der Quizfragen und Ergebnisse sowie React Router zur Navigation zwischen den verschiedenen Quizseiten.
•	Hinzufügen eines Timers für jede Frage.
•	Möglichkeit mehrere / eigene Quizze zu erstellen.
•   Responsive Design

## Technologien

- [React](https://reactjs.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Router DOM](https://reactrouter.com/)
- [localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)



## ▶️ Installation & Start
/* git clone https://github.com/NaghamIstevo/Quiz-App_mit_Multiple-Choice-Fragen.git */
cd ReactAbschlussProjekt_NaghamIstevo
npm install
npm install redux react-redux
npm install @reduxjs/toolkit
npm install react-router-dom
npm run dev


## 📁 Projektstruktur
src/
│
├── components/
│ ├── TimerChallange.jsx
│ ├── MainNavigation.jsx
│ ├── TimerChallange.module.css
│ ├── Header.jsx
│ ├── pages/
│ │ ├── QuizReduxComponent.jsx
│ │ ├── QuizReduxComponent.module.css
│ │ ├── ResultPage.jsx
│ │ ├── ResultPage.module.css
│ │ ├── CreateQuiz.jsx
│ │ ├── CreateQuiz.module.jsx
│ │ ├── HomePage.jsx
│ │ ├── HomePage.module.jsx
│ ├── error/
│ │ ├── Error.jsx
|
├── data/
│ └── MatheQuestion.json
│
├── store/
│ |── quizSlice.js
│ |── store.js
│
├── layout/
│ └── RootLayout.jsx
│
├── utils/
│ └── storage.js
│
├── App.jsx
├── main.jsx
└── index.css



## 🧠 Ideen für Erweiterungen

    Schwierigkeitsstufen und Kategorien
    Benutzer-Login mit externem Backend
    Mehrsprachigkeit (i18n)


## 👨‍💻 Autor

Nagham Istevo
