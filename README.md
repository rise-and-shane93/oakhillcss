# oakhillcss
h1 {
  color: green;
}
p {
	font-family: 'Lato' , sans-serif;
}
footer p {
	color: #ffe4c4;
}
.nav-link:hover {
  color: green !important;
  text-decoration: underline;
  text-decoration-color: green;
}
.underline-on-hover:hover {
	text-decoration: underline;
	text-decoration-color: green;
	color: green;
}
/*Find a different inactive color for links.*/
/*See if you can add a smooth scale transition,
as if the element is growing. Also, make sure
this effect does NOT apply to the active page.*/
footer {
  background-image: url("http://www.wildtextures.com/wp-content/uploads/2011/11/wildtextures-dark-wood-board.jpg");
}
address {
	color: #ffe4c4 !important;
}
footer h2 {
	text-align: center;
	color: #ffe4c4;
}
.small-image {
	width: 100px;
}
.medium-image {
	width: 350px;
	display: block;
    margin-left: auto;
    margin-right: auto;
}
.logo-image {
	display: block;
    margin-left: auto;
    margin-right: auto;
	width: 300px;
}
.main-image {
	display: block;
    margin-left: auto;
    margin-right: auto;
	padding: 10px;
}
#Header h1 {
	text-align: center;
}
.navbar {
	border-bottom: 1px solid black;
}
.navbar-nav {
    float:none;
    margin:0 auto;
    display: block;
    text-align: center;
}
.navbar-nav li {
    display: inline-block;
    float: none;
	border-right: 1px solid black;
	font-family: 'Work Sans', sans-serif;
	font-size: 14px;
}
.navbar-nav a {
	transition: transform .3s !important;
	backface-visibility: hidden;
	color: black !important;
}
.navbar-nav li:last-child {
	border: none;
}
.dropdown-menu li {
	border: none;
}
.dropdown-menu a {
	display: block;
}
/* See if you can target all but the last nav-link with the class above and below. */
.navbar-nav a:hover {
    color: #228B22;
	text-decoration: none;
	transform: scale(1.1)!important;
}
.navbar-nav i:hover {
	background-color: green !important;
	border-width: 0 2px 2px 0;
	transform: scale(1.2)!important;
}
/* See what you can do to edit the color upon hover i class. */
.active {
	color: black;
	text-decoration: underline;
	text-decoration-color: black;
}
#Header p {
	text-align: right;
}
#main-body {
	margin: 2%;
}
/*Ask if it's better to use percentage or pixel values for margin & padding.*/
a.fa {
  font-size: 15px;
  width: 30px;
  height: 30px;
  text-align: center;
  margin: 3px 2px;
  padding-top: 6px;
  transition: transform .2s !important;
  backface-visibility: hidden;
  align: right;
  border: 2px solid #228B22;
  border-radius: 50%;
}
a.fa:hover {
    opacity: 0.7;
    text-decoration: none;
    color: #d0d0d0;
	transform: scale(1.2) !important;
	/* animation: sweep 1s forwards; */
}
.fa-facebook {
  background: white;
  color: #228B22;
  border-radius: 50%
  border-color: #228B22;
}
.fa-envelope-o {
  background: white;
  color: #228B22;
  border-radius: 50%
  border-color: #228B22;
}
.text-center {
	text-align: center;
}
input {
	width: 100%;
	margin: auto;
	margin: 1%;
	padding: 1%;
}
.margin-bottom {
	margin-bottom: 10px;
}
.email-link {
	color: #ffe4c4;
}
.email-link:hover {
	text-decoration: underline;
	text-decoration-color: #ffe4c4;
	color: #ffe4c4;
}
/*.navbar {
	border: 1px solid black !important;
} */
.navbar i {
    border: solid black;
    border-width: 0 2px 2px 0;
    display: inline-block !important;
    padding: 3px;
	transition: transform .2s !important;
	backface-visibility: hidden;
}
.down {
    transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
}
