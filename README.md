# When Less is More: Evaluating Structural Pruning in Geospatial Foundation Models

#### Paper accepted at CV4EO Workshop of WACV 2026


### Dataset
Four different datasets are used for experimentation:
* [Above Ground Biomass](https://huggingface.co/ibm-granite/granite-geospatial-biomass) - regression task
* [Burn Scars](https://huggingface.co/datasets/ibm-nasa-geospatial/hls_burn_scars) - binary segmentation task
* [m-Cashew-Plantation](https://source.coop/technoserve/cashews-benin) - multiclass segmentation task
* [m-EuroSAT](https://zenodo.org/records/8276933) - classification task


  ### Geospatial Foundation Models
Three different Geospatial Foundation Models (GeoFMs) are tested on structural pruning:
* [Clay-v1](https://github.com/Clay-foundation/model)
* [Prithvi-L](https://github.com/NASA-IMPACT/Prithvi-EO-2.0)
* [TerraMind-B](https://github.com/IBM/terramind/tree/main)

  ### Structural Pruning Strategies
  Experimented on below strategies:
  * L2
  * Taylor
  * Hessian
