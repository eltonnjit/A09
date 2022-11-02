<!DOCTYPE html>
<html>
	<head>
    <meta charset="utf-8">
    <title> San Joaquin Valley Town Hall </title>
  </head>
    <body>
      <header>
		<img src="images/town_hall_logo.gif" alt="Town Hall logo" width="80">
        <h2> San Joaquin Valley Town Hall</h2>
        <h3> Celebrating our 75<sup>th</sup>year</h3>
        <h2> Our Mission</h2>
        <p> San Joaquin Valley Town Hall is a non-profit organization that is run by an all-volunteer board of directors. 
         Our mission is to bring nationally and internationally renowned, thought-provoking speakers who inform, educate, and entertain our audience!
         As one or our members told us:<br>
          &quot; Each year I give a ticket package to each of our family members. I think of it as the gift of knowledge...and that is priceless.&quot;</p>
        <h2> Our Ticket Package</h2>
        <ul>
          <li>Season Package: $95</li>
			    <li>Patron Package: $200</li>
			    <li>Single Speaker: $25</li>
        </ul>
        <h1> This season's guest speakers </h1>
        <h3>
          October <br> <a href="speakers/brancaccio.html"> David Brancaccio </a>
            <br> 
             <img src="img/brancaccio75.jpg" height="100" width="100" alt="David Brancaccio October Speaker">
          November <br> <a href="speakers/sorkin.html"> Andrew Ross Sorkin </a>
             <br>
              <img src="img/sorkin75.jpg" height="100" width="100" alt="Andrew Ross Sorkin November Speaker">
          January <br> <a href="speakers/chua.html"> Amy Chua </a>
          <br>
          <img src="img/chua75.jpg" height="100" width="100" alt="Amy Chua January Speaker">
        </h3>
        <footer>
          <p>
            &copy; Elton Haskaj, NJIT, NJ, 2022
          </p>
        </footer>
        </body>
	    </html>
	
	/* the styles for the elements */
* {
	margin: 0;
	padding: 0;
}
html {
	background-color: white;
}
body {
	font-family: Arial, Helvetica, sans-serif;
    font-size: 100%;
    width: 800px;
    margin: 0 auto;
    border: 3px solid #931420;
    background-color: #fffded;
}
a:focus, a:hover {
	font-style: italic;
}
/* the styles for the header */
header {
	padding: 1.5em 0 2em 0;
	border-bottom: 3px solid #931420;
		background-image: -moz-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -webkit-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: -o-linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
	background-image: linear-gradient(
	    30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
}
header h2 {
	font-size: 175%;
	color: #800000;
}
header h3 {
	font-size: 130%;
	font-style: italic;
}
header img {
	float: left;
	padding: 0 30px;
}
.shadow {
	text-shadow: 2px 2px 2px #800000;
}
/* the styles for the main content */
main {
	clear: left;
}

/* the styles for the section */
section {
	width: 525px;
	float: right;
	padding: 0 20px 20px 20px;
}
section h1 {
	color: #800000;
	font-size: 150%;
	padding-top: .5em;
	margin: 0;
}
section p {
	padding-bottom: .5em;
}
section blockquote {
	padding: 0 2em;
	font-style: italic;
}
section ul {
	padding: 0 0 .25em 1.25em;
}
section li {
	padding-bottom: .35em;
}

/* the styles for the article */
article {
	padding: .5em 0;
}
article h2 {
	font-size: 115%;
	padding: 0 0 .25em 0;
}
article img {
	float: right;
	margin: .5em 0 1em 1em;
	border: 1px solid black;
}

/* the styles for the aside */
aside {
	width: 215px;
	float: right;
	padding: 0 0 20px 20px;
}
aside h2 {
	color: #800000;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}

aside h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
aside img {
	padding-bottom: 1em;
}

/* the styles for the footer */
footer {
	background-color: #931420;
	clear: both;

}
footer p {
	text-align: center;
	color: white;
	padding: 1em 0;
}
   
