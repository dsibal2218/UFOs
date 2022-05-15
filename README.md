# UFOs
**Overview** Through out the module, we were able to create a webpage about UFO sightings with a basic date filter. For this challenge, we are to modify and enhanced that webpage by providing users a more in-depth analysis by allowing users to filter for multiple criteria at the same time. 

## Requirements

1. Using JavaScript and HTML, we’ll modify the code in our index.html file to create more table filters. In addition to the date filter we created in this module, we’ll add filters for the city, state, country, and shape.

2. Using JavaScript, we’ll replace the handleClick() function in our app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, we’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

## Results

1. The webpage now has filters for city, state, country and shape located on the left part of the page. 

<img width="468" alt="Screen Shot 2022-05-15 at 7 38 58 AM" src="https://user-images.githubusercontent.com/98235755/168470916-b7cd74b6-94bf-4514-9442-c67f128d2845.png">


2. A user can type in the appropriate field what they need to filter on (e.g. "us" in the "Enter a Country" field); press enter and the table will populate the results. The user can filter on multiple fields at a time to further narros the results. 


<img width="1204" alt="Screen Shot 2022-05-15 at 7 42 08 AM" src="https://user-images.githubusercontent.com/98235755/168470996-ef4a593f-413b-41d3-9c4e-388a5668ef11.png">



## Summary

1. Overall, the page is user-friendly and straightforward

2. To note, the filter is case sentive. The data fields are mostly in lower case. If the user filters dont return any result it would either be the case format is wrong or there really isnt a result for the requested filters. Additionally, the user will need to manually clear out the filters to reset it.These are some of he drawbacks of the webpage as it currently stands.

3. A few things that I would recommend to further enhance the webpage are:
      
      a. Make the filters not be case sensitive
      
      b. Make it so that the filter also has a dropdown where it would provide what the existing items are for each 
      field (e.g. Enter a State field would have a dropdown listing all the possible states existing in the dataset).
      
      c. Add a clear button so that filters are reset without having to manually delete the things user typed in each 
      field
