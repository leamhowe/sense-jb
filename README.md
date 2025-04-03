# sense-jb
![SENSE CDT written by Landsat](images/SENSE_CDT.png)


Repository for the [Jupyter Book](https://jupyterbook.org/en/stable/intro.html) of [SENSE](https://eo-cdt.org/) training materials.

- html files are found under `/build/html`.
- All tutorials are found in `/book`.

## View website locally

If you clone this repo you will then have all the necessary files to view the book locally. Simply open `/build/html/intro.html` in your browser.


## Additions

If you want to make additions or changes, you will need the correct environment. 

The environment requirements needed to run all notebooks and build the Jupyter Book is found in [`environment.yml`](environment.yml). This can be installed using conda. I recommend using the [Miniforge](https://github.com/conda-forge/miniforge) distribution of conda. Once installed you can run:
```
conda env create -f environment.yml -n sensebook
```

Once the environment is setup (which might take a while), it can be activated with:
```
conda activate sensebook
```

Once the environment is activated, and you are in the home dir /sense-jb. The book can be built using:
```
jb build .
```


## Issues

Please don't hesitate to get in contact if you have any issues. Email me at
leam.howe@ed.ac.uk or leamhowe1@gmail.com.