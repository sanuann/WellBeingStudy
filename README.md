# WellBeingStudy


Code to run the MIT Month of Wellness Challenge protocol using Reproschema.



### Instructions for making edits
* For each commit, a github action will test the JSONLD code. to know where the error is, you can run the commands in subdirectories.

    ```
    python -m pip install --upgrade pip setuptools
    pip install reproschema requests_cache
    
    reproschema -l DEBUG validate activities
    reproschema -l DEBUG validate protocol/WellBeing_schema
    ```

 


* To display images, click on the image, click on "raw" and copy the URL into the file (e.g., the README-en.md for the landing page). 
    In Markdown: 
    
    `![Timeline](https://raw.githubusercontent.com/danielmlow/WellBeingStudy/master/protocol/wellbeing_logo.svg)` 
    
    
    
When referencing to reproschema-library use the latest commit number

    