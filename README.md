<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<body>
    <div class="container desk-view">
        <nav class="navbar">
            <h1 class="logo">Aeezah.</h1>
            <div class="navitem-cont">
                <a class="nav-link active" id="navItem1">NEW ARRIVALS</a>
                <a class="nav-link" id="navItem2">SHOP</a>
                <a class="nav-link" id="navItem3">BEAUTY</a>
                <a class="nav-link" id="navItem4">SALE</a>
                <a class="nav-link" id="navItem5">JOURNAL</a>
            </div>
        </nav>
        <hr class="hori">
        <div class="input-container">
            <input class="input" type="text" placeholder="Search videos, people, and more">
            <div class="inst">
                <a class="instagram">INSTAGRAM</a>
                <hr>
                <i class="fa fa-instagram"></i>
            </div>
        </div>
        <div class="middle-container">
            <div>
                <hr class="mid-hor">
                <h1 class="mid-heading">FABRIC THAT</h1>
                <hr class="mid-hor">
                <h1 class="mid-heading">SPEAKS</h1>
                <hr class="mid-hor">
                <button class="viewall">VIEW ALL</button>
                <button class="watchnow">Watch now</button>
            </div>
            <div class="yellow">
                <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708066869/My_project_11_1_dz1lph.png" class="image1">
                <p class="edition yellow">New Edition</p>
            </div>
        </div>
        <div class="bottom-container">
            <div class="shirts">
                <p class="edition">Shirts</p>
                <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708067152/1_rcjox1.png" class="image1">
            </div>
            <div class="shirts">
                <p class="edition">Hoodies</p>
                <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708067398/2_xtvdrd.png" class="image1">
            </div>
            <div class="quote-cont">
                <p class="quote">"Fashion is not about clothes, it is about a look.</p>
            </div>
        </div>
    </div>


    <div class="container mobile-container">
        <nav class="navbar">
            <h1 class="logo">Aeezah.</h1>
            <div class="navitem-cont">
                <i class="fa fa-shopping-bag"></i>
            </div>
        </nav>
        <div>
            <hr class="mid-hor">
            <h1 class="mid-heading">FABRIC THAT</h1>
            <hr class="mid-hor">
            <h1 class="mid-heading">SPEAKS</h1>
            <hr class="mid-hor">
        </div>
        <div class="yellow">
            <p class="edition">New Edition</p>
            <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708066869/My_project_11_1_dz1lph.png" class="image1">
        </div>
        <div class="button-cont">
            <button class="viewall">VIEW ALL</button>
            <button class="watchnow">Watch now</button>
        </div>
        <div class="shirts">
            <p class="edition">Shirts</p>
            <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708067152/1_rcjox1.png" class="image1">
        </div>
        <div class="shirts">
            <p class="edition">Hoodies</p>
            <img src="https://res.cloudinary.com/difbmfdoo/image/upload/v1708067398/2_xtvdrd.png" class="image1">
        </div>
        <div class="quote-cont">
            <p class="quote">"Fashion is not about clothes, it is about a look.</p>
        </div>
    </div>

</body>

</html>
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.navbar {
    display: flex;
    justify-content: space-between;
}

.container {
    padding: 14px;
}

.nav-link {
    margin-right: 12px;
    font-family: "Roboto";
    font-size: 13px;
}

.navitem-cont {
    margin-top: 25px;
}

.logo {
    margin-right: 13px;
    justify-content: space-between;
    font-family: "Roboto";
    font-weight: 500;
}

.active {
    font-weight: bold;
}

.input {
    border: 2px solid skyblue;
    height: 25px;
    width: 230px;
}

.input-container {
    display: flex;
    justify-content: space-between;
    padding: 10px;
    margin-left: 35px;

}

.hori {
    width: 100%;
}

hr {
    width: 100px;

}

.inst {
    display: flex;
}

.image1 {
    width: 260px;
    margin-right: 15px;
}

@media screen and (max-width: 767px) {
    .button-cont {
        text-align: center;
    }
}

.mid-hor {
    width: 320px;
}

.mid-heading {
    font-family: "Roboto";
    font-weight: 600;
}

.middle-container {
    display: flex;
    justify-content: space-between;
}

.viewall {
    background-color: black;
    color: #ffffff;
    height: 40px;
    width: 100px;
    margin-right: 20px;
}

.watchnow {
    background-color: transparent;
    width: 100px;
    height: 40px;
}

.edition {
    font-weight: bold;
    font-family: "Roboto";
}

@media screen and (max-width: 767px) {
    .edition {
        text-align: center;
    }
}

.yellow {
    margin-left: 95px;
}

.bottom-container {
    display: flex;
    text-align: center;
}

.quote-cont {
    font-family: "Roboto";
    display: flex;
    align-items: center;
    font-weight: bold;
    font-size: 25px;
}

@media screen and (min-width: 768px) {
    .mobile-container {
        display: none;
    }
}

@media screen and (max-width: 767px) {
    .desk-view {
        display: none;
    }
}
