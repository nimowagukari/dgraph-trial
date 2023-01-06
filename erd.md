サービス依存関係
``` mermaid
erDiagram
    service ||--o{ service : "dependencies"
    service {
        serviceCode string
        serviceName string
        parentServices service
        childServices service
        description string
    }
```
