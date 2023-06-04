# goit-markup-hw-01

/_ .logo-footer {
margin-bottom: 16px;
display: block;
text-align: center;
} _/

.footer-text {
margin-left: auto;
margin-right: auto;
}

.footer-text-subscribe, .footer-text-social {
text-align: center;
}

.footer-form-input {
width: 100%;
}

.footer-subscribe-btn {
margin-left: auto;
margin-right: auto;
margin-top: 16px;
}
/_======================== MOBILE-FOOTER ========================_/
.footer-container {
display: flex;
flex-direction: column;
align-items: center;
gap: 72px;
}
.page-footer {
background-color: var(--secondary-background-color-dark);
padding-top: 96px;
padding-bottom: 96px;
}

.logo-footer-color {
color: var(--primary-background-color-light);

}

.logo-footer {
margin-bottom: 16px;
display: block;
text-align: center;
}

.footer-text {
width: 264px;
line-height: 1.5;
letter-spacing: 0.02em;
color: var(--primary-background-color-light);
/_ margin-bottom: 72px; _/
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

    /* margin-top: 72px; */

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
============================================================
/_======================== TABLET-FOOTER ========================_/

.footer-container {
display: flex;
}

.footer-box-text {
margin-right: 24px;
}

.footer-form {
display: flex;
gap: 24px;
}

.footer-form-input {
width: 264px;
}
/_======================== DESKTOP-FOOTER ========================_/
.page-footer {
padding-top: 100px;
padding-bottom: 100px;
}
.footer-container {
align-items: baseline
}
.footer-box-text {
margin-right: 120px;
}

.footer-box-social {
margin-right: 80px;
}
