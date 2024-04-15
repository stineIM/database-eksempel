<h2>Dette må du endre/sjekke før du starter: </h2>
<ul>
 <li>Databasefila di må ligge i mappa saman med kodefilene</li>
 <li>I index.js: Linje 8: Pass på at navnet databasefila er rett </li>
 <li>I index.js: Linje 51 og 61  henter informasjon frå tabellen users, og kolonnene firstname, lastname, email og password. Desse må passe til din tabell og dine kolonner. </li>
 <li>Filene du trenger å konsentrere deg om er: index.js og filene i views og public-mappene. Du trenger ikkje tenke på dei andre filene. </li>
 <li>Filene som ligger i "views"-mappa, er dei sidene som viser informasjonen på nettsida. Dei er skrevet i HTML og bruker ejs for å skrive JavaScript for å hente informasjon frå databaser.</li>
</ul>

<h2>Styling:</h2> 
Linke til css: <link rel="stylesheet" href="/style.css">
Denne må inn i .ejs filene der du ønsker å ha css

<h2>Bilder:</h2> 
Bildefiler må inn i public-mappa. Gjerne i ei mappe som heiter images. (public/images)

<h2>Starte applikasjonen: </h2>
<ul>
 <li>Bruk CMD (command prompt) og naviger til mappa.</li>
 <li>Kommando: node index.js</li>
</ul>

<h2>Database:</h2> 
<ul>
 <li>Databasefila eg bruker heiter database.db</li>
 <li>Tabellane eg bruker er:</li>
 <ul>
  <li>users: </li>
   <ul>
  <li>firstname</li>
  <li>lastname</li>
  <li>email</li>
  <li>password</li>
   </ul>
  <li>products</li>
  <ul>
   <li>name</li>
   <li>category</li>
   <li>price</li>
 </ul>
</ul>
