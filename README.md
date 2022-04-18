# 100-day-DSA

>Left Shift :
Denoted as : <<

eg: lets take **N=22**; which is **00010110** in Binary Form.
 Now, if “N is left-shifted by 2”
 i.e **N=N<<2** then N will become **N=N*(2^2)**.
 Thus, **N=22*(2^2)=88** which can be wriiten as **01011000**.
 
 ```C++
 #include <iostream>
using namespace std;
  
int main()
{
    // a = 5(00000101), b = 9(00001001)
    unsigned char a = 5, b = 9; 
  
    // The result is 00001010 
    cout <<"a<<1 = "<< (a<<1) << endl;
    
    // The result is 00010010 
    cout <<"b<<1 = "<< (b<<1) << endl;  
    return 0;
}
 
 ```
 
