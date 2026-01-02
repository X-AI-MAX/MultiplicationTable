# MultiplicationTable 乘法表

## Project Description 项目描述

This Java project generates and prints the 9x9 multiplication table (also known as the "Nine-Nine Table" or "Multiplication Song").
这个Java项目用于生成并打印9x9乘法表（也称为“小九九”或“乘法口诀”）。

## How to Build and Run 如何构建和运行

### Prerequisites 前提条件

- Java Development Kit (JDK) 8 or higher installed on your system.
- 系统上已安装 Java 开发工具包 (JDK) 8 或更高版本。

### Building and Running 构建和运行

1. **Open a terminal or command prompt.**
   **打开终端或命令提示符。**

2. **Navigate to the project directory (where this README.md file is located).**
   **导航到项目目录（即此 README.md 文件所在的目录）。**

3. **Compile the Java source code:**
   **编译 Java 源代码：**
   ```bash
   javac src/main/java/com/example/multiplicationtable/MultiplicationTableGenerator.java
This command compiles the .java file into a .class file.
此命令将 .java 文件编译成 .class 文件。

Run the compiled program:
运行编译后的程序：
Bash
编辑
java -cp src/main/java com.example.multiplicationtable.MultiplicationTableGenerator
This command runs the main method of the MultiplicationTableGenerator class.
此命令运行 MultiplicationTableGenerator 类的 main 方法。 You should see the 9x9 multiplication table printed in the terminal.
您应该能在终端中看到打印出的9x9乘法表。
License 许可证
This project is licensed under the MIT License.
本项目采用 MIT 许可证。

Text
编辑

---

### 3. 编译和运行示例

完成目录创建和文件创建后，您可以按如下步骤操作：

1.  打开您的终端或命令提示符。
2.  使用 `cd` 命令进入 `MultiplicationTable` 目录。
    -   例如: `cd MultiplicationTable`
3.  执行编译命令：
    -   `javac src/main/java/com/example/multiplicationtable/MultiplicationTableGenerator.java`
4.  执行运行命令：
    -   `java -cp src/main/java com.example.multiplicationtable.MultiplicationTableGenerator`
5.  程序将输出以下内容：
    ```
    1*1=1 
    1*2=2 2*2=4 
    1*3=3 2*3=6 3*3=9 
    1*4=4 2*4=8 3*4=12 4*4=16 
    1*5=5 2*5=10 3*5=15 4*5=20 5*5=25 
    1*6=6 2*6=12 3*6=18 4*6=24 5*6=30 6*6=36 
    1*7=7 2*7=14 3*7=21 4*7=28 5*7=35 6*7=42 7*7=49 
    1*8=8 2*8=16 3*8=24 4*8=32 5*8=40 6*8=48 7*8=56 8*8=64 
    1*9=9 2*9=18 3*9=27 4*9=36 5*9=45 6*9=54 7*9=63 8*9=72 9*9=81 
    ```
Windows (使用 cmd):
Cmd

mkdir MultiplicationTable
cd MultiplicationTable
mkdir src\main\java\com\example\multiplicationtable
MacOS/Linux:
Bash

mkdir -p MultiplicationTable/src/main/java/com/example/multiplicationtable
cd MultiplicationTable