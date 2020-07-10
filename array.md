# Array
数组是用来存储相同类型的变量的顺序集合。

所有的数组都是由连续的内存位置组成。

**语法**
type arrayName [ arraySize ]

int a[5] =  {0,1,2,3,4}; 

int b[]  =  {0,1,2,3,4};

#include <iostream> 

using namespace std; 

#include <iomanip>   

using std::setw;   

int main ()

{   

   int n[ 10 ]; // n 是一个包含 10 个整数的数组   
   
   // 初始化数组元素     
   
   for ( int i = 0; i < 10; i++ )
   
   {
   
      n[ i ] = i + 100; // 设置元素 i 为 i + 100   
      
   }
   
   cout << "Element" << setw( 13 ) << "Value" << endl;
   
   // 输出数组中每个元素的值         
   
   for ( int j = 0; j < 10; j++ )
   
   {
   
      cout << setw( 7 )<< j << setw( 13 ) << n[ j ] << endl;
      
   }
   
   return 0;
   
}
