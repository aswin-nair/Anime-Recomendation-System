# Anime-Recomendation-System

![](https://i.pinimg.com/originals/a8/be/b0/a8beb06c120be3358360ae2be20588fd.gif)
    
<h2 style='text-align:center;font-family:Comic Sans MS;font-size:30px;background-color:lightseagreen;border:30px;color:white'>table of contents<h2>

# Introduction

This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. The data was scraped thanks to [myanimelist.net](https://myanimelist.net) API.


# Data Id 📋

## Anime Dataset

This dataset is named **anime**. The dataset contains a set of **12,294 records** under **7 attributes**:

| Column Name | Description                                                    |
|-------------|----------------------------------------------------------------|
| `anime_id`  | myanimelist.net's unique id identifying an anime.              |
| `name`      | full name of anime.                                            |
| `genre`     | comma separated list of genres for this anime.                 |
| `type`      | movie, TV, OVA, etc.                                           |
| `episodes`  | how many episodes in this show. (1 if movie).                  |
| `rating`    |  average rating out of 10 for this anime.                      |
| `members`   | number of community members that are in this anime's "group".  |
                                                


## Rating Dataset

This dataset is named **rating**. The dataset contains a set of **7,813,737 records** under **3 attributes**:

| Column Name | Description                                                                        |
|-------------|------------------------------------------------------------------------------------|
| `user_id`   | non identifiable randomly generated user id.                                       |
| `anime_id`  | the anime that this user has rated.                                                |
| `rating`    | rating out of 10 this user has assigned (-1 if the user watched without assigning) |


### Aim of the Notebook:
Building a better anime recommendation system based only on similiar anime. 

                                                
