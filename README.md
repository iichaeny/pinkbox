<meta charset="utf-8">
<body>
	<div id="myRect" style="width: 100px;height: 100px;background: pink;
	transition: all 1s"></div>
	<input type="range" id="myPicker" min="100" max="600">
	<div id="rangeValue" > </div>	
	<script>
		myPicker.onchange = function()
		{  myRect.style.marginLeft = myPicker.value + "px";
    	rangeValue.innerHTML = myPicker.value; }
	</script>
</body>
