```mermaid
graph TD;
   Browser-->|POST: new_note|Server 
   Server-->|GET: notes|Browser 
   Server-->|Get: main.css| Browser
   Server-->|Get: main.js| Browser
   Server-->|Get: data.json| Browser
```