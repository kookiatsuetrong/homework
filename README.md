# Homework
Homework for Java Bootcamp in July 2019

### Oil Platform
Dynamic Programming (Base Case & Build)

### Glass
Dynamic Programming (Base Case & Build)

Memoization, Depth-First

[1] [4] [5]

How many?

Generate All

### Bus Station
Greedy


### Divide & Conquer in Binary Tree

![](binary-tree.png)

ตัวอย่างการหาค่าทั้งหมดใน Tree
```
int getSum(Node c) {
	if (c == null) return 0;
	return getSum(c.left) + getSum(c.right);
}
```

จาก Binary ที่กำหนดให้ซึ่งอาจจะมีข้อมูลนับล้านตัว 
ให้เขียนโค้ดหาตอบดังนี้

- หา Leaf ที่มีค่ามากที่สุด ตัวอย่างในภาพคือ 9

- ค่าผลรวมของค่าใน Leaf ตัวอย่างในภาพคือ 5 + 9 + 1 + 5 + 1 + 2 = 23

- หาค่าที่มากที่สุดจาก Root ไปยัง Leaf ตัวอย่างในภาพคือ 3 + 7 + 2 + 9 = 21

### X Dominoes
Depth-First Search and Iterative Deepening for NP-Complete Problem

ม้าหมุนแต่ละตัวจะ 4 ขา แต่ละขามีสีหรือตัวเลขกำกับไว้ ให้เขียนโค้ดหมุนม้าหมุนเพื่อให้ขาที่ติดกัน มีสีหรือตัวเลขเดียวกัน พิมพ์ Possible ถ้าทำได้ หรือ Impossible ถ้าทำไม่ได้

![](rotation.png)

ตัวอย่างในภาพคือหมุน 4 ครั้ง

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


