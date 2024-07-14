<div align="center">
<img src="https://github.com/Helen1Z/Color-Sorting-Robotic-Arm/blob/main/simulation/box_pickup.png" width="400" title="box_pickup"/>
<h3 align="center">Lexical And Syntax Analyzer</h3>
<p align="center">
In Linux
<br/>
<br/>
<a href="https://github.com/Helen1Z/Lexical-And-Syntax-Analyzer"><strong>Explore the docs</strong></a>
</p>
</div>

 ### Built With

This project was built with the following:
- <a href="https://www.geeksforgeeks.org/flex-fast-lexical-analyzer-generator/">Flex</a> for the lexical analyzer.
- <a href="https://www.gnu.org/software/bison/">Bison</a> for the syntax analyzer. 
- Your preferred IDE (we used VS Code).


 ## About The Project
 
<p align="center">
<img src="https://github.com/Helen1Z/Color-Sorting-Robotic-Arm/blob/main/simulation/simulation_example.gif" width="400" title="arm_in_position"/>
</p>

The Lexical and Syntax Analyzer is a crucial component in the compilation process of programming languages. This project provides tools to analyze the structure and syntax of code written in a specific programming language. It breaks down the source code into tokens and checks for grammatical structure, ensuring that the code adheres to the rules of the language.

## Getting Started
 
 ### Installation
 
<p>Please follow the following steps for successful installation:</p>

1. Clone the repo
   ```sh
   gh repo clone Helen1Z/Lexical-And-Syntax-Analyzer
   ```
2. Install Flex and Bison by typing the following commands in a Linux terminal:
    ```sh
   sudo apt-get update
    ```
    ```sh
   sudo apt-get install flex
    ```
    ```sh
   sudo apt-get install bison
    ```

## How To Run

To run the Lexical and Syntax Analyzer, follow these steps:

1. **Open the terminal of your IDE**.

2. **Navigate to the code directory**:
    ```sh
    cd code
    ```

3. **Generate the lexical analyzer using Flex**:
    ```sh
    flex project.l
    ```

4. **Generate the syntax analyzer using Bison**:
    ```sh
    bison -d project.y
    ```

5. **Compile the generated C code using GCC**:
    ```sh
    gcc -o a.out project.tab.c lex.yy.c
    ```

6. **Run the compiled program**:
    ```sh
    ./a.out
    ```


 ## Features

- **Efficient Tokenization**: Quickly processes source code and converts it into a stream of tokens.
- **Robust Parsing**: Constructs syntax trees that accurately represent the structure of the code.
- **Comprehensive Error Messages**: Provides error messages to help developers correct their code.
- **Extensible Design**: Easily adaptable to different programming languages by modifying the grammar rules.


 ## Usage

Here are some examples of the simulation program running:
<table>
  <tr>
    <td>
      <img src="https://github.com/Helen1Z/Lexical-And-Syntax-Analyzer/blob/main/screenshots/arm_in_position.png" width="400" title="arm_in_position"/>
    </td>
    <td>
      <img src="https://github.com/Helen1Z/Lexical-And-Syntax-Analyzer/blob/main/screenshots/box_pickup.png" width="400" title="box_pickup"/>
    </td>
    <td>
      <img src="https://github.com/Helen1Z/Lexical-And-Syntax-Analyzer/blob/main/screenshots/placing_box.png" width="400" title="placing_box"/>
    </td>
  </tr>
</table>
 
## Collaborators

<p>A special thanks to the following for their contributions and support:</p>
<table>
<tr>

<td align="center">
<a href="https://github.com/Helen1Z">
<img src="https://avatars.githubusercontent.com/u/128386591?v=4" width="100;" alt="Helen Zina"/><br>
<sub>
<b>Helen Zina (Me)</b>
</sub>
</a>
</td>

<td align="center">
<a href="https://github.com/alk-an">
<img src="https://avatars.githubusercontent.com/u/147655333?v=4" width="100px;" alt="Alkinoos Anastasiadis"/><br>
<sub>
<b>Alkinoos Anastasiadis</b>
</sub>
</a>
</td>

</tr>
</table>

 ## License

Distributed under the MIT License. See the LICENSE file for more information.

 ## Contact
 
If you have any questions or suggestions, feel free to reach out to us:
- Helen Zina - helenz1@windowslive.com
- Project Link: https://github.com/Helen1Z/Lexical-And-Syntax-Analyzer


 ## Acknowledgments

The resources that helped us through this whole process were the following:

- [Flex (Fast Lexical Analyzer Generator ) - GeeksForGeeks](https://www.geeksforgeeks.org/flex-fast-lexical-analyzer-generator/)
- [Bison](https://www.geeksforgeeks.org/bison-command-in-linux-with-examples/?ref=header_search)


For more information, read the english version of our report (**project en.pdf**).
