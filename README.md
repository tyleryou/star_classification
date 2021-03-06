# Star Classification

![image](https://user-images.githubusercontent.com/84543484/155414709-90300560-9a49-4433-a520-1d10c42bddba.png)


This dataset was obtained from Kaggle at: https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17

The purpose of this dataset is to be used in classification models for designating stars, galaxies, and quasars using data taken from spectral characteristics. The nomenclature below includes all of the celestial features used in the dataset.

## Nomenclature 
- obj_ID = Object Identifier, the unique value that identifies the object in the image catalog used by the CAS

- alpha = Right Ascension angle (at J2000 epoch)

- delta = Declination angle (at J2000 epoch)

- u = Ultraviolet filter in the photometric system

- g = Green filter in the photometric system

- r = Red filter in the photometric system

- i = Near Infrared filter in the photometric system

- z = Infrared filter in the photometric system

- run_ID = Run Number used to identify the specific scan

- rereun_ID = Rerun Number to specify how the image was processed

- cam_col = Camera column to identify the scanline within the run

- field_ID = Field number to identify each field

- spec_obj_ID = Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)

- class = object class (galaxy, star or quasar object)

- redshift = redshift value based on the increase in wavelength

- plate = plate ID, identifies each plate in SDSS

- MJD = Modified Julian Date, used to indicate when a given piece of SDSS data was taken

- fiber_ID = fiber ID that identifies the fiber that pointed the light at the focal plane in each observation
