##### while 语句
- while 语句
	- 循环控制语句, 用于在条件表达式为真时重复执行某段代码, 与[[C.do-while 语句|do-while 语句]]不同, while 语句先检查条件表达式, 然后再决定是否执行循环体
- 语法
```c
while (条件表达式) { 循环语句 }
    // 计算条件表达式的值, 如果条件表达式为真(非0), 则执行循环体, 如果为假(0), 则退出循环
    // 循环返回第1步
```
- 示例.
```c
// 打印数字 1-10
#include <stdio.h>

int main() {
    int i = 1;

    while (i <= 10) {
        printf("%d\n", i);
        i++;
    }

    return 0;
}
```