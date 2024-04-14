SDSS_LAB2024_photometry.fits
---------------------------
A photometric catalogue from the SDSS DR18 photometric catalogue in the north galactic cap. 

A description of the columns:
ID = SDSS unique photometric ID
ra = Right Ascension (J2000) (degrees)
dec = Declination (J2000) (degrees)
redshift = best estimate for the redshift of the source
sdss.Xp = observed flux in the SDSS filter X (mJy, corrected for Galactic extinction), where X can be u g r i z 
sdss.Xp_err = uncertainty on observed flux in the SDSS filter X (mJy, corrected for Galactic extinction), where X can be u g r i z 

3dhst_catalogue.fits
---------------------
A catalogue with the results of the stellar population fitting run on the 3D-HST fields using the FAST code. 
The papers explaining the dataset in detail are:
https://ui.adsabs.harvard.edu/abs/2016ApJS..225...27M/abstract
https://ui.adsabs.harvard.edu/abs/2014ApJS..214...24S/abstract

A description of the columns:
ID = Unique identifier
FIELDID = Unique identifier of the 3DHST field 
FIELDNAME = String description of the 3DHST field
RA_degree = Right Ascension (J2000) (degrees)
Dec_degree = Declination (J2000) (degrees)
m_F140W = Observed Magnitude in the HST WFC3 F140W filter (mag)
redshift = best estimate for the redshift of the source
Log_tau_yr = log10 of the tau of the exp. decining SFH (yr)
Log_age_yr = log10 of the age of the exp. declining SFH (yr)
Stellar_metallicity = metallicity of the stellar population model (0.02 is solar metallcity)
Av_old = Dust extinction for the old stellar component in V-band (mag)
Log_Mstar_Msun = log10 of the stellar mass (Msun)
Log_SFR_Msun_yr = log10 of the SFR (Msun/yr)
