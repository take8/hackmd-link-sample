# シーケンスのサンプル

[![hackmd-github-sync-badge](https://hackmd.io/0wha4KpqSWSmSd_0BZ7uRQ/badge)](https://hackmd.io/0wha4KpqSWSmSd_0BZ7uRQ)

```mermaid
%%{init:{'theme':'dark'}}%%
sequenceDiagram
    participant Alice
    participant John

    rect rgb(191, 223, 255)
    note right of Alice: Alice calls John.
    Alice->>+John: Hello John, how are you?
    rect rgb(200, 150, 255)
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    end
    John-->>-Alice: I feel great!
    end
    Alice ->>+ John: Did you want to go to the game tonight?
    John -->>- Alice: Yeah! See you there.
```
