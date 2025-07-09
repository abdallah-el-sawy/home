<html>
  <head>

      <title>Portfolio</title>
      <style>
        .body{
          position: relative;
        }
      ul{
        background-color: rgb(57, 56, 56);
        display: flex;
        height: 70px;
        color: aliceblue;
        justify-content: space-evenly;
        align-content: center;
      }

      ul li{
        margin: 25px;
        list-style: none;
      }

      ul li a{
        text-decoration: none;
        color: white;
      }

      ul li a:hover{
        color: green;

      }

      .profile{
        background-color: rgb(255, 255, 255);
        display: flex;
        height: 210px;
        position: relative;
        width: 100%;
      }

      .profile img{
        border-radius: 50%;
        scale: 0.7;
        width:200px;
        height: 180px;
        align-items: center;
        position: absolute;
        display: flex;
        left: 400px;
        border: 3px solid;
        border-color: rgb(123, 175, 244);
      }

      .profile h2{
        background-color: rgb(57, 192, 255);
        display: flex;
        width: 125px;
        height: 27px;
        text-align: center;
        text-indent: 6px;
        color:aliceblue;
        font-size: 16px;
        font-style: normal;
        left: 590px;
        top: 30px;
        position: absolute;
        border-radius: 3px;
        align-items: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        
      }

      #description{
        background-color: rgb(255, 255, 255);
        height: 60px;
        align-items: center;
        left: 590px;
        top: 65px;
        position: absolute;
      }
     
      .skills{
        background-color: rgb(217, 214, 214);
        height: 280px;
        width: 99%;
        position: absolute;
        text-align: center;
        font-family:'Times New Roman', Times, serif;
        font-size:20px;


      }

      .images {
        background-color: red;
        width: 70%;
        align-items: center;
        align-content: center;
        position: absolute;
        left: 230px;
        height: 205px;
     
      }

  .images {
  background-color: rgb(217, 214, 214);
  width: 70%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 205px;
}

.images img {
  width: 100px; 
  border: 5px solid ;  
  border-color: lightgray;
}

.images p{
  color :black;
  font-size: 15px;
  top: 150px;
  position: absolute;
  left: 90px;
  display: flex;
  

}

.contact{
  background-color: aqua;
  width: 100%;
  height: 500px;
  top:500px
}

.contact h2{
  align-items: center;
  text-align: center;
  font-size: 16px;
  left: 0;
  
}

.skill-icon {
  width: 100px;
  height: auto;
  border: 3px solid lightgray;
  transition: transform 0.3s ease, filter 0.3s ease, border-color 0.3s ease;
  cursor: pointer;
}

.skill-icon:hover {
  transform: scale(1.2); 
  filter: brightness(1.2); 
  border-color: rgb(0, 183, 255); 
  background-color: rgb(159, 243, 159);
  opacity: 0.7;
}

.contact {
  background-color: rgb(255, 255, 255);
  width: 100%;
  height: 430px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;    
  text-align: center;      
}

.contact h2 {
  font-size: 28px;
  margin-top:300px ;
  color: #000;
}

.contact p {
  font-size: 18px;
  color: #000;
}





      



      </style>
  </head>
    <ul>
      <li><a href="">Home</a></li>
      <li><a href="">About</a></li>
      <li><a href="">Skills</a></li>
      <li><a href="">Contact</a></li>
    </ul>

    <div class="profile">
      <img src = "3.jpg" alt="profile picture">
      <h2>Abdallah Elsawy</h2>
      <p id="description">I'm passionate about programming and constantly driven to learn and explore new technologies. Whether <br> it's writing clean code, building projects, or solving problems, I love diving deep into the world of software<br>development.<br>
      </p>
    </div>

    <div class="skills">
      <h3>My Skills</h3>
      <div class="images">
        <img class="skill-icon" src="html.png" alt="HTML">
        <img class="skill-icon" src="css-3.png" alt="css">
        <img class="skill-icon" src="c-.png" alt="cpp">
        <img class="skill-icon" src="java.png" alt="java">
        <img class="skill-icon" src="java-script.png" alt="js">

        <p>HTML&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CSS &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CPP &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; JAVA &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; JAVA SCRIPT</p>
        


      </div>
    </div>


    <div class="contact">
      <h2>Contact Me</h2>
      <p>Email: abdallahelsawy706@gmail.com <br> Phone : 01027173150</p>
    </div>







</html>
