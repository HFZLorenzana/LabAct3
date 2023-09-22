fun main() {
    val age = 22
    val days_in_a_year = 365
    val age_in_days = age * days_in_a_year
    val name = "Hans"
    val border = "%=%="
    val repeat = 6
    
    printBorder(border, repeat)
    println("Happy Birthday! Hans :D")
	printBorder(border, repeat)
    println("I am ${age_in_days} days old!")
    println("${age_in_days} days old is the best age to learn Kotlin!")
    
    // Let's print a cake!
    println("   ,,,,,   ")
    println("   |||||   ")
    println(" =========")
    println("@@@@@@@@@@@")
    println("{~@~@~@~@~}")
    println("@@@@@@@@@@@")
    println("")
    println("${name} is already ${age_in_days} days old!")
   
}

fun printBorder(border: String, timesToRepeat: Int) {
    repeat(timesToRepeat){
        print(border)
    }
    println()
}
