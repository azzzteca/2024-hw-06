.section {
max-width: 1440px;
margin-left: auto;
margin-right: auto;

padding-top: 120px;
padding-bottom: 120px;
}

.container-title {

margin-left: auto;
margin-right: auto;

}

.section-header .container {
align-items: center;
}

.header-nav {
margin-left: 76px;
}

.header-nav .nav-list {
display: flex;

align-items: center;

list-style-type: none;
}

.nav-list .nav-item:not(:last-child) {
margin-right: 40px;
}

.nav-item .nav-link.current::after {
content: "";

position: absolute;
left: 0;
bottom: 0;

display: block;
width: 100%;
height: 4px;
border-radius: 2px;

background-color: var(--pressed-color-ocean);

transition: opacity;
}

.nav-item .nav-link {
display: block;
padding-top: 24px;
padding-bottom: 24px;

position: relative;

font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;

color: var(--dark-color-navyblue);
text-decoration: none;

transition-property: color;
transition-duration: var(--duration-250);
transition-timing-function: var(--timing-function-cubic);
}

.nav-link:hover,
.nav-link:focus {
color: var(--pressed-color-ocean);
}

.header-adress {
margin-left: auto;
}

.adress-list {
display: flex;
gap: 40px;

list-style-type: none;
}

.adress-link {
color: var(--body-text-color-slate);

font-style: normal;
line-height: 1.5;
letter-spacing: 0.02em;

text-transform: none;
text-decoration: none;

transition-property: color;
transition-duration: var(--duration-250);
transition-timing-function: var(--timing-function-cubic);
}

.adress-link:hover,
.adress-link:focus {
color: var(--pressed-color-ocean);
}

Hero

.section-hero > .container {
display: block;
}

.hero-header {
font-size: 56px;
font-weight: 700;
line-height: 1.07;
letter-spacing: 0.02em;

margin-bottom: 48px;
text-align: center;

color: var(--bacground-color-white);
}

.hero-button {
color: var(--bacground-color-white);
background-color: var(--primary-color-iris);

border: 0;
border-radius: 4px;

cursor: pointer;

display: block;
margin-left: auto;
margin-right: auto;

padding: 16px 32px;

transition-property: background-color;
transition-duration: var(--duration-250);
transition-timing-function: var(--timing-function-cubic);
}

.hero-button:hover,
.hero-button:focus {
background-color: var(--pressed-color-ocean);
}

.feature-list {
display: flex;

list-style-type: none;
}

.feature-item {
width: calc((100% - 72px) / 4);
}

.feature-item:not(:last-child) {
margin-right: 24px;
}

.feature-thumb {
display: flex;
justify-content: center;
align-items: center;

margin-bottom: 8px;
padding-top: 24px;
padding-bottom: 24px;

border: 1px solid rgba(142, 143, 153, 1);
border-radius: 4px;

background-color: var(--light-color-cloud);
}

.feature-item > h3 {
margin-bottom: 8px;

font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;

color: var(--dark-color-navyblue);
}

.feature-item > p {
padding: 0;

line-height: 1.5;
letter-spacing: 0.02em;
}

.section-team {
background-color: var(--light-color-cloud);
}

.section-team .container-title {
margin-bottom: 72px;
}

.team-list {
display: flex;

list-style: none;
}

.team-card {
width: calc(((100% - 72px) / 4));

box-shadow: 0px 2px 1px 0px rgba(46, 47, 66, 0.08),
0px 1px 1px 0px rgba(46, 47, 66, 0.16),
0px 1px 6px 0px rgba(46, 47, 66, 0.08);

cursor: pointer;
}

.team-card:not(:nth-child(4n)) {
margin-right: 24px;
}

.team-info {
padding: 32px 16px;

text-align: center;

min-height: 120px;
background-color: var(--bacground-color-white);
}

.team-info .team-header {
margin-bottom: 8px;

font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;

color: var(--dark-color-navyblue);
}

.team-card .info-person {
line-height: 1.5;
letter-spacing: 0.02em;

margin-bottom: 8px;
}

.socials {
display: flex;

list-style: none;
}

.socials.team-socials {
justify-content: space-between;
}

.social-item .social-link {
display: flex;
justify-content: center;
align-items: center;

border-radius: 50%;

width: 40px;
height: 40px;

fill: var(--bacground-color-white);
background-color: var(--primary-color-iris);

transition-property: background-color;
transition-duration: var(--duration-250);
transition-timing-function: var(--timing-function-cubic);
}

.social-item .social-link:hover,
.social-item .social-link:focus {
background-color: var(--pressed-color-ocean);
}

.section-portfolio .container-title {
margin-bottom: 80px;
}

.portfolio-list {
display: flex;
flex-wrap: wrap;

list-style: none;
}

.portfolio-card {
width: calc((100% - 48px) / 3);
}

.portfolio-card:not(:nth-child(3n)) {
margin-right: 24px;
}

.portfolio-card:nth-child(-n + 3) {
margin-bottom: 48px;
}

.card-thumb {
position: relative;

overflow: hidden;
}

.card-overlay {
position: absolute;

width: 100%;
height: 100%;

transform: translateY(100%);

top: 0;
left: 0;

background-color: var(--primary-color-iris);

transition-property: transform, box-shadow;
transition-duration: var(--duration-250), var(--duration-250);
transition-timing-function: var(--timing-function-cubic),
var(--timing-function-cubic);
}

.overlay-info {
padding: 40px 32px;

line-height: 1.5;

color: var(--bacground-color-white);
}

.portfolio-card:hover,
.portfolio-card:focus {
box-shadow: 0px 2px 1px 0px rgba(46, 47, 66, 0.08),
0px 1px 1px 0px rgba(46, 47, 66, 0.16),
0px 1px 6px 0px rgba(46, 47, 66, 0.08);
}

.portfolio-card:hover .card-overlay,
.portfolio-card:focus .card-overlay {
transform: translateY(0);
}

.portfolio-info {
border-right: 1px solid var(--light-color-cloud);
border-bottom: 1px solid var(--light-color-cloud);
border-left: 1px solid var(--light-color-cloud);

padding: 32px 16px 32px 16px;
}

.portfolio-info .info-header {
margin-bottom: 16px;

font-size: 20px;
font-weight: 500;
line-height: 1.2;
letter-spacing: 0.02em;

color: var(--dark-color-navyblue);
}

.portfolio-card > .info-text {
line-height: 1.5;
letter-spacing: 0.02em;
}

.section-footer {
padding-top: 100px;
padding-bottom: 100px;

background-color: var(--dark-color-navyblue);
}

.footer-info {
max-width: 264px;

margin-right: 120px;
}

.footer-info .footer-logo {
display: block;

font-size: 21px;
font-weight: 700;
line-height: 1.17;
letter-spacing: 0.03em;
text-decoration: none;
text-transform: uppercase;
margin-bottom: 22px;
}

.footer-adv {
line-height: 1.5;
letter-spacing: 0.02em;

color: var(--light-color-cloud);
}

.footer-socials {
margin-right: 80px;
}

.social-header {
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;

color: var(--bacground-color-white);

margin-bottom: 16px;
}

.socials-list .social-item:not(:last-child) {
margin-right: 16px;
}

.socials-list .social-link:hover {
background-color: var(--succsess-color-green);
}

.footer-label {
display: block;

margin-bottom: 20px;

font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;

color: var(--bacground-color-white);
}

.footer-email {
width: 264px;
padding: 8px 20px 8px 16px;
margin-right: 24px;

border: 1px solid var(--bacground-color-white);
border-radius: 4px;

color: var(--bacground-color-white);
background-color: inherit;
}

.footer-email::placeholder {
display: inline-block;

font-size: 12px;
line-height: 2;
letter-spacing: 0.04em;

color: var(--bacground-color-white);
}

.footer-button {
position: relative;
padding: 8px 62px 8px 24px;

font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;

color: var(--bacground-color-white);
background-color: var(--primary-color-iris);

border: none;
border-radius: 4px;

cursor: pointer;
}

.button-icon {
position: absolute;
top: 10px;
right: 24px;
}

/_ Модалка _/

.overlay {
display: none;
justify-content: center;
align-items: center;

position: fixed;

top: 0;
left: 0;
z-index: 999;

width: 100%;
height: 100%;

background-color: var(--dark-color-navyblue);
background-color: rgba(46, 47, 66, 0.4);
}

.is-open {
display: flex;
}

.modal {
position: relative;

padding: 76px 24px 24px 24px;

width: 408px;

background-color: var(--modal-bgc-color-dairy);

border-radius: 4px;
}

/_ кнопка закриття - _/

.modal-close {
display: flex;
justify-content: center;
align-items: center;

position: absolute;
top: 24px;
right: 24px;

width: 24px;
height: 24px;

border: none;
border-radius: 50%;
cursor: pointer;

fill: var(--dark-color-navyblue);
background-color: #f4f4fd;
border: 1px solid #e7e9fc;

transition: fill var(--duration-250) var(--timing-function-cubic),
background-color var(--duration-250) var(--timing-function-cubic);
}

.modal-close:hover,
.modal-close:focus {
fill: var(--bacground-color-white);
background-color: var(--primary-color-iris);
}

/_ оформлення фрази модального вікна _/

.modal-phrase {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;

margin-bottom: 20px;

text-align: center;

color: var(--dark-color-navyblue);
}

/_ оформлення форми модального вікна _/

.modal-form {
display: flex;
flex-wrap: wrap;
}

.modal-form .input-label {
display: flex;
flex-direction: column;

font-size: 12px;
line-height: 1.1667;
letter-spacing: 0.04em;

color: var(--subtle-text-color-light-slate);

margin-bottom: 10px;
}

.modal-form .input-label span {
margin-bottom: 7px;
}

.input-label.label-texarea {
margin-bottom: 16px;
}

.modal-form .input-line {
position: relative;

width: 360px;
height: 40px;

padding-left: 40px;

border: 1px solid rgba(46, 47, 66, 0.4);
border-radius: 4px;

transition: border-color var(--duration-250) var(--timing-function-cubic);
}

.modal-form .input-line:focus-within {
outline: none;

border-color: var(--primary-color-iris);
}

.modal-form .input-line:focus-within ~ .icon {
fill: var(--primary-color-iris);
}

.input-label .input-item {
position: relative;
}

.input-item .icon {
position: absolute;
top: 14px;
left: 16px;

transition: fill var(--duration-250) var(--timing-function-cubic);
}

.input-line.textarea-line {
height: 120px;

padding: 10px 16px;

resize: none;
}

.textarea-line::placeholder {
font-size: 12px;
line-height: 1.167;
letter-spacing: 0.04em;

color: #75757580;
}

.checkbox-input {
appearance: none;
position: absolute;
}

.checkbox-icon {
width: 16px;
height: 16px;

border: 1px solid rgba(46, 47, 66, 0.4);
border-radius: 2px;

background-image: url(../images/full-check.svg);
background-size: contain;
background-origin: border-box;
}

.checkbox-input:checked + .checkbox-icon {
background-color: var(--primary-color-iris);
border: var(--primary-color-iris);
}

.checkbox-label {
display: flex;
align-items: center;
margin-bottom: 24px;

font-size: 12px;
line-height: 1.167;
letter-spacing: 0.04em;

color: #757575;
}

.checkbox-label a {
color: var(--primary-color-iris);
}

.checkbox-info {
margin-left: 9px;
}
