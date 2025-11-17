# Biosample_Survery_Scraper
This project converts an existing R Shiny web application into a standalone Python program for retrieval of NCBI BioSample attribute survey responses.

## Overview  
This tool replaces an R Shiny application by providing a workflow for retrieving BioSample attribute surveys.  
Given a text file containing a list of BioSample IDs, the script:

1. Downloads each sample’s HTML page from NCBI  
2. Extracts the table of survey attributes  
3. Identifies the value associated with the question: "dominant hand" 
4. Outputs a clean CSV file  
