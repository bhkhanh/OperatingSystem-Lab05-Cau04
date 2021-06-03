# Operating System - Lab 05 - Exercise 04
Cho mô hình 2 processes A và B chạy song song như sau:  
int x = 0;  
processA()  
{  
  while(1)  
    {  
    x = x + 1;  
    if (x == 20)  
    x = 0;  
    print(x);  
  }
	
processB()  
{  
while(1)  
{  
x = x + 1;  
if (x == 20)  
x = 0;  
print(x);  
}  
}
