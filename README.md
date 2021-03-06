# object-oriented-design

面向对象设计 OOD

## 01 面向对象设计入门 Introduction to Object Oriented Design

### Question

- 什么是OOD，他和系统设计有什么区别?
- OOD经常在面试中出现吗?它重要吗?
- 怎么样的设计才算是好的设计?
- 如何解答OOD的题目 – 5C解题法
- 这门课有什么要求吗 ?
- 什么是OOD，他和系统设计有什么区别?
- OOD经常在面试中出现吗?它重要吗?
- 怎么样的设计才算是好的设计?
- 如何解答OOD的题目 – 5C解题法
- 这门课有什么要求吗?

### S.O.L.I.D 原则

- S – Single responsibility principle
- O – Open close principle
- L – Liskov substitution principle
- I – Interface segregation principle
- D – Dependency inversion principle

#### Single responsibility principle 单一责任原则

一个类应该有且只有一个去改变他的理由，这意味着一个类应该只有一项工作。

#### Open close principle 开放封闭原则

对象或实体应该对扩展开放，对修改封闭 (Open to extension, close to modification)。

### 奔雷手 - 5C解题法

![001](/images/001.jpeg)

- Clarify
- Core objects
- Cases
- Classes
- Correctness

## 02 管理类面向对象设计 OOD for Management System

![001](/images/C02/001.png)

### Clarify

- What
  - 关键字：Parking lot
  - `它` 管理到时什么？
  - Vehicle / Parking Spots

> Vehicle --> Parking Lot --> Parking Spot

- Parking lot: 考虑多层的 Parking lot，没有错层
- Vehicle：考虑三种大小的车
- 不考虑残疾人车位 / 充电车位

### Law of Demeter

"Each unit should have only limited knowledge about other units: only units 'closely' related to the current unit. Each unit should only talk to its friends; don't talk to strangers."

- Only talk to you immediate friends
- Don't talk to strangers

## 03 预定类面向对象设计 OOD for Reservation System

## 04 实物类面向对象设计 OOD for Real Life Object

## 05 游戏棋牌类面向对象设计 OOD for Games
