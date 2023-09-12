<!DOCTYPE html.
<body>
<html>


<h2>Javascript</h2>
<p>Let,s learn Some of the basic javascript</p>

<script> 
   
   function oldMathAdd() {
       return console.log(10 + 20);	   
    }
	oldMathAdd();
	
	 function oldMathAddParams(a,b) {
       return console.log(a + b);	   
    }
	oldMathAddParams(100,200);
	
	let saveValue = function (a,b) {
	   return console.log(a - b);
	}
	saveValue(50, 70);
	
	setTimeout (function () {
	   console.log("hello");
	},5000);

</script>

</body>
</html>

<!DOCTYPE html.
<body>
<html>


<h2>Javascript</h2>
<p>Let,s learn Some of the basic javascript</p>

<script>

let userDetails = {
   
   firstName: "Manju",
   lastName: "kaushik",
   invokeName (a,b) {
         console.log('This is, firstName: ${this.firstName} and lastName: ${this.lastName}');
		 console.log(a+b);
		 
	}
};

setTimeout ( function() {
         userDetails.invokeName (12, 13);
}, 3000);
	
</script>

</body>
</html>
