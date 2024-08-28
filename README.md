# Secondary-Constructor-Example-in-Kotlin-


class introduction{
   val name: String ,
    val age: Int
    
    constructor(x: String , y: Int){
        this.name= x
        this.age = y
    }
    constructor(x : String) {
        this.name= x
        this.age = 0
    }
    constructor() {
        this.name =  "abc"
        this.age = 30
    }
    
    fun info(){
        println("My name is $name and my age is $age")
    }
}






fun main() {
    val a = xyz()
    a.intro("Jashan")
    
    
    val r = introduction("Jashan" )
    r.info()
    
    
    
}

