---
name: Emaily
tools:
  [
    React,
    Redux,
    react-router-dom,
    mongodb,
    express,
    sendgrid,
    passport.js,
    nodejs,
  ]
image: https://i.imgur.com/fgQEqVh.gif
description: Emaily is a mini email surveys service. Created as a fullstack JavaScript application on React and Node. With technologies like Redux, Redux Thunk, React Router, Express, MongoDB and materializeCSS for styling.
---

## Emaily

is a mini email surveys service. Created as a fullstack JavaScript application on React and Node. With technologies like Redux, Redux Thunk, React Router, Express, MongoDB and Bootstrap for styling.

This application implements the ability to log in using Google oauth. It uses plugin passport for the Node and connected strategy passport-google-oauth20. To send Emails used SendGrid API. And to simulate charging, the Stripe API is connected in test mode. All received data is stored on mongodb.com and managed using the mongoose plugin.

> You can view [live demo](https://emaily-recreation.herokuapp.com/)
> Because it's free heroku account, it goes to the "App is asleep" mode and may load for some time.

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
    <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="6"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="7"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.imgur.com/EeSZFa3.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/xEa03wA.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/S9WJfIC.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/L3iVJbl.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/1UDXUtD.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/NV4wLL8.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/3de2kIZ.png" class="d-block w-85" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.imgur.com/uPNi23D.png" class="d-block w-100" alt="...">
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

Once you are logged in, you can view a list of previously created surveys and if you are looking to create a new survey, you can do it by clicking on the "+" icon on the bottom right corner and after doing this you will be directed to a survey Form filling page when you have the option to give the body,title of the email along with the **recipients which should be given as "," seperated**. On forwarding and confirming your survey in the form review page you will be given the "send" button to send your mail to the recipients

After the letters are delivered, you can click on the links placed inside and using SendGrid Webhooks the selected option is transferred to our server. Each vote adds 1 to the selected option and the site is automatically refreshed on the updates given

<p class="text-center">
{% include elements/button.html link="https://emaily-recreation.herokuapp.com/" text="Live Demo" style="outline-danger" %}
</p>
***
### Running locally

if you want to run this project on your machine, then after downloading you need to run `npm install`. Next, in the _config_ folder, create the _dev.js_ file and add all the necessary data to connect to the database and third-party services. You can see the structure in the _template.dev.js_ file. Then you need to run the `npm run dev` command - this will start both the backend server and the frontend server.

> this project was made during the Node with React: Fullstack Web Development course at udemy.com and then improved.

<p style="display:flex; align-items:center; justify-content:center;" class="wow">
{% include elements/button.html link="https://github.com/woomiz/portfolio" text="Open Git Repo" %}
<a class="github-button" href="https://github.com/woomiz/portfolio/archive/master.zip" data-color-scheme="no-preference: dark; light: light; dark: dark;" data-icon="octicon-cloud-download" data-size="large" aria-label="Download woomiz/portfolio on GitHub">Download Repo</a>
</p>
