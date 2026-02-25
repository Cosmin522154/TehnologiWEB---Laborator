# TehnologiWEB---Laborator

1. Ce este o resura (resource) in aplicatia ta?
	
2. Da exemplu de un URI si explica componentele acestuia.
	
3. Care parti sunt statice si care sunt dinamice?
	
4. Este aplicatia ta document-centric sau interactive (sau ambele)? De ce?


1. Ce este o resura (resource) in aplicatia ta?:
   
În cadrul acestui „Campus Info Hub”, am tratat ca resursă orice unitate de informație independentă care deservește studentul. Concret, resursele mele sunt:
  Obiectele de date: Informațiile despre punctele de interes (Bibliotecă, Cantină), care sunt stocate și manipulate prin JavaScript.
  Fișierele media: Imaginile reprezentative pentru campus și iconițele care ajută la identificarea vizuală a categoriilor.
  Documentele web: Paginile HTML și stilurile CSS care sunt livrate utilizatorului la cerere.

3. Da exemplu de un URI si explica componentele acestuia.:
Pentru a accesa resursele aplicației, am utilizat o structură ierarhică de adrese. De exemplu:
  https://campusinfohub.ro/pages/librarie.html

  Protocolul (https://): Metoda securizată de comunicare între browser și server.
  Domeniul (campusinfohub.ro): Adresa unde este găzduit Hub-ul meu.
  Calea (/pages/): Directorul în care am organizat secțiunile secundare ale aplicației.
  Resursa finală (librarie.html): Fișierul specific care conține informațiile despre bibliotecă.

  3. Care parti sunt statice si care sunt dinamice?:
Am încercat să echilibrez performanța cu interactivitatea, împărțind aplicația astfel:
  Componente Statice: Header-ul, sistemul de navigație și textele descriptive (precum istoricul universității). Acestea sunt scrise direct în HTML și rămân constante indiferent de acțiunile utilizatorului.
  Componente Dinamice: Lista de resurse din pagina principală. Folosind app.js, conținutul se schimbă în timp real atunci când utilizatorul aplică filtrele (de exemplu, selectarea categoriei „Studiu”), fără a fi nevoie de reîncărcarea întregii pagini.

4. Este aplicatia ta document-centric sau interactive (sau ambele)? De ce?:
Consider că am dezvoltat o aplicație hibridă.
  Este document-centrică în paginile de detalii (Bibliotecă/Cantină), deoarece accentul cade pe citirea unor informații lungi și bine structurate.
  Este interactivă pe pagina index.html, unde am implementat funcționalități de filtrare prin care utilizatorul decide ce conținut vrea să vadă. Această abordare transformă site-ul dintr-o simplă broșură într-un instrument util de navigare rapidă prin resursele campusului.
