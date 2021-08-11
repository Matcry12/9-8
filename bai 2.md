# 9-8
     const quarterOf = (month) => {
  
     if (month <= 3) {
       month = 1
    }
    else if (month <=6) {
        month = 2
    } 
    else if (month <= 9) {
       month = 3
    }
    else if (month <=12) {
        month = 4
    }
  
  return month
}
