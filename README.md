# Mr.HTML
HTML tools and conversion websites for reference 

</BR>

## TEXT TO HTML converter :  
https://www.textfixer.com/

</BR>

## Excel Cells to HTML tabl converter : 
https://tableconvert.com/excel-to-html

</BR>

## HTML pretty print : 
https://jsonformatter.org/html-pretty-print

</BR>

## Color picker : 
https://htmlcolors.com/google-color-picker

https://www.w3schools.com/colors/colors_picker.asp

</BR>

## CSS Generators : 

https://webcode.tools/css-generator

https://css-generator.netlify.app/

https://html-css-js.com/css/generator/

https://cssgenerator.org/

https://workik.com/css-code-generator

https://css3generator.com/

https://www.toptal.com/developers/css3maker

https://cssgradient.io/

https://layout.bradwoods.io/

https://www.mymap.ai/css-generator

</BR>
</BR>
</BR>

## Template panel  

### Green <<<<<

```html

<body bgcolor="black">
<p style="color:#11ff00">

</p>
</body>

```

</BR>

### NSA Blue # 1

```html

<body bgcolor="black">
<p style="color:#00d4f0">

</p>
</body>

```

</BR>

### NSA Blue # 2 <<<<<

```html

<body bgcolor="black">
<p style="color:#02e1f5">

</p>
</body>

```

</BR>

### Yellow-Green # 1 

```html

<body bgcolor="black">
<p style="color:#a7f542">

</p>
</body>

```

</BR>

### Yellow-Green # 2 <<<<<

```html

<body bgcolor="black">
<p style="color:#ADFC03">

</p>
</body>

```

</BR>

### Yellow <<<<<

```html

<body bgcolor="black">
<p style="color:yellow">

</p>
</body>

```

</BR>
</BR>


### Table for list of items with dark background <<<<<

```html

<html>
	<head>
		<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  color: #02e1f5;
  padding: 8px;
}


}
</style>
	</head>
	<p style="color:#02e1f5">
		<body bgcolor="black">

<!--Put your table items here-->

		</p>
	</body>
</HTML>

```


</BR>
</BR>

### Split screen <<<<<

```html

<html>
	<head>
		<title>sample data split screen</title>
		<style>
body {
  font-family: Arial;
  /* color: white; */
  color: white; 
}


.split {
  height: 100%;
  /* width: 50%; */
  position: fixed;
  z-index: 1;
  top: 0;
  overflow-x: hidden;
  padding-top: 20px;
}

.left {
  left: 0;
  /* background-color: #111; */
  background-color: #111;
  zoom: 90%;
  width: 15%;
}

.right {
  right: 0;
  /* background-color: red; */
  background-color: #2429d; /*github background */
  zoom: 90%;
  width: 85%;
}

td {

text-align : left;
}


.centered {
  position: absolute;
  top: 50%;
  left: 50%;

  transform: translate(-50%, -50%);
  text-align: center;
}

.centered img {
  width: 150px;
  border-radius: 50%;
}



  a {
    text-decoration: none; /* Remove underline from all links by default */
  }

  a:link {
    color: #ADFC03; /* Style for unvisited links */
  }

  a:visited {
    color: yellow; /* Style for visited links */
  }

  a:hover {
    color: #FFFFFF; /* Style for links when moused over */
    text-decoration: underline; /* Add underline on hover */
	/* background-color: red; */
  }

  a:active {
    color: orange; /* Style for links when clicked (actively selected) */
  }
 
</style>
	</head>
	
	<body>
		<div>
			<div class="split left">
				<!--<div class="centered">-->
				<body bgcolor="black">
			<p style="color:#ADFC03"></p>
			<center>
					SAMPLE LEFT
			</center>
		</div>
		
		
		<div class="split right">
			<center>
					SAMPLE RIGHT 
            </center>
        </div>
    </body>

</html>

```

</BR>
</BR>

### Multiple search of the clicking link <<<<< with search id text 

```
<html>
	<head>
		<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  color: #02e1f5;
  padding: 8px;
}

a:link {
  color:#ADFC03;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color:#ADFC03;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}

}
</style>

<script type="text/javascript">

var el = document.getElementById('myLink');
el.onclick = showFoo;

function showFoo(myMessage) {
  //alert('I am foo!' + " " + myMessage);
  //return false;
  
  const urlsToOpen = [
    'https://www.google.com/search?q=' + myMessage + '+game',
    'https://www.google.com/search?q=' + myMessage + '+game+reviews' ,
    'https://www.google.com/search?q=' + myMessage + '+gameplay',
	"https://www.google.com/search?q=" + myMessage + "+gameplay+videos",
	"https://www.google.com/search?q=" + myMessage + "+gameplay+trailers" 
];
  
       for (let i = 0; i < urlsToOpen.length; i++) {
        // The second argument, a unique name, is important for opening in new tabs
        // otherwise, subsequent calls might overwrite the first tab.
        window.open(urlsToOpen[i], "_blank"); 
    } 
  	

}

</script>

	</head>
	<p style="color:#02e1f5">
		<body bgcolor="black">

<!--Put your table items here-->

<a id="myLink" href="#" onclick="showFoo('God of war ragnarok');">link text</a>


		</p>
	</body>
</HTML>

```

</BR>
</BR>

<!-- 

</BR>

</BR>
</BR>


```diff
+ this text is highlighted in green
- this text is highlighted in red
```

-->

## 

</br></br>

<p align="center"> 
<a href="https://github.com/Octavius-Dante/Mr.Index"> >> Go To INDEX << </a> 
</p>

##

</br></br></br>
