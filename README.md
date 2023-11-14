//creating a new java class, having basic elements such a Push, Pop, Peek(returns topmost element), IsEmpty, isFull, FILO(FIRST IN LAST OUT)
class MyStack {
int arr[];
int top;
int cap;//capacity
MyStack(int c) //constructor
{
 top=-1;//when stack is empty, tehre is no element i.e index can't be zero, since 1st element lies in index 0.
 cap = c;
 arr = new int[cap];
 }
 
