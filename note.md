# ARIEL Data Challenge

## What is ARIEL

ARIEL is an acronym.
It stands for **Atmospheric Remote sensing Infrared Exoplanet Large-survey**.
Basically te mission is to establish a link beetween the characteristics of an exoplanet (like details about its atmosphere and stuff) and the host star.
Hence, we need a large-scale survey (like civil engineering survey) of exoplanets.
ARIEL is the first mission dedicated to measuring the chemical make-up and atmospheric temperature profiles of hundreds of exoplanets.

![](https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2023/03/transmission_spectroscopy/24759493-1-eng-GB/Transmission_spectroscopy_article.png)

![](https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2023/03/transmission_spectroscopy/24759493-1-eng-GB/Transmission_spectroscopy_article.png)

## Understanding the Data

Short Background:
    - Important to understan what is contained in the atmosphere of exoplanets.
    
We require the participant to detrend a large number of sequential 2D images of the spectral focal plane taken over several hours of observing the exoplanet as it eclipses its host star.

### How is it collected
 - Collected by telescopic measurement of light as planets move across their respective stars
    - The ARIEL instrument has:
        1. Cassegrain reflector telescope
        1. Med-res IR Spectrometer (SPECTRAL)
        1. Fine Guidance System (FGS)
            - Three NIR photometer channels (SPATIAL)
                - Measures brightness (light intensity)
            - Low res NIR Spectrometer
        1. It takes these over time, like several hours (TEMPORAL)
            
    - Somethings to consider:
        - Natural wavelengths of the star
        - How they're changed by gyroscopic noisee atmosphere as it passes throu h
        - High "vibrational" and ghg

- 50–200 photons per million is the "concentration" of photons from the exoplanets atmosphere, compared to light that the instrument receives


### What do the 3D tensors mean

## Objectives

1. The task of this competition is to **extract the atmospheric spectra** from each observation, with an estimate of its level of uncertainty.