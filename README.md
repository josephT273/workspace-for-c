# C++ Workspace simple configuration
I tryied to start c++ program into my Google IDX workspace the i find it not working to the work space. Then i have come with this idea why i setup the google idx enviroment for my C++ code then i configured the idx config file by adding some packages and vs code extensions.

```nix
packages = [
  # you can add more packages here
  # this packages only works on nix environtment
  # you can grab the packages from https://search.nixos.org/packages
    pkgs.gcc
  ];
```

Then added the vscode pack from the market place like this 
```nix
idx = {
    extensions = [
      # Search for the extensions you want on https://open-vsx.org/ and use "publisher.id"
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

# Contributing to Workspace For C

Thank you for considering contributing to Workspace For C! We welcome contributions from the community to help improve and grow this project.

Before contributing, please take a moment to review the following guidelines to ensure a smooth collaboration process.

## How Can I Contribute?

There are several ways you can contribute to Workspace For C:

1. **Reporting Bugs**: If you encounter any bugs or issues while using Workspace For C, please open a GitHub issue and provide detailed information about the problem.
   
2. **Feature Requests**: If you have ideas for new features or enhancements, feel free to submit a GitHub issue with a clear description of the feature request.
   
3. **Code Contributions**: You can contribute to the project by fixing bugs, implementing new features, or improving existing functionality. To do so, follow the steps below:
   
   - Fork the repository and create a new branch for your contribution.
   - Make your changes, ensuring adherence to coding standards and best practices.
   - Test your changes thoroughly to ensure they work as expected.
   - Submit a pull request with a clear description of your changes and the problem they address.

4. **Documentation Improvements**: Help improve the project's documentation by fixing typos, adding missing information, or clarifying existing content.
   
5. **Feedback and Suggestions**: Provide feedback on the project's usability, design, or any other aspect that you think could be improved.

## Code Style and Guidelines

When contributing code to Workspace For C, please adhere to the following guidelines:

- Follow the coding style and conventions used in the project.
- Write clear and concise code with meaningful variable and function names.
- Comment your code when necessary to improve readability and understanding.

## Getting Help

If you need any assistance or have questions about contributing to Workspace For C, feel free to reach out to us by [opening an issue](../../issues).

We appreciate your interest in contributing to Workspace For C and look forward to your valuable contributions!

Happy coding!


## License 📝
Telegram Community Gallery is licensed under the [MIT License](LICENSE).

Connect me with my social links https://linktr.ee/josepht273

## Learn more
at https://developers.google.com/idx/guides/customize-idx-env

# Thank You and Enjoy! 🥰