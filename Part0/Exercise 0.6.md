## Diagram 3


```mermaid
sequenceDiagram;
    participant browser
    participant server
     
    browser->>+server: GET https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    server-->>-browser: Add the data
    
    browser->>+server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    server-->>-browser: [{ "content": "Hola desde Ecuador!!", "date": "2023-10-4" }, ... ]
  
```
