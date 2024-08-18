<div align="center">
<img src="https://user-images.githubusercontent.com/69423088/253824433-a6b55273-b084-4283-a0b6-b8d40bc52890.png" width="250px"/>
</div>

# _**Solvate Suite**_

**STABLE REPOSITORY**

Click [here](https://github.com/otaviolsantana/solvate) to visit stable repository.

**INSTALLATION**

	The suite is distributed pre-compiled for Linux systems, being only necessary to configure it.
	To do this, download the program with the commands:

   	   wget https://github.com/otaviolsantana/solvate-beta/archive/refs/heads/main.zip
   	   unzip main.zip && mv -f solvate-beta-main solvate

 	Then, adjust the “profile” and “config” files, and run the “solvate.config” script:

	   cd solvate && chmod +x solvate.config && ./solvate.config
 
**CHANGELOG**

	- Inclusion of parameters for simulation configuration through the MDPAR submodule.
	- Expansion of the list of parameterized solvents via SOLVS submodule.
	- Integration of the MICRO, GCALC, and ONIOM modules to automate the microsolvation procedure.
	- Addition of SAC and SOC optimization procedures in the treatment of microsolvation.
	- Implementation of the search for similarities in the SOC procedure.
 	- RMSD cutoff estimate for the SOC procedure via the RMSDE submodule.
 	- Data extraction from SUMMY and SUPPY modules with concentration and temperature correction.
   	- Minimization of structural RMSD from files with multiple structures (trj.xyz).
  	- Microssolvation clusters extraction with reorientation of structures relative to the solute.
	- Implementation of the treatment for two-phase systems (under development).
	- Automation of molecular dynamics equilibration steps (under development).
	- Include the EBIND module to calculate the free energy of protein-inhibitor interaction (under development).
 	- Bug fixes...

**CITATION**

If you use _Solvate Suite_, please cite:

	Solvate Suite: A Command-Line Interface for Molecular Simulations and Multiscale Microsolvation Modeling
 	Otávio L. Santana, Daniel G. Silva, Sidney R. Santana
	J. Chem. Inf. Model. 2024, 64, 9, 3767–3778

Link: [https://doi.org/10.1021/acs.jcim.3c01899]

**LICENSE**

SOLVATE is a free software: you can redistribute it under the terms of the BSD 3-Clause License. This software is provided by the copyright holders and contributors “as is”, and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose, are disclaimed. In no event shall the copyright holder or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.
