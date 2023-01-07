# 知识点

## 1.栈区 堆区 静态区

 ### 栈区：局部变量、函数形参等临时变量

 ### 堆区：动态内存分配的    malloc/free  calloc     realloc

 ### 静态区：全局变量  静态变量

### 2.while的break代表终止while 而不是终止本次，继续下一次

### 3.while 的continue代表跳过后面的代码，直接去判断部分，判断是否执行下一次

### 4.解决scanf缓冲区有\n的方法

可以再%c前 键入一个空格 (优解)

```c
eg:``scanf``(``" %c"``,&a);
```

> 这里 %c前面加上空格键 可以消除前面所有的空白字符(输入的时候就会消化掉这个\n) 从而 不需要使用getchar()去吞\n



2. 清理缓冲区

   ```c
   getchar（）；
   ```


3. 清理缓冲区的多个字符

   ```
   int tmp=0;
   while((tmp=getchar())!='/n')
   {
   	;
   }
   ```

   

### 5.随机数不随机的话，可将时间戳设置为种子

### 6.printf          **Return Value** Each of these functions returns the number of characters printed, or a  negative value if an error occurs.  每个函数返回打印的字符数，如果发生错误则返回负值。





