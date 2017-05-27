# How to create a Singleton Class

```
var MyClass = (function(){

	var _instance;

	function MyClass(){
		if(!_instance)
			_instance = this;

		return _instance;
	}

	return MyClass;
})();
```