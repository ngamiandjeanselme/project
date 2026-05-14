#include <iostream>
using namespace std;

int main() {

    // Family members' names and ages
    string names[5] = {"John", "Sarah", "David", "Mary", "Kevin"};
    int ages[5] = {45, 40, 18, 15, 10};

    string key;
    bool found = false;

    // Display available family members
    cout << "Family Members:\n";
    for(int i = 0; i < 5; i++) {
        cout << names[i] << " - " << ages[i] << " years" << endl;
    }

    // Enter name to search
    cout << "\nEnter family member name to search: ";
    cin >> key;

    // Linear Search
    for(int i = 0; i < 5; i++) {

        if(names[i] == key) {

            cout << names[i] << " was found and is aged "
                 << ages[i] << " years." << endl;

            found = true;
            break;
        }
    }

    // If not found
    if(found == false) {
        cout << "Not found" << endl;
    }

    return 0;
}
