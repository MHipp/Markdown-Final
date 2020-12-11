[Main Page](README.md) 
### Code
Here is my adaptation of the FizzBuzz assignment

	function fizzbuzz() {
		var display = document.getElementById('display');
		var displayHTML = "";
		for (i = 1; i <= 100; i++) {
			if(i%3 == 0 && i%5 == 0){
			    displayHTML += "<p>" + "FizzBuzz" + "</p>";
			}
		else if(i%3 == 0){
			    displayHTML += "<p>" + "Fizz" + "</p>";
			}
			else if(i%5 == 0){
			    displayHTML += "<p>" + "Buzz" + "</p>";
			}
			else{
			    displayHTML += "<p>" + i + "</p>";
			}
		}
		display.innerHTML = displayHTML
	}


