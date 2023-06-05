# goit-markup-hw-01

:root {
--accent-color:#404BBF;
--primary-background-color-light:#F4F4FD;
--secondary-background-color-dark:#2E2F42;
--primary-text-color-dark: #2E2F42;
--primary-text-color-light:#434455;
--primary-text-color-white:#ffffff;  
}

.list {
list-style: none;
}

.link {
text-decoration: none;
}

button {
cursor: pointer;
font-family: inherit;
}

body {
font-family: 'Roboto', sans-serif;
font-size: 16px;
color: #434455;
background-color: var(--primary-text-color-white)
}

h1,
h2,
h3,
h4,
p {
margin-top: 0;
margin-bottom: 0;
}

ul,
ol {
margin-top: 0;
margin-bottom: 0;
padding-left: 0;
}

img {
display: block;
}

.container {
max-width: 428px;
padding-left: 16px;
padding-right: 16px;
margin-left: auto;
margin-right: auto;
}

@media screen and (min-width: 768px) {
.container {
max-width: 768px;
}
}

@media screen and (min-width: 1158px) {
.container {
max-width: 1158px;
padding-left: 15px;
padding-right: 15px;  
 }
}

/\* .container {
width: 1158px;
margin-left: auto;
margin-right: auto;
padding-left: 15px;
padding-right: 15px;
}

.section {
padding-top: 120px;
padding-bottom: 120px;
} \*/

/_======================= MOBILE-HEADER =======================_/

@media screen and (max-width: 767px) {

.menu {
display: none;
}

.address {
display: none;
}  
/_====== mobile-menu ======_/
.mobile-menu-open-btn {
border: none;
background-color: transparent;
padding: 0;
line-height: 0;
}

.mobile-menu {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: #ffffff;
opacity: 0;
visibility: hidden;
pointer-events: none;
}

.mobile-menu.is-open {
opacity: 1;
visibility: visible;
pointer-events: auto;
}

.mobile-menu-container {
position: relative;
padding-top: 80px;
padding-left: 24px;
}

.mobile-menu-link {
font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
color: var(--primary-text-color-dark);
}

.mobile-menu-link:hover,
.mobile-menu-link:focus {
color: var(--accent-color);
}

.modal-menu-close-btn{
position: absolute;
top: 24px;
right: 24px;
display: flex;
align-items: center;
justify-content: center;
width: 24px;
height: 24px;
background: transparent;
border: 1px solid #2E2F42;
border-radius: 50%;
}

.mobile-menu-contact-list {
position: absolute;
left: 40px;
bottom: 128px;
}

.mobile-menu-contact-tel {
display: block;
font-style: normal;
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
color: #4D5AE5;
margin-bottom: 40px;
}

.mobile-menu-contact-mail {
font-style: normal;
font-weight: 500;
font-size: 20px;
line-height: 1.2;
letter-spacing: 0.02em;
color: var(--primary-text-color-light);

}

.mobile-menu-social-list {
position: absolute;
bottom: 40px;
left: 40px;
display: flex;
justify-content: center;
align-items: center;
gap: 56px;
}

.mobile-menu-social-link {
display: flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border-radius: 50%;
background-color: #4D5AE5;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.mobile-menu-social-icon {
fill: var(--primary-background-color-light);
}

}

.section {
padding-top: 96px;
padding-bottom: 96px;
}

.page-header {
padding-top: 24px;
padding-bottom: 24px;
border-bottom: 1px solid #e7e9fc;
box-shadow: 0px 2px 1px rgba(46, 47, 66, 0.08),
0px 1px 1px rgba(46, 47, 66, 0.16),
0px 1px 6px rgba(46, 47, 66, 0.08);
}

.page-header-container {
display: flex;
justify-content: space-between;
align-items: center;
}

.logo {
color: #4D5AE5;
font-family: "Raleway", sans-serif;
font-weight: 800;
font-size: 18px;
line-height: 1.17;
letter-spacing: 0.03em;
text-transform: uppercase;
text-align: center;
/_ display: inline-block; _/
}

.logo-header {
color: var(--primary-text-color-dark);
}

/_======================= MOBILE-HERO =======================_/

.hero-section {
background: var(--secondary-background-color-dark);
padding-top: 112px;
padding-bottom: 112px;
text-align: center;
background-image: linear-gradient(rgba(46, 47, 66, 0.7), rgba(46, 47, 66, 0.7)), url(../images/hero/people-office.jpg);
background-size: cover;
/_ max-width: 428px; _/
background-repeat: no-repeat;
background-position: center;
margin: 0 auto;
}

.hero-title {
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
color: var(--primary-text-color-white);
text-align: center;
max-width: 320px;
margin-left: auto;
margin-right: auto;
}

.hero-btn {
font-size: 16px;
font-style: normal;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
background: #4D5AE5;
color: var(--primary-text-color-white);
border: none;
border-radius: 4px;
min-width: 169px;
padding: 16px 32px 16px 32px;
margin-top: 48px;
display: block;
margin-left: auto;
margin-right: auto;
height: 56px;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.hero-btn:hover,
.hero-btn:focus {
background-color: var(--accent-color);
}
/_======================== MOBILE-ADVANTAGES ========================_/
.advantages-list {
display: flex;
flex-wrap: wrap;
column-gap: 24px;
row-gap: 72px;
}

.advantages-title {
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
color: var(--primary-text-color-dark);
margin-bottom: 8px;
text-align: center;  
}

.advantages-text {
font-weight: 500;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-text-color-light);
}

/_======================== MOBILE-TEAM ========================_/

.team-section {
background-color: var(--primary-background-color-light);
}

.team-main-title {
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
color: var(--primary-text-color-dark);
text-align: center;
margin-bottom: 72px;
}

.team-list {
display: flex;
flex-direction: column;
align-items: center;
padding: 0px;
gap: 72px;
}

.team-item {
flex-basis: calc((100% - 24px) / 2);
border-radius: 0px 0px 4px 4px;
box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08), 0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);

}

.team-title {
font-weight: 500;
font-size: 20px;
line-height: 1.2;
letter-spacing: 0.02em;
color: var(--primary-text-color-dark);
text-align: center;
margin-bottom: 8px;
}

.team-subtitle {
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-text-color-light);
text-align: center;
}

.team-title-box {
background-color: var(--primary-text-color-white);
padding: 32px 0;
}
/_icon_/
.social-list {
display: flex;
justify-content: center;
align-items: center;
gap: 24px;
margin-top: 8px;
}

.social-list-link {
display: flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border-radius: 50%;
background-color: #4D5AE5;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.social-list-icon {
fill: var(--primary-background-color-light);
}

.social-list-link:hover, .social-list-link:focus {
background-color: #404BBF;
}

/_======================== MOBILE-CUSTOMERS ========================_/

.customers-list {
display: flex;
}

.customers-title {
font-weight: 700;
font-size: 36px;
line-height: 1.11;
text-align: center;
letter-spacing: 0.02em;
text-transform: capitalize;
color: var(--primary-text-color-dark);
margin-bottom: 72px;
}

.customers-item {
height: 88px;
width: calc((100% - 16px) / 2);  
}

.customers-link {
display: flex;
justify-content: center;
align-items: center;
width: 190px;
height: 88px;
color: #8E8F99;
border: 1px solid #8E8F99;
border-radius: 4px;
transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.customers-icon {
fill: currentColor;
}

.customers-link:hover,
.customers-link:focus {
color: #404BBF;
border-color: #404BBF;
}

/_======================== MOBILE-FOOTER ========================_/

.page-footer {
background-color: var(--secondary-background-color-dark);
padding-top: 96px;
padding-bottom: 96px;
}

.footer-text {
width: 264px;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-background-color-light);  
}
.logo-footer {
margin-bottom: 16px;
}
.logo-footer-color {
color: var(--primary-background-color-light);
}
/_=====social=====_/

.footer-text-social {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: #FFFFFF;
margin-bottom: 16px;

}

.foter-social-list {
display: flex;
justify-content: center;
align-items: center;
gap: 16px;
margin-top: 16px;
}

.footer-social-list-link {
display: flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border-radius: 50%;
background-color: #4D5AE5;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.footer-social-list-link:hover,
.footer-social-list-link:focus {
background-color: #31D0AA;
}

.footer-social-list-icon {
fill: var(--primary-background-color-light);
}

/_======subscribe======_/

.footer-text-subscribe {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: #FFFFFF;
margin-bottom: 16px;
}

.footer-form-input {

    height: 40px;
    padding: 8px 16px;
    background-color: transparent;
    border: 1px solid #FFFFFF;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
    border-radius: 4px;
    transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1);
    line-height: 1.5;
    font-size: 12px;
    letter-spacing: 0.04em;
    color: #ffffff;

}

.footer-form-input::placeholder {
font-weight: 400;
font-size: 12px;
line-height: 2.0;
letter-spacing: 0.04em;
color: #ffffff;
}

.footer-subscribe-btn {
display: flex;
justify-content: center;
align-items: center;
min-width: 165px;
height: 40px;
padding: 8px 24px;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 1.5;
text-align: center;
letter-spacing: 0.04em;
color: #FFFFFF;
background: #4D5AE5;
border-radius: 4px;
border: none;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.footer-subscribe-btn:hover,
.footer-subscribe-btn:focus {
background-color: #404BBF
}

.footer-form-btn-icon {
margin-left: 16px;
}

/_**\*\***\*\*\*\***\*\***\_\_\_**\*\***\*\*\*\***\*\***TABLET**\*\***\*\*\*\***\*\***\_\_\_**\*\***\*\*\*\***\*\***_/

@media screen and (max-width: 1157px){

/_======================= TABLET-HEADER =======================_/
.advantages-picture-box {
display: none;
}
.product-section {
display: none;
}
.footer-container {
flex-wrap: wrap;
gap: 72px 24px;
width: 552px;
}

.customers-item {
flex-basis: calc((100% - 48px) / 3);
}
}

@media screen and (min-width: 768px)
{
.mobile-menu {
display: none;
}

.mobile-menu-open-btn {
display: none;
}

.header-nav {
display: flex;
align-items: center;
column-gap: 120px;
}

.menu {
display: flex;
gap: 40px;
}

.menu-link {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-text-color-dark);
padding: 24px 0;
transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
position: relative;
}
.current::after {
content: '';
position: absolute;
display: block;
width: 100%;
height: 4px;
background-color: var(--accent-color);
border-radius: 2px;
bottom: -1px;
}

.current {
color: var(--accent-color);
}

.menu-link:hover,
.menu-link:focus {
color: var(--accent-color);
}

.contact-link {
font-style: normal;
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: var(--primary-text-color-light);
transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.contact-link:hover,
.contact-link:focus {
color: var(--accent-color);
}
/_======================= TABLET-HERO =======================_/
.hero-section {
padding-top: 112px;
padding-bottom: 112px;
}

    .hero-title {
        font-size: 56px;
        line-height: 1.07;
        max-width: 496px;

}
/_======================== TABLET-ADVANTAGES ========================_/
.advantages-item {
flex-basis: calc((100% - 24px) / 2);
}

/_======================== TABLET-TEAM ========================_/
.team-list {
display: flex;
flex-wrap: wrap;
gap: 24px;
}

.team-item {
flex-basis: calc((100% - 24px) / 2);
border-radius: 0px 0px 4px 4px;
box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08), 0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
}

/_======================== TABLET-CUSTOMERS ========================_/

.customers-list {
column-gap: 24px;
row-gap: 72px;
}

/_ .customers-link {
width: 168px;
} _/

/_======================== TABLET-FOOTER ========================_/
.footer-container {
display: flex;
align-items: baseline;
}
.footer-form-input {
width: 264px;
}

.footer-box-text {
margin-right: 24px;
}

.footer-form {
display: flex;
gap: 24px;
}

}
/_**\*\***\*\*\*\***\*\***\_\_\_**\*\***\*\*\*\***\*\***DESKTOP**\*\***\*\*\*\***\*\***\_\_\_**\*\***\*\*\*\***\*\***_/

@media screen and (min-width: 1158px) {
.section {
padding-top: 120px;
padding-bottom: 120px;
}
/_======================= DESKTOP-HEADER =======================_/
.header-nav {
column-gap: 76px;
}

.contact-list {
display: flex;
margin-left: auto;
gap: 40px;
}

    .contact-link {
        font-size: 16px;
        line-height: 1.5;
        letter-spacing: 0.02em;

}

/_======================= DESKTOP-HERO =======================_/
.hero-section {
padding-top: 188px;
padding-bottom: 188px;
max-width: 1440px;
}

/_======================== DESKTOP-ADVANTAGES ========================_/

.advantages-picture-box {
display: flex;
justify-content: center;
align-items: center;
height: 112px;
background-color: #f4f4fd;
border-radius: 4px;
margin-bottom: 8px;
}

.advantages-picture-icon {
margin: 24px 100px;
}

.advantages-list {
gap: 24px;
}

.advantages-item {
flex-basis: calc((100% - 94px) / 4);

}
.advantages-title {
font-weight: 500;
font-size: 20px;
line-height: 1.20;
letter-spacing: 0.02em;
color: var(--primary-text-color-dark);
}

.advantages-text {
font-weight: 400;
}

/_======================== DESKTOP-PRODUCT ========================_/
.product-section {
padding-top: 0;
}

.product-list {
display: flex;
gap: 24px;
}

.product-item {
flex-basis: calc((100% - 48px) /3);
}

.product-title {
text-align: center;
font-weight: 700;
font-size: 36px;
line-height: 1.11;
letter-spacing: 0.02em;
text-transform: capitalize;
color: var(--primary-text-color-dark);
margin-bottom: 72px;
}

/_======================== DESKTOP-TEAM ========================_/
.team-item {
flex-basis: calc((100% - 72px) / 4);  
}
/_======================== DESKTOP-CUSTOMERS ========================_/
.customers-list {
gap: 24px;
display: flex;
justify-content: center;
align-items: center;
}

/_======================== DESKTOP-FOOTER ========================_/
.page-footer {
padding-top: 100px;
padding-bottom: 100px;
}

.footer-box-text {
margin-right: 120px;
}

.footer-box-social {
margin-right: 80px;
}
/\*.footer-subscribe-btn-wrapper {
position: relative;
display: block;
}

.footer-form-btn-icon {
position: absolute;
margin-left: 16px;
top: 8px;
right: 24px;

}\*/
}

/_========================= footer =========================_/

/\*

.footer-container {
display: flex;
align-items: baseline
}

.footer-box-left {
margin-right: 120px;
}

.logo-footer {
margin-bottom: 16px;
}

.page-footer {
padding-top: 100px;
padding-bottom: 100px;
}

.logo-footer-color {
color: var(--primary-background-color-light);
font-family: "Raleway", sans-serif,
}

                                              .page-footer {
                                                  background-color: var(--secondary-background-color-dark);

                                              }

.footer-text {
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-background-color-light);
max-width: 264px;
margin-bottom: 16px;

}

/_icon_/
/\* .footer-text-social {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: #FFFFFF;
margin-bottom: 16px;

}
.foter-social-list {
display: flex;
justify-content: center;
align-items: center;
gap: 16px;
margin-top: 16px;
}

.footer-social-list-link {
display: flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
border-radius: 50%;
background-color: #4D5AE5;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.footer-social-list-link:hover,
.footer-social-list-link:focus {
background-color: #31D0AA;
}

.footer-social-list-icon {
fill: var(--primary-background-color-light);
} \*/

/_ ===================Subscribe=================== _/

/\* .footer-box-social {
margin-right: 80px;
}

.footer-form {
display: flex;
gap: 24px;

}

.footer-text-subscribe {
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.02em;
color: #FFFFFF;
margin-bottom: 16px;

}

.footer-form-input {
width: 264px;
height: 40px;
padding: 8px 16px;
background-color: transparent;
border: 1px solid #FFFFFF;
filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
border-radius: 4px;
transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1);
line-height: 1.5;
font-size: 12px;
letter-spacing: 0.04em;
color: #ffffff;

}

.footer-form-input::placeholder {
font-weight: 400;
font-size: 12px;
line-height: 2.0;
letter-spacing: 0.04em;
color: #ffffff;
}

.footer-subscribe-btn {
display: flex;
justify-content: center;
align-items: center;
min-width: 165px;
height: 40px;
padding: 8px 24px;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 1.5;
text-align: center;
letter-spacing: 0.04em;
color: #FFFFFF;
background: #4D5AE5;
border-radius: 4px;
border: none;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.footer-subscribe-btn:hover,
.footer-subscribe-btn:focus {
background-color: #404BBF
}

.footer-subscribe-btn-wrapper {
position: relative;
display: block;

}

.footer-form-btn-icon {
position: absolute;
margin-left: 16px;
top: 8px;
right: 24px;

} \*/

/_======================== portfolio ========================_/

/\* .service-filter-section {
padding: 96px 0 120px;
}

.service-filter-list {
display: flex;
justify-content: center;
gap: 24px;
margin-bottom: 72px;
}

.service-filter-btn {
font-family: "Roboto", sans-serif;
font-size: 16px;
font-weight: 500;
line-height: 1.5;
letter-spacing: 0.04em;
background: var(--primary-background-color-light);
color: #4D5AE5;
border: none;
padding: 12px 24px 12px 24px;
border: 1px solid #e7e9fc;
border-radius: 4px;
transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),
background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
border-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);  
}

.service-filter-btn:hover, .service-filter-btn:focus {
background: var(--accent-color);
color:var(--primary-text-color-white);
border: 1px solid transparent;
box-shadow: 0px 2px 2px 0px #0000001F, 0px 2px 1px 0px #00000014, 0px 3px 1px 0px #0000001A;

}

.service-list {
display: flex;
flex-wrap: wrap;
column-gap: 24px;
row-gap: 48px;
}

.service-item {
flex-basis: calc((100% - 48px) / 3);
border-radius: 0px 0px 4px 4px;  
}

.service-item-link{
display: block;
transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.service-item-link:hover, .service-item-link:focus {
box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08),
0px 1px 1px rgba(46, 47, 66, 0.16),
0px 2px 1px rgba(46, 47, 66, 0.08);
transform: translateY(0%)
}

.service-list-img-wrapper {
position: relative;
overflow: hidden;
}

.overlay {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
padding: 40px 32px;
font-weight: 400;
line-height: 1.5;
letter-spacing: 0.02em;
color: #F4F4FD;
background-color: #4D5AE5;
overflow: auto;
padding: 40px 32px;
transform: translateY(100%);
transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.service-item-link:hover .overlay,
.service-item-link:focus .overlay {
transform: translateY(0%);
}

.service-title-box {
padding: 32px 16px;  
 border: 1px solid #E7E9FC;
border-top: none;
}

.service-title {
font-weight: 500;
font-size: 20px;
line-height: 1.2;
letter-spacing: 0.02em;
color: var(--primary-text-color-dark);
margin-bottom: 8px;
}

.service-subtitle {
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-text-color-light);
} \*/

/_====================backdrop====================_/

/\* .backdrop {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: rgba(46, 47, 66, 0.4);
transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1),
visibility 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal {
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
width: 408px;
min-height: 584px;
background-color: #FCFCFC;
border-radius: 4px;
box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 1px 3px rgba(0, 0, 0, 0.12),
0px 2px 1px rgba(0, 0, 0, 0.2);
transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
padding: 72px 24px 24px 24px;
}
.modal-close-btn {
position: absolute;
top: 24px;
right: 24px;
display: flex;
align-items: center;
justify-content: center;
width: 24px;
height: 24px;
padding: 0;
background-color: #E7E9FC;
border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
border 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal-close-btn:hover, .modal-close-btn:focus {
background-color: #404bbf;
border: none;
fill: #ffffff;
}

.modal-close-icon {
transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.is-hidden {
opacity: 0;
visibility: hidden;
pointer-events: none;
}

.modal-title {
font-family: 'Roboto', sans-serif;  
 font-weight: 500;
font-size: 16px;
line-height: 1.5;
text-align: center;
letter-spacing: 0.02em;
color: #2E2F42;
margin-left: auto;
margin-right: auto;
margin-bottom: 16px;
}

.contact-form-field-wrapper {
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: #8e8f99;
margin-bottom: 4px;
}

.contact-form-field-wrapper, .contact-form-checkbox-wrapper {
display: block;
}

.contact-form-wrapper {
margin-bottom: 8px;  
}

.contact-form-field-desc {
display: block;
font-weight: 400;
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: #8E8F99;
margin-bottom: 4px;
}

.contact-form-input-wrapper {
position: relative;
display: block;
}

.contact-form-input {
width: 100%;
height: 40px;
border: 1px solid rgba(46, 47, 66, 0.4);
border-radius: 4px;
padding-left: 38px;
outline: transparent;
background-color: transparent;
transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.contact-form-input:hover, .contact-form-input:focus {
outline: none;
border-color: #4D5AE5;
}

.contact-form-icon {
display: block;
position: absolute;
top: 50%;
transform: translateY(-50%);
left: 16px;
transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.contact-form-input:hover,
.contact-form-input:focus + .contact-form-icon {
fill: #4D5AE5;
}

.contact-form-comment-wrapper {
margin-bottom: 16px;
}

.contact-form-comment {
line-height: 1.17;
font-size: 12px;
letter-spacing: 0.04em;
color: rgba(46, 47, 66, 0.4);
border: 1px solid rgba(46, 47, 66, 0.2);
width: 100%;
height: 120px;
resize: none;
border-radius: 4px;
background-color: transparent;
outline: transparent;
padding: 8px 16px;
transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.contact-form-comment::placeholder {
font-weight: 400;
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: #8E8F99;
}

.contact-form-comment:hover,
.contact-form-comment:focus {
outline: none;
border-color: #4D5AE5;
}

.contact-form-policy {
margin-bottom: 24px;
}

.contact-form-checkbox-wrapper {
font-size: 12px;
line-height: 1.17;
letter-spacing: 0.04em;
color: #8e8f99;

}

.visually-hidden {
appearance: none;
position: absolute;
}

.contact-form-icon-checkbox {
width: 16px;
height: 16px;
border: 1px solid rgba(46, 47, 66, 0.4);
border-radius: 2px;
display: inline-flex;
align-items: center;
justify-content: center;
fill: transparent;
cursor: pointer;
margin-right: 8px;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
border 250ms cubic-bezier(0.4, 0, 0.2, 1),
fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.contact-form-checkbox:checked + .contact-form-checkbox-wrapper > .contact-form-icon-checkbox {

    background-color: var(--accent-color);
    border: none;
    fill: var(--primary-text-color-white);
    border-color: var(--accent-color);

}

.contact-form-checkbox-policy {
color: #4d5ae5;
}

.contact-form-btn {
display: block;
padding: 16px 32px 16px 32px;
min-width: 169px;
margin-left: auto;
margin-right: auto;
margin-top: 24px;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 1.5;
text-align: center;
letter-spacing: 0.04em;
color: #FFFFFF;
background: #4D5AE5;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
border: none;
border-radius: 4px;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

}

.contact-form-btn:hover,
.contact-form-btn:focus {
background-color: var(--accent-color);
} \*/
