1)Write a C program to print the sample output.
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello World...!";
    return 0;
}
2)Write a C program to print sample output.
#include<iostream>
using namespace std;
int main(){
    cout<<"Hello World...!";
    cout<<"\nHello World...!";
    return 0;
}
3)Write a C program to print sample Output.
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello\tWorld...!";
    return 0;
}
4)Write a program to print a character
#include<iostream>
using namespace std;
int main(){
    char A;
    cin>>A;
    cout<<A;
    return 0;
}
5)Ravi and Varma went to a textile shop for festival purchase. Ravi took few T-shirts and went for billing. Varma wants discount on the purchased items. The biller shows computer keyboard and asks to press an alpha numeric key and that key’s ASCII value will be the discounted amount on the purchase. Help Varma to know his discounted amount.
Sample Input:
A
Sample Output:
65

#include<iostream>
using namespace std;
int main(){
    char A;
    cin>>A;
    cout<<int(A);
    return 0;
}
6)ASCII - American Standard Code for Information Interchange.
Write a program to get a number(ASCII) as input and print its equivalent character.
You can display a character if you know ASCII code of that character.
Sample Input:
103
Sample Output:
g

#include<iostream>
using namespace std;
int main()
{
    int a;
    cin>>a;
    cout<<char(a);
    return 0;
}
7)Write a program to get a float value from the user and display it.
Sample Input:
23.115
Sample Output:
23.115000
#include<iostream>
#include<iomanip>
using namespace std;
int main()
{
    float a;
    cin>>a;
    cout<<fixed<<setprecision(6)<<a;
    return 0;
}

8)

