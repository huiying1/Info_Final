# My-Project
For my project, I will analyze the Malawi dataset "mw2012_preg_20210915.sas7bdat".
This study focuses on estimating the mean trajectory of CRP during the course of pregnancy and characterizing interaction effects on this association.

## Execute the analysis

To execute the analysis from Docker, first pull the image from Docker hub using

``` bash
docker pull huiying1/info_final
```
To build the image and report, run

``` bash
docker run -v /your_local_path/project_output:/project/output -it huiying1/info_final
```
Replace "/your_local_path" with desired directory on your laptop. If you want to retrieve the html report at your local diectory, you can create a folder in your local directory. In the example here, I created a folder called output under Desktop. 
``` bash
docker run -v ~/Desktop/output:/one/output -it huiying1/info_10
```
The report can be retrieved from the output folder in this directory.



