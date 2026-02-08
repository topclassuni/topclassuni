```mermaid
graph LR
    You["👨‍💻 Developer Profile"]

    %% Backend
    You --> Backend
    Backend --> GoLang["Go"]
    GoLang --> GoHTTP["HTTP"]
    GoLang --> Gin

    Backend --> KotlinLang["Kotlin"]
    KotlinLang --> SpringBoot["Spring Boot"]

    Backend --> JSBackend["JavaScript"]
    JSBackend --> Express
    JSBackend --> Bun

    Backend --> PHP
    PHP --> WPBackend["WordPress (Backend)"]

    %% Frontend
    You --> Frontend
    Frontend --> React
    Frontend --> Svelte
    Frontend --> NextJS["Next.js"]
    Frontend --> WPFrontend["WordPress (Frontend)"]

    %% Component Libraries
    You --> ComponentLibs["Component Libraries"]
    ComponentLibs --> ShadCN["shadcn/ui"]
    ComponentLibs --> DaisyUI

    %% General Purpose
    You --> GeneralPurpose["General Purpose Languages"]
    GeneralPurpose --> Python
    GeneralPurpose --> JS["JavaScript"]
    GeneralPurpose --> TS["TypeScript"]

    %% Databases
    You --> Databases
    Databases --> SQL
    SQL --> PostgreSQL
    SQL --> MySQL
    SQL --> SQLite

    Databases --> DocumentDB["Document DB"]
    DocumentDB --> MongoDB

    Databases --> GraphDB["Graph DB"]
    GraphDB --> Neo4j

    Databases --> RealtimeDB["Realtime DB"]
    RealtimeDB --> PocketBase

    %% Mobile
    You --> Mobile
    Mobile --> ReactNative["React Native"]


