# Fylo-dark-themed-webpage
Coolest shit ever
css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-size: 14px;
  font-family: "Open Sans", sans-serif;
  overflow-x: hidden;
}

.header {
  background-color: #1c2431;
  font-family: "Raleway", sans-serif;
  position: relative;
}

.header nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 1.5em;
  max-width: 1200px;
  margin: auto;
}

.header nav img {
  height: 30px;
  margin-left: 5%;
}

.header nav ul {
  list-style-type: none;
}

.header nav ul li {
  display: inline-block;
  margin-right: 1em;
}

.header nav ul li {
  text-decoration: none;
  color: white;
}
 

.header picture img {
  position: absolute;
  bottom: -10px;
  z-index: -10;
  width: 100%;
  left: 0;
}

.header-intro {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.header-intro-illustration {
  display: block;
  width: 80%;
  max-width: 600px;
  margin: 4em auto;
  z-index: 100000;
}

.header-intro-product-info {
  color: white;
  margin-top: 4em;
  margin-bottom: 2em;
  z-index: 100000;
}

.header-intro-product-info h1,
.header__intro__product-info p {
  z-index: 100000;
}

.header-intro-product-info h1 {
  text-align: center;
  line-height: 1.4;
  font-size: 1.6rem;
  width: 93%;
  margin: 0 auto;
  margin-bottom: 0.8em;
}

.header-intro-product-info p {
  text-align: center;
  line-height: 1.6;
  font-size: 1rem;
  margin: 0 auto;
  width: 85%;
}

.header button {
  display: block;
  color: white;
  font-weight: 700;
  border: none;
  width: 270px;
  padding: 1.1em 2em;
  background: linear-gradient(to right, #65e2d9, #339ecc);
  border-radius: 2em;
  font-size: 1.2em;
  z-index: 10000;
  margin: 1rem auto;
}

.header button:active {
  transform: translateY(2px);
}

.header button:hover {
  cursor: pointer;
}

.header button:hover span {
  padding-right: 25px;
}

.header button:hover span::after {
  opacity: 1;
  right: 0;
}

.header button span {
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.header button span::after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

main {
  background: #181f2a;
  padding-top: 5em;
}

main .feature {
  display: flex;
  flex-direction: column;
  text-align: center;
  color: white;
  font-family: "Open Sans", sans-serif;
}

main section {
  max-width: 1200px;
  margin: auto;
}

.feature-icon {
  margin-bottom: 1.5em;
}

[class*='feature-item'] {
  margin-bottom: 5em;
}

[class*='feature-item'] h2 {
  margin-bottom: 0.5em;
}

[class*='feature-item'] p {
  width: 80%;
  margin: 0 auto;
  line-height: 1.6;
}

.feature-item4 p {
  width: 85%;
}

.produce-news {
  color: white;
  margin-bottom: 4em;
  display: grid;
}

.produce-news img img {
  max-width: 100%;
  display: block;
  width: 80%;
  margin: 0 auto 3em;
}

.produce-news div {
  padding-left: 7%;
  padding-right: 6%;
}

.produce-news h3 {
  margin-bottom: 1em;
}

.produce-news p {
  margin-bottom: 5%;
}

.produce-news span {
  color: #65e2d9;
  font-weight: 400;
  border-bottom: #65e2d9 solid 1px;
  padding: 0 0 2px;
}

.produce-news span img {
  position: relative;
  top: 3px;
  left: 2px;
  margin-bottom: 0%;
}

.testimonial {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.testimonial-quotes {
  height: 25px;
  position: relative;
  left: -150px;
  top: 2px;
}

.testimonial-item {
  background: #202a3c;
  color: white;
  border: none;
  padding: 2em 1.5em;
  margin: 0 auto;
  width: 90%;
  margin-bottom: 6%;
  border-radius: 7px;
  box-shadow: 0px 0px 4px 1px #202a3c;
}

.testimonial-item p {
  line-height: 1.6;
  margin-bottom: 1.5em;
}

.testimonial-item-user {
  display: flex;
}

.testimonial-item-user-image {
  display: block;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  margin-right: 4%;
}

.testimonial-item-user .title {
  font-weight: 700;
  margin-bottom: 0.5em;
}

.testimonial-item-user .subtitle {
  font-size: 0.7rem;
  display: inline-block;
  margin-top: 0.5em;
}

.signup {
  background: #1c2431;
  border: none;
  padding: 3em 1.5em;
  width: 90%;
  margin: 0 auto;
  color: white;
  border-radius: 7px;
  position: relative;
  top: 12em;
  max-width: 800px;
}

.signup-title {
  text-align: center;
  margin-bottom: 0.7em;
  font-size: 1.2rem;
}

.signup-details {
  text-align: center;
  line-height: 1.6;
  width: 93%;
  margin: 0 auto;
}

.signup-form {
  margin-top: 2em;
}

.signup-form input[type='text'] {
  border: none;
  border-radius: 30px;
  width: 100%;
  display: block;
  margin: 0 auto;
  padding: 1em 1.8em;
  font-size: 1em;
}

.signup-form input[type='submit'] {
  border: none;
  border-radius: 30px;
  width: 100%;
  display: block;
  margin: 0 auto;
  padding: 1em 1.8em;
  background: linear-gradient(to right, #65e2d9, #339ecc);
  color: white;
  font-weight: 700;
  cursor: pointer;
}

.footer {
  background: #0b1523;
  padding: 15em 1em 0.2em 2em;
  color: white;
  font-family: "Raleway", sans-serif;
}

.footer__img {
  margin-bottom: 2.5em;
}

.footer-item {
  display: flex;
  margin-bottom: 2em;
}

.footer-item-icon1 {
  height: 20px;
  width: 20px;
  margin-right: 5%;
}

.footer-item .details {
  line-height: 1.6;
}

.footer-item-icon {
  margin-right: 4%;
}

address {
  margin-bottom: 4em;
}

.footer-list {
  margin-bottom: 3em;
}

.footer-list-item {
  list-style-type: none;
}

.footer-list-item li {
  margin-bottom: 1.3em;
}

.attribution a.attribution__link {
  color: white;
}

.attribution {
  font-size: 11px;
  text-align: center;
}

.attribution a {
  color: #3e52a3;
}

@media only screen and (min-width: 768px) {
  .header nav {
    padding-top: 3em;
  }
  .header nav ul li {
    margin-right: 4em;
  }
  .header-intro-illustration {
    width: 50%;
  }
  .header-intro-product-info h1 {
    width: 50%;
    font-size: 1.7rem;
  }
  .header-intro-product-info p {
    width: 46%;
  }
  main .feature {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-column-gap: 2em;
    grid-row: 1fr;
    padding: 4em 6em 0 6em;
    margin-bottom: 4em;
  }
  .produce-news {
    grid-template-columns: 1fr 1fr;
    margin-bottom: 15em;
  }
  .produce-news img img {
    margin: 0;
    margin-left: 5%;
  }
  .produce-news div > * {
    margin: 0;
    margin-bottom: 0.5em;
  }
  .produce-news div h3 {
    font-size: 1.8rem;
    width: 50%;
    line-height: 1.5;
  }
  .produce-news div p {
    margin-bottom: 3%;
  }
  .testimonial {
    flex-direction: row;
  }
  .testimonial-quotes {
    height: 35px;
    position: relative;
    top: -10.4em;
    left: 2.4em;
  }
  .testimonial-item {
    margin-right: 30px;
    box-shadow: none;
  }
  .testimonial-item:nth-child(2) {
    position: relative;
  }
  .signup {
    width: 70%;
    top: 9em;
  }
  .signup-title {
    font-size: 1.5rem;
  }
  .signup-details {
    width: 80%;
  }
  .signup-form {
    display: flex;
    margin-top: 3em;
  }
  .signup-form input[type='text'] {
    width: 500px;
  }
  .signup-form input[type='submit'] {
    margin-left: 20px;
    width: 220px;
  }
  .footer > div {
    max-width: 1200px;
    margin: 0 auto;
  }
  .footer-container {
    display: grid;
    grid-gap: 20px;
    grid-template-columns: 1.5fr 1fr 1fr 1fr .5fr;
  }
  
  
}
