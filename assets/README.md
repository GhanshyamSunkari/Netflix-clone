@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap");
* {
  margin: 0;
  padding: 0;
}
body {
  background-color: black;
}
/* Navbar and Main Sections */
.navmain {
  background-image: url(assets/images/bg.jpg);
  height: 80vh;
  background-size: max(1200px, 100vw);
  background-position: center center;
  background-repeat: no-repeat;
}

.box {
  background-color: black;
  height: 80vh;
  opacity: 0.8;
}

/* Navbar section */
nav {
  height: 20vh;
  max-width: 80vw;
  display: flex;
  align-items: center;
  margin: auto;
  justify-content: space-between;
}
nav img {
  width: 100px;
  position: relative;
  z-index: 10;
}

nav button {
  position: relative;
  z-index: 10;
}

/* Main section */

.hero {
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 30px;
  gap: 20px;
  position: relative;
}

.hero > :first-child {
  font-size: 48px;
  font-weight: bolder;
  text-align: center;
  font-family: "Poppins", sans-serif;
}

.hero > :nth-child(2) {
  font-size: 24px;
  font-weight: 400;
  text-align: center;
}
.hero > :nth-child(3) {
  font-size: 24px;
  font-weight: 400;
  text-align: center;
}

main .email {
  display: flex;
  margin-top: 30px;
  justify-content: center;
  position: relative;
}

/* separation */
.separation {
  background-color: rgba(169, 169, 169, 0.479);
  height: 5px;
}

/* buttons */
header .btn {
  padding: 3px 8px;
  margin-right: 10px;
  font-weight: bold;
  color: white;
  border-radius: 5px;
  background-color: #f0f8ff00;
  border: 1px solid rgba(255, 255, 255, 0.189);
  cursor: pointer;
}

.btn-sm-red {
  background-color: red;
  color: white;
  padding: 3px 8px;
  font-weight: bold;
  border-radius: 5px;
  border: 1px solid rgba(255, 255, 255, 0.189);
  cursor: pointer;
}

.btn-red {
  background-color: red;
  font-weight: bold;
  color: white;
  border-radius: 5px;
  padding: 5px 20px;
  font-size: 15px;
  border: 1px solid rgba(255, 255, 255, 0.196);
  cursor: pointer;
}

/* input box */
.email input {
  padding: 3px 100px 3px 20px;
  font-size: 10px;
  color: white;
  border-radius: 5px;
  background-color: rgba(169, 169, 169, 0.1);
  margin-right: 10px;
  border: 1px solid rgba(255, 255, 255, 0.386);
}

/* ------------------------break point--------------------------------------- */

written this whole code without AI