```mermaid
graph TD;
    A[Start] --> B{Is it working?};
    B -- Yes --> C[Continue working];
    B -- No --> D[Fix the issue];
    D --> B;
```