<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Profile Card</title>
   <link rel="stylesheet" href="profile card style.css">
</head>
<body>

  <div class="card">
    <div class="header-img">
      <div class="profile-pic">
        <img src="./instabutton-png-design-5690390.png" alt="profile" class="profile-img">
      </div>
    </div>
    <div class="three-dots">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot"></div>
    </div>
    <div class="card-content">
      <div class="name">Morgan Sweeney</div>
      <div class="title">Ant Collector</div>
      <div class="stats">
        <div>
          <div class="number">12</div>
          <div>Followers</div>
        </div>
        <div>
          <div class="number">1000</div>
          <div>Following</div>
        </div>
      </div>
      <button class="follow-btn">Follow</button>
      <div class="text">
        Morgan has collected ants since they were six years old and now has many dozen ants but none in their pants.
      </div>
    </div>
  </div>

</body>
</html>
q
body {
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient( #fd98ac, #a015f7 );
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-size: 18px;
    line-height: 1.8em;
  }

  .card {
    background-color: white;
    width: 340px;
    border-radius: 20px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    overflow: hidden;
    text-align: center;
    position: relative;
  }

  .card .header-img {
    height: 140px;
    background-image: url(./ant.jpg);
    background-position: center;
    position: relative;
    cursor: pointer;
  }
.profile-img{
  border-radius: 50%;
  width: 120px;
  height: 128px;
}
  .profile-pic {
    width: 120px;
    height: 128px;
    background-color: white;
    border-radius: 50%;
    position: absolute;
    bottom: -60px;
    left: 50%;
    transform: translateX(-50%);
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .three-dots {
    position: absolute;
    right: 15px;
    top: 145px;
    display: flex;
    flex-direction: column;
    gap: 4px;
  }

  .dot {
    width: 5px;
    height: 5px;
    background-color: #555;
    border-radius: 1px;
    margin-left: -2em;
  }

  .card-content {
    padding: 70px 25px 25px;
  }

  .name {
    font-weight: bold;
    font-size: 22px;
  }

  .title {
    font-size: 16px;
    color: #888;
    margin: 5px 0 15px;
  }

  .stats {
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
  }

  .stats div {
    text-align: center;
  }

  .stats div .number {
    color: #2196F3;
    font-weight: bold;
    font-size: 18px;
  }

  .follow-btn {
    background-color: #FFD700;
    color: black;
    padding: 12px 0;
    width: 85%;
    border: none;
    border-radius: 25px;
    font-weight: bold;
    font-size: 16px;
    cursor: pointer;
    margin-bottom: 20px;
  }

  .text {
    padding: 0 20px 25px;
    font-size: 15px;
    color: #555;
  }
