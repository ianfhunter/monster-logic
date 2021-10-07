# Zombie / Undead Melee

**Likes:** Brains

**Dislikes:** Clerics

**Targets:** Closest

```mermaid
flowchart TD 
    A[Start] --> B{In Melee?}; 
    B -- Yes --> C[Attack];
    B -- No ----> D[Move Closer]
    D --> E{In Melee?}
    E -- Yes --> F[Attack];
    E -- No --> G[Move Closer];
```
