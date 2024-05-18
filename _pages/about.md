---
permalink: /
title: ""
excerpt: "About me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Two Columns</title>
    <style>
        .columns {
            display: flex;
            justify-content: space-between;
        }

        .column1 {
            width: 30%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column2 {
            width: 70%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column3 {
            width: 40%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column4 {
            width: 60%; /* 조절 가능 */
            border: 1px solid #F2F2F2;
            padding: 10px;
            box-sizing: border-box;
        }

        .column5 {
            width: 100%; /* 조절 가능 */
            border: 1px solid #FFFFFF;
            padding: 20px;
            box-sizing: border-box;
        }

        .column6 {
            width: 50%; /* 조절 가능 */
            border: 1px solid #FFFFFF;
            padding: 20px;
            box-sizing: border-box;
        }

        .column7 {
            width: 50%; /* 조절 가능 */
            border: 1px solid #d3d3d3;  /* 회색 색상 코드 추가 */
            padding: 20px;
            box-sizing: border-box;
        }

        h1 { text-align: center; }

        li{ list-style-position: inside; 
            text-indent: -20px;
        }

        .inside { list-style-position: inside; }

        
    </style>
</head>


<body bgcolor='#F2F2F2'>

<div class="columns">
    <div class="column1">
        <p>  <img src="https://github.com/int141312/int141312.github.io/blob/gh-pages/images/profile.png?raw=true">   </p> 
        <h1> Jisung Son </h1>
        <a> jisung9973@gmail.com  </a>
    </div>

    <div class="column2">
        <p>I am a deep learning enthusiast with a keen interest in generative models, diffusion models, and the underlying principles of deep learning. My passion lies in designing interpretable and inferable generative models that can emulate the complexities of the real world.
        </p>
        
        <p>
My goal is not just to create models that can generate realistic outputs, but also to forge a deeper understanding of deep learning architectures and methodologies. Through this journey, I am committed to advancing research that demystifies the core mechanics of AI, making it as accessible and as natural to use in our daily lives as a calculator.
        </p>
    <div class="columns">
      <div class="column3">
        <h3> Interests </h3>
        <ul class="inside">
          <li> Deep Learning </li>
          <li> Generative AI </li>
          <li> Diffusion models </li>
        </ul>
      </div>

      <div class="column2">
        <h3> Education </h3>
        <ul class="inside">
          <li> Gwangju Institute of Science and Technology <br> (2023-2025) M.S in Artificial Intelligence  </li>
           
          <li> Ulsan National Institute of Science and Technology <br> (2014-2019) B.S in Physics, minor in Nuclear Science and Engineering </li> 
          
        </ul>
        
      </div>

    </div>
        
    </div>
</div>

<br>


<div id="research" name="research" class="columns" style='background-color: #ffffff' >
    <br>
    <div class="column5">
      <h1> Research & Projects </h1> 
      <h3> Model Sensitivity (Ongoing) </h3>
      <p>
      Apply formulas to predict how parameters change as data changes without retraining.
      </p>      

      <h3> Development and Training of Reinforcement Learning Environments with Dynamic Terrain Considerations: A Case Study on Robot Vacuum Cleaner (2023.03 ~ 2023.06) </h3>
      <p> * Language: Python </p>

      <div class="columns" style='background-color: #ffffff'>
        <div class="column6">
        <p>  Reinforcement learning is commonly applied to learn optimal decision-making in stationary environments. However, in real-world scenarios, stationary environments are limited, and thus, the use of reinforcement learning in machine intelligence applications is limited. In the case of robot vacuum cleaners, companies typically employ simple algorithms or basic machine learning techniques to determine the robot’s movement path. These approaches fail to address the issue of adapting to environmental changes that occur during the cleaning process. We aim to develop a reinforcement learning environment that can be used to enhance the efficiency of robot vacuum cleaners and use the environment to train a robot vacuum cleaner agent. We created a dynamic grid-world-based learning environment that incorporates potential changes in the real world. We trained a robot vacuum cleaner to navigate the room efficiently and compared its performance with traditional algorithm-based approaches.  </p> 
        </div>

        <div class="column6">
          <p> {% include video.html id="3AfjKQNlUwY"%} </p>
        </div>

      </div>

      <h3> Development of efficient dictionary training technology for large Korean language models (2024. 01 ~ 2024. 12) </h3>
      
    </div>
</div>

<br>

<div id="study" name="study" class="columns" style='background-color: #ffffff' >
    <br>
    <div class="column5">
      <h1> Study </h1> 

      <div class="column6">
        <div class="card">    
        <h3> Why ML lost and DL became the trend? </h3>
          <a href="https://www.notion.so/Why-ML-lost-and-DL-became-the-trend-  2249f0f11b16451c93b79d5214356bc7" target="_blank"> Notion </a>
        </div>

        <div class="card">
        <h3> Diffusion model Background </h3>
          <a href="https://www.notion.so/Diffusion-model-Background-9b61df6e3d8846a2a55c378a8024bfa1" target="_blank"> Notion </a>
        </div>

      </div>



      <div class="column6"> 

        <div onclick='window.location.href = "https://panoramic-timer-f8a.notion.site/Discussion-of-deep-learning-representations-a48f244a96264b578ae3ffb277ceb1cf" target="_blank" class="card"> Discussion of deep learning representations </div>

        <div class="card">
          <h3> Why Cross Entropy? </h3>
            <a href="https://panoramic-timer-f8a.notion.site/Why-Cross-Entropy-4f0809c9077f4bde8cccfa80d849d1b9?pvs=4"> Notion </a>
        </div>

      </div>

      
    </div>
</div>

<br>

<div id="experience" name="experience" class="columns" style='background-color: #ffffff' >
  <br>
  <div class="column5">
    <h1> Experience </h1>
    <h3> Teaching </h3>
    <ul class="inside">
    <li> General PhysicsⅠ, UNIST (spring 2018) </li>
    <li> General Physics Ⅱ, UNIST (fall 2018) </li>
    <li> Calculus Ⅱ, UNIST (fall 2018) </li>
    </ul>
 
    <h3> Military Service </h3>
    <ul class="inside">
    <li> ROKAF (2020-2022) </li>
    </ul>

    <h3> Additional Education </h3>
    <ul class="inside">
    <li> KIAS-APCTP Statistical Physics Winter School (POSTECH) (2020) - ML & Deep Learning </li>
    <li> Data Youth Campus (Yonsei University) (2022) - Big Data analysis & Deep Learning </li>
    </ul>


  </div>
</div>

<br>

<div id="Motto" name="Motto" class="columns" style='background-color: #ffffff' >
  <br>
  <div class="column5">
    <h1> Life Motto </h1>
    <h3> Let's do something I'm passionate about. </h3>
    <p> No matter what you do, there will always come a time when it's hard and you feel like giving up. To get through those moments, you need to do something you love and are passionate about. This is the secret to success and how I live my life. </p>

    <h3> Muscle growth </h3>
    <p> If you look at the process of muscle development, the first thing that happens is that muscle fibers tear, and new muscle fibers grow to fill the void. Human growth is no different than muscle development. The right amount of "tearing" is what makes you grow. </p> 
 



  </div>
</div>



</body>
</html>







<h2> Skills </h2>
* Python, C++, C#, HTML  
* Deep Learning Frame work: PyTorch
* 3D modeling: Unreal Engine, Unity, Sketchup







