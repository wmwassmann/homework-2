# homework-2
Reactive Website


So before we dive in to this - I know it's a mess of "divs" and very little refactoring.  I'll be spending a nice chunk of my day refactoring this monday 6/22.  I spent most of my time trying to understand why anything I tried to put under my carousel was instead floating over it (many hairs were pulled), and I finally, like only a half hour before I submitted, realized that I was missing a </div> closing out the carousel.  

The lesson learned was the value of html validation services, because that's how I found the error.

Now that I know what's going on, after I refactor a bit tomorrow, I'll be adding in a section which talks about my travels throughout the country and some of my favorite things to do, which I tried to do at first, but it kept floating over the carousel, for like 3 days. 

I'm also realizing I need a 1 on 1 with a tutor. So I'm sending Jen and email.  Back when I went to university, I had the very stupid mindset of "I don't need a tutor, I'm doing just fine in my class." Even if I "understand" the material, I think it's definitely a good to work with someone 1 on 1. 



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link rel="stylesheet" href="assets.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>

    <title>William Wassmann</title>
  
  </head>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
     <a class="navbar-brand" href="#">W.M.Wassmann's</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="https://twitter.com/WMWassmann">Twitter</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="https://www.linkedin.com/in/william-wassmann-287a14a4/?trk=nav_responsive_tab_profile_pic">LinkedIn</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://www.facebook.com/">Facebook</a>
          </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About Me
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="https://wmwassmann.com/">My Writing</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="https://github.com/wmwassmann?tab=repositories">Portfolio</a>
          </div>
        </li>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-o
