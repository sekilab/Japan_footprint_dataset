# Japan footprint dataset

The Japan Footprint Dataset comprises approximately 50 million building footprints located within Japan extracted from Mapbox satellite imagery（0.6m resolution) through the utilization of a super-resolution-based instance segmentation method. Extracted models and training details can be found in [this paper](https://www.sciencedirect.com/science/article/pii/S0924271622002933).

![Image text](https://github.com/sekilab/Japan_footprint_dataset/blob/master/Image/Building_count.png)

![Image text](https://github.com/sekilab/Japan_footprint_dataset/blob/master/Image/Example.png)


## Download dataset
For ease of extraction, the whole of Japan is divided into 4424 10km by 10km grids, and a geojson file exists for each region containing buildings. The number of each folder corresponds to the [Japanese secondary standard mesh](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjq0L7vxPeDAxVAmlYBHRgRBcEQFnoECBIQAQ&url=https%3A%2F%2Fwww.gsi.go.jp%2Fcommon%2F000218188.pdf&usg=AOvVaw21NZvHJVipnWzBngY28Cl0&opi=89978449).

Download link: s3://sekilab-public-data/Building_footprint_Japan/


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.





<!-- CONTACT -->
## Contact

For any question and support, please create an issue on GitHub or write to the author here:

Shenglong Chen  - chen-sl[at]csis.u-tokyo.ac.jp



## Citations
```csv
@article{chen2023large,
  title={Large-scale individual building extraction from open-source satellite imagery via super-resolution-based instance segmentation approach},
  author={Chen, Shenglong and Ogawa, Yoshiki and Zhao, Chenbo and Sekimoto, Yoshihide},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={195},
  pages={129--152},
  year={2023},
  publisher={Elsevier}
}
```

