# dock Hello Git!
# include<iostream>
 using namespace std;
 void main()
{
    int a,b;
    char s;
    cin>>a>>s>>b;
    switch (s)
    {
        case '+':
        cout<<(a+b);
        case '-':
        cout<<(a-b);
        case '*':
        cout<<(a*b);
        case '/':
        cout<<(a/b);
        default:
        cout<<"Error";
    }
}