# Gaia-DR2-Tutorial

Gaia DR2 tutorial

## Goals

- Learn about Gaia DR2 data products
- Learn how to interface with Gaia archive with ADQL
- Perform the Gaia-KIC crossmatch
- (if time) Compute precise stellar radii using `isoclassify`

## Preparation 


1. Bring your laptops. We will be using ipython and pandas. 

1. Read the [executive summary](https://gea.esac.esa.int/archive/documentation/GDR2/index.html) of Gaia DR2 and familiarize yourself with the following datafields

   1. parallax
   1. astrometric_excess_noise
   1. phot_bp_mean_mag
   1. phot_rp_mean_mag 
   1. phot_g_mean_mag

1. Familiarize yourself with the following terms

   1. Distance modulus
   1. Bolometric correction
   1. Extinction 
   
1. Familiarize yourself with the [Gaia archive](https://gea.esac.esa.int/archive/) and the ADQL language

1. Learn about the ADQL language 
   
   1. Resources [1](https://gea.esac.esa.int/archive-help/adql/index.html) and [2](https://www.cosmos.esa.int/documents/915837/915858/ADQL_handson_slides.pdf/652b9120-a3fe-4857-b5eb-933b476687ad)
   1. Perform the "ADQL positional cross-match: Hipparcos vs. Gaia 1" radius" (Listed as a query example on the ADQL search page.)

1. Download the KIC Gaia crossmatch [link](https://www.dropbox.com/sh/rqrd0xcfrunwq3a/AABST14YsIwZAYH4cnfo7x8Aa?dl=0)

1. (If time) Skim [Fulton and Petigura 2018](https://arxiv.org/abs/1805.01453). Focus on Section 3.

1. (If time) Download and install [isoclassfiy](https://github.com/petigura/isoclassify)
    
    1. Make sure the following command works
    1. `isoclassify run direct sol --csv examples/example.csv --outdir output/sol`
  
