# kotlin-vscode
Compile &amp; Run Kotlin using Visual Studio Code

## Prequisites
1. Kotlin (Command Line) & VS Code are already installed on your system.
2. Enviornment Variable for Kotlin Compiler is set.

## Installation
1. Open Terminal & navigate to your project folder and execute following command. 
 ``` git clone https://github.com/pavittarx/kotlin-vscode.git && xcopy /E kotlin-vscode && rm -rf kotlin-vscode ```
2. If you want Keyboard Shortcuts, Copy & Paste content or 'keybindings' file provided to your keybindings.json
    File > Prefrences > Keyboard Shortcuts > Open & edit keybindings.json
        
## Compiling & Running Kotlin Code
If Keybindins are not set.
   1. Open Command Palette (F1 or Ctrl+Shift+K)
   2. Search for 'Tasks:Run Build Tasks' (Ctrl+Shift+B)
   3. Choose an option (Compile/Run/Compile+Run) from the list provided.
   
If Keybindings are set

   F9 - Compile+Run Kotlin Code
   
   F10 - Compile Kotlin Code
   
   F11 - Run Kotlin Application Binary
   
   F12 - Lists the Available Tasks (same as Ctrl+Shift+B)

## Note 

1. The following only works on Windows Systems as of this moment.
2. A test file 'hello.kt' is compiled as of this moment, you can edit kotlin/compile.cmd & change it to your own file.
3. The compilerun.cmd must be edited to match your kotlin  (.kt) file if you use Compile+Run

### License: MIT
### Authored by: pavittarx
