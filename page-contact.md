--- 
title: Contact
subtitle: We would love to hear from you!
layout: page
show_sidebar: false
#tabs: example_tabs
#hero_image: assets/ext_images/Home_logo.png
---

## <span style="color:#004777"> Contact us at openmrbenelux@gmail.com </span>
<p><div style="text-align: justify">Questions or feedback? Do not hesitate and use the <i>Contact Form</i> to send us an e-mail at openmrbenelux@gmail.com. We will answer you as soon as possible, to the best of our abilities! 
You are also welcome to subscribe to our <i>Newsletter</i> to receive the latest updates regarding the program and more. You will also be among the first to know when registration opens!</div></p>
<p><div style="text-align: justify"><b>IMPORTANT</b>: Please disable AdBlock or Privacy Badger when submitting the <i>Contact Form</i> or subscribing to the <i>Newsletter</i>! If you don't, we won't receive your request.</div></p>
<br>

<!-- ### <span style="color:#004777"> Contact Form </span> -->

<html>

<head>
    <script type="text/JavaScript">
        function showMessage(){
            //window.alert("Done"); 
            //$("#contact-form")[0].reset();
            // var message = document.getElementById("message").value; 
            // display_message.innerHTML= message; 
        }
    </script>

    <style>
    <!-- body {font-family: Arial, Helvetica, sans-serif;} -->

    form {
      display: block;
      width: 50%;
      float: left;
      padding-right: 4%;
      <!-- border: 3px solid #f1f1f1; -->
      <!-- font-family: Arial; -->
    }

    .container {
      padding: 20px;
      <!-- background-color: #f1f1f1;-->
    }

    input[type=text], input[type=email], textarea {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    input[type=submit], input[type=reset] {
      width: 20%;
      padding: 12px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    input[type=checkbox] {
      margin-top: 16px;
    }

    input[type=submit] {
      background-color: #004777;
      color: white;
      border: none;
    }

    input[type=submit]:hover {
      opacity: 0.8;
    }
 
    .line { 
      height: 75%; 
      position:absolute; 
      left: 48%;
      width: 1px;
      background: #ccc;
      z-index: 1; 
     } 

    </style>

</head>
<body>

<div class="line"></div>

<form id="contact-form" action="https://script.google.com/macros/s/AKfycbxFvlT1LVB4mrKHuMl0-HkOb62QP4n_rFHm8-6vH7Zhe_CcQ8XX/exec">

<h2 style="font-family:Courier New; color:#004777; opacity:0.7">Contact Form</h2>
  
  <div class="form-group">
    <label>Name:</label>
    <input type="text" name="Name" placeholder="Name" class="form-control" required>
  </div>

  <div class="form-group">
    <label>Surname:</label>
    <input type="text" name="Surname" placeholder="Surname" class="form-control" required>
  </div>
  
  <div class="form-group">
    <label>E-mail:</label>
    <input type="email" name="E-mail" placeholder="E-mail" class="form-control" required>
  </div>
  
  <div class="form-group">
    <label>Questions or feedback?</label>
    <!-- <input type="text" name="Message" placeholder="Message" required> -->
    <textarea rows="5" name="Message" placeholder="Questions or feedback?" class="form-control" required></textarea>
  </div>

  <div class="form-group">
    <input id="Newsletter" type="checkbox" checked="checked" name="Newsletter" value="true" class="form-control"><label for="Newsletter"> Subscribe to our Newsletter to receive the latest updates.</label>
  </div>

  <br>

  <div>
    <!-- Enter message: <input type="text" id = "message"> -->
    <!-- <button type="submit" id="submit-form" value="Submit" onclick="showMessage()" >Submit</button> -->
    <input type="submit" id="submit-form" value="Submit" class="form-control">
    <input type="reset" id="reset-form" value="Reset" class="form-control">
 </div>

</form>

<!-- ### <span style="color:#004777"> Newsletter </span> -->

<form id="subscribe-form" action="https://script.google.com/macros/s/AKfycbxFvlT1LVB4mrKHuMl0-HkOb62QP4n_rFHm8-6vH7Zhe_CcQ8XX/exec">

<h2 style="font-family:Courier New; color:#004777; opacity:0.7">Newsletter</h2> 

  <div class="form-group">
    <label>E-mail:</label>
    <input type="email" name="E-mail" placeholder="E-mail" class="form-control" required>
  </div>

  <div class="form-group">
    <input id="Newsletter" type="checkbox" checked="checked" name="Newsletter" value="true" class="form-control" required><label for="Newsletter"> Subscribe to our Newsletter to receive the latest updates.</label>
  </div>
  
  <br>

  <div>
    <!-- Enter message: <input type="text" id = "message"> -->
    <!-- <button type="submit" id="submit-form" value="Submit" onclick="showMessage()" >Submit</button> -->
    <input type="submit" id="submit-form" value="Subscribe" class="form-control">
    <input type="reset" id="reset-form" value="Reset" class="form-control">
 </div>

</form>

<!-- <p> Message is: <span id = "display_message"></span> </p> -->

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script src='../contact.js'></script>
<script src='../subscribe.js'></script>

</body>
</html>
