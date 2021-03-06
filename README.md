# A dataset of thin-walled deformable objects

This is a dataset of thin-walled object models with volumetric representations, which is generated based on 13 real objects. To create more object models, we use a model generator which includes two types of variants:

- Geometric variants
  - We use primitives to paramerize the object geometry. The object models are generated by varying the value of the geometric parameters within a realistic range. 
  
- Structural variants
  - We include structural parameters including:
    - rim: A reinforcement structure on the top of the object.
    - cap: A cap to close the top of the object. This represents a closed object.
    - flat: Partially flat walls.
    - dent: A dent on one side of the object.


Two subsets are presented, which has different variants: 

- ObjectModelsDemo
  - Geometric variants: Not included. The geometry of the object models are generated based on the real objects.
  - Structural variants: Included.
  - In total: 30 obj files. 
  
- ObjectModelsVariants
  - Geometric variants: Included.
  - Structural variants: Included.
  - In total: 2214 obj files. 
  
Each subset contains a file object_parameters.csv, which is the list of objects with geometric (unit mm) and structure parameters (rim, enclosed, dent, flat).  

Details please refer to the paper:
N. Alt, J. Xu, E. Steinbach, 
A dataset of thin-walled deformable objects for manipulation planning,
Grasping and Manipulation Datasets (ICRA Workshop), Stockholm, Sweden, Mai 2016.

### License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
