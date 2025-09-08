```mermaid
  classDiagram
      class Item {
        +String title
        +String author
        +int year
        +getInfo()
      }
  
      class Book {
        +String ISBN
        +borrow()
        +return()
      }
  
      class DVD {
        +int duration
        +play()
      }
  
      class Library {
        +String name
        +addItem()
        +removeItem()
      }
  
      Item <|-- Book
      Item <|-- DVD
      Library o-- Item : contains
```
