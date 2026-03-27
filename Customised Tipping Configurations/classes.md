---
Class Diagram
---
```mermaid
classDiagram
  Tipping Configuration "1" *-- "1..*" Action
  Tipping Area "1" o-- "1" Tipping Configuration
  Tipping Area "1" o-- "1" Dump Area
  Destination <|-- Dump Area
```
