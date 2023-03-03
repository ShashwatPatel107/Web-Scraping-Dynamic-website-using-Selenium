# Scraping-Topic-Wise-Video-Details-on-YouTube-using-Selenium
## TECHNOLOGIES USED:
* Python
* Selenium
* Beautiful Soup


## GOAL:
To create helping function to built dataset of video informations on perticular topic.


## PROCESS:
1. Understanding the structure of the YouTube Website. 
2. Installing and Importing required libraries. 
3. Getting the keyword(s) from user. 
4. Using we search videos for the Keyword.
5. Download the webpage URL using selenium Web-driver.
5. Parsing the Top Videos get the below attributes using functions. 

    A. Video Title  
    B. Name of the Channel    
    C. No.  Of views      
    D. Video Length	    
    E. Thumbnail image  
    F. Video Link 
    
6. Create helper functions to get combined lists.
7. Storing the extracted data into a dictionary.
8. Compiling all the data into a DataFrame using Pandas and saving the data into .CSV file. 


## CONCLUSION:
*   Program successfully created using Python Web-Scraping.
*   Scraping was done using Selenium and requests.
*   Users can type any topic that they want.
*   Automatically CSV has been generated using user given keyword.

