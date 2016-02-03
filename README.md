<div class="navbar navbar-custom navbar-fixed-top" role="navigation">
            <div class="container">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle navbar-center" data-toggle="collapse" data-target=".navbar-main-collapse">
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand page-scroll" href="#page-top">Mineblox</a>
                </div>
                <div class="collapse navbar-collapse navbar-main-collapse">
                    <ul class="nav navbar-right navbar-nav">
                        <li class="hidden">
                            <a href="#page-top"></a>
                        </li>
                        <li class="navbar-nav-li">
                            <a class="page-scroll" href="#about">About Us</a>
                        </li>
                        <li class="navbar-nav-li">
                            <a class="page-scroll" href="#team">Our Team</a>
                        </li>
                        <li class="navbar-nav-li">
                        	<a class="page-scroll" href="#voting">Vote Links</a>
                        </li>
                        <li class="navbar-nav-li">
                            <a class="page-scroll" href="#contact">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
		

.navbar-custom {
    margin-bottom: 0;
    border-bottom: 1px solid rgba(255,255,255,.3);
    text-transform: uppercase;
    font-family: 'minecraft';
    background-color: black;
	border: none;
}

.navbar-custom .navbar-brand {
  font-weight: 700;
}

.navbar-brand {
	
}

.navbar-brand:hover {
    color: lightgreen;
    -webkit-transition: all ease 0.3s;
    transition: all ease 0.3s;
}

.navbar-custom a {
    color: lightgreen;
}

.navbar-custom .nav li a {
    -webkit-transition: background .3s ease-in-out;
    -moz-transition: background .3s ease-in-out;
    transition: background .3s ease-in-out;
}

.navbar-custom .nav li a:hover {
    outline: 0;
    color: lightgreen;
    -webkit-transition: all ease 0.3s;
    transition: all ease 0.3s;
    border-bottom: solid;
    background-color: transparent;
}

.navbar-custom .nav li a:focus,
.navbar-custom .nav li a:active {
    outline: 0;
    background-color: transparent;
}

.navbar-custom .nav li.active {
    outline: 0;
}

.navbar-custom .nav li.active a {
    color: lightgreen;
    border-bottom: solid;
}

.navbar-custom .nav li.active a:hover {
    color: lightgreen;
    border-bottom: solid;
}

@media(min-width:768px) {
    .navbar-custom {
        padding: 15px 0;
        border-bottom: 0;
        letter-spacing: 1px;
        background: black;
        -webkit-transition: background .5s ease-in-out,padding .5s ease-in-out;
        -moz-transition: background .5s ease-in-out,padding .5s ease-in-out;
        transition: background .5s ease-in-out,padding .5s ease-in-out;
    }

.navbar-custom.top-nav-collapse {
    padding: 0;
    background: black;
    }
}
