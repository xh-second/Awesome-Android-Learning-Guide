##哈希表的特点，性能和使用场景
@(数据结构，算法)

###定义
哈希表，又叫散列表，是能够通过给定的关键字的值访问到具体对应的值的一种数据结构，也就是说，把关键字映射到一个表中的位置来直接访问记录，以加快访问速度。
通常，我们把这个关键字叫做 Key，对应的值称为 Value，所以也可以说是通过 Key 访问一个映射表来得到 Value 的地址，而这个映射表，也叫做散列函数或哈希函数，存放记录的数据叫做哈希表。
这里面有个特殊情况，就是不同的 Key，可能会访问到同一个地址，这叫做碰撞，也就是产生了冲突。

###哈希函数冲突的几种解决办法
1. 开放地址法（开放寻址法）
2. 再哈希法
3. 链地址法
4. 建立一个公共溢出区

###哈希表的特点
1. 访问速度很快
2. 需要额外的空间
3. 无序
4. 可能会产生碰撞

###哈希表的适用场景
1. 缓存，比如浏览器的 Cookies，Android 中的 SharePerference 等
2. 快速查找
