# jupyter-template
This is a template repository for Jupyter based training material.

## Best practices for Jupyter notebooks

### Keep notebooks short
Focus on one topic / visualisation / processing routine. Consider separate notebooks if multiple parts or topics are included.

### Keep headings consistent
- Keep headings in separate cells
- Use # for first level headings, ## for second level, and so on. Do not skip a level (e.g. do not follow a 1st level heading with a third level, without a second level in between).
### Make use of MyST markdown
Use coloured cells, icons, etc. where needed.

### Use of images
Any images unique to the Jupyter notebook should be stored in the ./img folder in this repository. Any images needed across multiple notebooks in multiple repositories (such as logolines) should be linked to elsewhere.

### Use of data
Data files should not be stored in the Github repository, but hosted externally and linked to, or downloaded from original source (CDS and ADS).
