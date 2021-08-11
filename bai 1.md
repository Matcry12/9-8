# 9-8
fun feast(beast: String, dish: String): Boolean {

    
    if (beast[0]==dish[0] && beast[beast.lastIndex]==dish[dish.lastIndex]) {
     return true
} else {
         return false
    }
}
