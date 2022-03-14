![](https://i.imgur.com/bYXzIWY.png)
# Relative Elevation Model 
Tutorial on creating a [relative elevation model](https://ngmdb.usgs.gov/Info/dmt/docs/DMT16_Coe.pdf) in Python using [xarray](https://xarray.pydata.org/) and [datashader](https://datashader.org/).

Based on [*Creating REMs in QGIS with the IDW Method*](https://dancoecarto.com/creating-rems-in-qgis-the-idw-method) by [Dan Coe](https://twitter.com/geo_coe).


# Try it out

<h3 align="center">
  💧 <a href="TODO">Binder</a> 💧 <a href="https://colab.research.google.com/github/DahnJ/REM-xarray/blob/master/rem-in-xarray-tutorial.ipynb">Colab</a> 💧 <a href="https://nbviewer.org/github/DahnJ/REM-xarray/blob/master/rem-in-xarray-tutorial.ipynb">nbviewer</a> 💧
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

# Examples


![](https://i.imgur.com/MFagpMt.jpg)
![](https://i.imgur.com/jRXcHVi.jpg)
![](https://i.imgur.com/2XcHIZW.jpg)
