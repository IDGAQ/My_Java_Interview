### 在问完Hashmap和ConcurrentHashmap之后：

### 问：
### 线程安全为什么选择CCHashMap?
### 答：
###     1.并发度高
###     2. 结构（*Array+LinkedList+Red_Black_Tree数组+链表+红黑树*）
###     3. 锁的原理 （*segment,单独锁，上锁时使用的是CAS Synchronized*）

