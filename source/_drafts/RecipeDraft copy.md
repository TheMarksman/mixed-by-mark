---
title: Title
date: YYYY-MM-DD
tags:
---
{% asset_img top-image PretzelTreats.jpg %}
<div class="post-body">
Short description

<br>
<!--more-->

<a class="jump-to-recipe-btn" href="#recipejump"> 
    Jump to Recipe
</a>

Detailed text

<div style="display:flex;">
<div>
    {% asset_img floating-image ButterCrisco.jpg %}
</div>
</div>

<div style="display:flex;">
    {% asset_img side-by-side CobbDip2.jpg %}
    {% asset_img side-by-side CobbDip3.jpg %}
</div>

<br>
</div>

<div id="recipejump"></div>
<div id="recipe">
    <div class="recipe-box">
        <div class="recipe-title-box">
            <div>
                <div class="recipe-title-box-title">
                    <div class="recipe-title-box-header">Title</div>
                </div>
                <p class="recipe-title-box-title" style="font-family: Arial;">Yield: </p>
            </div>
            <!-- {% asset_img recipe-title-box-img ButterCrisco.jpg %} -->
            <button class="print-recipe"
                    type="button"
                    onclick="printDIV('recipe')" >
                Print Recipe
            </button>
        </div>
        <p style="font-size:150%;"><b>Ingredients</b></p>
        <ul class="post-body">
                <li>Ingredient1</li>
                <li>Ingredient2</li>
                <li>Ingredient3</li>
        </ul>
        <hr style="height:1px;background-color:rgb(189, 189, 189) ">
        <p style="font-size:150%;"><b>Directions</b></p>
        <ol class="post-body">
            <li>Step1</li>
            <li>Step2</li>
            <li>Step3</li> 
        </ol> 
        <hr style="height:1px;background-color:rgb(189, 189, 189) ">
        <p style="font-size:150%;"><b>Notes</b></p>
        <ol class="post-body">
            <li>Note1</li>
        </ol>
    </div>
</div>

<br>
