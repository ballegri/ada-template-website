---
layout: default
---

# Why is it important ?

In recent years, the US movie industry has often been criticised in the media for its lack of female representation. As a simple and quick example: type 'most famous wizardess' in a Google research bar. Google automatically suggests 'most famous wizard' and not wizardess. By clicking on the first link provided (https://faceoffdb.com/lists/powerful-wizards-and-witches/), a ranking of the top 45 most famous widards/wizardesses is given with only **one** woman in the top 10. In the Wikipedia "Bechdel test" page (measure of the representation of women in film) (METTRe URL OU ON PEUT CLIQUER DESSUS????), the following graph was produced based on four different studies:

**METTRE IMAGE "WIKI_"**

This result clearly shows that the film industry is men dominated. But why is that such an issue one might ask (hopefully not...)? This lack of women representations has a large impact on our society, reinforcing the gender inequality of men doing great things (superhero, pilot, intelligent detective, scientist), and women being of secondary importance. As stated in (Bazzini et al., 1997): "Popular media images are reflections of a culture's attitudes, beliefs, and standards, as well as projections of desired realities [...] To the extent that consumers digest such material as truth, rather than fiction, the depictions laid forth by the media can be influential in the propagation and maintenance of stereotypes". In other words, what we see in movies is, to some extent, mirrored in real life.

Through this project, the gender inequalities will be assessed in a quantitative and qualitative way.



# General overview of the data
In order to have a better feel for the data we are using, let's explore by visualizing what we were given.

## Where does the data come from ? 
The data from which our analysis will be based consists of 42'306 movie plot summaries extracted from Wikipedia. In addition to that, some movie metadata was also extracted from Freebase such as country, language, genre, characters, information about the actors/actresses playing the characters, movie runtime and release date.

## Who produces the movies and what are the most recurrent genres ?

In the table below, the top 10 most producing countries and frequently represented genres are displayed. In all of the movie dataset, almost 50% of all films have been produced in the USA or India (out of 147 countries). The genres are more equally distributed.


<table>
<tr><th>Countries </th><th>Genres</th></tr>
<tr><td>

|       **Countries**      | **Total number of movies** | **Ratio** | **Cumulative sum** |
|:------------------------:|:--------------------------:|:---------:|:------------------:|
| United States of America |            34408           |   39.80   |        39.81       |
|           India          |            8411            |    9.73   |        49.54       |
|      United Kingdom      |            7868            |    9.10   |        58.64       |
|          France          |            4395            |    5.08   |        63.72       |
|           Italy          |            3163            |    3.66   |        67.38       |
|           Japan          |            2647            |    3.06   |        70.45       |
|          Canada          |            2534            |    2.93   |        73.38       |
|          Germany         |            2393            |    2.77   |        76.15       |
|         Argentina        |            1468            |    1.70   |        77.84       |
|         Hong Kong        |            1240            |    1.43   |        79.28       |

</td><td>
  
|    **Genre**    | **Total number of movies** | **Ratio** | **Cumulative sum** |
|:---------------:|:--------------------------:|:---------:|:------------------:|
|      Drama      |            34007           |   13.98   |        13.98       |
|      Comedy     |            16349           |    6.72   |        20.70       |
|   Romance Film  |            10234           |    4.21   |        24.90       |
| Black-and-white |            9094            |    3.74   |        28.64       |
|      Action     |            8798            |    3.62   |        32.25       |
|     Thriller    |            8744            |    3.59   |        35.85       |
|    Short Film   |            8141            |    3.35   |        39.19       |
|   World cinema  |            7155            |    2.94   |        42.13       |
|  Crime Fiction  |            6948            |    2.86   |        44.99       |
|      Indie      |            6897            |    2.83   |        47.82       |

</td></tr> </table>


## When where the movies released ? How much money did they generate ? How long are they?

**METTRE LES 3 HISTOGRAMMES** et les commenter

## ROMANA ET MATHIAS

# Getting into the heart of the matter

Now that we have a better overview of the data that was used, let's get into the actual analysis of the inequalities. Are these inequalities still present today? Have they evolved in time? For the better of for the worse? Theses questions will be answered by making a quantitative and qualitaitve analysis of women in the film industry.

## Quantitative analysis of women's underrepresentation in movies
In order to quantify the discrepancy between the number of men and women in movies, a 'Female share' index was created as:

$Female \quad share = \frac{Number \quad of \quad women}{Number \quad of \quad men \quad + \quad Number \quad of \quad women}$

If the value of the index is close to zero: the movie is men-dominated, close to one: female-dominated, close to 0.5: equal number of actors and actresses.

Using a ratio rather than absolute values makes the analysis robust to the increasing number of movies (hence yearly number of actors/actresses cast) these last decades. As it can be seen in the following plots:

number-FS_evolution.png

Although the number of movie produced has seen a great boost starting around the 1960's. the proportion of women compared to men does not seem to have know a significant increase on a global scale.

### Is the situation the same for every country ?
piechart of top 3 countries
hello
### And for every genre ? 

pie chart of top 3 genres


