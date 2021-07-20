<!DOCTYPE html>
<html lang="en" > 
<head>
  <meta charset="UTF-8">
  <title>ЧайТеа </title>
  <link href="https://fonts.googleapis.com/css?family=Abel|Lobster" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script><link rel="stylesheet" href="./style.css">

</head>
<style> 
    .hideShow{
    display: none;
} 
    
    </style>
   
<body>
    <script>
       
    </script>
<!-- partial:index.partial.html -->
<div class="align-center">

    <h1 class="heading">ЧайТеа</h1>
    <p class="desc">Гра на пам'ять по видам інтелекту</p>
        <div class ="hideShow" id="rick">
            <video width="625" height="397" controls>
                <source src="./Assets/Rick Astley - Never Gonna Give You Up (Video).mp4" type="video/mp4">
                <source src="./Assets/Rick Astley - Never Gonna Give You Up (Official Music Video).ogg" type="video/ogg">
            </video>    
        </div>
    <button class="btn" id="btn-start">
        Почати
    </button>

    <div class="cards-container" id="cards">
        <div class="flip-container hide" id="card-template">
            <div class="flipper">
                <div class="front">
                    <label>Види інтелектів</label>
                </div>
                <div class="back">
                    <label></label> 
                </div>
            </div>
        </div>
    </div>

    <div class="timer">
        <label id="minutes"></label>:
        <label id="seconds"></label>
        <div class="time">
            НАЙКРАЩИЙ ЧАС: <span id="bestTime"></span>
        </div>
    </div>
    <div class="pointsText">
        <div class="time">
            HP: <span id="points"></span>
        </div>
    </div>

</div>
<!-- partial -->
  <script  src="./script.js"></script>

</body>
</html>
