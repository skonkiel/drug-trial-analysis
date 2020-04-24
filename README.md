# Drug trial analysis

## About this project
This project analyzes ficticious cancer drug trial information for Capomulin and its competitors, to determine their effectiveness in reducing tumor size in test subjects.

A major focus of this project was using [Matplotlib](https://matplotlib.org/) to visualize the data, and applying linear regression (via [SciPy.stats](https://www.scipy.org/scipylib/index.html)) to determine if results were statistically significant.

## Findings

The results from this drug trial are promising, but should be interpreted carefully due to the small sample size.

* Capomulin-treated mice had a much smaller average tumor size at the end of treatment (38.125164 mm3) than mice treated with Infubinol (60.165180 mm3) and Ceftamin (59.851956 mm3). The largest tumor for Capomulin-treated mice (47.685 mm3) was only slightly larger than the smallest tumor for Infubinol (45.0 mm3).
* Ramicane performed comparably to Capomulin with regard to tumor size at the end of treatment, making it the strongest competitor.
* Capomulin saw the smallest number of subject deaths during the course of the 45-day study (n=4) compared to the other most promising drugs studied (Ramicane, n=5; Infubinol, n=16; Ceftamin, n=12).
* There is a strong positive correlation (r squared = 0.84) between mouse weight and average tumor size for mice treated with Capomulin.

## Explore the analysis
Open the `Pymaceuticals.ipynb` Jupyter Notebook to learn more about the analysis and review the visualizations.
