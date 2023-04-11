
## Diagram 2


```mermaid
sequenceDiagram;
    participant browser
    participant server

    browser->>+server: GET https://studies.cs.helsinki.fi/exampleapp/spa;
    server-->>-browser: HTML document
    Note right of browser: RELOAD
  
```
