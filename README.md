# Login Flowchart - My First Project

This is my first flowchart project. It shows the logic of a simple Login System step by step.

## How Login Works

1. START
2. Enter Username and Password
3. Check if Username and Password are correct?
4. If YES -> Login Successful -> Go to Dashboard -> END
5. If NO -> Show "Wrong Username or Password" -> Try Again? 
6. If Try Again = YES -> Go back to Step 2
7. If Try Again = NO -> END

## Flowchart

```mermaid
flowchart TD
    A[START] --> B[Enter Username and Password]
    B --> C{Correct?}
    C -->|Yes| D[Login Successful]
    D --> E[Go to Dashboard]
    E --> F[END]
    C -->|No| G[Show Wrong Username or Password]
    G --> H{Try Again?}
    H -->|Yes| B
    H -->|No| F
