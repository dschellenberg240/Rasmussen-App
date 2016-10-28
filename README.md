<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>MySite</title>
<link href="http://code.jquery.com/mobile/1.3.0/jquery.mobile-1.3.0.min.css" rel="stylesheet" type="text/css"/>

<script src="http://code.jquery.com/jquery-1.8.3.min.js" type="text/javascript"></script>
<script src="http://code.jquery.com/mobile/1.3.0/jquery.mobile-1.3.0.min.js" type="text/javascript"></script>

<style>

.header {
	color: #6E0000;
	}

</style>

</head>
<body>

<div data-role="page">
  <div data-role="header" class="header">
    <h1>Homepage</h1>
  </div>
  <br>
  <br>
  	<a href="#signIn">Sign In</a>
    <p><strong>Welcome!</strong></p>
    <a href="#course" data-transition="fade">Course</a>
    <br>
    <a href="#videoTutorials">Video Tutorials</a>
    <br>
    <a href="#forumsChat" data-transition="fade">Forums / Chat</a>
    <br>
    <a href="#directory" data-transition="fade">Directory</a>
    <br>
    <a href="#additionalResources" data-transition="fade">Additional Resources</a>
  </div>
<div>
  <div data-role="footer">
    <h1>Mobile web app for Students!</h1>
  </div>
</div>

<div data-role="page" data-add-back-btn="true" id="signIn">
  <div data-role="header">
    <h1>Sign In</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>In your to ensure the best experience and you recieve content specifically for you, please sign in.</p>
    <br>
    
    <form>
      <div data-role="fieldcontain">
        <label for="textinput">Email: </label>
        <input type="text" name="textinput" id="textinput" value=""  />
      </div>
      <div data-role="fieldcontain">
        <label for="passwordinput">Password: </label>
        <input type="password" name="passwordinput" id="passwordinput" value=""  />
      </div>
      <button>Sign In</button>    
    
    </form>
    
  </div>

</div>

<div data-role="page" data-add-back-btn="true" id="course">
  <div data-role="header">
    <h1>Course</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Welcome! Here you will find contect about your course. You will need to log in to view specific information related to your course.</p>
    <br>
    
  </div>

</div>

<div data-role="page" data-add-back-btn="true" id="videoTutorials">
  <div data-role="header">
    <h1>Video Tutorials</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Welcome! Here you will find different video tutorials that will help your knowldge of programming grow.</p>
    <br>
   
  </div>

</div>

<div data-role="page" data-add-back-btn="true" id="forumsChat">
  <div data-role="header">
    <h1>Forums / Chat</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Welcome! Here you will be able to stay in touch with your fellow students. You can see who is on chatting now, or start a conversation in the forums.</p>
    <br>
    
  </div>

</div>

<div data-role="page" data-add-back-btn="true" id="directory">
  <div data-role="header">
    <h1>Directory</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Welcome! Here you will be able to find information for your current professors and fellow students. You will need to log in first in order to see information pertaining to you. Without logging in you will see general contact information for the school and administration contact information</p>
    <br>
    
  </div>

</div>

<div data-role="page" data-add-back-btn="true" id="additionalResources">
  <div data-role="header">
    <h1>Additional Resources</h1>
  </div>

  <div data-role="main" class="ui-content">
    <p>Welcome! Here you will find additional resources to help you grow. You will find links and videos to various toppics in computer science; such as programming, networking etc..</p>
    <br>
    
  </div>

</div>

</body>
</html>
