# Javascript 的prototype与__proto__

prototype 是每一个函数上的一个属性，比如Object，Function，String，Array，Boolean，Number，又或者是自定义个函数function Animal(){}，prototype本身也是对象

__proto__是每个对象上的一个属性，默认指向生成这个对象的函数的prototype，作用是可以中访问prototype中的属性（可认为是继承）

因为函数也是对象，是由Function生成的对象，所以Object，Function，String，Array，Boolean，Number，Animal，都有一个__proto__指向Function的prototype

所以搜到了下面的几张图，可以更进一步说明他们的关系
​​

​​![image](https://github.com/user-attachments/assets/a39a26c7-00d8-4254-806b-9c09dc713e88)


![image](https://github.com/user-attachments/assets/361ff657-a91f-415a-8167-384637dd5a2f)
