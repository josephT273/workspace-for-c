# C++ Workspace simple configuration
I tryied to start c++ program into my Google IDX workspace the i find it not working to the work space. Then i have come with this idea why i setup the google idx enviroment for my C++ code then i configured the idx config file by adding some packages and vs code extensions.

```nix
packages = [
    pkgs.gcc
  ];
```

Then added the vscode pack from the market place like this 
```nix
idx = {
    extensions = [
      "franneck94.vscode-c-cpp-dev-extension-pack"
    ];
}
```

FInaly i created the **main.cpp** file and i put some code to test it

```cpp
#include <iostream>

using namespace std;
int main(){
    cout << "Hello World" << endl;
    return 0;
}
```
and comple it using g++
```bash
g++ -o build/main main.cpp
./build/main
```
It works fine.

Connect me with my social links https://linktr.ee/josepht273

Learn more at https://developers.google.com/idx/guides/customize-idx-env