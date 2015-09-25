### Paper typeahead

![out](https://cloud.githubusercontent.com/assets/883126/10092995/9a69aa06-6301-11e5-85d3-02ac8e537eeb.gif)

#### API

* data - **required** an array of your data
* input-label - **optional** the label for your input
* filter-fn - **optional** your filter by logic
```js
function(data, input) { return data; }
```

#### Events

* `on-item-selected`: e.details === item that was tapped

#### Todo

* [x] Add tab / enter result selection
* [ ] Add conditional empty list template
* [ ] Use iron-list to display results
* [ ] Add better style interface
* [ ] jsdoc all the methods
* [x] extract js to external file
* [ ] add tests
* [ ] Any other ideas welcome 🎷
