##controller.js
```javascript
function AppCtrl($scope){
	$scope.greeting = {text: 'hello'};
	}
```

>$scope.greeting

This 'greeting' which is a scope object is now eligible for using in view. "$scope" which maintains relation between controller(controller.js) and view(index.html).As "greeting" is an object with one single property "text", so index.html just view it using {{greeting.text}}. 


##index.html
```html
<p> {{greeting.html}},word </p>
```
So, {{greeting.text}} will be treat like html element in index.html and can be replace by any value from controller.js
