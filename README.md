# UFO_challenge

#### Project Overview 

In this project, we are focus on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.
In order to perform their analysis, we will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

#### Results 

This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.

<img width="1429" alt="Screen Shot 2022-03-28 at 12 24 04 PM" src="https://user-images.githubusercontent.com/95304774/160443457-a3a3ff49-2083-48c1-9dd9-bed93e08d012.png">

###### Filtering by event date
The user enters the desired date, the change is detected and the table is updated accordingly.

<img width="1429" alt="Screen Shot 2022-03-28 at 12 25 01 PM" src="https://user-images.githubusercontent.com/95304774/160443637-2f9d7d88-59b6-4b0f-88e7-a4763d95d2a0.png">

###### Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.

<img width="1429" alt="Screen Shot 2022-03-28 at 12 26 57 PM" src="https://user-images.githubusercontent.com/95304774/160443979-e23dc9cd-fd31-43ad-a909-785b2a91fc15.png">

###### Filtering by state and shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.

<img width="1429" alt="Screen Shot 2022-03-28 at 12 30 18 PM" src="https://user-images.githubusercontent.com/95304774/160444550-952e97aa-1440-4c34-b93a-2ea8b37c5ed6.png">

###### Filtering by country
The user enters the desired country, the change is detected and the table is updated accordingly.

<img width="1429" alt="Screen Shot 2022-03-28 at 12 31 42 PM" src="https://user-images.githubusercontent.com/95304774/160444762-1c687056-337f-4fb8-8bbf-ec68a1e25e88.png">

All filter parameters can be entered simultaneously.

#### Summary:

Drawbacks: 

* One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis. The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly.

Recommendations:

* A way to address this would be to present drop-down lists including all filter values in place of the input fields.
Each list would need to update after a parameter is selected in any filter.

* Remove case-sensitivity in all the textbox search fields.

* Including a button to clear the filters is also needed. The button would be located below the last filter.




