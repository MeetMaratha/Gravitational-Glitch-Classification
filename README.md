# Gravitational-Glitch-Classification
The data provided contains information about the type of gravitational glitch a non-Gaussian noise transient is detected. A high occurrence rate for these glitches in data can endanger the data we use for finding gravitational waves. There are 22 types of glitches in the data, for which we are trying to prepare a model that can classify these glitches.
#### Requirement to run IPYNB File
For running the ipynb file you will need to create a folder system in the folder containing IPYNB file
<ul>
  <li> <ul>Models
    <li> <ul>Bagging Classifier
      <li> Normal
      <li> Quantile Transformer
      <li> Quantile Transformer Normal
      <li> Robust Scaler
      </ul>
    <li> <ul> Random Forest
      <li> Normal
      <li> Quantile Transformer
      <li> Quantile Transformer Normal
      <li> Robust Scaler
      </ul>
    <li> <ul> Support Vector Machines
      <li> Quantile Transformer
      <li> Quantile Transformer Normal
      <li> Robust Scaler
    </ul>
  </ul>
</ul>

#### Required Python packages
<ul>
  <li> Numpy       == 1.22.2
  <li> SKLearn     == 1.0.2
  <li> Pandas      == 1.4.1
  <li> Matplotlib  == 3.5.1
  <li> Pickle      == 0.7.5
  <li> Seaborn     == 0.11.2
