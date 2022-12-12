
```mermaid
sequenceDiagram
User->>browser: Submit note
browser->>server:Request URL: https://studies.cs.helsinki.fi/exampleapp/new_note
server->>browser:HTML code
browser->>server:Request URL: https://studies.cs.helsinki.fi/exampleapp/main.css
server->>browser:main.css
browser->>server:https://studies.cs.helsinki.fi/exampleapp/main.js
server->>browser:main.js
browser->>server:https://studies.cs.helsinki.fi/exampleapp/data.json
server->>browser: {content"....", date: "2022-12-09T11:09:02.907Z"}
browser->>User:render to page
```
