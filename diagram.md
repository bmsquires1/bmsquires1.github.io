``` mermaid
    flowchart LR
        subgraph The hero in this story is an 
          armoured-knight
        end
        subgraph The hero comes across two foes 
          snakes
          trolls
        end
        subgraph Did the hero win
          defeatedsnakes
          losttosnakes
        end
        subgraph Did the hero win
          defeatedtrolls
          losttotrolls
        end

        armouredknight --> snakes
        armouredknight --> trolls
        snakes --> defeatedsnakes
        snakes --> losttosnakes
        trolls --> defeatedtrolls
        trolls --> losttotrolls
        

```
