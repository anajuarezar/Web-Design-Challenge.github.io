# Web-Design-Challenge.github.io

For this challenge, we had to replicate a series of web pages following photographs that were given. The information we had was from a previous assignment.

The website must consist of 7 pages total, including:

1.A landing page. 2.Four visualization pages. 3. A "Comparisons" page. 4. A "Data" page. 5. Media queries.

This landing page was made using Bootstrap to create a navbar. I copied the code, earased the collapse section, gave it the correct names and links and format it accordingly. For the body, I created a grid so we had two sections: one with the summary and another with the visualizations. The visualizations presented a problem because of the images. I tried to do it with the positions but, in the end, I chose to make a nested grid. This proved to be the better choice for the adjustment of the web's size.

For the visualization pages, I used the same code for the navbar and a very similar process to the landing page. I also used a nested grid. I used this process for the four other visualization pages.

The comparison page was more complicated. At first, like with the landing page, I tried to use positioning the images in both static and absolute positions, however I failed to make them adjust to the change in viewport. Finally, I decided to use a grid and give it an appropriate format. Additionally, I used the navbar code.

The "Data" page was difficult but once I realised my mistake, it was very easy. Since our data came in a csv file, I needed to convert it to html. I used pandas to do this. As proven by my folder, I went to jupyter notebook to convert it using the function "to_html" in this function I created a new html file. Later, I thought I had to import it but I realized that it was a code and I copied and pasted it in the html. To fully use it as a table, I used the TABLE code from Boostrap, adding the responsive element to convert the table into a responsive element. Once this was done, I gave it the format that was required.

Finally, the media queries. The pages had to be responsive accordingly to the size of the viewport. In order to do this, I used media queries. In this I specified the size of the viewport and the changes need. The once I made were about the navbar, to create a single button and eliminating the other links. Most of the things responded accordingly on their own except the comparison page, where I specified it to occupy totallity of the page.
