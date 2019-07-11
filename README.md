# Homework
Homework for Java Bootcamp in July 2019

### Oil Platform
(Dynamic Programming, Base Case & Build)

### Glass
(Dynamic Programming, Base Case & Build)

Memoization, Depth-First

[1] [4] [5]

How many?

Generate All

### Bus Station
(Greedy)

### Divide & Conquer in Binary Tree

![](binary-tree.png)

จาก Binary ที่กำหนดให้ซึ่งอาจจะมีข้อมูลนับล้านตัว 
ให้เขียนโค้ดหาคำตอบดังนี้

- หา Leaf ที่มีค่ามากที่สุด ตัวอย่างในภาพคือ 9

- ค่าผลรวมของค่าใน Leaf ตัวอย่างในภาพคือ 5 + 9 + 1 + 5 + 1 + 2 = 23

- หาค่าที่มากที่สุดจาก Root ไปยัง Leaf ตัวอย่างในภาพคือ 3 + 7 + 2 + 9 = 21

ตัวอย่างการหาค่าทั้งหมดใน Tree
```
int getSum(Node c) {
	if (c == null) return 0;
	return getSum(c.left) + getSum(c.right);
}
```

### X Dominoes
(Breadth-First Search, Depth-First Search, Iterative Deepening for NP-Complete Problem)

ม้าหมุนแต่ละตัวจะมี 4 ขา แต่ละขามีสีหรือตัวเลขกำกับไว้ ให้เขียนโค้ดหมุนม้าหมุนเพื่อให้ขาที่ติดกัน มีสีหรือตัวเลขเดียวกัน พิมพ์ Possible ถ้าทำได้ หรือ Impossible ถ้าทำไม่ได้

![](rotation.png)

ตัวอย่างข้อมูลในภาพจาก File ชื่อ rotation.txt มีม้าหมุน 6 ตัว แบ่งเป็น 2 x 3 ตัว แต่ละตัวมีข้อมูลตามเข็มนาฬิกา
```
2 3
1 2 3 4
5 3 4 2
3 2 1 5
4 2 5 3
2 4 3 1
4 3 5 2
```

ตัวอย่างผลลัพธ์จากภาพคือหมุน 4 ครั้ง

### Square Dominoes

ต่อเป็นแถวเดียว

```
|2 3| |3 2| |2 3|
|4 1| |1 5| |5 4|
```

Permutation

Greedy

Dynamic Programming (Easiest Hard Problem)

Josephus

Caterpillar Method


