<html>
  <head>
<style>
  
.button {
    background-color: #00ff00; /* Green */
    border: 0px;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.raju {border-radius: 8px;}
div.scrollmenu {
    background-color: #0000ff;
    overflow:auto;
    white-space: nowrap;
}

div.scrollmenu a {
    display: inline-block;
    color: yellow;
    text-align: center;
    padding: 1px;
    text-decoration: none;
	font-size:23px;
}

div.scrollmenu a:hover {
    background-color: #ff0000;
}
</style>
  </head>
  <body>

	<h2><div class="scrollmenu">
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'raju')"><h2>RAJU KUMAR</h2></a></button>
		<button><a href="javascript:void(0)" class="button raju" onclick="openCity(event, 'girja')"><h2>GIRJA PARSAD</h2></a></button>







	  </div></h2>
	<div id="raju" class="tabcontent">
	  <span onclick="this.parentElement.style.display='none'" class="topleft"><img src="http://www.pd4pic.com/images/stop-icon-theme-action-delete-cancel.png" style="hight: 33px; width: 33px;"></span>
	  <center><h3>raju</h3></center>
	  <div class="scrollmenu"><p><img src="http://cdn.arstechnica.net/wp-content/uploads/2016/02/5718897981_10faa45ac3_b-640x624.jpg"><img src="http://pngimg.com/upload/rose_PNG637.png"style=" width: 670px;"></p></div>
	</div>

	<div id="girja" class="tabcontent">
	  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
	  <h3>girja</h3>
	  <p>Tokyo is the caiyd7didkydkgfh!fmg
		djxgmdykfiyctidteudtu yxmgfiycfhckyfkh
		cykykchkchkckvykchkcykcklhvypital of J
		apan.</p>
	</div>

<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>

  </body>
</html>
