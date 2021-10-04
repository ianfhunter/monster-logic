# Goblin 

**Likes:** Gold, Goblins

**Dislikes:** Humans, Horses

**Targets:** Lowest Remaining HP

```mermaid
flowchart TD 
    A[Start] --> B{Is HP Critical?}; 
    B -- Yes --> C[Attempt Escape];
    B -- No ----> D{In melee?};

    D -- Yes --> E[Attack, Move Away, Hide];
    D -- No --> F{Is HP Low?};
    F -- Yes --> G[Disengage, Attempt Escape]
    F -- No --> H[Attack, Disengage, Move Away]
```
