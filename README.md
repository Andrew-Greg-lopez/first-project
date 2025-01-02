# first-project
the project to be good at something 
#include <iostream>
#include <fstream>
#include <string>

using namespace std;

int main() {
    string filename = "Andrew'secretsuprise.txt";
    ifstream inputfile;
    int number, count = 0, sum = 0;

  
    inputfile.open(filename);

   
    if (inputfile.is_open()) {   
        cout << "File did open which is great!" << endl;
    } else {
        cout << "I'm sorry you gonna have to try that again" << endl;
        return 1; 
    }

    
    inputfile.close();

    return 0; 
}
