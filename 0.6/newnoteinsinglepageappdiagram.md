```mermaid
sequenceDiagram
Note right of browser: form submits, spa.js appends new note and re-renders
Note right of browser: spa.js sends new note to server
browser->>server: POST, exampleapp/new_note_spa, {content: "example", date: "example"}
server->>browser: RES, 201
```
