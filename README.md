This repository contains a sample of Python code I wrote for statistically analyzing the linearity between sample concentration and detection of an oncogenic target.  

The datasets were generated from high-throughput, automated Western blot assays I ran in the lab.

How the code works:
<ul>
  <li>Uses Pandas and Numpy to split the data into different concentration "regions".</li>
  <li>Uses Scikit-learn to apply a linear regression model to each region and extract the corresponding $R^2$ value.</li>
  <li>Uses functions for plotting subplots with the different concentration regions defined/highlighted. Legends display the corresponding $R^2$ value.
    <ul>
      <li>The highest $R^2$ value is displayed in red text for ease of determination.</li>
    </ul>
  </li>
</ul>

