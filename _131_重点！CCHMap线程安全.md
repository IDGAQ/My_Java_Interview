## 在问完Hashmap和ConcurrentHashmap之后：

# 问：线程安全为什么选择CCHashMap, 而不是加上Synchronized,lock的HashTable或Collection.Synchronized?

# 答：1.并发度高
#     2. 结构（*Array+LinkedList+Red_Black_Tree数组+链表+红黑树*）
#     3. CCHashMap Segment锁的原理


