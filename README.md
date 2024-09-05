# UserStorys

 1. First Item
 2. Second Item
 3. Third Item
 4. Fourth Item 
> Blockquotes
**_This text is both bold and italic_**
Make Koshin Free Again

1. Make a app

2. Break it down

3. Make it work

4. Hello

5. Osman top dog

# Heres is intructions on how to make classdiagram in MD

```mermaid
classDiagram
    class User {
        +String name
        +String email
        +login()
        +logout()
    }

    class Product {
        +String name
        +float price
        +String description
        +addToCart()
    }

    class Cart {
        +List~Product~ items
        +addItem(Product item)
        +removeItem(Product item)
        +calculateTotal()
    }

    User "1" --> "1" Cart
    Cart "1" --> "*" Product





