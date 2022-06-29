# profile
rizvi sir project profile page
DONOR PROFILE :
<html>
<head>
    <link rel="stylesheet" href="design.css">
</head>
<body>
    <div class="container">
        <div class="main">
            <div class="topbar">
                <h1> Spreading Joy</h1>
                <a href="">Home</a>
                <a href="">Logout</a>
                <a href="">Support</a>
            </div>
            <div class="row">
                <div class="left">
                    <div class="card text-center sidebar">
                        <div class="card-body">
                            <div class="profile buttons">
                                <h3>Donor's Name </h3>
                                <a href="">Donate History</a>
                                <a href="">Settings</a>
                                <a href="">signout</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="right">
                    <div class="user info content">
                        <h1 class="card content">About</h1>
                        <div class="card-body">
                            <div class="row">
                                <div class="info">
                                    <h3>Full Name :</h3>
                                </div>
                                <div class="info-desc">
                                    <h5>XYZ</h5>
                                </div>
                            </div>
                            <hr>
                            <div class="row">
                                <div class="info">
                                    <h3>Email :</h3>
                                </div>
                                <div class="info-desc">
                                    <h5>xyz2001@gmail.com</h5>
                                </div>
                            </div>
                            <hr>
                            <div class="row">
                                <div class="info">
                                    <h3>Phone :</h3>
                                </div>
                                <div class="info-desc">
                                   <h5>01676232360</h5>
                                </div>
                            </div>
                            <div class="row">
                                <div class="info">
                                    <h3>Address :</h3>
                                </div>
                                <div class="info desc">
                                  <h5>street no. 4,abc,Chittagong</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="card content">
                    <h3 class="m-3">Previous Donations</h3>
                    <div class="card-body">
                        <div class="row">
                            <div class="info">
                                <h5>Donation Info</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
  CSS:
  body{
    margin-top: 20px;
    background-color: lightgray;
}
.main{
    padding: 15px;
    font-family: Arial, Helvetica, sans-serif;

}
.topbar{
    background-color: greenyellow;
    overflow: hidden;
}
.topbar a{
    float: right;
    background-color: aquamarine;
    text-align: center;
    padding: 20px 26px;
    text-decoration: none;
    font-size: 26px;
    color: brown;
    
}

.sidebar {
    background-color: rgb(231, 147, 147);
    color: maroon;
    height: 96.5%;
    margin-top:18px;
    
    
}
.row{
    margin-top:10px;
	display:flex;
	justify-content: center;
	margin:auto;
	text-align: center;
	padding-top: 20px;
    width: 500px;
	
}
.sidebar  a{
    margin-left: 10px;
    display: block;
    color: white;
    padding-bottom: 20px;
    font-size: 30px;
    text-decoration: none;
    width: 200px;
}
.card{
    display: flex;
    flex-direction: column;
    color: rgb(57, 16, 82);
    padding-bottom: 10px;
    font-size: 30px;
    text-decoration: none;
}
.content{
    background-color: rgb(226, 113, 113);
    margin-left: 10px;
    display: block;
}
.container
{
    background-image: url(/image/248445692_579268383156655_7434293478413941860_n.jpg);
    background-size: cover;
    background-attachment: fixed;
}
REVEIVER:
  HTML:
<html>
<head>
    <link rel="stylesheet" href="designr.css">
</head>
<body>
    <div class="container">
        <div class="main">
            <div class="topbar">
                <h1> Spreading Joy</h1>
                <a href="">Home</a>
                <a href="">Logout</a>
                <a href="">Support</a>
            </div>
            <div class="row">
                <div class="left">
                    <div class="card text-center sidebar">
                        <div class="card-body">
                            <div class="profile buttons">
                                <h3>Receiver's Name</h3>
                                <a href="">Receive History</a>
                                <a href="">Settings</a>
                                <a href="">signout</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="right">
                    <div class="user info content">
                        <h1 class="card content">About</h1>
                        <div class="card-body">
                            <div class="row">
                                <div class="info">
                                    <h3>Full Name :</h3>
                                </div>
                                <div class="info-desc">
                                    <h5>XYZ</h5>
                                </div>
                            </div>
                            <hr>
                            <div class="row">
                                <div class="info">
                                    <h3>Email :</h3>
                                </div>
                                <div class="info-desc">
                                    <h5>xyz2001@gmail.com</h5>
                                </div>
                            </div>
                            <hr>
                            <div class="row">
                                <div class="info">
                                    <h3>Phone :</h3>
                                </div>
                                <div class="info-desc">
                                   <h5>01676232360</h5>
                                </div>
                            </div>
                            <div class="row">
                                <div class="info">
                                    <h3>Address :</h3>
                                </div>
                                <div class="info desc">
                                  <h5>street no. 4,abc,Chittagong</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="card content">
                    <h3 class="m-3">Recceived Donations</h3>
                    <div class="card-body">
                        <div class="row">
                            <div class="info">
                                <h5>Recceived Info</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
  CSS:
body{
    margin-top: 20px;
    background-color: lightgray;
}
.main{
    padding: 15px;
    font-family: Arial, Helvetica, sans-serif;

}
.topbar{
    background-color: greenyellow;
    overflow: hidden;
}
.topbar a{
    float: right;
    background-color: aquamarine;
    text-align: center;
    padding: 20px 26px;
    text-decoration: none;
    font-size: 26px;
    color: brown;
    
}

.sidebar {
    background-color: rgb(231, 147, 147);
    color: maroon;
    height: 96.5%;
    margin-top:18px;
    
    
}
.row{
    margin-top:10px;
	display:flex;
	justify-content: center;
	margin:auto;
	text-align: center;
	padding-top: 20px;
    width: 500px;
	
}
.sidebar  a{
    margin-left: 10px;
    display: block;
    color: white;
    padding-bottom: 20px;
    font-size: 30px;
    text-decoration: none;
    width: 200px;
}
.card{
    display: flex;
    flex-direction: column;
    color: rgb(57, 16, 82);
    padding-bottom: 10px;
    font-size: 30px;
    text-decoration: none;
}
.content{
    background-color: rgb(226, 113, 113);
    margin-left: 10px;
    display: block;
}
.container
{
    background-image: url(/image/248445692_579268383156655_7434293478413941860_n.jpg);
    background-size: cover;
    background-attachment: fixed;
}


