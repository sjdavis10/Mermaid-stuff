# Mermaid-stuff
classDiagram
    class Car {
        +String model
        +String color
        +Engine engine
        +start_engine()
    }

    class Engine {
        +String type
        +int horsepower
        +start()
    }

    Car --> Engine : has a
