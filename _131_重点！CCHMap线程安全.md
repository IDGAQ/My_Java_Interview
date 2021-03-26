### 在问完Hashmap和ConcurrentHashmap之后：\

![hh](https://via.placeholder.com/15/c5f015/000000?text=+) 
### 问：
### 线程安全为什么选择CCHashMap？

![hh](https://via.placeholder.com/15/c5f015/000000?text=+) 
### 答：
###     1.并发度高
###     2. 结构（*Array+LinkedList+Red_Black_Tree数组+链表+红黑树*）
###     3. 锁的原理 （*segment,单独锁，上锁时使用的是CAS Synchronized*）

