```mermaid
sequenceDiagram
browser->>server:Request URL: https://studies.cs.helsinki.fi/exampleapp/spa
server->>browser:HTML code
browser->>server: https://studies.cs.helsinki.fi/exampleapp/main.css
server->>browser:main.css
browser->>server: Request URL:  https://studies.cs.helsinki.fi/exampleapp/spa.js
server->>browser: main.js
browser->>server:https://studies.cs.helsinki.fi/exampleapp/data.json
server->>browser:updated json data
```
