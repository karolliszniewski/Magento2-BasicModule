![Screenshot 2024-10-12 194533](https://github.com/user-attachments/assets/da920fad-85b3-4b7b-a17f-b123d55643e6)


```
graph TD
    A[Controller] -->|Executes| B[Module]
    B -->|Configures| C[Layout]
    C -->|Defines| D[Block]
    D -->|Renders| E[content.phtml]
    C -->|References| E
    F[View] -->|Contains| E
    B -->|Uses| F
    D -->|Uses| F

    style A fill:#f9d71c,stroke:#333,stroke-width:2px
    style B fill:#f9963b,stroke:#333,stroke-width:2px
    style C fill:#eb4034,stroke:#333,stroke-width:2px
    style D fill:#3489eb,stroke:#333,stroke-width:2px
    style E fill:#34eb77,stroke:#333,stroke-width:2px
    style F fill:#a134eb,stroke:#333,stroke-width:2px
```
