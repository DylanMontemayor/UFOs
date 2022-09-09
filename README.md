# UFOs
## Overview of the Module 11 Challenge

This project has the purpose of building a web page that shows data and it has five filters through which a user can add certain parameters and fin data according to that. The web page that was created for this project was built in two main languages: HTML and js. The web page visualization is in the HTML file and the engine for filtering and building the data is in js. An additional CSS file was added for styling purposes. 

### Folders/Files

index.html

static Folder: CSS (style.css), images (nasa.jpg), and js (app.js, data.js)

## Results

In the first two rows is possible to see the web page title and an image that was loaded through the images folder. In the third row, there is a paragraph that describes more about UFO Sightings. The next row is divided into two, one part for the filters and the other one for the table with the data. 

!['1'](https://github.com/DylanMontemayor/UFOs/blob/main/Resources/1.png)

### Enter the elements for the filters

In the "Filter Search" section, the user can enter up to five filters: date, city, state, country, and shape. There is a placeholder for each filter so the user has an example of how to add the data there. The code will detect the changes after pressing the enter key on the keyboard. 

!['2'](https://github.com/DylanMontemayor/UFOs/blob/main/Resources/2.png)

### Perform the search

After the user has pressed the enter key, the app will run a function within js that will save the elements added in the "Filter Search" section and will build a new table applying all the matches that it founds. As an example, the next image shows the data that is filtered after addind a state ("ca") and a shape ("light") filter. 

!['3'](https://github.com/DylanMontemayor/UFOs/blob/main/Resources/3.png)

## Summary

When having a big database, it always has filters that help you find the data you are looking for. One drawback of this program is that it will perform the search until you press the enter key and sometimes it is more user-friendly to have a button. So, two recommendations for improving this web page will be: adding a button, so the user knows what to do to kick off the search; adding comments next to the filter when the user enters data that doesn't match, so the user can know which field is causing no getting any data from the filters. 
