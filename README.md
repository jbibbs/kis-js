# Keep It Simple JS Library #

A Minimal, Modular Javascript library for Modern browsers.

Aims to be fast, small, and easily split into individual modules.

Browser support: IE8+, Latest versions of Firefox, Chrome, Safari, Opera

## Basic Use: ##

* Selector:
    var x = $(selector);

* Function:
    $_.module.function(params);

## Modules: ##

**Ajax**: simple, jQuery-like ajax functions

	functions:
		
		* Get: 
			Use:
			    $_.get(url, data_object, callback);
		
		* Post:
			Use:
			    $_.post(url, data_object, callback);
			
**QS**: querystring parsing and serialization for hashbang strings, and pushState urls
	
	functions:
		
		* Parse:
			Use:
			    $_.qs.parse(hb);
		
		* Set: This function will set the hash url if browser doesn't have history.pushState
			Use:
			    $_.qs.set(key, value);
		
		* Get: Retrieves the value of the key in the url string
			Use:
			    $_.qs.get(key);
			
			
				
	
	
	
