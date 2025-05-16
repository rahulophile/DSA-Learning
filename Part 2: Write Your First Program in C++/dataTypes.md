**Data Types :** If we want to store any kind of data in computer then we need to create a variable and define it's type and that type is called Data Types in C++ and that variable name is called variable in C++.

**Variable :** It is a special name for storing each of the data in memory. In following examples ```first``` is ```Data Tyes```, ```second``` is ```Variable``` and ```after =``` is ```value```

**Note :** Variable name can't be start from ```numbers```.

*example :* 
```bash
int x = 20;
```
Here it means that x is a variable of *Integer* type. Integer genrally stores 4 bytes of data for 32-bit system.

*example :*
```bash
char x = 'q';
```
Here it means that x is a variable of *Character* type. Character genrally stores 1 byte of data, and it will always in single inverted comma ' ' not in " ".

*example :*
```bash
float f = 3.14;
```
Here it means that f is a variable of float type, and it takes 4 bytes of memory.

*example :*
```bash
double d = 3.1424
```
Here is means that d is a variable of type double, and it takes 8 bytes of memory.

*example :*
```bash
bool b = false;
bool t = true;
```
Here its means that b and t is a variable of boolean type and it always returns 1(true) or 0(for false).

*example :*
```bash
string str = "Rahul Raj"
```
Here its means that str is a variable of string type. String size vary it means, for ```str = "Rahul"``` size is 5 bytes but at the same time ```char str[] = "Rahul"``` here it's size is 6 bytes (+1 byte for null terminator ```\0```).

**Note :** 
```bash
int a = 12;
cout<< a;

char a = 'Q';
cout<< a;
```
Here it gives error because same name can't be assign for same or different type of variable.