# Arduino Motor Rotator

## Run locally with vscode

* Install the [Arduino](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) plugin
* Install the [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) plugin
* Compile `g++ ./src/main.cpp -o ./out/sample.out`
* Run `./out/sample.out`


Power on
  Rotate stepper motor to the left until hits end
  Rotate stepper motor to the right five steps
  Rotate stepper motor to the left to verify five steps is the end
  Set 0 
  run main code
  
Main code
  Speed variables 1 - 10
  1. Point A - Point B - Stop
  2. Point A - Point B - Point A - Stop
  3. Point A - Point B - Point A - Continuous
  
LCD
  2 Lines
  4 buttons?
  1. Speed Up
  2. Speed Down
  3. Start
  4. Stop
  
