# Product-of-odd-numbers

Product of odd numbers

Problem Description

给你n个整数，求他们中所有奇数的乘积。 


Input

输入数据包含多个测试实例，每个测试实例占一行，每行的第一个数为n，表示本组数据一共有n个，接着是n个整数，你可以假设每组数据必定至少存在一个奇数。 


Output

输出每组数中的所有奇数的乘积，对于测试实例，输出一行。

 
Sample Input

3 1 2 3

4 2 3 4 5 


Sample Output

3

15


解答：

#include<stdio.h>

main()

{

    int n,s,i,a;
    
    while(scanf("%d",&n)!=EOF)
    
    {
    
        s=1;
        
        for(i=0;i<n;i++)
        
        {
        
            scanf("%d",&a);
            
            if(a%2==1)
            
            s=s*a;
            
            else ;
            
        }
        
        printf("%d\n",s);
        
    }
    
}

