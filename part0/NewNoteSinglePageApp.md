```mermaid
sequenceDiagram
    participant browser
    participant server
    browser->>browser: add new_note_spa to json
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
```
