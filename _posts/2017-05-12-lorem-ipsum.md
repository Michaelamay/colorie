---
layout: post
title: Furnitureland
description: Lorem Ipsum is simply dummy text
summary: A mock website that sells furniture.

---
<style>
h1{
    color: maroon;
    margin-left: 40px;
}
        .slider-holder
        {
            width: 800px;
            height: 400px;
            background-color: yellow;
            margin-left: auto;
            margin-right: auto;
            margin-top: 0px;
            text-align: center;
            overflow: hidden;
        }
       
        .image-holder
        {
            width: 2400px;
            background-color: red;
            height: 400px;
            clear: both;
            position: relative;
           
            -webkit-transition: left 2s;
            -moz-transition: left 2s;
            -o-transition: left 2s;
            transition: left 2s;
        }
       
        .slider-image
        {
            float: left;
            margin: 0px;
            padding: 0px;
            position: relative;
        }
       
        #slider-image-1:target ~ .image-holder
        {
            left: 0px;
        }
       
        #slider-image-2:target ~ .image-holder
        {
            left: -800px;
        }
       
        #slider-image-3:target ~ .image-holder
        {
            left: -1600px;
        }
       
        .button-holder
        {
            position: relative;
            top: -20px;
        }
       
        .slider-change
        {
            display: inline-block;
            height: 10px;
            width: 10px;
            border-radius: 5px;
            background-color: brown;
        }
</style>

A mock website that sells furniture online. Furnitureland lists multiple items for sale and has a dynamic array of categories. When users enter the site, only the hottest and featured items are listed in the large-scale window. This captures the attention of users immediately. Users can also click the next and previous arrow to see other items. Furthermore, the scrolling down on the page, this section focuses solely on individuals’ items. The pages contain great practice of footer and headers ideally for e-commerce sites.@

Written: HTML, CSS, Javascript, jQuery, Bootstrap, Font Awesome

<a href="https://michaelamay.github.io/Furnitureland/">Furnitureland</a>

<!-- Image section -->

<h1>This is a test. </h1>

<div class="slider-holder">
    <span id="slider-image-1"></span>
    <span id="slider-image-2"></span>
    <span id="slider-image-3"></span>
    <div class="image-holder">
        <img src="https://i.ibb.co/D7YvZ6m/forest.jpg" alt="forest" class="slider-image"/>
        <img src="https://i.ibb.co/D7YvZ6m/forest.jpg" alt="forest" class="slider-image"/>
        <img src="https://i.ibb.co/D7YvZ6m/forest.jpg" alt="forest" class="slider-image"/>
    </div>
    <div class="button-holder">
        <a href="#slider-image-1" class="slider-change"></a>
        <a href="#slider-image-2" class="slider-change"></a>
        <a href="#slider-image-3" class="slider-change"></a>
    </div>
</div>

<br>
<img src="https://i.ibb.co/D7YvZ6m/forest.jpg" alt="forest" />



<img src="./images/forest.jpg" alt="forest"/>

<img src="../images/forest.jpg" alt="forest"/>

<img src="/images/forest.jpg" alt="forest"/>