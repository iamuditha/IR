# IR

This project contains a sinhala song search engine developed using elastic search and python.

the **scraper** folder contains the code for the data extracting. For the whole project 1000+ song data were used and all of them were scarped from the website www.sinhalasongbook.com . Each of the song consisted the following data fields. 
       
        1.	Title ( name of the song / the first few words of the song)
        
        2.	Genre ( the genre the song belongs to. )
        
        3.	Guitar key
        
        4.	Views ( number of views of the song)
        
        5.	Artist ( singer of the song)
        
        6.	Lyrics (author of the song)
        
        7.	Music ( musician of the song )
        
        8.	Song Lyrics ( song )

All of the above data are in Sinhala language.

**Guide to insatll the project**

  1. Run the **song_scraper.py** file in the scraper folder. It will scrap the song details
  
  2. Insatll and Run **Elastic Search** and **Kibana**
  
  3. Copy and Paste the code in **mapping.json** in the Kibana
  
  4. Run the **app.py** in the IR folder



