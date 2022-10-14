### Workflow: Test new versions of Plotly and Dash

    # clone conda environment
    conda create --name spot2 --clone spot1
    
    # check whether pip is installed in the active environment
    where pip
    
    # upgrade plotly
    pip install plotly --upgrade
    
    # upgrade dash
    pip install dash --upgrade