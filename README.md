# A socioeconomic assessment of projected health impacts from outdoor air pollution under current European climate policy

Clàudia Rodés-Bachs<sup>1</sup>, Jon Sampedro<sup>1,2</sup>, Mercè Amich<sup>1,3</sup>, Alexandros Nikas<sup>4</sup>, Konstantinos Koasidis<sup>4</sup>, Claudio A. Belis<sup>5</sup>, and Dirk-Jan Van de Ven<sup>1</sup>, 

<sup>1 </sup> Basque Center for Climate Change, Leioa, Spain

<sup>2 </sup> IKERBASQUE, Basque Foundation for Science, Plaza Euskadi 5, 48009 Bilbao, Spain

<sup>3 </sup> Euskal Herriko Unibertsitatea (UPV/EHU), 48940, Leioa, Spain

<sup>4 </sup> National Technical University of Athens, Athens, Greece

<sup>5 </sup> European Commission – Joint Research Centre, via Fermi 2749, 21027, Ispra, Italy

\* corresponding author:  claudia.rodes@bc3research.org

## Abstract
Background Outdoor air pollution poses a major threat to human health and is closely interlinked to climate change, as both stem largely from the same emission sources and pollutants affect both health and climate. Despite sustained mitigation efforts, over 239,000 premature deaths in Europe were attributed to PM2.5 exposure in 2022, while climate policies are projected to yield substantial yet insufficient co-benefits by 2030, with uneven impacts across regions and socioeconomic groups.

We applied GCAM-Europe to model emission pathways under the National Energy and Climate Plans (NECPs) and Fit-for-55 policy package. Premature mortality attributable to PM2.5 was estimated at both 1 km2 grid and NUTS3 levels using rfasst. Results were further analyzed through socioeconomic lens, both between and within countries, using quantitative assessments and machine learning techniques.

The Balkan countries and northern Italy emerge as the most affected regions in Europe. Urban populations face the greatest risks, with disproportionate burdens among low- and high-income groups and areas with average concentrations of elderly residents. Within-country analyzes reveal distinct, country-specific vulnerability patterns.

Incorporating social and health dimensions into environmental policymaking is essential for designing strategies that jointly advance decarbonization, reduce air pollution, and promote environmental justice. Attention to spatial resolution and geographic scale is critical, as coarse analyzes risk obscuring vulnerable populations and regional disparities.


## Code reference
Available at Zenodo [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17913693.svg)](https://doi.org/10.5281/zenodo.17913693)


Rodés-Bachs, C., Sampedro, J., Amich, M., Nikas, A., Koasidis, K., Belis, C. A., & Van de Ven, D.-J. (2025). Rodes-Bachs_etal_AP_health_ineq_EU (Version Rev1). Zenodo. https://doi.org/10.5281/zenodo.17913693


## Contributing modeling software
| Model | Version | Repository Link 
|-------|---------|-----------------
| Global Change Analysis Model Europe (GCAM-Europe) | 7.2 | [https://doi.org/10.5281/zenodo.15655568](https://zenodo.org/records/15655568) | 
| rfasst | 2.1 | [upcomming release](https://github.com/bc3LC/rfasst) | 

| Component| Version | Repository Link 
|-------|---------|-----------------
| gcamdata | 1.0 | https://github.com/JGCRI/gcamdata | 
| rgcam | 1.2.0 | https://github.com/JGCRI/rgcam | 
| pridr | 0.1.0 | https://github.com/JGCRI/pridr | 
| rmap | 1.0.0 | https://github.com/JGCRI/rmap | 

## Reproduce the experiment
To reproduce the results and figures shown in Rodés-Bachs et al.,

1. Install `R` (https://www.r-project.org/).
2. Install `R studio` (https://www.rstudio.com/).
3. Download the data files available at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17913230.svg)](https://doi.org/10.5281/zenodo.17913230) and place them in the `data` folder.
3. Run the script called `R/main.R` to generate the figures and reproduce the analysis.

## Acknowledgments
<img src="./diamond-logo.png" alt="DIAMOND logo" width="80" height="54" align="left"/>
This project has received funding from the European Union's Horizon 2020 research and innovation program under grant agreement numbers 101081179 (DIAMOND project).
