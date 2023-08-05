# CPP-Program-to-calculate-the-area-of-a-circle

Finding the Area of  circle in C++ :-
Here we will discuss how to find the area of a circle when its radius is given using c++ programming language.

The area of a circle can be found by using the formula:
Area of circle= 𝝅R*R

Area of circle in C++
While loop in C
Working:-
User gives an input
The input is stored in a float type variable say rad.
Another float type variable is taken say circleArea.
Now using the formula we find the area of the circle of radius rad and store it in circleArea.
                          circleArea= 3.14* rad* rad;

Print the value of circleArea.
Code in C++
Run
#include<bits/stdc++.h>
using namespace std;

int main(){
    float rad = 3, area;
    
    area=(3.14*rad*rad);
    cout<<"Area of circle is "<<area;
}
Output
Area of circle is 28.26
Algorithm using diameter :-
User gives an input (diameter of the circle)
The input is stored in a float type variable say d.
Another float type variable is taken say circleArea.
Now using the formula we find the area of the circle of diameter d and store it in circleArea.
                          circleArea= (3.14* d* d)/4;

Print the value of circleArea.
Code in C++
Run
#include<bits/stdc++.h>
using namespace std;

int main(){
    float d = 6, area;
    
    area=(3.14*d*d)/4;
    cout<<"Area of circle is "<<area;
}
Output
Area of circle is 28.26
