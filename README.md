### LINQ

| C# | JS | Scala | Example |
| --- | --- | -----  |
| Where | filter | filter | people.filter(function (item) { return item.age < 30; });|
| Select| map | map | people.map(function (item) { return item.name; });|
| All| every | forall | people.every(function (item) { return  item.age < 40; });|
| Any| some | exists | people.some(function (item) { return  item.age < 30; });|
| Aggregate| reduce | fold (or reduce) | people.reduce(function (item1, item2) {	return  { name: '', age: item1.age + item2.age }; });|
| OrderBy| sort | sortBy/sortWith | people.sort(function (a, b) { return  a.name > b.name ? 1 : 0; });|
| foreach| forEach | foreach or for comprehension | people.forEach(function(item) { console.log(item); });|


### jQuery AJAX

```
$.ajax(
	url: '/hello',
	method: 'POST' //'GET',
	complete:
	error:
	success:
).done.fail.always;
```
