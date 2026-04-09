# When Less is More: Evaluating Structural Pruning in Geospatial Foundation Models

#### Paper accepted at [CV4EO](https://geoai.ornl.gov/cv4eo-wacv/) Workshop of [WACV 2026](https://wacv.thecvf.com).


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


## Citation

If you use this code in your research, please cite the paper:

```bibtex
@InProceedings{Said_2026_WACVW,
    author    = {Said, Amina and Dietlmeier, Julia and McCaul, Margaret and O'Connor, Noel E.},
    title     = {When Less is More: Evaluating Structural Pruning in Geospatial Foundation Models},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) Workshops},
    year      = {2026},
    pages     = {1403-1413},
    url       = {"https://openaccess.thecvf.com/content/WACV2026W/CV4EO/html/Said_When_Less_is_More_Evaluating_Structural_Pruning_in_Geospatial_Foundation_WACVW_2026_paper.html"}
}
