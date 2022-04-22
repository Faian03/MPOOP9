@startuml
package "POOP9" #DDDDDD{
    class  SerVivo{
        -nombre:String
        -edad:int
        -peso:float
        +dormir()
        +comer()
    }

    class Mascota{
        -color:String
        -raza:String
        -tamaño:char
        +jugar()
        +correr()
    }

    abstract class claseAbstracta{
        +metodoAbstracto:String
    }

    interface interfaz{
        +metodoInterfaz:double
    }

    SerVivo <|-- Mascota
}

@enduml