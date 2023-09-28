<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>forher</title>
</head>
<body>
<h1 id="resultText"></h1>
<script>
let response = prompt("I miss you, do you miss me too? Type Yes or No");
let outputText = "";


if (response=="Yes"){
outputText = "I love you, baby! Thank you for understanding my busy days";

}else if(response=="No"){
outputText = "Ouch, iiyak na ako kasi di mo ako miss";
}else{
outputText = "Please type Yes or No!!";
}


document.getElementbyId("resultText").innerHTML = outputText;
</script>
</body>
</html
