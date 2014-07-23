Treehouse-css
=============
/****************************
GENERAL
****************************/


#wrapper {
  max-width: 940px;
  margin: 0 auto;
  padding: 0 5%;
  
}

a {
  text-decoration: none;
 
}

img {
 max-width: 100%; 
}

/****************************
HEADING
****************************/
header {
  float: left;
  margin: 0 0 30px 0;
  padding: 5px 0 0 0;
  width: 100%;
}

#logo {
  text-align: center;
  margin: 0;
  }

h1 {
  font-family: 'Roboto', sans-serif;
  margin: 15px 0;
  font-size: 1.75em;
  font-weight: bold;
  line-height: 0.8em;
}

h2 {
  font-family: 'Oswald', sans-serif;
  font-size: 0.75em;
  font-weight: normal;
  margin: -5px 0 0;
}
  /****************************
NAVIGATION
****************************/
nav {
  text-align: center;
  padding: 10px 0;
  margin: 20px 0 0;
}

nav ul {
 list-style: none;
  margin: 0 10px;
  padding 0;
}

nav li {
 display:inline-block; 
}

nav a {
 font-weight: 800;
  padding: 15px 10px;
}

  /****************************
FOOTER
****************************/
footer {
  font-size: 0.75em;
  text-align: center;
  clear: both;
  padding-top: 50px;
  
    .social-icon {
    width: 20px;
    height: 20px;
    margin: 0 5px;
}

/****************************
PAGE: PORTFOLIO
****************************/
#gallery {
  margin: 0;
  padding: 0;
  list-style: none;
}


#gallery li {
  float: left;
  width: 45%;
  margin: 2.5%;
  background-color: #f5f5f5;
  color: #bdc3c7;
  
}
  
#gallery li a p {
   margin: 0;
   padding: 5%;
   font-size: 0.75em;
   color: #bdc3c7;
}




/****************************
COLORS
****************************/

/* site body */

body  {
  background-color: #fff;
  color: #999;
  
}

/* green header */

header {
 background: #6ab47b; 
 border-color: #599a68;
}

/* logo text */

h1, h2 {
 color: #fff; 
}


/* links */

a {
   color: #6ab47b;
}

/* nav background on mo devices */

nav {
 background: #599a68; 
}

/* nav link */

nav a, nav a:visited {
 color: #fff; 
}

/* selected nav link */

nav a.selected, nav a:hover {
 color: #32673f; 
}

