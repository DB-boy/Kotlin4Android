#kotlin4Android

kotlin for Android developers

###变量&常量

   * var 变量  
   * val 常量


###函数
>    fun 引起  如无返回，不需要加
   有返回值在参数列表后    ： 返回值类型
   
 ```  
  //eg. 
    fun name(xx: Int) : Int{
        return xx+2
    }
 // 如只有一行表达式 eg.
     fun name(xx: Int) : Int = xx+2 
     
 ```
 * 参数默认值
 
   在方法的参数里，可以定义一个参数的默认值
   
   ```
    fun getAge(age : Int =18): Int{
     return age
     }
   ```