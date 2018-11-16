# c++日记
  
[toc]

## 第1讲 C++语言概述
### C++和C的关系
1. C++保留了C语言原有的所有优点，增加了面向对象的机制
2. C++是由C发展而来的，与C兼容，C++是C的超集
3. 用C语言写的程序基本上可以不加修改地用于C++
4. C++既可用于面向过程的结构化程序设计，又可用于面向对象的程序设计，是一种功能强大的混合型的程序设计语言

### C++字符集
1. 小写字母26个： `a b c d e f g h i j k l m n o p q r s t u v w x y z`
2. 大写字母26个： `A B C D E F G H I J K L M N O P Q R S T U V W X Y Z `
3. 数字字符10个： `0 1 2 3 4 5 6 7 8 9`
4. 符号29个： `_ { } [ ] # ( ) < > % : ; . ? * + - / ^ & | ~ ! = , \ " ’`
5. 空白符5个： <kbd>space</kbd> <kbd>TAB</kbd> <kbd>return</kbd>  <kbd>CTRL</kbd>+<kbd>L</kbd> <kbd>CTRL</kbd>+<kbd>K</kbd>

### 简单的C++程序
``` c++
#include <iostream>
using namespace std;  
int main()  
{
	cout << "hello word!" << endl;  
	return 0;
}
```





















