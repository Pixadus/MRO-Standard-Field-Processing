# Standard Field Processing

This is a notebook to automatically process standard fields, plate-solve for them and identify transformation coefficients.

UW's Jupyter instance should already have all necessary packages - if running locally, create a Python virtual environment with `python -m venv venv`, then run `source venv/bin/activate`, then install necessary packages with 

```
pip install astropy ccdproc astrometry scipy numpy==1.26.4 pathlib sep logging matplotlib photutils
```

Currently, I have images of the standard field SA 38-303 in `data/standard-fields` - replace them with your own, and put calibration frames in `data/calibration-frames` if your standard fields are not yet calibrated. 