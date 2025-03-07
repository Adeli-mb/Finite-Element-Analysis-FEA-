<h1>Finite Element Analysis (FEA)</h1>

<h2>Project Outline</h2>
<ul>
<li>Performed a finite element analysis using ABAQUS software, to determine the maximum stress experienced by a plate with a hole due to an applied tensile force.</li>
<li>Thin plates with holes facilitate service ducts, structural connects and more.The holes however induce stress concentrations and higher stress distribution parameters. FEA allows for adequate determination of stress capacity. </li>
</ul>  

<h2>How? - Design Changes</h2>
<ul>
<li>Simplified the 3d plate to a 2d model using plane stress approximations  </li>
<li>Utilised symmetry boundary conditions to model a quarter of the plate.</li>
<li>Conducted a mesh convergence study with element counts ranging from 30 to 9000 </li>
<li>Compared FEA results with theoretical stress concentration calculations </li>
<li>Modelled the load as uniform</li>
</ul>
  <p align="center"> 
Plate with a hole - Boundary condtions and Tensile load applied<br/>
      <a href="https://imgbb.com/"><img src="https://i.ibb.co/7tZJj2Pw/FEA-original-shape-small.png" alt="FEA-original-shape-small" border="0">
      
<h2>Results</h2>
    <ul>
  <li>Determined an optimal mesh density of 996 elements, this balanced accuracy and computational time </li>
  <li>Maximum stress occurred around the hole, this aligned with theoretical values(percentage error of under 5%) - FEA mesh converged and was validated as superior to theoretical calculations values, proving to be more accurate</li>
</ul>
  <p align="center"> 
Deformed Plate - using optimal mesh density
    <br/>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/mVYqLRWr/FEA-deformed-shape.png" alt="FEA-deformed-shape" border="0">

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
