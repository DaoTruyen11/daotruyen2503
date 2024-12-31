---
title: "Bài 1: Giới thiệu về Java"
date: 2024-12-31T08:00:00+07:00
draft: false
author: "Minh Quang"
tags:
  - Java
  - Lập trình
  - Học Java
image: /images/java-intro.jpg
description: "Tổng quan về ngôn ngữ lập trình Java và lý do nên học Java."
toc: true
---

## Giới thiệu Java
Java là một ngôn ngữ lập trình bậc cao, hướng đối tượng, và đa nền tảng. Nó được phát triển bởi Sun Microsystems (nay thuộc Oracle). Java được sử dụng trong phát triển ứng dụng web, di động, và phần mềm doanh nghiệp.

### Lý do học Java
1. Được sử dụng rộng rãi trong các ngành công nghiệp.
2. Đa nền tảng với khẩu hiệu "Write Once, Run Anywhere".
3. Có cộng đồng hỗ trợ lớn và tài liệu phong phú.

### Cách cài đặt Java
1. Tải Java Development Kit (JDK) từ [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Cài đặt IDE như IntelliJ IDEA, Eclipse, hoặc VS Code.

> **Chú ý**: Đảm bảo cài đặt đúng biến môi trường `JAVA_HOME` để sử dụng Java từ dòng lệnh.

### Chạy chương trình Java đầu tiên
Tạo file `HelloWorld.java`:
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Xin chào, Java!");
    }
}
