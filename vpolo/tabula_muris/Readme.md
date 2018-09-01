# Motication
quick and dirty way to download tabula muris data from [czBiohub/Geo](https://github.com/czbiohub/tabula-muris)

# Install
`pip install vpolo`

# Requirements:
Python 3  
click  

# Use
```
from vpolo.tabula_muris import tmuris
```

```
⇒  python tmuris.py --help  
Usage: tmuris.py [OPTIONS]  

Options:
  -t, --tool TEXT                 Currently only tenx.
  --out TEXT                      Path to the folder where to save the data;
                                  make sure you have write permission
  -o, --organ [Tongue|Liver|Bladder|Kidney|Spleen|Marrow|Heart|Lung|Trachea|Thymus|Mammary|Muscle]
                                  Choose a type of organ
  -d, --datatype [bam|mtx|fastq]  type of data to download, if fastq make sure
                                  you have bamtofastq in path
  --help                          Show this message and exit.
```
