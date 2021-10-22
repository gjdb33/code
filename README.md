# Coding 

-This page is used to present to you an example code I have created during this semester. This code is a FizzBuzz, which is often times used during interview processes for jobs/internships in the programming field. 

-The FizzBuzz program is to output numbers from 1 to 100. If the number is divisible by 3, replace it with “Fizz”. If it is divisible by 5, replace it with “Buzz”. If it is divisible by 3 and 5 replace it with “FizzBuzz”.

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	var result = '';
	for (i = 1; i < 101; i++) {

   	 if (i % 3 === 0 && i % 5 === 0) {
	 result = "FizzBuzz";

    	} else if (i % 5 === 0) {
	  result = "buzz";

    	} else if (i % 3 === 0) {

    	  result = "Fizz";

    	} else {
     	  result = i;
   	 }
	displayHTML += "<p>" + result + "</p>"
	display.innerHTML = displayHTML
	}
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">
  
</div>
  
</body>
</html>
```

-Link to the [README page](https://github.com/gjdb33/midterm_project.git)
