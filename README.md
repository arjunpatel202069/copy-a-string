#include <iostream>
using namespace std;
int main()
{
    string first, second;

    cout << "Enter string first: ";
    getline (cin, first);

    second = first;

    cout << "first = "<< first << endl;
    cout << "second = "<< second;

    return 0;
}
