+++
date = '2024-12-26T11:41:19+07:00'
draft = false
title = 'Cài đặt JDK'
+++

# **1. Cài Đặt**

# **Bước 1: Cài đặt JDK (Java Development Kit)**

Tải JDK mới nhất từ Oracle hoặc OpenJDK.

# **Bước 2: Thiết lập môi trường**

export JAVA_HOME=/path/to/jdk

export PATH=$JAVA_HOME/bin:$PATH

#  2.Chương trình đầu tiên chạy
public class HelloWorld {

    public static void main(String[] args) {

        System.out.println("Hello, World!");

    }
}

# **Cách chạy chương trình**
javac HelloWorld.java # Biên dịch

java HelloWorld # Chạy chương trình

