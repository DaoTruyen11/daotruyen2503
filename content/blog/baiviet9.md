---
title: "Bài 9: Lập trình hướng đối tượng cơ bản"
date: 2024-12-31T16:00:00+07:00
draft: false
author: "Tên của bạn"
tags:
  - Java
  - OOP
  - Lập trình hướng đối tượng
image: /images/java-oop.jpg
description: "Tìm hiểu các khái niệm cơ bản trong lập trình hướng đối tượng với Java."
toc: true
---

## Khái niệm cơ bản
- **Lớp (Class)**: Khuôn mẫu để tạo đối tượng.
- **Đối tượng (Object)**: Thực thể của lớp.
- **Thuộc tính (Attribute)** và **Phương thức (Method)**.

### Ví dụ OOP
```java
class Animal {
    String name;

    // Hàm khởi tạo
    Animal(String name) {
        this.name = name;
    }

    // Phương thức
    void makeSound() {
        System.out.println(name + " đang kêu.");
    }
}

public class OOPExample {
    public static void main(String[] args) {
        Animal cat = new Animal("Mèo");
        cat.makeSound();
    }
}