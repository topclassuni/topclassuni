graph TD
    You["👨‍💻 Developer Profile"]

    %% Backend
    You --> Backend
    Backend --> Go
    Go --> "HTTP"
    Go --> Gin

    Backend --> Kotlin
    Kotlin --> "Spring Boot"

    Backend --> JavaScript_BE["JavaScript"]
    JavaScript_BE --> Express
    JavaScript_BE --> Bun

    Backend --> PHP
    PHP --> WordPress_BE["WordPress (Backend)"]

    %% Frontend
    You --> Frontend
    Frontend --> React
    Frontend --> Svelte
    Frontend --> "Next.js"
    Frontend --> WordPress_FE["WordPress (Frontend)"]

    %% Component Libraries
    You --> "Component Libraries"
    "Component Libraries" --> ShadCN["shadcn/ui"]
    "Component Libraries" --> DaisyUI

    %% General Purpose
    You --> "General Purpose Languages"
    "General Purpose Languages" --> Python
    "General Purpose Languages" --> JavaScript_GP["JavaScript"]
    "General Purpose Languages" --> TypeScript

    %% Databases
    You --> Databases
    Databases --> SQL
    SQL --> PostgreSQL
    SQL --> MySQL
    SQL --> SQLite

    Databases --> "Document DB"
    "Document DB" --> MongoDB

    Databases --> "Graph DB"
    "Graph DB" --> Neo4j

    Databases --> "Realtime DB"
    "Realtime DB" --> PocketBase

    %% Mobile
    You --> Mobile
    Mobile --> "React Native"

    %% Education
    You --> Education
    Education --> "Sri Lankan A/L"
    "Sri Lankan A/L" --> "AAB (Maths Stream)"

    Education --> "Sri Lankan O/L"
    "Sri Lankan O/L" --> "9 A's"
