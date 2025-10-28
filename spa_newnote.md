```mermaid
graph TD;
   Server-->|GET: spa|Browser 
   Server-->|Get: main.css| Browser
   Server-->|Get: spa.js| Browser
   Server-->|Get: data.json| Browser
   Browser-->|POST: new_note_spa| Server
```