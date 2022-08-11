![](https://i.imgur.com/bYXzIWY.png)
# Relative Elevation Model 
Tutorial on creating a [relative elevation model](https://ngmdb.usgs.gov/Info/dmt/docs/DMT16_Coe.pdf) in Python using [xarray](https://xarray.pydata.org/) and [datashader](https://datashader.org/).

Based on [*Creating REMs in QGIS with the IDW Method*](https://dancoecarto.com/creating-rems-in-qgis-the-idw-method) by [Dan Coe](https://twitter.com/geo_coe).


# Try it out

<h3 align="center">
  💧 <a href="https://mybinder.org/v2/gh/DahnJ/REM-xarray/HEAD?filepath=rem-in-xarray-tutorial.ipynb">Binder</a> 💧 <a href="https://colab.research.google.com/github/DahnJ/REM-xarray/blob/master/rem-in-xarray-tutorial.ipynb">Colab</a> 💧 <a href="https://nbviewer.org/github/DahnJ/REM-xarray/blob/master/rem-in-xarray-tutorial.ipynb">nbviewer</a> 💧
</h3>

# Run locally

### Conda
```bash
conda env create -f environment.yaml
conda activate rem-tutorial
jupyter notebook
```

### venv
```bash
python -m venv rem-tutorial
source rem-tutorial/bin/activate
pip install -r requirements.txt
jupyter notebook
```

### Downloading the sample data
If you have [git-lfs](https://git-lfs.github.com/) installed, the sample data gets cloned with this repository automatically.

Alternatively, you can follow [the video](https://nbviewer.org/github/DahnJ/REM-xarray/blob/master/rem-in-xarray-tutorial.ipynb#VIDEO:-How-to-download-data-from-NLS) on downloading the original raster data.

On Debian, Git LFS can be installed by
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
apt-get install git-lfs
git lfs install
```

# Examples

![](https://i.imgur.com/MFagpMt.jpg)
![](https://i.imgur.com/jRXcHVi.jpg)
![](https://i.imgur.com/2XcHIZW.jpg)


# REMs in other languages/tools
- [QGIS](https://dancoecarto.com/creating-rems-in-qgis-the-idw-method) by [Dan Coe](https://twitter.com/geo_coe)
- [Google Earth Engine](https://twitter.com/KelMarkert/status/1509714680364748801) by [Kel Markert](https://twitter.com/KelMarkert)
- [RiverREM](https://github.com/klarrieu/RiverREM), a Python package for producing REMs automatically
