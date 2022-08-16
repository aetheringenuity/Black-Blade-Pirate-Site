# Black-Blade-Pirate-Site
Project website
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.parallax {
  background-image: url("https://media4.giphy.com/media/PR5vbMZ6zDaR9EugXY/giphy.gif?cid=ecf05e47s8h8pdkfq91l0fy34af6n89mk3zv3bwzmborzd9k&rid=giphy.gif&ct=g");
  min-height:1000px; 
  background-attachment: fixed;
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  border: 30px solid black
}
a {
    color: whitesmoke;
}
ul {
      padding: 10px;
      background: rgba(255, 235, 205, 0.438);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    
    * {
  border: 0;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
:root {
  font-size: calc(16px + (24 - 16)*(100vw - 320px)/(1920 - 320));

}
.search-bar input,
.search-btn, 
.search-btn:before, 
.search-btn:after {
  transition: all 0.25s ease-out;
}
.search-bar input,
.search-btn {
  width: 3em;
  height: 3em;
}
.search-bar input:invalid:not(:focus),
.search-btn {
  cursor: pointer;
}
.search-bar,
.search-bar input:focus,
.search-bar input:valid  {
  width: 100%;
}
.search-bar input:focus,
.search-bar input:not(:focus) + .search-btn:focus {
  outline: transparent;
}
.search-bar {
  margin: auto;
  padding: 1.5em;
  justify-content: center;
  max-width: 30em;
}
.search-bar input {
  background: transparent;
  border-radius: 1.5em;
  box-shadow: 0 0 0 0.4em #171717 inset;
  padding: 0.75em;
  transform: translate(0.5em,0.5em) scale(0.5);
  transform-origin: 100% 0;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}
.search-bar input::-webkit-search-decoration {
  -webkit-appearance: none;
}
.search-bar input:focus,
.search-bar input:valid {
  background: #fff;
  border-radius: 0.375em 0 0 0.375em;
  box-shadow: 0 0 0 0.1em #d9d9d9 inset;
  transform: scale(1);
}
.search-btn {
  background: #171717;
  border-radius: 0 0.75em 0.75em 0 / 0 1.5em 1.5em 0;
  padding: 0.75em;
  position: relative;
  transform: translate(0.25em,0.25em) rotate(45deg) scale(0.25,0.125);
  transform-origin: 0 50%;
}
.search-btn:before, 
.search-btn:after {
  content: "";
  display: block;
  opacity: 0;
  position: absolute;
}
.search-btn:before {
  border-radius: 50%;
  box-shadow: 0 0 0 0.2em #f1f1f1 inset;
  top: 0.75em;
  left: 0.75em;
  width: 1.2em;
  height: 1.2em;
}
.search-btn:after {
  background: #f1f1f1;
  border-radius: 0 0.25em 0.25em 0;
  top: 51%;
  left: 51%;
  width: 0.75em;
  height: 0.25em;
  transform: translate(0.2em,0) rotate(45deg);
  transform-origin: 0 50%;
}
.search-btn span {
  display: inline-block;
  overflow: hidden;
  width: 1px;
  height: 1px;
}

/* Active state */
.search-bar input:focus + .search-btn,
.search-bar input:valid + .search-btn {
  background: #2762f3;
  border-radius: 0 0.375em 0.375em 0;
  transform: scale(1);
}
.search-bar input:focus + .search-btn:before, 
.search-bar input:focus + .search-btn:after,
.search-bar input:valid + .search-btn:before, 
.search-bar input:valid + .search-btn:after {
  opacity: 1;
}
.search-bar input:focus + .search-btn:hover,
.search-bar input:valid + .search-btn:hover,
.search-bar input:valid:not(:focus) + .search-btn:focus {
  background: #0c48db;
}
.search-bar input:focus + .search-btn:active,
.search-bar input:valid + .search-btn:active {
  transform: translateY(1px);
}

  .search-bar input {
    box-shadow: 0 0 0 0.4em #f1f1f1 inset;
  }
  .search-bar input:focus,
  .search-bar input:valid {
    background: #3d3d3d;
    box-shadow: 0 0 0 0.1em #3d3d3d inset;
  }
  .search-btn {
    background: #f1f1f1;
  }
}
    
</style>
</head>
<body>

</form>
<div class="parallax"></div>

<div style="height:1000px;background-color:rgba(22, 48, 73, 0.932); text-align: center; font-size: larger; color:aliceblue; border: 30px solid black">
<h1>The Black Blade Pirates</h1>
<ul>
    <li><a href="#">The Crew Bios</a></li>
    <li><a href="#">The Siren's Song</a></li>
    <li><a href="#">The Players</a></li>
  </ul>
  
  <form action="" class="search-bar">
  
  
	<input type="search" name="search" pattern=".*\S.*" required>
	<button class="search-btn" type="submit">
		<span>Search</span>
	</button>

<h2>The Crew</h2>
<p>The crew of the Siren's Call, also known as the Black Blade Pirates, are led by six pirates who act as the leading officers of the ship. These six are Captain Maereck the Black Blade, 
    Shimmer of Oil Beneath the Water, Killick the Rogue Wizard, Leofwine Shadesbrother and his shadow snake, Granthem, Reika Seilman the Sea Touched, and Smoggy the Illbringer. The rest of 
    the crew consist of people they had been press ganged with and members of Scourge's crew he left for dead, that they saved, as well as any who wish to join them and, of course, the ship's cat.
</p>
<button>Join the Black Blades</button>
<h3>The Growing Legend</h3>
<p>Though our heros are still new to being and having their own crew, they have already come across and defeated many dangerous foes as well as willingly made much more dangerous ones. With 
    their infamy on the rise, will our heros become a power of good out on the seas or will they become the most cut throat evil to have ever passed over the oceans?
    </p>
    
   <iframe width="560" height="315" src="https://www.youtube.com/embed/tPLodwT58nE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>
<script>
    $("button").on("click", function() {
      alert("You have joined the Black Blade Pirate Crew!");
    });
  </script>
</body>
</html>
