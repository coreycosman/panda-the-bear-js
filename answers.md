1)
<!-- Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead. -->
document.body
<body data-gr-c-s-loaded=​"true">​…​</body>​
var profileImage = document.querySelector(".profile-image")
undefined
profileImage.src
"http://bitmakerlabs.github.io/panda-the-bear-js/images/self-portrait-grassbg.jpg"
profileImage.src = "https://placebear.com/400/400"
"https://placebear.com/400/400"

1)
<!-- Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing. -->
var skyImage = document.querySelector(".portfolio-image")
undefined
skyImage
<div class=​"portfolio-image" id=​"left-image">​<img src=​"images/​clouds-man.jpg" alt=​"Man Walking on Ice" title=​"Man Walking on Ice">​<div class=​"portfolio-image-description">​…​</div>​</div>​

skyImage
<div class=​"portfolio-image" id=​"left-image">​…​</div>​
var skyPic = skyImage.querySelector("img")
undefined
skyPic
<img src=​"images/​clouds-man.jpg" alt=​"Man Walking on Ice" title=​"Man Walking on Ice">​
skyPic.src
"http://bitmakerlabs.github.io/panda-the-bear-js/images/clouds-man.jpg"
skyPic.src = "https://placebear.com/325/225"
"https://placebear.com/325/225"
2)
<!-- Select the heading that says "Panda the Bear" and change it to your own name. -->

document
a = document.body
<body data-gr-c-s-loaded=​"true">​…​</body>​
a
<body data-gr-c-s-loaded=​"true">​…​</body>​
var mainTitle = a.querySelector("section .highlight")
undefined
mainTitle
<h1 class=​"highlight">​Panda The Bear​</h1>​
mainTitle.innerText = "Hello"
"Hello"

3)
<!-- Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector) -->
var x = a.querySelector("#employment .info-title")
undefined
x
<h3 class=​"info-title">​<i class=​"icon-suitcase">​::before​</i>​" &nbsp; Employment"</h3>​
x.innerText
"   Employment"
x.innerText = "hello"
"hello"
4)
<!-- Change the colour of the body. -->
a = document.body
<body data-gr-c-s-loaded=​"true">​…​</body>​
a.style.backgroundColor = "yellow"
"yellow"


5)
<!-- Change the colour of each element using the highlight class. Use a for loop to do this. -->
elements = document.body.getElementsByClassName("highlight")
for (var i = 0; i < elements.length; i++) {
    elements[i].style.backgroundColor="blue"}
"blue"
for (var i = 0; i < elements.length; i++) {
    elements[i].style.backgroundColor="green"}
"green"

6)
<!-- Change the font family of the h1 to 'monospace'. -->

a = document.body.querySelector("h1")
a.style.fontFamily="monospace"

7)
<!-- Find a way to select the round icons in the sidebar and then change their colour. -->
document.body.querySelector(".action-icon-bg").style.background="yellow"
"yellow"


8)
<!-- Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself". -->

document.body.querySelector("form #name").placeholder = "hello"
"hello"


9)

<!-- Change the placeholder attribute of the message field to "state your business". -->
document.body.querySelector("form #message").placeholder = "hello"
"hello"
10)
<!-- Give the name field a "value" attribute of "your nemesis". -->

document.body.querySelector("form #name").value = "hello"
"hello"
11)
<!--
Change the value attribute of the email field to "koalathebear@gmail.com". -->

document.body.querySelector("form #email").value = "hello"
"hello"

12)
<!-- Change the value of the submit button on the contact form to "En garde!". -->
document.body.querySelector("form #submit").value = "hello"
"hello"


13)
<!-- We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute). -->

document.body.querySelector("form #submit").disabled = true
true
14)
<!--
We should help Panda protect their privacy by erasing their personal details from the sidebar. -->

document.body.querySelector("aside ul .bio-info-name").hidden = true
true
document.body.querySelector("aside ul .bio-info-location").hidden = true
true
document.body.querySelector("aside ul .bio-info-phone").hidden = true
true
