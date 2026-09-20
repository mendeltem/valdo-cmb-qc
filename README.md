# VALDO microbleed quality control

**Open the page: https://mendeltem.github.io/valdo-cmb-qc/**

An interactive quality-control view of automatic cerebral microbleed detection on the 57 cross-validation cases of the
VALDO 2021 challenge, Task 2 (T2*-weighted MRI): axial slices in three columns per patient, reference annotation in yellow,
network prediction in red (anisotropic 3D U-Net, 5-fold cross-validation; every case is predicted by the model that never saw it).
Research and teaching use only -- not a medical device, not for clinical decisions.

## Data, attribution and licence

The images and reference annotations are derived from the public training data of the challenge:

> Sudre, Carole Hélène; Van Wijnen, Kimberlin; Dubost, Florian; de Groot, Marius; de Bruijne, Marleen (2021).
> Training dataset for the VALDO 2021 challenge - Vascular Lesion Detection. Zenodo. DOI: 10.5281/zenodo.4520773

Challenge paper: Sudre CH et al., "Where is VALDO? VAscular Lesions Detection and segmentatiOn challenge at MICCAI 2021",
Medical Image Analysis 2024 (arXiv 2208.07167).

Task 2 data come from the SABRE study, the Rotterdam Scan Study and the ALFA study, **for the ALFA Study**. ALFA contributors:
Müge Akinci, Annabella Beteta, Raffaele Cacciaglia, Alba Cañas, Irene Cumplido, Carme Deulofeu, Ruth Dominguez, Maria Emilio, Carles Falcón, Karine Fauria, Sherezade Fuentes, Juan Domingo Gispert, Oriol Grau-Rivera, José M. González-de-Echávarri, Laura Hernandez, Gema Huesa, Jordi Huguet, Iva Knezevic, Eider M. Arenaza-Urquijo, Eva M Palacios, Paula Marne, Tania Menchón, Marta Milà-Alomà, Carolina Minguillon, José Luis Molinuevo, Grégory Operto, Albina Polo, Gemma Salvadó, Sandra Pradas, Blanca Rodríguez, Aleix Sala-Vila, Gonzalo Sánchez-Benavides, Mahnaz Shekari, Anna Soteras, Marc Suárez-Calvet, Laura Stankeviciute, Marc Vilanova and Natalia Vilor-Tejedor.

Funding acknowledged as requested by the data providers: Wellcome Trust (082464/Z/07/Z), British Heart Foundation (SP/07/001/23603, PG/08/103, PG/12/29/29497 and CS/13/1/30327), Erasmus MC University Medical Center, the Erasmus University Rotterdam, the Netherlands Organization for Scientific Research (NWO) Grant 918-46-615, the Netherlands Organization for Health Research and Development (ZonMW), the Research Institute for Disease in the Elderly (RIDE), and the European Union Seventh Framework Programme (FP7/2007–2013) under grant agreement No. 601055, VPHDARE@IT, the Dutch Technology Foundation STW.

Cohort references: Tillin T, et al. Southall And Brent REvisited: Cohort profile of SABRE. Int J Epidemiol 2012, doi:10.1093/ije/dyq175 ·
Jones S, et al. Cohort profile update: SABRE. Int J Epidemiol 2020, doi:10.1093/ije/dyaa135 · Molinuevo JL, et al. 2016,
doi:10.1016/j.trci.2016.02.003 · Ikram MA, et al. The Rotterdam Scan Study: design update 2016 and main findings.
Eur J Epidemiol 2015, doi:10.1007/s10654-015-0105-7.

**Licence:** the source data are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
The slice images, outlines and this page are adaptations of that material and are shared under the same licence,
CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/): non-commercial use only, give credit as above, share adaptations alike.
Changes made: bias-field correction, resampling to 0.5 x 0.5 x 1.0 mm, cropping to the brain, conversion of selected axial slices
to 8-bit images, drawing of outlines.
