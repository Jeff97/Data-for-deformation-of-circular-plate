Here, we provide some supplementary files for the paper[1]. 

- The 'Movie 1' shows the simulated deformation process of different samples. To download the video, one can click the item, then click "View raw". 
- Each folder contains ABAQUS input files and the corresponding FORTRAN files (UMAT subroutines). The results presented in the paper can be duplicated by these files. 

[1] Li, Z., Wang, Q., Du, P., Kadapa, C., Hossain, M., & Wang, J. (2022). Analytical study on growth-induced axisymmetric deformations and shape-control of circular hyperelastic plates. *International Journal of Engineering Science*, *170*(31), 103594. https://doi.org/10.1016/j.ijengsci.2021.103594

# Simulation(needs expertise)

Each folder also contains necessary files to run the simulation using ABAQUS. To run the simulation, please make sure 

- Visual Studio and Parallel Studio are linked to ABAQUS, such that it can be used for subroutine development. [Here](https://www.researchgate.net/publication/349991987_Linking_ABAQUS_20192020_and_Intel_oneAPI_Base_Toolkit_FORTRAN_Compiler) is a linking guide from the internet. 

- Submit the job through ABAQUS COMMAND window, for example

  ```fortran
  C:
  cd C:\$YourPath$\growth-of-circular-plate\ShapeProgramming
  
  abaqus job=CASE1 user=Growth-CASE1.for 
  ```

  

# Graphical abstract

![GraphicalAbstract](https://github.com/Jeff97/growth-of-circular-plate/blob/main/GraphicalAbstract.jpg)

