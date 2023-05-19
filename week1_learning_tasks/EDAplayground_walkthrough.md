#### EDAplayground walkthrough tutorial

#### step-1:EDAplayground interface
1. Log in. Click the Log in button (top right) Then either
• click on Google or Facebook or
• register by clicking on ‘Register for a full account’ (which enables all the simulators on EDA Playground)
1. Select your language from the Testbench + Design menu.
2. Select your simulator from the Tools & Simulators menu. Using certain simulators will require you to supply
additional identifcation information.
3. Type in your code in the testbench and design windows.
4. Click Run.
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/98b0bd0d-f3e5-4c20-b149-8a966b877d17)
#### step-2:
1. Select ‘Aldec Riviera Pro’ from the Tools & Simulators menu. This selects the Aldec Riviera Pro simulator,
which can be used however you logged in. Using certain other simulators will require you to have registered for
a full account.
2. In either the Design or Testbench window pane, type in the following code:
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/7a879fbd-6a02-4187-abb4-1af435b29090)
3. Click Run (top left)
Yes, running a simulation is as simple as that!
4. In the bottom pane, you should see real-time results as your code is being compiled and then run. A run typically
takes 1-5 seconds, depending on network traffic and simulator. Near the bottom of result output, you should see:
Hello World!
5. Now, let’s save our good work. Click the Share tab near in the bottom pane and then type in a name and
description. Then click Save.
6.on the left editor panel before end initial block and the following:
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/45793c1b-2795-43f6-8616-9699063839f3)
#### sidebar options:
EDA Playground provides many options that can be configured for running your code.
Languages & Libraries
This section allows selection of coding languages and the available libraries for those languages.
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/3ee048b6-0801-4b6b-876f-a97f40c48816)
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/d94517f1-7170-4f4c-8081-39a621bcccf1)

Open EPWave after run
Checking this option will open EPWave wave viewer in a new window after the simulation run completes (pop-ups
must be enabled). It is available for all simulators that have a run step.
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/295c094b-1353-4c22-998c-dc9c8d7b3768)
simulator:
Additional command-line compile options and run options may be specified in the bottom textboxes.
(If available), the Run Time option can be used to specify the number of timesteps for the simulation to run. By
default, the simulation runs forever until it hits a breakpoint or $finish.
The Use run.do Tcl file option is for using a custom run.do DO file for specifying simulation commands. To use a
run.do Tcl file, check the option and add a new file called ‘run.do’.
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/1bdcff24-abce-4eae-9765-066ce20e6c03)
yosys:
Yosis is a synthesis tool for performing logical synthesis and creating a netlist. It supports using ABC to synthesize
for a sample cell library.
Yosys will only process code in the right Design pane. The code in the left Testbench pane will be ignored.
UVM/OVM/Methodology/Libraries selections are also ignored.
The following synthesis options are available:
• use ABC with cell library - synthesize for a demo cell library using ABC
• memory -nomap - skip memory_map step
![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/44dc3058-e418-4eec-a4f2-ae51e47d2446)

yosys circuit diagram:

![image](https://github.com/Raviyazareen22/internship_training/assets/132916138/255c7c7c-fddb-43f3-bf88-6b13ee741599)





















