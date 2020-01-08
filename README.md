# GEOG5990-Assessment-1
This repository is for assessment 1 of the course GEOG5990.

**List of files**
This is README, including agentframework file, animatedmodel file and in file.

**Software**
Both python files(agentframework.py and animatedmodel.py) are finished and tested in the "Spyder".

**Running steps**
1.The right steps to run files are to open two files and firstly run the agentframework.py and then run the animatedmodel.py.

2.Note that the Bakend of Graphics is "Tkinter", which can be found on the top of the window(Tools-References-Ipython console-Graphics-Backend-Tkinter).

**Running outputs** 
1.When it runs, two pop-up windows called "Figure" and "Model" respectively are shown on the main window. Meanwhile, Console 1/A window shows <td class="y">int</td>,<td class="x">int</td> and values in "in.txt".

2.If clicking on "Run model" on the menu of "Model" of Model window, then the animation appears with the green-blue background in the square of 300*300. Ten points move from top-left corner to differen and random directions and leave the moving path represented as shadows.

3.Console 1/A window shows some texts and figures starting from "Move Eat and Share" and ending by "Plot", which represents a loop.

4.The process is iterated 100 times and then the animation and the Console 1/A window stop updating until clicking "Run model" again to continue the process. If this action is repeated enough times, then an increasing area of shadow will cover the background.

5.This animation simulates the process by which 10 sheeps eat grass.

**Known issues**
There are two obvious issues: the first one is that the pop-up window "Figure" is never used or influenced when running the model, the second one is that a warning symbol indicate "local variable 'animation' is assigned to but never used"; but effective solutions have not been found.

**Test**
The code 'matplotlib.pyplot.imshow(environment)' is designed to test whether the data from "in.txt" is read correctly or not and the test result proves that the data reading is correct, which means that the environment can be suitable for next step.

**Roadmap**
For further roadmap, it is useful to set up a GUI to input or modify parameters without having to modify the code so that more changes can be shown in the model.

**License**
See the [MIT LICENSE](https://github.com/kexinsun123/GEOG5990-Assessment-1/blob/master/LICENSE) here. 
