# Jquery
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js">
</script>
<script>
$(document).ready(function(){
   $("button").click(function(){
     $("p").toggle();
   }); 
});    
</script>    
</head>
<body>
    
<button> Toggle between hiding and showing the paragraphs </button>

<p> upar wale button par click kroge to</p>
<p> mai aur mera saathi gaayab hojayenge</p>

</body>
</html>
