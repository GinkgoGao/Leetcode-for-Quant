# 1. C++

class Solution {
public:
    int fib(int a)
    {
        int res;
        if(a==1) res=1;
        else if(a==2) res=2;
        else 
        {
            int temp1=1;
            int temp2=2;
            for(int i=2;i<a;i++)
            {
                res=temp1+temp2;
                temp1=temp2;
                temp2=res;
            }
        }
        return res；
    }
//得这样写，不然超时
    int climbStairs(int n) {
        int ans;
        if(n==1) {ans=1;}
        else {ans=fib(n);}
        return ans;
    }
};
