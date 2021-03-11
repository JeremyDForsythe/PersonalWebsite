---
title: "Software"
date: 2020-06-09
---

<p align="center">
<img src="Computer.png", width =200>
</p>


As a data scientist I tend to write simple code, using only the minimal amount of external
packages required to complete the task. Most of my software is used internally in the labs I work for
and is tailored for specific uses or data-sets, however I am a strong advocate for open source development.

My software is primarily written in R or Python, though occasional bash scripts and GNU Octave
code are utilized for specific tasks. All of my documents are typeset with <span class="latex">L<sup>A</sup>T<sub>E</sub>X</span> or R Markdown.


> To download, clone, contribute to, comment on, or fork any of my public coding projects [please visit my GitHub page](https://github.com/JeremyDForsythe).

<p style="margin-bottom:1.5cm;"></p>

<p align="center">
<img src="Octocat.png", width =200>
</p>

### Projects With Code Publicly Available Through GitHub

* <span style="text-decoration:underline"> My Personal Website:</span>
  * The branch [Personal Website](https://github.com/JeremyDForsythe/PersonalWebsite)
is this webpage, which was built in Hugo, themed with LoveIt, pushed to GitHub, and hosted with Netlify.
{{< style "img { height: 1.25rem; }" >}}
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.62.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)
[![LoveIt GitHub Release](https://img.shields.io/github/v/release/dillonzq/LoveIt?style=flat-square)](https://github.com/dillonzq/LoveIt/releases)
[![GitHub](GitHub.png)](https://www.github.com/)
[![Netlify](Netlify.png)](https://www.netlify.com/)
{{< /style >}}

<p style="margin-bottom:1.5cm;"></p>

<p align="center">
<img src="Lab.png", width =150>
</p>

### "In House" Lab Coding Projects 

(Please <a href = "mailto: jdforsy@g.clemson.edu"> contact me</a> if You Are Interested In The Source Code, Or Developing One Of These Projects Into An Open Source Program)

* <span style="text-decoration:underline"> Flux Tower QA/QC:</span> 
  * In George Burba's book [A Brief Practical Guide to Eddy Covariance Flux](https://www.licor.com/env/pdf/eddy_covariance/Brief_Intro_Eddy_Covariance.pdf), he describes the main challenge of adopting eddy covariance flux methods for research "is the shear complexity of system design, implementation and processing of the large volume of data". As our flux sensors record observations at 10hz continously throughout the year, we wanted a way to keep track of the performance of our instruments and flag interesting or anomalous readings. 
  * Built in R Markdown and utilizing code chunks from R and Python, the Flux Tower QA/QC program automatically generates a PDF document reporting out of tolerance values, plotting timeseries for variables of interest, and converts diagnostic codes from our Licor and Cambell Scientific hardware into counts, descriptions, and time down percentages. 

* <span style="text-decoration:underline"> Ameriflux Data Pipeline:</span>  
  * We publish our publicly available data to the Ameriflux network, which was established to store, distribute, and synthesize data from eddy covariance sites studying terrestrial carbon cycling in the Americas. Since the network accepts data from PI-managed sites in addition to its own towers, there is a set of protocols that are used to standardize the data across the network. 
  * Using R code the Ameriflux data pipeline combines the output from [Licor's Eddypro Software](https://www.licor.com/env/support/EddyPro/home.html) and measurements made by our meteorology stations to an Ameriflux formatted CSV data file that is ready to submit to the network.

* <span style="text-decoration:underline"> Analyzing Forest Diameter Distributions with Maximum Likelihood:</span>
  * The underlying distribution of tree diameters is often used by foresters and ecologists examing the health and stability of tree populations.
  * This R code determines which distribution best fits a sampled tree population from a pool of candidate models using maximum likelihood methods.
  * This project is part of a publication that is currently being drafted and will soon be a R package available through github.

<p style="margin-bottom:1.5cm;"></p>

<p align="center">
<img src="Globe.png", width =150>
</p>

### Freelance / Collaboration

I enjoy solving puzzles and I find coding/data science challenges to be exciting. If you are interested in collaboration or hiring me for a freelance project <a href = "mailto: jdforsy@g.clemson.edu">please feel free to contact me</a>.

Previous projects include teaching R & RMarkdown, analyzing an upstart brewery's brand
ambassador program performance, web scraping for sports statistics, and
using machine learning to predict future housing market changes.

<p align="center" style="margin-top:1.25cm;"><i class='fas fa-tree'></i><i class='fas fa-tree'></i><i class='fas fa-tree'></i></p>
