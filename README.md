# 鄙人的自我介绍

鄙人名为Sakura，爱好如下：
1. 篮球
2. 游泳
3. 编程
4. 学习
5. etc······

前女友数不过来了，就不一一列举了。

而在下现在仍是编程NEWBIE，只学过一丢丢python，演示如下：
~~~Python
def binarySearch(orderedList,target):
    n = len(orderedList)
    first = 0
    last = n - 1
    while first <= last:
        mid = (last + first) // 2
        if orderedList[mid] > target:
            last = mid - 1
        elif orderedList[mid]< target:
            first = mid + 1
        else:
            return True
    return False

orderedList=[1,2,3]
target=2
print(binarySearch(orderedList,target))
~~~
上述为一个BinarySearch的python演示，虽然啰里啰唆，但也确实表现出了我这个Newbie的风采。
