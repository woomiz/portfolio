---
name: Exercise-Tracker
tools:
  [React, react-router-dom, mongodb, express, nodejs, react infinite calendar]
image: https://i.imgur.com/WJseL5z.png
description: Exercise-Tracker is a small project extended to test the power of pure React on its own with the use of express as a backend to power up the react side and bootstrap to effectively style it.
---

## Exercise-Tracker

is a small project extended to test the power of pure React on its own with the use of express as a backend to power up the react side. Bootstrap along with my own custom made made inline CSS is being used to style the entire website which is being made responsible to useres. This is just a demo project on how React is being used to help with the input form fields along with the props system which is being used to pass states and functions so that there is a good interaction between parent and child component.

<style>
.carousel-control-next,
.carousel-control-prev {
    filter: invert(100%);
}
.wow a{
  margin:0px 20px;
}
</style>
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.imgur.com/1QhBfEj.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/7hbb2LW.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/GzKi7Al.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/HoP1vgx.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/WJseL5z.png" class="d-block w-85" alt="...">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

The Home page contains details about the list of exercises with description , duration and date of doing the exercise. The Users are able to modify or delete the exercise on the same page itself by clicking on the icons on the right side. A new User can be created by entering just the username in the **Create User** page and the new exercise that is being made from the **Create exercise Log** is made using the username created and automatically redirects to homepage after creation of the new exercise.

---

### Running locally

if you want to run this project on your machine, then after downloading you need to install all the node module inside both the server and client side by using the `npm install` after this the project could be started using the command `npm run start` from the root directory.

<p style="display:flex; align-items:center; justify-content:center;" class="wow">
{% include elements/button.html link="https://github.com/woomiz/Exercise-Tracker" text="Open Git Repo" %}
<a class="github-button" href="https://github.com/woomiz/Exercise-Tracker/archive/master.zip" data-color-scheme="no-preference: dark; light: light; dark: dark;" data-icon="octicon-cloud-download" data-size="large" aria-label="Download woomiz/Exercise-Tracker on GitHub">Download Repo</a>
</p>
