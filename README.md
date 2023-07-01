# Wildlife-conservation-
* {
    box-sizing: border-box;
    margin: 0;
  }

  body {
    font-family: "Roboto", sans-serif;
  }

  /* Navigation */

.nav-container {
    background: #000000,#FF00008F,#FF06068F;
    box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.1);
    height: 100px;

   
   
}

.wrapper {
    width: 1650px;
    margin: 0 auto;
  }

  nav ul {
    display: flex;
  }

  .nav-items li {
    list-style: none;
    margin-right: 100px;
  }

  .nav-items li:nth-last-of-type(1) {
    margin: 0;
  }
  .nav-items li a {
    color: #000;
    font-size: 40px;
    font-family: Inter;
    text-decoration: none;

  }
  /* search box */

.search-box {
    /*display: none;*/
    width: 1650px;
    margin: 0 auto;
    text-align: right;
    position: relative;
    top: 0;


    transition: 300ms;
  }
  .search-box.active {
    top: 72px;
  }

  .search-box input {
    background: #fffffa;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.15);
    border-radius: 0px 0px 8px 8px;
  
    font-size: 24px;
    line-height: 42px;
    border: 0;
    padding: 12px 48px;
  }
  .search-box input::placeholder {
    color: #b3b3b3;
  }

  /* Header */

.header-container {
    background: url(<path-to-image>), lightgray 50% / cover no-repeat;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    display: flex;
    align-items: center;
}
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  header h1 {
    font-weight: 900;
    font-size: 64px;
    line-height: 75px;
    color: #021718;
    margin-bottom: 24px;
  }
  header p{
    color: #000;
font-size: 40px;
line-height: normal;
width: 500px;
margin-bottom: 48px;
  }
  .social-icons {
    display: flex;
    align-items: center;
  }
  .social-icons a {
    margin: 0 24px;
  }
  .social-icons a:nth-of-type(1) {
    margin-left: 0;
  }
  /* Hero image */
  header .hero-image {
    position: relative;
    transition: 300ms;
    z-index: 100;
  }
  header .hero-image img:hover {
    transform: rotate(-6deg);
  }
  /* Search & Close Buttons */

.nav-btn-container {
    display: flex;
    position: relative;
  }
  
  .nav-btn-container img {
    position: absolute;
  }
  .nav-btn-container .close-btn {
    opacity: 0;
    pointer-events: none;
    transform: translateY(-8px);
    transition: 300ms;
  }
  
  .nav-btn-container .search-btn {
    pointer-events: auto;
    transition: 300ms;
  }
  .nav-btn-container.active .search-btn {
    opacity: 0;
    pointer-events: none;
    transform: translateY(-8px);
  }
  
  .nav-btn-container.active .close-btn {
    opacity: 1;
    pointer-events: auto;
    transform: translateY(0);
