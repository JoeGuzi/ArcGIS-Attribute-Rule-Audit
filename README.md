Description: This will audit all of the items in the GDB and report the attribute rules.

Created on: 9/11/2023

Purpose:This is a Jupyter Notebook that prompts the user for a path to a gdb, then the script will audit that gdb, list all of the feature classes/tables that have attribute rules, and the details about them.This script will prompt the user for a path to a file geodatabase or a sde geodatabase connection file. Then the script will loop through the feature classes\tables and document details about the attribute rules. All of the data gathered is written to a csv file. This is a Jupyter Notebook written using arcpy.

Authored by: Joe Guzi

Previous Production Date: 9/11/2023 

Production Date: 8/12/2024

Notes:
- Sources used to develop this notebook:
    - https://community.esri.com/t5/arcgis-pro-questions/iterate-through-sde-to-find-and-export-fcs-with/td-p/1154338
    - https://www.esri.com/arcgis-blog/products/api-python/data-management/automate-attribute-rules-deployment/
    - https://pro.arcgis.com/en/pro-app/latest/arcpy/functions/attribute-rule-properties.htm
- 8/12/2024 --- Updated with template
