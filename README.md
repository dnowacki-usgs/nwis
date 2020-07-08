# nwis: Fetch USGS NWIS data

A simple utility to fetch data from [USGS Water Services](https://waterservices.usgs.gov) and return as a pandas DataFrame or xarray Dataset.

## Installation

Clone the repository, and from the `nwis` directory, type `pip install .`.

## Usage

```python
import nwis
ds = nwis.nwis_json("01646500", parm="00060", start="1995-01-01", end="1995-12-19T12:00", xarray=True)
```
