
# Callistory

`callistory` is a reusable project to assist creating DIY technology events.  This project will prototype the first Callisto Morn event in Atlanta, Georgia on November 11.

# Build

All build logic is contained with in the `readme.ipynb` file.  Use `nbconvert` to execute this notebook with the command below.

    !jupyter nbconvert --inplace --execute --to notebook readme.ipynb


```python
    !jupyter nbconvert --to markdown *.ipynb
    !jupyter nbconvert --TemplateExporter.exclude_input=True --TemplateExporter.exclude_input=True index.ipynb 
```

    [NbConvertApp] Converting notebook about.ipynb to markdown
    [NbConvertApp] Writing 585 bytes to about.md
    [NbConvertApp] Converting notebook contributing.ipynb to markdown
    [NbConvertApp] Writing 648 bytes to contributing.md
    [NbConvertApp] Converting notebook index.ipynb to markdown
    [NbConvertApp] Writing 5493 bytes to index.md
    [NbConvertApp] Converting notebook long.ipynb to markdown
    [NbConvertApp] Writing 1140 bytes to long.md
    [NbConvertApp] Converting notebook participants.ipynb to markdown
    [NbConvertApp] Writing 30 bytes to participants.md
    [NbConvertApp] Converting notebook readme.ipynb to markdown
    [NbConvertApp] Writing 927 bytes to readme.md
    [NbConvertApp] Converting notebook short.ipynb to markdown
    [NbConvertApp] Writing 124 bytes to short.md
    [NbConvertApp] Converting notebook index.ipynb to html
    [NbConvertApp] Writing 257733 bytes to index.html


# [contributing](contributing.ipynb)


```python
    %%file custom.css
    .output code {display: none;}
```

    Writing custom.css

