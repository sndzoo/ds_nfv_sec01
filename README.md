# SND-Zoo Data Set: ds_nfv_sec01

This is a data set published as part of the [**Software Network Data Zoo (SNDZoo)**](https://sndzoo.github.io). You can find more information about this data set and instructions how to use it at the official SNDZoo project website: [sndzoo.github.io](https://sndzoo.github.io).

## Author / Contact

**Manuel Peuster**<br>
Twitter: [@ManuelPeuster](https://twitter.com/ManuelPeuster)<br>
GitHub: [@mpeuster](https://github.com/mpeuster)<br>
Web: [https://peuster.de/](https://peuster.de/)<br>
Mail: manuel (at) peuster (dot) de<br>

## How to fetch the dataset?

This repository uses [DVC.org](https://dvc.org/), an open-source version control system for machine learning projects, to version the data blobs contained in the data set. You need to install [DVC](https://dvc.org/) to fetch the full data set, which is hosted by Amazon S3.

To fetch the full dataset follow these steps:

```sh
# 1. install DVC (https://dvc.org/), for example:
pip install dvc
# 2. clone this repository
git clone <https://github.com/<path-to-this-repo>
# 3. swtich into the cloned directory
cd <path-to-this-repo>
# 4. fetch the full data sets (this can take some time)
dvc pull
```

You find the actual data blobs, e.g., CSV files, inside `data/`.

## Acknowledgments
This work has received funding from the European Union's Horizon 2020 research and innovation program under grant agreement No. H2020-ICT-2016-2 761493 (5GTANGO), and the German Research Foundation (DFG) within the Collaborative Research Centre "On-The-Fly Computing" (SFB 901).

## License
(c) 2019 by Manuel Peuster (Paderborn University)<br /><br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
