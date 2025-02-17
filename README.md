# Graph Based Method and Radiomics Signature for Identification of Tuberculous Meningitis
This repository is for code of Tuberculous Meningitis Classification between baseline patients and control using RoI patches from three regions, bone, corpus callosum, interpeduncular cistern

![Sample Outputs](image/Image__2024-05-16__12-32-30_output_wLegend.png)

## Comparitive results for the Graph Based Approach
![Sample Outputs](image/alpha.png)

## Comparitive results for the Radiomics based approach
![Sample Outputs](image/beta.png)


## Project Contacts

Snigdha Agarwal (snigdha.agarwal@iiitb.ac.in)
Jitender Saini (jsaini76@gmail.com)
Neelam Sinha (neelamsinha@iisc.ac.in)

## Security and Permissions

Images for this study are sourced internally from the Neurology Department of the National Insitute for Mental Health and Neuroscience, Bangalore, India. The images will be provided on request to any qualified researcher using the contacts below,
Ganaraja VH
Jiteder Saini

## Results

### Graph Based model with f1-score across all three regions is given below

![Performance](image/alpha_performance.png)

### Comparison with radiomics approach is given below

![Performance](image/beta_performance.png)

## Set-Up

We used python 3.10.9 (e.g., `/Users/snig/.pyenv/versions/3.10.9/bin/python`)


#### Git clone

```commandline
```

### To run and evaluate the model on existing images

Set up virtual environment using venv

```commandline
pip install pip==24.2
pip install -r requirements.txt
```
