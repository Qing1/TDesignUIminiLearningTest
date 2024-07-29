# TDesignUIminiLearningTest
TDesignUI组件库爬坑之路

![image](https://github.com/user-attachments/assets/399c0d2b-df52-49b3-bb1d-dc923275031c)
![image](https://github.com/user-attachments/assets/9bf73ff2-b425-43fd-8706-423e102e2906)

![image](https://github.com/user-attachments/assets/1ab908d2-a0ab-4565-afa0-d5e638f726f7)

起初以为是创建的linkOrderList是个数组的原因 然后使用link1()创建了一个对象 结果还是有这个警告。

 查看警告代码时候 发现 链接组件的黄色警告在前 link链接生成在后  所以应该是 猜测可能是linkOrderList还是空白的时候，组件已经初始化导致的
后面才执行了 this.link()函数 生成了 链接列表对象 
