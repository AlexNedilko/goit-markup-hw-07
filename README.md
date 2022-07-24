# goit-markup-hw-06

Home work mod6

old CSS
/* html {
  box-sizing: border-box;
}
*,
*::before,
*::after {
  box-sizing: inherit;
} */
/* :root {
  --header-bgd-color: #ffffff;
  --footer-bgd-color: #2f303a;
  --title-color: #212121;
  --text-color: #757575;
  --link-selection-solor: #2196f3;
} */
/* body {
  color: var(--text-color);
  font-family: "Roboto", sans-serif;
} */
/* .container {
  width: 1200px;
  margin-left: auto;
  margin-right: auto;
  padding-left: 15px;
  padding-right: 15px;
} */
/* .list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.link {
  text-decoration: none;
  color: currentColor;
}
h1,
h2,
h3,
h4,
h5,
h6,
p,
ul {
  margin-top: 0;
  margin-bottom: 0;
  padding: 0;
} */
/* .visually-hidden {
  position: absolute;
  white-space: nowrap;
  width: 1px;
  height: 1px;
  overflow: hidden;
  border: 0;
  padding: 0;
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  margin: -1px;
}
.section {
  padding-top: 94px;
  padding-bottom: 94px;
} */
/* img {
  display: block;
  max-width: 100%;
  height: auto;
} */
/* .centering {
  display: flex;
  justify-content: center;
  align-items: center;
} */
/* ------------- HEADER ----------------- */
/* .header {
  border-bottom: 1px solid #ececec;
}
.header-bar {
  display: flex;
  align-items: center;
}
.header__logo {
  margin-right: 93px;
}
.logo {
  font-family: "Raleway";
  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  letter-spacing: 0.03em;
  color: var(--link-selection-solor);
}
.logo__accent {
  color: #000000;
}
.nav-bar__list {
  display: flex;
}
.nav-bar__item {
  position: relative;
}
.nav-bar__item:not(:last-child) {
  margin-right: 50px;
}
.nav-bar__link {
  display: block;
  padding-top: 32px;
  padding-bottom: 32px;
  font-family: "Roboto";
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
  color: var(--title-color);
  transition: color var(--animation-timing-function);
}
.nav-bar__link:hover,
.nav-bar__link:focus {
  color: var(--link-selection-solor);
}
.nav-bar__link--active {
  color: var(--link-selection-solor);
}
.nav-bar__link--active::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  display: inline-block;
  width: 100%;
  height: 4px;
  background-color: #2196f3;
  border-radius: 2px;
}
.contacts {
  display: flex;
  align-items: center;
  margin-left: auto;
}
.contacts__item + .contacts__item {
  margin-left: 50px;
}
.contacts__link {
  padding-top: 32px;
  padding-bottom: 32px;
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
  transition: color;
}
.contacts__link:hover,
.contacts__link:focus {
  color: var(--link-selection-solor);
}
.contacts__icon {
  margin-right: 10px;
  fill: currentColor;
} */
/* ------------- HERO ----------------- */
/* .section-hero {
  padding: 200px 0px;
  margin-left: auto;
  margin-right: auto;
  max-width: 1600px;
  height: 600px;
  background-image: linear-gradient(
      to right,
      rgba(47, 48, 58, 0.4),
      rgba(47, 48, 58, 0.4)
    ),
    url(../images/hero-Img.jpg);
  background-color: #c4c4c4;
  text-align: center;
}
.section-hero__title {
  width: 696px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 30px;
  font-weight: 900;
  font-size: 44px;
  line-height: 1.36;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #ffffff;
} */
/* .section-hero__btn {
  padding: 10px 32px;
  min-width: 200px;
  border: 0px;
  font-family: "Roboto";
  font-weight: 700;
  font-size: 16px;
  line-height: 1.88;
  align-items: center;
  letter-spacing: 0.06em;
  color: #ffffff;
  background: var(--link-selection-solor);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  transition: background-color;
}
.section-hero__btn:hover,
.section-hero__btn:focus {
  cursor: pointer;
  background-color: #188ce8;
} */
/* ------------- SPECIALITY ----------------- */
/* .speciality__list {
  display: flex;
  justify-content: space-between;
}
.speciality__item {
  width: 270px;
  margin-right: 30px;
}
.speciality__item:last-child {
  margin-right: 0;
}
.speciality__icon-bg {
  width: 270px;
  height: 120px;
  margin-bottom: 30px;
  background: #f5f4fa;
  border-radius: 4px;
}
.speciality__title {
  margin-bottom: 10px;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--title-color);
}
.speciality__text {
  max-width: 270px;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
} */
/* ------------- DIRECTION ----------------- */
/* .work {
  padding-top: 0;
}
.work-title,
.team-title,
.clients-title {
  margin-bottom: 50px;
  font-weight: 700;
  font-size: 36px;
  line-height: 1.16;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--title-color);
}
.work-list {
  display: flex;
}
.work-item:not(:last-child) {
  margin-right: 30px;
}
.work-card {
  position: relative;
}
.about-back {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 370px;
  height: 70px;
  background: rgba(47, 48, 58, 0.8);
}
.about-text {
  font-weight: 700;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.03em;
  text-transform: uppercase;

  color: #ffffff;
} */
/* ------------- TEAM ----------------- */
/* .team {
  background-color: #f5f4fa;
}
.team-list {
  display: flex;
}
.team-item:not(:last-child) {
  margin-right: 30px;
}
.team-item {
  background: var(--header-bgd-color);
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
    0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 0px 0px 4px 4px;
}
.team-card-text {
  width: 270px;
  padding-top: 30px;
  padding-bottom: 30px;
}
.team-name {
  margin-bottom: 10px;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.18;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--title-color);
}
.team-position {
  margin-bottom: 16px;
  font-size: 16px;
  line-height: 1.18;
  text-align: center;
  letter-spacing: 0.03em;
}
.member-social {
  width: 206px;
  height: 44px;
  margin-left: auto;
  margin-right: auto;
  color: #afb1b8;
}
.member-links-list {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.member-links-list .item {
  width: 44px;
  height: 44px;
  border-radius: 50%;
}
.member-social-link {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  transition: background-color, color;
}
.member-social-link:hover,
.member-social-link:focus {
  background-color: var(--link-selection-solor);
  color: var(--header-bgd-color);
}
.member-social-icon {
  fill: currentColor;
} */
/* ------------- CLIENTS----------------- */
/* .clients-item {
  width: 170px;
  height: 92px;
  color: #afb1b8;
}
.clients-link {
  width: 100%;
  height: 100%;
  border: 1px solid #afb1b8;
  border-radius: 4px;
  transition: border-color, color;
}
.clients-item:not(:last-child) {
  margin-right: 30px;
}
.clients-link:hover,
.clients-link:focus {
  border-color: var(--link-selection-solor);
  color: var(--link-selection-solor);
}
.clients-icon {
  fill: currentColor;
} */
/* ------------- FOOTER----------------- */
/* .footer {
  display: flex;
  padding-top: 60px;
  padding-bottom: 60px;
  background-color: var(--footer-bgd-color);
}
.footer-bar {
  display: flex;
  align-items: baseline;
}
.footer-info {
  min-width: 231px;
}
.footer-info__address {
  margin-top: 20px;
  font-style: normal;
}
.footer-info__item {
  margin-bottom: 9px;
}
.footer-info__item:last-child {
  margin-bottom: 0;
}
.logo__accent--light {
  font-family: "Raleway";
  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  letter-spacing: 0.03em;
  color: var(--header-bgd-color);
}
.footer-info__map {
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: var(--header-bgd-color);
}
.footer-info__contact {
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: rgba(255, 255, 255, 0.6);
}

.company-socials {
  margin-left: 70px;
}
.company-socials__title {
  margin-bottom: 20px;
  font-family: "Roboto";
  font-weight: 700;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--header-bgd-color);
}
.company-socials__list {
  display: flex;
}
.company-socials__item:not(:last-child) {
  margin-right: 10px;
}
.company-socials__link {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  color: var(--header-bgd-color);
  background-color: rgba(255, 255, 255, 0.1);
  transition: background-color;
}
.company-socials__link:hover,
.company-socials__link:focus {
  background-color: var(--link-selection-solor);
}
.company-socials__icon {
  fill: currentColor;
}
.subscribe {
  margin-left: auto;
}
.subscribe .title {
  display: inline-block;
  margin-bottom: 20px;
  font-weight: 700;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--header-bgd-color);
}
.subscribe-mail-input {
  width: 358px;
  height: 50px;
  padding-top: 15px;
  padding-left: 16px;
  padding-bottom: 15px;
  color: var(--header-bgd-color);
  background-color: transparent;
  border: 1px solid rgba(255, 255, 255, 0.3);
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
  border-radius: 4px;
} */
/* .subscribe-btn {
  padding: 0;
  margin-left: 12px;
  min-width: 200px;
  min-height: 50px;

  font-weight: 700;
  font-size: 16px;
  line-height: 1.88;
  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.06em;
  color: var(--header-bgd-color);
  border: none;
  background-color: var(--link-selection-solor);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  cursor: pointer;
}
.subscription-icon {
  margin-left: 10px;
  fill: currentColor;
} */
/* ------------- MODAL ----------------- */
/* .backdrop {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 1;
  background-color: rgba(0, 0, 0, 0.2);
  transition: opacity;
}
.backdrop.is-hidden {
  opacity: 0;
  pointer-events: none;
}
.backdrop.is-hidden .modal {
  transform: translate(-50%, -50%) scale(0.9);
}
.modal {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) scale(1);
  padding: 40px 39px 40px 41px;
  width: 528px;
  height: 581px;
  background-color: #ffffff;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
    0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 4px;
  transition: transform;
} */
/* .modal-title {
  margin-bottom: 12px;
  font-weight: 700;
  font-size: 20px;
  line-height: 1.15;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--title-color);
}
.input-label {
  display: inline-block;
  margin-bottom: 4px;
  font-size: 12px;
  line-height: 1.16;
  letter-spacing: 0.01em;
  color: var(--text-color);
}
.input-field {
  position: relative;
  margin-bottom: 10px;
  color: var(--title-color);
}
.input-field:focus-within {
  color: var(--link-selection-solor);
}
.modal-input {
  width: 100%;
  padding-left: 42px;
  height: 40px;
  color: var(--title-color);
  border: 1px solid rgba(33, 33, 33, 0.2);
  border-radius: 4px;
  transition: color, border-color;
}
.modal-input:focus {
  border-color: var(--link-selection-solor);
  outline: none;
}
.input-icon {
  position: absolute;
  top: 50%;
  left: 21px;
  transform: translate(-50%, -50%);
  fill: currentColor;
}
.modal-input.coment:placeholder {
  font-weight: 400;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.01em;
  color: rgba(117, 117, 117, 0.5);
}
.modal-input.coment {
  margin-bottom: 20px;
  padding: 12px 16px;
  height: 120px;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.01em;
  color: rgba(117, 117, 117, 0.5);
  resize: none;
}
.check-box {
  position: absolute;
}
.accept {
  display: inline-block;
  position: relative;
  margin-left: 15px;
}
.custom-box {
  display: inline-block;
  width: 16px;
  height: 15px;
  outline: 1px solid red;
}
.icon-unchecked {
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  transition: opacity var(--animation-timing-function);
}
.icon-checked {
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  opacity: 0;
  transition: opacity var(--animation-timing-function);
}
.check-box:checked ~ .icon-checked {
  opacity: 1;
}
.check-box:checked ~ .icon-unchecked {
  opacity: 0;
}
.police-accept {
  display: inline-block;
  padding-left: 23px;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: var(--text-color);
}
.accept-accent {
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: var(--link-selection-solor);
}
.subscribe-btn.send {
  margin-top: 30px;
  margin-left: auto;
  margin-right: auto;
} */
/* .modal .close {
  position: absolute;
  top: 8px;
  right: 8px;
  width: 30px;
  height: 30px;
  background-color: #ffffff;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 50%;
  cursor: pointer;
} */
/* ------------- page 2 - FILTERS ----------------- */
/* .filters-list {
  display: flex;
  justify-content: center;
  margin-bottom: 50px;
}
.filters-item:not(:last-child) {
  margin-right: 8px;
} */
/* .filters-btn {
  padding: 6px 22px;
  font-family: inherit;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.62;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--title-color);
  background-color: #f5f4fa;
  border-radius: 4px;
  border: 0;
  transition: background-color, box-shadow, color;
}
.filters-btn:hover,
.filters-btn:focus {
  background-color: var(--link-selection-solor);
  box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 1px 2px rgba(0, 0, 0, 0.08),
    0px 2px 2px rgba(0, 0, 0, 0.12);
  color: var(--header-bgd-color);
  cursor: pointer;
} */
/* ------------- page 2 - PROJECTS CARDS ----------------- */
/* .projects-list {
  display: flex;
  flex-wrap: wrap;
}
.projects-item {
  margin-bottom: 30px;
  margin-right: 30px;
}
.projects-card-link {
  display: inline-block;
  transition: box-shadow var(--animation-timing-function);
}
.projects-card-link:hover,
.projects-card-link:focus {
  box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06),
    1px 4px 6px rgba(0, 0, 0, 0.16);
}
.projects-item:nth-child(3n) {
  margin-right: 0;
}
.projects-item:nth-last-child(-n + 3) {
  margin-bottom: 0;
}
.projects-card-text {
  width: 370px;
  padding: 20px 24px;
  border: 1px solid #eeeeee;
  border-top: 0;
  background-color: var(--header-bgd-color);
}
.projects-pic {
  display: block;
}
.projects-thumb {
  position: relative;
  overflow: hidden;
}
.card-overlay {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  background: rgba(33, 150, 243, 0.9);
  transform: translateY(100%);
  transition: transform var(--animation-timing-function);
}
.projects-card-link:hover .card-overlay {
  transform: translateY(0px);
}
.overlay-text {
  padding: 63px 24px;
  font-size: 18px;
  line-height: 1.56;
  letter-spacing: 0.03em;
  color: #ffffff;
}
.projects-item-name {
  margin-bottom: 4px;
  font-weight: 700;
  font-size: 18px;
  line-height: 2;
  letter-spacing: 0.06em;
  color: var(--title-color);
}
.projects-item-about {
  font-size: 16px;
  line-height: 1.88;
  letter-spacing: 0.03em;
} */
