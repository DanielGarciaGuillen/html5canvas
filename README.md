# Project Title

This is a list where you can type and it will automically select items from the list that match the query. Based on the 30 days Javascript challenge.

## Getting Started

Type any query to start the search.

## Demo

## [Type Ahead List](https://danielgarciaguillen.github.io/typeahead/)
![Css Controler](/image/typeahead.jpg?raw=true "CssClock")


## Learnings

* How to fetch data with 
```
fetch(endpoint)
              .then(blob => blob.json())
              .then(data => cities.push(...data))
```

* Use regex to match city or state with 
```
    const regex = new RegExp (wordToMatch, 'gi');
    return place.city.match(regex) || place.state.match(regex)
```
* 

## Built With

* Vanilla Javascript
* Css
* Html