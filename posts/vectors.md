title: Vectors in c++
tags:
  - C++
  - 'Competitve '
  - Programming
  - ''
categories:
  - Programming
  - C++
date: 2017-11-13 13:04:00
---
<p id="icon" class="mx-auto" style="text-shadow: rgb(48, 117, 165) 0px 0px, rgb(48, 118, 166) 1px 1px, rgb(48, 118, 167) 2px 2px, rgb(49, 119, 168) 3px 3px, rgb(49, 120, 169) 4px 4px, rgb(49, 121, 170) 5px 5px, rgb(50, 122, 171) 6px 6px, rgb(50, 122, 172) 7px 7px, rgb(50, 123, 173) 8px 8px, rgb(51, 124, 175) 9px 9px, rgb(51, 125, 176) 10px 10px, rgb(51, 126, 177) 11px 11px, rgb(51, 126, 178) 12px 12px, rgb(52, 127, 179) 13px 13px, rgb(52, 128, 180) 14px 14px, rgb(52, 129, 181) 15px 15px, rgb(53, 130, 182) 16px 16px, rgb(53, 130, 184) 17px 17px, rgb(53, 131, 185) 18px 18px, rgb(54, 132, 186) 19px 19px, rgb(54, 133, 187) 20px 20px, rgb(54, 134, 188) 21px 21px, rgb(55, 134, 189) 22px 22px, rgb(55, 135, 190) 23px 23px, rgb(55, 136, 191) 24px 24px, rgb(56, 137, 192) 25px 25px, rgb(56, 138, 194) 26px 26px, rgb(56, 138, 195) 27px 27px, rgb(57, 139, 196) 28px 28px, rgb(57, 140, 197) 29px 29px, rgb(57, 141, 198) 30px 30px, rgb(58, 142, 199) 31px 31px, rgb(58, 142, 200) 32px 32px, rgb(58, 143, 201) 33px 33px, rgb(59, 144, 203) 34px 34px, rgb(59, 145, 204) 35px 35px, rgb(59, 146, 205) 36px 36px, rgb(60, 146, 206) 37px 37px, rgb(60, 147, 207) 38px 38px, rgb(60, 148, 208) 39px 39px, rgb(61, 149, 209) 40px 40px, rgb(61, 150, 210) 41px 41px, rgb(61, 150, 212) 42px 42px, rgb(62, 151, 213) 43px 43px, rgb(62, 152, 214) 44px 44px, rgb(62, 153, 215) 45px 45px, rgb(62, 153, 216) 46px 46px, rgb(63, 154, 217) 47px 47px, rgb(63, 155, 218) 48px 48px, rgb(63, 156, 219) 49px 49px, rgb(64, 157, 220) 50px 50px, rgb(64, 157, 222) 51px 51px, rgb(64, 158, 223) 52px 52px, rgb(65, 159, 224) 53px 53px, rgb(65, 160, 225) 54px 54px, rgb(65, 161, 226) 55px 55px, rgb(66, 161, 227) 56px 56px, rgb(66, 162, 228) 57px 57px, rgb(66, 163, 229) 58px 58px, rgb(67, 164, 231) 59px 59px, rgb(67, 165, 232) 60px 60px, rgb(67, 165, 233) 61px 61px, rgb(68, 166, 234) 62px 62px; font-size: 75px; color: rgb(255, 255, 255); background-color: rgb(68, 167, 235); height: 334px; width: 334px; line-height: 334px; border-radius: 0%; overflow: hidden; text-align: center;">Vectors</p>
## Introduction

Vector is a template class that is a perfect replacement for the good old C-style arrays. It allows the same natural syntax that is used with plain arrays but offers a series of services that free the C++ programmer from taking care of the allocated memory and help operating consistently on the contained objects.

The first step using vector is to include the appropriate header:
```c++
#include <vector>
```
Note that the header file name does not have any extension; this is true for all of the Standard Library header files. The second thing to know is that all of the Standard Library lives in the namespace std. This means that you have to resolve the names by prepending std:: to them:
```c++
std::vector<int> v;    // declares a vector of integers
```
For small projects, you can bring the entire namespace std into scope by inserting a using directive on top of your cpp file:
```c++
#include <vector>
using namespace std;
//...
vector<int> v;         // no need to prepend std:: any more
```
This is okay for small projects, as long as you write the using directive in your cpp file. Never write a using directive into a header file! This would bloat the entire namespace std into each and every cpp file that includes that header. For larger projects, it is better to explicitly qualify every name accordingly. I am not a fan of such shortcuts. In this article, I will qualify each name accordingly. I will introduce some typedefs in the examples where appropriate—for better readability.

Now, what is std::vector<T> v;? It is a template class that will wrap an array of Ts. In this widely used notation, 'T' stands for any data type, built-in, or user-defined class. The vector will store the Ts in a contiguous memory area that it will handle for you, and let you access the individual Ts simply by writing v[0], v[1], and so on, exactly like you would do for a C-style array.

Note that for bigger projects it can be tedious to repeatedly write out the explicit type of the vectors. You may use a typedef if you want:
```c++
typedef std::vector<int> int_vec_t;    // or whatever you
                                       // want to name it
//...
int_vec_t v;
Do not use a macro!
```
```c++`
#define int_vec_t std::vector<int> ;    // very poor style!
```
For the beginning, let's see what a vector can do for us. Let's start small and take the example of an array of integers. If you used plain arrays, you had either a static or a dynamic array:
```c++
size_t size = 10;
int sarray[10];
int *darray = new int[size];
// do something with them:
for(int i=0; i<10; ++i){
    sarray[i] = i;
    darray[i] = i;
}
// don't forget to delete darray when you're done
delete [] darray;
```
Let's do the same thing using a vector:
```c++
#include <vector>
//...
size_t size = 10;
std::vector<int> array(size);    // make room for 10 integers,
                                 // and initialize them to 0
// do something with them:
for(int i=0; i<size; ++i){
    array[i] = i;
    // no need to delete anything
}
```

As you see, vector combines the advantages of both the static and the dynamic array because it takes a non-const size parameter such as the dynamic one and automatically deletes the used memory like the static one.

## Declaring  a 2D vector 
You can declare the 2D vector and initialize  with some specific value 
eg.
```c++
# include <bits/stdc++.h>
using namespace std;
int main()
{
int n,m;
cin>>n>>m;
vector < vector <int > > V(n,vector<int >(m,-1));
//created a vector V of order nXm and intialize with -1 
}
```
