<div align="center">
<img src="https://user-images.githubusercontent.com/69423088/253824433-a6b55273-b084-4283-a0b6-b8d40bc52890.png" width="250px"/>
</div>

# _**Solvate Suite**_

**STABLE REPOSITORY**

Click [here](https://github.com/otaviolsantana/solvate) to visit stable repository.

**INSTALLATION**

	The suite is distributed pre-compiled for Linux systems, being only necessary to configure it.
	To do this, download the program with the command:
 
	   git clone https://github.com/otaviolsantana/solvate-beta.git

   	or

   	   wget https://github.com/otaviolsantana/solvate-beta/archive/refs/heads/main.zip ; unzip main.zip

 	Then, adjust the “profile” and “config” files, and run the “solvate.config” script:

	   cd solvate && chmod +x solvate.config && ./solvate.config
 
**CONTENTS**

	- solvate           : Main program
	- solvate.profile   : Script with suite definitions
	- solvate.config    : Script to configure suite
	- solvate/modules   : Suite modules and sub-modules
	- solvate/share     : Parameterized solvents and counterions

**DEPENDENCIES**

   ***Simulation Box Creation***

     - PackMol v20.14.2
     - Q-Force v1.0

   ***Electronic Structure and Molecular Dynamics Simulation Programs***

     - xTB v6.6.1
     - CREST v2.12
     - ORCA 5.0
     - GROMACS 2023.3

   ***Visualization Programs***

     - JMol
     - VMD

   ***Scripts Interpreter and Libraries***

     - Python 3.10
     - MatPlotLib 3.5
     - Tqdm 4.65
     - PyQt5 5.15

**LICENSE**

SOLVATE is a free software: you can redistribute it under the terms of the BSD 3-Clause License. This software is provided by the copyright holders and contributors “as is”, and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose, are disclaimed. In no event shall the copyright holder or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.

**LINKS**

PackMol: [https://m3g.github.io/packmol/download.shtml] | Q-Force: [https://qforce.readthedocs.io/en/latest/index.html] | xTB: [https://xtb-docs.readthedocs.io/en/latest/] | CREST: [https://crest-lab.github.io/crest-docs/] | ORCA: [https://orcaforum.kofo.mpg.de/app.php/portal] | GROMACS:  [https://www.gromacs.org] | JMol: [https://jmol.sourceforge.net/] | VMD: [https://www.ks.uiuc.edu/Research/vmd/]
