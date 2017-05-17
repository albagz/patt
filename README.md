# My Pattern Library

*My description*



## Table of Contents

  1. [Navigation bar](#navigation-bar)
  1. [Header element](#header-element)
  1. [Buttons](#buttons)
     * [Button one](#button-one)
     * [Button two](#button-two)
     * [Button three](#button-three)
     * [Button four](#button-four)
     * [Button five](#button-five)
     * [Button six](#button-six)
  1. [Jumbotron](#jumbotron)
  1. [Footer](#footer)
  1. [Login screen](#other-component)


## Navigation bar

![Alt text](https://cloud.githubusercontent.com/assets/25457208/26154388/29e649e4-3b07-11e7-9dc8-01e2d17e1458.png)

Usually created to guide the user around the website with ease. 

	<div>
	<html>
	<head>
		<title>Pattern Library</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<link rel="stylesheet" href="patt.css" />
	</head>
	<body class="subpage">
	<header id="header">
				<div class="inner">
					<a href="index.html" class="logo">Pattern Library</a>
					<nav id="nav">
						<a href="">Home</a>
						<a href="">One</a>
						<a href="">Two</a>
						<a href="">Three</a>
					</nav>
					<a href="#navPanel" class="navPanelToggle"><span class="fa fa-bars"></span></a>
				</div>
	</header>
	</body>
	</html>
	</div>
<br />
  


**[⬆ back to top](#table-of-contents)**

## Header Element
![header2](https://cloud.githubusercontent.com/assets/25457208/26155023/b0a85fa6-3b09-11e7-9642-b7a90912bfef.png)


This is usually below the navigation, and includes pre-information of the webiste or sometimes pictures. Helps grab the users attention. 

	<div>
   	<section>
  	<span>Header!</span>
	</section>
	
	section {
 	 height: 100vh;
 	 background: #F0544F;
	}
	</div>
<br />


**[⬆ back to top](#table-of-contents)**

## Buttons

Buttons are useful for the user to understand what may be imnportant or a link. Having different colour buttons and hover colours can ensure that the user will psychologically know the difference.

### Important Button
![button 1](https://cloud.githubusercontent.com/assets/25457208/26155227/672f6706-3b0a-11e7-9c02-619cf04cddb4.png)

This is described as the important colour because of its size and its colour is akin to the whole scheme of the wesbite. 

	
	<div>
 	<h3>Buttons</h3>
		<ul class="actions">
		<li><a href="#" class="button special">Important</a></li>
	</ul>
								
	</div>
<br />


### Link/Page Button
![button 2](https://cloud.githubusercontent.com/assets/25457208/26155641/cd123804-3b0b-11e7-92c3-55f4658e5b1d.png)

This is described as a normal button and can be seen around the website when accessing certain areas such as the next page or a link.

	<div>
    	<ul class="actions">							
	<li><a href="#" class="button">Normal</a></li>
	</ul>
	</div>
<br />



### Email Button
![button 3](https://cloud.githubusercontent.com/assets/25457208/26155651/d4de7c64-3b0b-11e7-91bd-16c7123bd870.png)

This button will be used when creating a form such as sending an email or accepting terms and conditions. Keeping it simple and as it says hidden.

	<div>
 	<ul class="actions">
	<li><a href="#" class="button alt">Hidden</a></li>
	</ul>
	</div>
<br />

  

### Attention button
![button 4](https://cloud.githubusercontent.com/assets/25457208/26155654/d9a0c7fc-3b0b-11e7-8733-f38726756edb.png)


This is the big button used to grab the audiences attention.


	<div>
    	<ul class="actions">
	<li><a href="#" class="button special big">Big</a></li>
	</ul>
	</div>
<br />

  
### Item select button
![button 5](https://cloud.githubusercontent.com/assets/25457208/26155661/e00376c6-3b0b-11e7-82d1-fd5fca2f2e85.png)

Used when users are selecting items.

	
	<div>
    	<ul class="actions">
	<li><a href="#" class="button">Medium</a></li>
	</ul>
	</div>
<br />



### Login Button
![button 6](https://cloud.githubusercontent.com/assets/25457208/26155672/e588a22e-3b0b-11e7-966a-505601bb4fd8.png)

Another example of keeping it simple and effective by having a small button to do commamnds for the user such as login and sign up. 

	
	<div>
    	<ul class="actions">
	<li><a href="#" class="button alt small">Small</a></li>
	</ul>
	</div>
<br />

 
  
**[⬆ back to top](#table-of-contents)**




## Jumbotron
![jumbo](https://cloud.githubusercontent.com/assets/25457208/26156471/6189973c-3b0e-11e7-8b68-8a72c1e1a0f6.png)

A jumbotron is described as a large grey box with rounded corners. It helps relay important information to the audience by using the large grey box.

	<div>
    	 <div class="container">
     	 <div class="jumbotron">
        <h1>Jumbotron</h1>
        <p>This is a Jumbotron.</p>
        <p><a class="btn btn-primary btn-large">Learn more</a></p>
      </div>
	</div>
<br />

  
**[⬆ back to top](#table-of-contents)**

## Footer
![footer](https://cloud.githubusercontent.com/assets/25457208/26158507/fa18c7b6-3b13-11e7-90a7-1655ddcbd1c8.png)


The footer will house the scoail side of the website, with links to facebook, instagram and twitter. These will help boost the appearance of the website. 

	<div class="socialbar">
  	<div class="container">
    	<h3>Find us</h3>
    <br><BR>
    <div><a href="https://twitter.com/madasudesign"><img title="Twitter" src="https://cdn4.iconfinder.com/data/icons/miu-flat-social/60/twitter-48.png" alt="Twitter" width="35" height="35" /></a> <a href="https://www.facebook.com/madasudesign"><img title="Facebook" src="https://cdn4.iconfinder.com/data/icons/miu-flat-social/60/facebook-48.png" alt="Facebook" width="35" height="35" /></a> <a href="mailto: dainpenman@gmail.com"><img title="Email" src="https://cdn4.iconfinder.com/data/icons/miu-flat-social/60/mail-48.png" alt="Email" width="35" height="35" /></a>
      <a href="www.instagram.com/madasudesign"><img title="Instagram" src="https://cdn3.iconfinder.com/data/icons/social-circle/512/social_6-48.png" alt="Instagram" width="35" height="35" /></a></div>
         
 
  	</div>
  	</div>

<br />

    
  
**[⬆ back to top](#table-of-contents)**

## Login screen

This is a standard login screen, that pops up when clicking on the initial login button.

	<h4>Login</h4>
        <form>
          <input type="text" name="username" class="username form-control" placeholder="Username"/>
          <input type="password" name="password" class="password form-control" placeholder="password"/>
          <input class="btn login" type="submit" value="Login" />
        </form>
<br />


  
**[⬆ back to top](#table-of-contents)**
