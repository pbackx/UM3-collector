Don't know how to get data of of your Ultimaker 3 printer? 
This project shows how to load the Ultimaker 3's diagnostic data 
into a Jupyter Notebook and process it with Pandas.

To get started, first create and activate the Conda environment:

    conda env create -f environment.yml
    source activate um3-collector
    
Next, you are ready to launch Jupyter and run the notebook:

    jupyter notebook

[You can get a preview right here](https://github.com/pbackx/UM3-collector/blob/master/Load%20UM3%20diagnostics.ipynb).
    
After you have this up and running, you can find more details on [the
UM3 API right here](https://ultimaker.com/en/community/23283-inside-the-ultimaker-3-day-2-remote-access-part-1) 
or check [my blog series on 3D printing](http://www.streamhead.com/category/3d-printing/).