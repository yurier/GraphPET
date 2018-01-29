# GraphPET <span style="color:green"> -- entry zero -- </span>

### Glass plot (Visualization)

* Human, mouse and rat 3D brain image
* written in Python
* input (isocurves matrices, positions, igraph description of connectivity)
* output brain 3D glassplot
* plot edges (directed(und), colored, alpha, arrowhead control)
* requires to add manually the brain regions using a template
* requires high throughput video acceleration hardware

### Representative Matrices (Visualization)

* written in Python (we have to change from R to python)
* inputs (PET data from regions and groups)
* interactive plot using plotly (zeros number, p-values, mean, median matrices (other averages matrices), mountain jump optimization for alpha and correlation)
* Plannar graphs (strength and correlation)(we have to change from R to python)
* Correlations plots

## Maximizing structure difference

* Optimization of correlation/alpha to separate classes structurally
* Extract graph theoretical measures
* Connectivity rules
* Other corrections different FDR

## Graph perturbations and iMBNs

* inputs (PET data from regions and groups - train and test)
* output (iMBNs, representative classes, performance measures)
* visualization of iMBNs using plotly

## To do

* correlation between pseudopermutations matrices.
* stabilization analysis (convert matlab to python)
* convert algorithms to python
