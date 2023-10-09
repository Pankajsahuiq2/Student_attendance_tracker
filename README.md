# Student_attendance_tracker
/*!--------------------------------------------------------------
# main.scss
#
# Sass file for Options-admin template.
# Author: SaltTechno
#
# This is compressed CSS file. You get uncompressed version of
# this file and all source scss files with download.
#
--------------------------------------------------------------*/
/*--------------------------------------------------------------
# [TABLE OF CONTENTS]
#
# 1. VARIABLES & MIXINS
# 2. TOP NAVABR
# 3. SIDEBARS
# 4. LAYOUT
# 5. PANELS
# 6. TABS
# 7. LABELS & BADGES
# 8. SECTIONS
# 9. BUTTONS
# 10. MODALS
# 11. DASHBOARD STATS
# 12. NOTIFICATIONS
# 13. PAGINATION
# 14. FORMS
# 15. ERROR PAGES
# 16. PRICING
# 17. LOGIN
# 18. DROPZONE
# 19. BOOTSTRAP SWITCH
# 20. JQUERY STEPS
# 21. DATATABLES
# 22. MISCELLANEOUS
--------------------------------------------------------------*/
/*--------------------------------------------------------------
# 1. VARIABLES & MIXINS
--------------------------------------------------------------*/
@import 'https://fonts.googleapis.com/css?family=Poppins:300,400,600';
html, body {
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  color: #494949;
  font-size: 12px;
  line-height: 1.75em;
}

@media (min-width: 600px) {
  html, body {
    font-size: calc( 12px + (14 - 12) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  html, body {
    font-size: 14px;
  }
}

h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td {
  margin: 0;
  padding: 0;
}

p, blockquote, pre,
address,
dl, ol, ul,
table {
  margin-bottom: 1.75em;
}

h1, h2, h3, h4, h5, h6, .h1, .h2, .h3, .h4, .h5, .h6 {
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  color: #292929;
  clear: both;
}

h1, .h1 {
  font-size: 27.8543898685px;
  margin-top: 0.9424008253em;
  line-height: 1.1308809903em;
  margin-bottom: 0.1884801651em;
}

@media (min-width: 600px) {
  h1, .h1 {
    font-size: calc( 27.8543898685px + (32.4967881799 - 27.8543898685) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h1, .h1 {
    font-size: 32.4967881799px;
    margin-top: 0.9424008253em;
    line-height: 1.1308809903em;
    margin-bottom: 0.1884801651em;
  }
}

h2, .h2 {
  font-size: 23.5370033519px;
  margin-top: 1.1152651681em;
  line-height: 1.3383182017em;
  margin-bottom: 0.2514831227em;
}

@media (min-width: 600px) {
  h2, .h2 {
    font-size: calc( 23.5370033519px + (27.4598372439 - 23.5370033519) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h2, .h2 {
    font-size: 27.4598372439px;
    margin-top: 1.1152651681em;
    line-height: 1.3383182017em;
    margin-bottom: 0.2474216814em;
  }
}

h3, .h3 {
  font-size: 19.888804939px;
  margin-top: 1.3198379732em;
  line-height: 1.5838055678em;
  margin-bottom: 0.3037841038em;
}

@media (min-width: 600px) {
  h3, .h3 {
    font-size: calc( 19.888804939px + (23.2036057621 - 19.888804939) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h3, .h3 {
    font-size: 23.2036057621px;
    margin-top: 1.3198379732em;
    line-height: 1.5838055678em;
    margin-bottom: 0.2980960311em;
  }
}

h4, .h4 {
  font-size: 16.8060715286px;
  margin-top: 1.5619355157em;
  line-height: 1.8743226189em;
  margin-bottom: 0.3681503615em;
}

@media (min-width: 600px) {
  h4, .h4 {
    font-size: calc( 16.8060715286px + (19.60708345 - 16.8060715286) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h4, .h4 {
    font-size: 19.60708345px;
    margin-top: 1.5619355157em;
    line-height: 1.8743226189em;
    margin-bottom: 0.3601841818em;
  }
}

h5, .h5 {
  font-size: 14.2011569368px;
  margin-top: 1.8484409486em;
  line-height: 2.2181291384em;
  margin-bottom: 0.3696881897em;
}

@media (min-width: 600px) {
  h5, .h5 {
    font-size: calc( 14.2011569368px + (16.5680164262 - 14.2011569368) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h5, .h5 {
    font-size: 16.5680164262px;
    margin-top: 1.8484409486em;
    line-height: 2.2181291384em;
    margin-bottom: 0.3696881897em;
  }
}

h6, .h6 {
  font-size: 12px;
  margin-top: 2.1875em;
  line-height: 2.625em;
  margin-bottom: 0.5104166667em;
}

@media (min-width: 600px) {
  h6, .h6 {
    font-size: calc( 12px + (14 - 12) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  h6, .h6 {
    font-size: 14px;
    margin-top: 2.1875em;
    line-height: 2.625em;
    margin-bottom: 0.4739583333em;
  }
}

blockquote {
  font-style: italic;
}

blockquote cite {
  font-style: normal;
}

pre {
  padding: 0.875em;
  margin-bottom: 1.75em;
}

pre code {
  padding: 0;
}

code {
  font-family: "Courier New", "Courier", "Lucida Sans Typewriter", "Lucida Typewriter", "monospace";
  padding: 0.0875em 0.2625em;
  line-height: 0;
}

big, small, sub, sup {
  line-height: 0;
}

abbr, acronym {
  border-bottom: 1px dotted currentColor;
  cursor: help;
}

address {
  font-style: normal;
}

dt {
  color: #292929;
  font-weight: bold;
}

ul {
  padding-left: 1.1em;
}

ol {
  padding-left: 1.4em;
}

fieldset {
  padding: 0.875em 1.75em 1.75em;
  border-width: 1px;
  border-style: solid;
  max-width: 100%;
  margin-bottom: 1.875em;
}

@media (min-width: 1140px) {
  fieldset {
    margin-bottom: 2.03125em;
  }
}

fieldset button, fieldset input[type="submit"] {
  margin-bottom: 0;
}

legend {
  color: #292929;
  font-weight: bold;
}

input[type="text"], input[type="email"], input[type="password"], input[type="date"], input[type="datetime-local"], input[type="color"], input[type="month"], input[type="time"], input[type="week"], input[type="number"], input[type="url"], input[type="search"], textarea {
  display: block;
  max-width: 100%;
  padding: 0.4375em;
  font-size: 12px;
  margin-bottom: 1.3125em;
}

@media (min-width: 600px) {
  input[type="text"], input[type="email"], input[type="password"], input[type="date"], input[type="datetime-local"], input[type="color"], input[type="month"], input[type="time"], input[type="week"], input[type="number"], input[type="url"], input[type="search"], textarea {
    font-size: calc( 12px + (14 - 12) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  input[type="text"], input[type="email"], input[type="password"], input[type="date"], input[type="datetime-local"], input[type="color"], input[type="month"], input[type="time"], input[type="week"], input[type="number"], input[type="url"], input[type="search"], textarea {
    font-size: 14px;
    margin-bottom: 0.546875em;
  }
}

input[type="submit"], button {
  /* display: block; */
  cursor: pointer;
  font-size: 12px;
  padding: 0.4375em 1.75em;
  margin-bottom: 0;
}

@media (min-width: 600px) {
  input[type="submit"], button {
    font-size: calc( 12px + (14 - 12) * ((100vw - 600px) / (1140 - 600)));
  }
}

@media (min-width: 1140px) {
  input[type="submit"], button {
    font-size: 14px;
    margin-bottom: 0;
  }
}

label {
  display: block;
  padding-bottom: 0.21875em;
  margin-bottom: -0.125em;
}

table {
  width: 100%;
  border-spacing: 0;
  border-collapse: collapse;
  margin-bottom: 2.375em;
}

@media (min-width: 1140px) {
  table {
    margin-bottom: 2.125em;
  }
}

th {
  text-align: left;
  color: #292929;
  padding: 0.21875em 0.875em;
}

@media (min-width: 1140px) {
  th {
    padding: 0.4375em 0.875em;
  }
}

td {
  padding: 0.875em;
  padding: 0.21875em 0.875em;
}

@media (min-width: 1140px) {
  td {
    padding: 0.4375em 0.875em;
  }
}

body {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  background-color: #f2f2f2;
  color: #494949;
  text-rendering: optimizeLegibility !important;
  letter-spacing: 0.5px;
  overflow-x: hidden;
}

::-moz-selection {
  background-color: #292929;
  color: #fff;
}

::selection {
  background-color: #292929;
  color: #fff;
}

a {
  outline: none !important;
  text-decoration: none !important;
  color: #494949;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

code:not(.language-html) {
  font-weight: 600;
}

/*--------------------------------------------------------------
# MIXIN TO CORRECT NAVBAR WITH OUR COLOR PALETTE
--------------------------------------------------------------*/
/*--------------------------------------------------------------
# BACKGROUND COLOR PALLETES
--------------------------------------------------------------*/
.bg-primary {
  background-color: #3498db;
  border-color: #3498db;
  color: #fff !important;
}

.bg-primary h1, .bg-primary h2, .bg-primary h3, .bg-primary h4, .bg-primary h5, .bg-primary h6 {
  color: #fff;
}

.bg-primary .nav .open > a, .bg-primary .nav .open > a:focus, .bg-primary .nav .open > a:hover {
  background-color: #258cd1;
  color: #fff !important;
}

.bg-primary .nav > li > a:focus, .bg-primary .nav > li > a:hover {
  background-color: #258cd1;
  color: #fff !important;
}

.bg-primary .navbar-nav > li > a {
  color: #fff;
}

.bg-primary.small-nav:hover .child-nav {
  background-color: #3498db;
}

.bg-primary.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #3498db;
}

.bg-primary-300 {
  background-color: #54a8e1;
  border-color: #54a8e1;
  color: #fff !important;
}

.bg-primary-300 h1, .bg-primary-300 h2, .bg-primary-300 h3, .bg-primary-300 h4, .bg-primary-300 h5, .bg-primary-300 h6 {
  color: #fff;
}

.bg-primary-300 .nav .open > a, .bg-primary-300 .nav .open > a:focus, .bg-primary-300 .nav .open > a:hover {
  background-color: #3f9ddd;
  color: #fff !important;
}

.bg-primary-300 .nav > li > a:focus, .bg-primary-300 .nav > li > a:hover {
  background-color: #3f9ddd;
  color: #fff !important;
}

.bg-primary-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-primary-300.small-nav:hover .child-nav {
  background-color: #54a8e1;
}

.bg-primary-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #54a8e1;
}

.bg-primary-100 {
  background-color: #75b9e7;
  border-color: #75b9e7;
  color: #fff !important;
}

.bg-primary-100 h1, .bg-primary-100 h2, .bg-primary-100 h3, .bg-primary-100 h4, .bg-primary-100 h5, .bg-primary-100 h6 {
  color: #fff;
}

.bg-primary-100 .nav .open > a, .bg-primary-100 .nav .open > a:focus, .bg-primary-100 .nav .open > a:hover {
  background-color: #5faee3;
  color: #fff !important;
}

.bg-primary-100 .nav > li > a:focus, .bg-primary-100 .nav > li > a:hover {
  background-color: #5faee3;
  color: #fff !important;
}

.bg-primary-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-primary-100.small-nav:hover .child-nav {
  background-color: #75b9e7;
}

.bg-primary-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #75b9e7;
}

.bg-primary-500 {
  background-color: #258cd1;
  border-color: #258cd1;
  color: #fff !important;
}

.bg-primary-500 h1, .bg-primary-500 h2, .bg-primary-500 h3, .bg-primary-500 h4, .bg-primary-500 h5, .bg-primary-500 h6 {
  color: #fff;
}

.bg-primary-500 .nav .open > a, .bg-primary-500 .nav .open > a:focus, .bg-primary-500 .nav .open > a:hover {
  background-color: #217dbb;
  color: #fff !important;
}

.bg-primary-500 .nav > li > a:focus, .bg-primary-500 .nav > li > a:hover {
  background-color: #217dbb;
  color: #fff !important;
}

.bg-primary-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-primary-500.small-nav:hover .child-nav {
  background-color: #258cd1;
}

.bg-primary-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #258cd1;
}

.bg-primary-600 {
  background-color: #217dbb;
  border-color: #217dbb;
  color: #fff !important;
}

.bg-primary-600 h1, .bg-primary-600 h2, .bg-primary-600 h3, .bg-primary-600 h4, .bg-primary-600 h5, .bg-primary-600 h6 {
  color: #fff;
}

.bg-primary-600 .nav .open > a, .bg-primary-600 .nav .open > a:focus, .bg-primary-600 .nav .open > a:hover {
  background-color: #1d6fa5;
  color: #fff !important;
}

.bg-primary-600 .nav > li > a:focus, .bg-primary-600 .nav > li > a:hover {
  background-color: #1d6fa5;
  color: #fff !important;
}

.bg-primary-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-primary-600.small-nav:hover .child-nav {
  background-color: #217dbb;
}

.bg-primary-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #217dbb;
}

.bg-primary-700 {
  background-color: #1d6fa5;
  border-color: #1d6fa5;
  color: #fff !important;
}

.bg-primary-700 h1, .bg-primary-700 h2, .bg-primary-700 h3, .bg-primary-700 h4, .bg-primary-700 h5, .bg-primary-700 h6 {
  color: #fff;
}

.bg-primary-700 .nav .open > a, .bg-primary-700 .nav .open > a:focus, .bg-primary-700 .nav .open > a:hover {
  background-color: #196090;
  color: #fff !important;
}

.bg-primary-700 .nav > li > a:focus, .bg-primary-700 .nav > li > a:hover {
  background-color: #196090;
  color: #fff !important;
}

.bg-primary-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-primary-700.small-nav:hover .child-nav {
  background-color: #1d6fa5;
}

.bg-primary-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #1d6fa5;
}

.bg-danger {
  background-color: #e74c3c;
  border-color: #e74c3c;
  color: #fff !important;
}

.bg-danger h1, .bg-danger h2, .bg-danger h3, .bg-danger h4, .bg-danger h5, .bg-danger h6 {
  color: #fff;
}

.bg-danger .nav .open > a, .bg-danger .nav .open > a:focus, .bg-danger .nav .open > a:hover {
  background-color: #e43725;
  color: #fff !important;
}

.bg-danger .nav > li > a:focus, .bg-danger .nav > li > a:hover {
  background-color: #e43725;
  color: #fff !important;
}

.bg-danger .navbar-nav > li > a {
  color: #fff;
}

.bg-danger.small-nav:hover .child-nav {
  background-color: #e74c3c;
}

.bg-danger.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #e74c3c;
}

.bg-danger-300 {
  background-color: #eb6b5e;
  border-color: #eb6b5e;
  color: #fff !important;
}

.bg-danger-300 h1, .bg-danger-300 h2, .bg-danger-300 h3, .bg-danger-300 h4, .bg-danger-300 h5, .bg-danger-300 h6 {
  color: #fff;
}

.bg-danger-300 .nav .open > a, .bg-danger-300 .nav .open > a:focus, .bg-danger-300 .nav .open > a:hover {
  background-color: #e85647;
  color: #fff !important;
}

.bg-danger-300 .nav > li > a:focus, .bg-danger-300 .nav > li > a:hover {
  background-color: #e85647;
  color: #fff !important;
}

.bg-danger-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-danger-300.small-nav:hover .child-nav {
  background-color: #eb6b5e;
}

.bg-danger-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #eb6b5e;
}

.bg-danger-100 {
  background-color: #ef8b80;
  border-color: #ef8b80;
  color: #fff !important;
}

.bg-danger-100 h1, .bg-danger-100 h2, .bg-danger-100 h3, .bg-danger-100 h4, .bg-danger-100 h5, .bg-danger-100 h6 {
  color: #fff;
}

.bg-danger-100 .nav .open > a, .bg-danger-100 .nav .open > a:focus, .bg-danger-100 .nav .open > a:hover {
  background-color: #ed7669;
  color: #fff !important;
}

.bg-danger-100 .nav > li > a:focus, .bg-danger-100 .nav > li > a:hover {
  background-color: #ed7669;
  color: #fff !important;
}

.bg-danger-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-danger-100.small-nav:hover .child-nav {
  background-color: #ef8b80;
}

.bg-danger-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #ef8b80;
}

.bg-danger-500 {
  background-color: #e43725;
  border-color: #e43725;
  color: #fff !important;
}

.bg-danger-500 h1, .bg-danger-500 h2, .bg-danger-500 h3, .bg-danger-500 h4, .bg-danger-500 h5, .bg-danger-500 h6 {
  color: #fff;
}

.bg-danger-500 .nav .open > a, .bg-danger-500 .nav .open > a:focus, .bg-danger-500 .nav .open > a:hover {
  background-color: #d62c1a;
  color: #fff !important;
}

.bg-danger-500 .nav > li > a:focus, .bg-danger-500 .nav > li > a:hover {
  background-color: #d62c1a;
  color: #fff !important;
}

.bg-danger-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-danger-500.small-nav:hover .child-nav {
  background-color: #e43725;
}

.bg-danger-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #e43725;
}

.bg-danger-600 {
  background-color: #d62c1a;
  border-color: #d62c1a;
  color: #fff !important;
}

.bg-danger-600 h1, .bg-danger-600 h2, .bg-danger-600 h3, .bg-danger-600 h4, .bg-danger-600 h5, .bg-danger-600 h6 {
  color: #fff;
}

.bg-danger-600 .nav .open > a, .bg-danger-600 .nav .open > a:focus, .bg-danger-600 .nav .open > a:hover {
  background-color: #bf2718;
  color: #fff !important;
}

.bg-danger-600 .nav > li > a:focus, .bg-danger-600 .nav > li > a:hover {
  background-color: #bf2718;
  color: #fff !important;
}

.bg-danger-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-danger-600.small-nav:hover .child-nav {
  background-color: #d62c1a;
}

.bg-danger-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #d62c1a;
}

.bg-danger-700 {
  background-color: #bf2718;
  border-color: #bf2718;
  color: #fff !important;
}

.bg-danger-700 h1, .bg-danger-700 h2, .bg-danger-700 h3, .bg-danger-700 h4, .bg-danger-700 h5, .bg-danger-700 h6 {
  color: #fff;
}

.bg-danger-700 .nav .open > a, .bg-danger-700 .nav .open > a:focus, .bg-danger-700 .nav .open > a:hover {
  background-color: #a82315;
  color: #fff !important;
}

.bg-danger-700 .nav > li > a:focus, .bg-danger-700 .nav > li > a:hover {
  background-color: #a82315;
  color: #fff !important;
}

.bg-danger-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-danger-700.small-nav:hover .child-nav {
  background-color: #bf2718;
}

.bg-danger-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #bf2718;
}

.bg-success {
  background-color: #27ae60;
  border-color: #27ae60;
  color: #fff !important;
}

.bg-success h1, .bg-success h2, .bg-success h3, .bg-success h4, .bg-success h5, .bg-success h6 {
  color: #fff;
}

.bg-success .nav .open > a, .bg-success .nav .open > a:focus, .bg-success .nav .open > a:hover {
  background-color: #229955;
  color: #fff !important;
}

.bg-success .nav > li > a:focus, .bg-success .nav > li > a:hover {
  background-color: #229955;
  color: #fff !important;
}

.bg-success .navbar-nav > li > a {
  color: #fff;
}

.bg-success.small-nav:hover .child-nav {
  background-color: #27ae60;
}

.bg-success.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #27ae60;
}

.bg-success-300 {
  background-color: #2ecd71;
  border-color: #2ecd71;
  color: #fff !important;
}

.bg-success-300 h1, .bg-success-300 h2, .bg-success-300 h3, .bg-success-300 h4, .bg-success-300 h5, .bg-success-300 h6 {
  color: #fff;
}

.bg-success-300 .nav .open > a, .bg-success-300 .nav .open > a:focus, .bg-success-300 .nav .open > a:hover {
  background-color: #29b866;
  color: #fff !important;
}

.bg-success-300 .nav > li > a:focus, .bg-success-300 .nav > li > a:hover {
  background-color: #29b866;
  color: #fff !important;
}

.bg-success-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-success-300.small-nav:hover .child-nav {
  background-color: #2ecd71;
}

.bg-success-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #2ecd71;
}

.bg-success-100 {
  background-color: #4bd786;
  border-color: #4bd786;
  color: #fff !important;
}

.bg-success-100 h1, .bg-success-100 h2, .bg-success-100 h3, .bg-success-100 h4, .bg-success-100 h5, .bg-success-100 h6 {
  color: #fff;
}

.bg-success-100 .nav .open > a, .bg-success-100 .nav .open > a:focus, .bg-success-100 .nav .open > a:hover {
  background-color: #36d278;
  color: #fff !important;
}

.bg-success-100 .nav > li > a:focus, .bg-success-100 .nav > li > a:hover {
  background-color: #36d278;
  color: #fff !important;
}

.bg-success-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-success-100.small-nav:hover .child-nav {
  background-color: #4bd786;
}

.bg-success-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #4bd786;
}

.bg-success-500 {
  background-color: #229955;
  border-color: #229955;
  color: #fff !important;
}

.bg-success-500 h1, .bg-success-500 h2, .bg-success-500 h3, .bg-success-500 h4, .bg-success-500 h5, .bg-success-500 h6 {
  color: #fff;
}

.bg-success-500 .nav .open > a, .bg-success-500 .nav .open > a:focus, .bg-success-500 .nav .open > a:hover {
  background-color: #1e8449;
  color: #fff !important;
}

.bg-success-500 .nav > li > a:focus, .bg-success-500 .nav > li > a:hover {
  background-color: #1e8449;
  color: #fff !important;
}

.bg-success-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-success-500.small-nav:hover .child-nav {
  background-color: #229955;
}

.bg-success-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #229955;
}

.bg-success-600 {
  background-color: #1e8449;
  border-color: #1e8449;
  color: #fff !important;
}

.bg-success-600 h1, .bg-success-600 h2, .bg-success-600 h3, .bg-success-600 h4, .bg-success-600 h5, .bg-success-600 h6 {
  color: #fff;
}

.bg-success-600 .nav .open > a, .bg-success-600 .nav .open > a:focus, .bg-success-600 .nav .open > a:hover {
  background-color: #19703e;
  color: #fff !important;
}

.bg-success-600 .nav > li > a:focus, .bg-success-600 .nav > li > a:hover {
  background-color: #19703e;
  color: #fff !important;
}

.bg-success-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-success-600.small-nav:hover .child-nav {
  background-color: #1e8449;
}

.bg-success-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #1e8449;
}

.bg-success-700 {
  background-color: #19703e;
  border-color: #19703e;
  color: #fff !important;
}

.bg-success-700 h1, .bg-success-700 h2, .bg-success-700 h3, .bg-success-700 h4, .bg-success-700 h5, .bg-success-700 h6 {
  color: #fff;
}

.bg-success-700 .nav .open > a, .bg-success-700 .nav .open > a:focus, .bg-success-700 .nav .open > a:hover {
  background-color: #145b32;
  color: #fff !important;
}

.bg-success-700 .nav > li > a:focus, .bg-success-700 .nav > li > a:hover {
  background-color: #145b32;
  color: #fff !important;
}

.bg-success-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-success-700.small-nav:hover .child-nav {
  background-color: #19703e;
}

.bg-success-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #19703e;
}

.bg-warning {
  background-color: #f39c12;
  border-color: #f39c12;
  color: #fff !important;
}

.bg-warning h1, .bg-warning h2, .bg-warning h3, .bg-warning h4, .bg-warning h5, .bg-warning h6 {
  color: #fff;
}

.bg-warning .nav .open > a, .bg-warning .nav .open > a:focus, .bg-warning .nav .open > a:hover {
  background-color: #e08e0b;
  color: #fff !important;
}

.bg-warning .nav > li > a:focus, .bg-warning .nav > li > a:hover {
  background-color: #e08e0b;
  color: #fff !important;
}

.bg-warning .navbar-nav > li > a {
  color: #fff;
}

.bg-warning.small-nav:hover .child-nav {
  background-color: #f39c12;
}

.bg-warning.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #f39c12;
}

.bg-warning-300 {
  background-color: #f5ab36;
  border-color: #f5ab36;
  color: #fff !important;
}

.bg-warning-300 h1, .bg-warning-300 h2, .bg-warning-300 h3, .bg-warning-300 h4, .bg-warning-300 h5, .bg-warning-300 h6 {
  color: #fff;
}

.bg-warning-300 .nav .open > a, .bg-warning-300 .nav .open > a:focus, .bg-warning-300 .nav .open > a:hover {
  background-color: #f4a11e;
  color: #fff !important;
}

.bg-warning-300 .nav > li > a:focus, .bg-warning-300 .nav > li > a:hover {
  background-color: #f4a11e;
  color: #fff !important;
}

.bg-warning-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-warning-300.small-nav:hover .child-nav {
  background-color: #f5ab36;
}

.bg-warning-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #f5ab36;
}

.bg-warning-100 {
  background-color: #f7ba5b;
  border-color: #f7ba5b;
  color: #fff !important;
}

.bg-warning-100 h1, .bg-warning-100 h2, .bg-warning-100 h3, .bg-warning-100 h4, .bg-warning-100 h5, .bg-warning-100 h6 {
  color: #fff;
}

.bg-warning-100 .nav .open > a, .bg-warning-100 .nav .open > a:focus, .bg-warning-100 .nav .open > a:hover {
  background-color: #f5b043;
  color: #fff !important;
}

.bg-warning-100 .nav > li > a:focus, .bg-warning-100 .nav > li > a:hover {
  background-color: #f5b043;
  color: #fff !important;
}

.bg-warning-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-warning-100.small-nav:hover .child-nav {
  background-color: #f7ba5b;
}

.bg-warning-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #f7ba5b;
}

.bg-warning-500 {
  background-color: #e08e0b;
  border-color: #e08e0b;
  color: #fff !important;
}

.bg-warning-500 h1, .bg-warning-500 h2, .bg-warning-500 h3, .bg-warning-500 h4, .bg-warning-500 h5, .bg-warning-500 h6 {
  color: #fff;
}

.bg-warning-500 .nav .open > a, .bg-warning-500 .nav .open > a:focus, .bg-warning-500 .nav .open > a:hover {
  background-color: #c87f0a;
  color: #fff !important;
}

.bg-warning-500 .nav > li > a:focus, .bg-warning-500 .nav > li > a:hover {
  background-color: #c87f0a;
  color: #fff !important;
}

.bg-warning-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-warning-500.small-nav:hover .child-nav {
  background-color: #e08e0b;
}

.bg-warning-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #e08e0b;
}

.bg-warning-600 {
  background-color: #c87f0a;
  border-color: #c87f0a;
  color: #fff !important;
}

.bg-warning-600 h1, .bg-warning-600 h2, .bg-warning-600 h3, .bg-warning-600 h4, .bg-warning-600 h5, .bg-warning-600 h6 {
  color: #fff;
}

.bg-warning-600 .nav .open > a, .bg-warning-600 .nav .open > a:focus, .bg-warning-600 .nav .open > a:hover {
  background-color: #b06f09;
  color: #fff !important;
}

.bg-warning-600 .nav > li > a:focus, .bg-warning-600 .nav > li > a:hover {
  background-color: #b06f09;
  color: #fff !important;
}

.bg-warning-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-warning-600.small-nav:hover .child-nav {
  background-color: #c87f0a;
}

.bg-warning-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #c87f0a;
}

.bg-warning-700 {
  background-color: #b06f09;
  border-color: #b06f09;
  color: #fff !important;
}

.bg-warning-700 h1, .bg-warning-700 h2, .bg-warning-700 h3, .bg-warning-700 h4, .bg-warning-700 h5, .bg-warning-700 h6 {
  color: #fff;
}

.bg-warning-700 .nav .open > a, .bg-warning-700 .nav .open > a:focus, .bg-warning-700 .nav .open > a:hover {
  background-color: #976008;
  color: #fff !important;
}

.bg-warning-700 .nav > li > a:focus, .bg-warning-700 .nav > li > a:hover {
  background-color: #976008;
  color: #fff !important;
}

.bg-warning-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-warning-700.small-nav:hover .child-nav {
  background-color: #b06f09;
}

.bg-warning-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #b06f09;
}

.bg-info {
  background-color: #5bc0de;
  border-color: #5bc0de;
  color: #fff !important;
}

.bg-info h1, .bg-info h2, .bg-info h3, .bg-info h4, .bg-info h5, .bg-info h6 {
  color: #fff;
}

.bg-info .nav .open > a, .bg-info .nav .open > a:focus, .bg-info .nav .open > a:hover {
  background-color: #46b8da;
  color: #fff !important;
}

.bg-info .nav > li > a:focus, .bg-info .nav > li > a:hover {
  background-color: #46b8da;
  color: #fff !important;
}

.bg-info .navbar-nav > li > a {
  color: #fff;
}

.bg-info.small-nav:hover .child-nav {
  background-color: #5bc0de;
}

.bg-info.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #5bc0de;
}

.bg-info-300 {
  background-color: #7bcce4;
  border-color: #7bcce4;
  color: #fff !important;
}

.bg-info-300 h1, .bg-info-300 h2, .bg-info-300 h3, .bg-info-300 h4, .bg-info-300 h5, .bg-info-300 h6 {
  color: #fff;
}

.bg-info-300 .nav .open > a, .bg-info-300 .nav .open > a:focus, .bg-info-300 .nav .open > a:hover {
  background-color: #66c4e0;
  color: #fff !important;
}

.bg-info-300 .nav > li > a:focus, .bg-info-300 .nav > li > a:hover {
  background-color: #66c4e0;
  color: #fff !important;
}

.bg-info-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-info-300.small-nav:hover .child-nav {
  background-color: #7bcce4;
}

.bg-info-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #7bcce4;
}

.bg-info-100 {
  background-color: #9bd8eb;
  border-color: #9bd8eb;
  color: #fff !important;
}

.bg-info-100 h1, .bg-info-100 h2, .bg-info-100 h3, .bg-info-100 h4, .bg-info-100 h5, .bg-info-100 h6 {
  color: #fff;
}

.bg-info-100 .nav .open > a, .bg-info-100 .nav .open > a:focus, .bg-info-100 .nav .open > a:hover {
  background-color: #85d0e7;
  color: #fff !important;
}

.bg-info-100 .nav > li > a:focus, .bg-info-100 .nav > li > a:hover {
  background-color: #85d0e7;
  color: #fff !important;
}

.bg-info-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-info-100.small-nav:hover .child-nav {
  background-color: #9bd8eb;
}

.bg-info-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #9bd8eb;
}

.bg-info-500 {
  background-color: #46b8da;
  border-color: #46b8da;
  color: #fff !important;
}

.bg-info-500 h1, .bg-info-500 h2, .bg-info-500 h3, .bg-info-500 h4, .bg-info-500 h5, .bg-info-500 h6 {
  color: #fff;
}

.bg-info-500 .nav .open > a, .bg-info-500 .nav .open > a:focus, .bg-info-500 .nav .open > a:hover {
  background-color: #31b0d5;
  color: #fff !important;
}

.bg-info-500 .nav > li > a:focus, .bg-info-500 .nav > li > a:hover {
  background-color: #31b0d5;
  color: #fff !important;
}

.bg-info-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-info-500.small-nav:hover .child-nav {
  background-color: #46b8da;
}

.bg-info-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #46b8da;
}

.bg-info-600 {
  background-color: #31b0d5;
  border-color: #31b0d5;
  color: #fff !important;
}

.bg-info-600 h1, .bg-info-600 h2, .bg-info-600 h3, .bg-info-600 h4, .bg-info-600 h5, .bg-info-600 h6 {
  color: #fff;
}

.bg-info-600 .nav .open > a, .bg-info-600 .nav .open > a:focus, .bg-info-600 .nav .open > a:hover {
  background-color: #28a1c5;
  color: #fff !important;
}

.bg-info-600 .nav > li > a:focus, .bg-info-600 .nav > li > a:hover {
  background-color: #28a1c5;
  color: #fff !important;
}

.bg-info-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-info-600.small-nav:hover .child-nav {
  background-color: #31b0d5;
}

.bg-info-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #31b0d5;
}

.bg-info-700 {
  background-color: #28a1c5;
  border-color: #28a1c5;
  color: #fff !important;
}

.bg-info-700 h1, .bg-info-700 h2, .bg-info-700 h3, .bg-info-700 h4, .bg-info-700 h5, .bg-info-700 h6 {
  color: #fff;
}

.bg-info-700 .nav .open > a, .bg-info-700 .nav .open > a:focus, .bg-info-700 .nav .open > a:hover {
  background-color: #2390b0;
  color: #fff !important;
}

.bg-info-700 .nav > li > a:focus, .bg-info-700 .nav > li > a:hover {
  background-color: #2390b0;
  color: #fff !important;
}

.bg-info-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-info-700.small-nav:hover .child-nav {
  background-color: #28a1c5;
}

.bg-info-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #28a1c5;
}

.bg-black {
  background-color: #292929;
  border-color: #292929;
  color: #fff !important;
}

.bg-black h1, .bg-black h2, .bg-black h3, .bg-black h4, .bg-black h5, .bg-black h6 {
  color: #fff;
}

.bg-black .nav .open > a, .bg-black .nav .open > a:focus, .bg-black .nav .open > a:hover {
  background-color: #1c1c1c;
  color: #fff !important;
}

.bg-black .nav > li > a:focus, .bg-black .nav > li > a:hover {
  background-color: #1c1c1c;
  color: #fff !important;
}

.bg-black .navbar-nav > li > a {
  color: #fff;
}

.bg-black.small-nav:hover .child-nav {
  background-color: #292929;
}

.bg-black.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #292929;
}

.bg-black-300 {
  background-color: #3c3c3c;
  border-color: #3c3c3c;
  color: #fff !important;
}

.bg-black-300 h1, .bg-black-300 h2, .bg-black-300 h3, .bg-black-300 h4, .bg-black-300 h5, .bg-black-300 h6 {
  color: #fff;
}

.bg-black-300 .nav .open > a, .bg-black-300 .nav .open > a:focus, .bg-black-300 .nav .open > a:hover {
  background-color: #2f2f2f;
  color: #fff !important;
}

.bg-black-300 .nav > li > a:focus, .bg-black-300 .nav > li > a:hover {
  background-color: #2f2f2f;
  color: #fff !important;
}

.bg-black-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-black-300.small-nav:hover .child-nav {
  background-color: #3c3c3c;
}

.bg-black-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #3c3c3c;
}

.bg-black-100 {
  background-color: #4f4f4f;
  border-color: #4f4f4f;
  color: #fff !important;
}

.bg-black-100 h1, .bg-black-100 h2, .bg-black-100 h3, .bg-black-100 h4, .bg-black-100 h5, .bg-black-100 h6 {
  color: #fff;
}

.bg-black-100 .nav .open > a, .bg-black-100 .nav .open > a:focus, .bg-black-100 .nav .open > a:hover {
  background-color: #434343;
  color: #fff !important;
}

.bg-black-100 .nav > li > a:focus, .bg-black-100 .nav > li > a:hover {
  background-color: #434343;
  color: #fff !important;
}

.bg-black-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-black-100.small-nav:hover .child-nav {
  background-color: #4f4f4f;
}

.bg-black-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #4f4f4f;
}

.bg-black-500 {
  background-color: #1c1c1c;
  border-color: #1c1c1c;
  color: #fff !important;
}

.bg-black-500 h1, .bg-black-500 h2, .bg-black-500 h3, .bg-black-500 h4, .bg-black-500 h5, .bg-black-500 h6 {
  color: #fff;
}

.bg-black-500 .nav .open > a, .bg-black-500 .nav .open > a:focus, .bg-black-500 .nav .open > a:hover {
  background-color: #101010;
  color: #fff !important;
}

.bg-black-500 .nav > li > a:focus, .bg-black-500 .nav > li > a:hover {
  background-color: #101010;
  color: #fff !important;
}

.bg-black-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-black-500.small-nav:hover .child-nav {
  background-color: #1c1c1c;
}

.bg-black-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #1c1c1c;
}

.bg-black-600 {
  background-color: #101010;
  border-color: #101010;
  color: #fff !important;
}

.bg-black-600 h1, .bg-black-600 h2, .bg-black-600 h3, .bg-black-600 h4, .bg-black-600 h5, .bg-black-600 h6 {
  color: #fff;
}

.bg-black-600 .nav .open > a, .bg-black-600 .nav .open > a:focus, .bg-black-600 .nav .open > a:hover {
  background-color: #030303;
  color: #fff !important;
}

.bg-black-600 .nav > li > a:focus, .bg-black-600 .nav > li > a:hover {
  background-color: #030303;
  color: #fff !important;
}

.bg-black-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-black-600.small-nav:hover .child-nav {
  background-color: #101010;
}

.bg-black-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #101010;
}

.bg-black-700 {
  background-color: #030303;
  border-color: #030303;
  color: #fff !important;
}

.bg-black-700 h1, .bg-black-700 h2, .bg-black-700 h3, .bg-black-700 h4, .bg-black-700 h5, .bg-black-700 h6 {
  color: #fff;
}

.bg-black-700 .nav .open > a, .bg-black-700 .nav .open > a:focus, .bg-black-700 .nav .open > a:hover {
  background-color: black;
  color: #fff !important;
}

.bg-black-700 .nav > li > a:focus, .bg-black-700 .nav > li > a:hover {
  background-color: black;
  color: #fff !important;
}

.bg-black-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-black-700.small-nav:hover .child-nav {
  background-color: #030303;
}

.bg-black-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #030303;
}

.bg-light-black {
  background-color: #494949;
  border-color: #494949;
  color: #fff !important;
}

.bg-light-black h1, .bg-light-black h2, .bg-light-black h3, .bg-light-black h4, .bg-light-black h5, .bg-light-black h6 {
  color: #fff;
}

.bg-light-black .nav .open > a, .bg-light-black .nav .open > a:focus, .bg-light-black .nav .open > a:hover {
  background-color: #3c3c3c;
  color: #fff !important;
}

.bg-light-black .nav > li > a:focus, .bg-light-black .nav > li > a:hover {
  background-color: #3c3c3c;
  color: #fff !important;
}

.bg-light-black .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black.small-nav:hover .child-nav {
  background-color: #494949;
}

.bg-light-black.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #494949;
}

.bg-light-black-300 {
  background-color: #5c5c5c;
  border-color: #5c5c5c;
  color: #fff !important;
}

.bg-light-black-300 h1, .bg-light-black-300 h2, .bg-light-black-300 h3, .bg-light-black-300 h4, .bg-light-black-300 h5, .bg-light-black-300 h6 {
  color: #fff;
}

.bg-light-black-300 .nav .open > a, .bg-light-black-300 .nav .open > a:focus, .bg-light-black-300 .nav .open > a:hover {
  background-color: #4f4f4f;
  color: #fff !important;
}

.bg-light-black-300 .nav > li > a:focus, .bg-light-black-300 .nav > li > a:hover {
  background-color: #4f4f4f;
  color: #fff !important;
}

.bg-light-black-300 .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black-300.small-nav:hover .child-nav {
  background-color: #5c5c5c;
}

.bg-light-black-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #5c5c5c;
}

.bg-light-black-100 {
  background-color: #6f6f6f;
  border-color: #6f6f6f;
  color: #fff !important;
}

.bg-light-black-100 h1, .bg-light-black-100 h2, .bg-light-black-100 h3, .bg-light-black-100 h4, .bg-light-black-100 h5, .bg-light-black-100 h6 {
  color: #fff;
}

.bg-light-black-100 .nav .open > a, .bg-light-black-100 .nav .open > a:focus, .bg-light-black-100 .nav .open > a:hover {
  background-color: #636363;
  color: #fff !important;
}

.bg-light-black-100 .nav > li > a:focus, .bg-light-black-100 .nav > li > a:hover {
  background-color: #636363;
  color: #fff !important;
}

.bg-light-black-100 .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black-100.small-nav:hover .child-nav {
  background-color: #6f6f6f;
}

.bg-light-black-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #6f6f6f;
}

.bg-light-black-500 {
  background-color: #3c3c3c;
  border-color: #3c3c3c;
  color: #fff !important;
}

.bg-light-black-500 h1, .bg-light-black-500 h2, .bg-light-black-500 h3, .bg-light-black-500 h4, .bg-light-black-500 h5, .bg-light-black-500 h6 {
  color: #fff;
}

.bg-light-black-500 .nav .open > a, .bg-light-black-500 .nav .open > a:focus, .bg-light-black-500 .nav .open > a:hover {
  background-color: #303030;
  color: #fff !important;
}

.bg-light-black-500 .nav > li > a:focus, .bg-light-black-500 .nav > li > a:hover {
  background-color: #303030;
  color: #fff !important;
}

.bg-light-black-500 .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black-500.small-nav:hover .child-nav {
  background-color: #3c3c3c;
}

.bg-light-black-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #3c3c3c;
}

.bg-light-black-600 {
  background-color: #303030;
  border-color: #303030;
  color: #fff !important;
}

.bg-light-black-600 h1, .bg-light-black-600 h2, .bg-light-black-600 h3, .bg-light-black-600 h4, .bg-light-black-600 h5, .bg-light-black-600 h6 {
  color: #fff;
}

.bg-light-black-600 .nav .open > a, .bg-light-black-600 .nav .open > a:focus, .bg-light-black-600 .nav .open > a:hover {
  background-color: #232323;
  color: #fff !important;
}

.bg-light-black-600 .nav > li > a:focus, .bg-light-black-600 .nav > li > a:hover {
  background-color: #232323;
  color: #fff !important;
}

.bg-light-black-600 .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black-600.small-nav:hover .child-nav {
  background-color: #303030;
}

.bg-light-black-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #303030;
}

.bg-light-black-700 {
  background-color: #232323;
  border-color: #232323;
  color: #fff !important;
}

.bg-light-black-700 h1, .bg-light-black-700 h2, .bg-light-black-700 h3, .bg-light-black-700 h4, .bg-light-black-700 h5, .bg-light-black-700 h6 {
  color: #fff;
}

.bg-light-black-700 .nav .open > a, .bg-light-black-700 .nav .open > a:focus, .bg-light-black-700 .nav .open > a:hover {
  background-color: #161616;
  color: #fff !important;
}

.bg-light-black-700 .nav > li > a:focus, .bg-light-black-700 .nav > li > a:hover {
  background-color: #161616;
  color: #fff !important;
}

.bg-light-black-700 .navbar-nav > li > a {
  color: #fff;
}

.bg-light-black-700.small-nav:hover .child-nav {
  background-color: #232323;
}

.bg-light-black-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #232323;
}

.bg-gray {
  background-color: #f2f2f2;
  border-color: #f2f2f2;
  color: #494949 !important;
}

.bg-gray h1, .bg-gray h2, .bg-gray h3, .bg-gray h4, .bg-gray h5, .bg-gray h6 {
  color: #494949;
}

.bg-gray .nav .open > a, .bg-gray .nav .open > a:focus, .bg-gray .nav .open > a:hover {
  background-color: #e5e5e5;
  color: #494949 !important;
}

.bg-gray .nav > li > a:focus, .bg-gray .nav > li > a:hover {
  background-color: #e5e5e5;
  color: #494949 !important;
}

.bg-gray .navbar-nav > li > a {
  color: #494949;
}

.bg-gray.small-nav:hover .child-nav {
  background-color: #f2f2f2;
}

.bg-gray.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #f2f2f2;
}

.bg-gray-300 {
  background-color: white;
  border-color: white;
  color: #494949 !important;
}

.bg-gray-300 h1, .bg-gray-300 h2, .bg-gray-300 h3, .bg-gray-300 h4, .bg-gray-300 h5, .bg-gray-300 h6 {
  color: #494949;
}

.bg-gray-300 .nav .open > a, .bg-gray-300 .nav .open > a:focus, .bg-gray-300 .nav .open > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-gray-300 .nav > li > a:focus, .bg-gray-300 .nav > li > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-gray-300 .navbar-nav > li > a {
  color: #494949;
}

.bg-gray-300.small-nav:hover .child-nav {
  background-color: white;
}

.bg-gray-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: white;
}

.bg-gray-100 {
  background-color: white;
  border-color: white;
  color: #494949 !important;
}

.bg-gray-100 h1, .bg-gray-100 h2, .bg-gray-100 h3, .bg-gray-100 h4, .bg-gray-100 h5, .bg-gray-100 h6 {
  color: #494949;
}

.bg-gray-100 .nav .open > a, .bg-gray-100 .nav .open > a:focus, .bg-gray-100 .nav .open > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-gray-100 .nav > li > a:focus, .bg-gray-100 .nav > li > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-gray-100 .navbar-nav > li > a {
  color: #494949;
}

.bg-gray-100.small-nav:hover .child-nav {
  background-color: white;
}

.bg-gray-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: white;
}

.bg-gray-500 {
  background-color: #e5e5e5;
  border-color: #e5e5e5;
  color: #494949 !important;
}

.bg-gray-500 h1, .bg-gray-500 h2, .bg-gray-500 h3, .bg-gray-500 h4, .bg-gray-500 h5, .bg-gray-500 h6 {
  color: #494949;
}

.bg-gray-500 .nav .open > a, .bg-gray-500 .nav .open > a:focus, .bg-gray-500 .nav .open > a:hover {
  background-color: #d9d9d9;
  color: #494949 !important;
}

.bg-gray-500 .nav > li > a:focus, .bg-gray-500 .nav > li > a:hover {
  background-color: #d9d9d9;
  color: #494949 !important;
}

.bg-gray-500 .navbar-nav > li > a {
  color: #494949;
}

.bg-gray-500.small-nav:hover .child-nav {
  background-color: #e5e5e5;
}

.bg-gray-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #e5e5e5;
}

.bg-gray-600 {
  background-color: #d9d9d9;
  border-color: #d9d9d9;
  color: #494949 !important;
}

.bg-gray-600 h1, .bg-gray-600 h2, .bg-gray-600 h3, .bg-gray-600 h4, .bg-gray-600 h5, .bg-gray-600 h6 {
  color: #494949;
}

.bg-gray-600 .nav .open > a, .bg-gray-600 .nav .open > a:focus, .bg-gray-600 .nav .open > a:hover {
  background-color: #cccccc;
  color: #494949 !important;
}

.bg-gray-600 .nav > li > a:focus, .bg-gray-600 .nav > li > a:hover {
  background-color: #cccccc;
  color: #494949 !important;
}

.bg-gray-600 .navbar-nav > li > a {
  color: #494949;
}

.bg-gray-600.small-nav:hover .child-nav {
  background-color: #d9d9d9;
}

.bg-gray-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #d9d9d9;
}

.bg-gray-700 {
  background-color: #cccccc;
  border-color: #cccccc;
  color: #494949 !important;
}

.bg-gray-700 h1, .bg-gray-700 h2, .bg-gray-700 h3, .bg-gray-700 h4, .bg-gray-700 h5, .bg-gray-700 h6 {
  color: #494949;
}

.bg-gray-700 .nav .open > a, .bg-gray-700 .nav .open > a:focus, .bg-gray-700 .nav .open > a:hover {
  background-color: #bfbfbf;
  color: #494949 !important;
}

.bg-gray-700 .nav > li > a:focus, .bg-gray-700 .nav > li > a:hover {
  background-color: #bfbfbf;
  color: #494949 !important;
}

.bg-gray-700 .navbar-nav > li > a {
  color: #494949;
}

.bg-gray-700.small-nav:hover .child-nav {
  background-color: #cccccc;
}

.bg-gray-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #cccccc;
}

.bg-white {
  background-color: #fff;
  border-color: #fff;
  color: #494949 !important;
}

.bg-white h1, .bg-white h2, .bg-white h3, .bg-white h4, .bg-white h5, .bg-white h6 {
  color: #494949;
}

.bg-white .nav .open > a, .bg-white .nav .open > a:focus, .bg-white .nav .open > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white .nav > li > a:focus, .bg-white .nav > li > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white .navbar-nav > li > a {
  color: #494949;
}

.bg-white.small-nav:hover .child-nav {
  background-color: #fff;
}

.bg-white.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #fff;
}

.bg-white-300 {
  background-color: white;
  border-color: white;
  color: #494949 !important;
}

.bg-white-300 h1, .bg-white-300 h2, .bg-white-300 h3, .bg-white-300 h4, .bg-white-300 h5, .bg-white-300 h6 {
  color: #494949;
}

.bg-white-300 .nav .open > a, .bg-white-300 .nav .open > a:focus, .bg-white-300 .nav .open > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white-300 .nav > li > a:focus, .bg-white-300 .nav > li > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white-300 .navbar-nav > li > a {
  color: #494949;
}

.bg-white-300.small-nav:hover .child-nav {
  background-color: white;
}

.bg-white-300.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: white;
}

.bg-white-100 {
  background-color: white;
  border-color: white;
  color: #494949 !important;
}

.bg-white-100 h1, .bg-white-100 h2, .bg-white-100 h3, .bg-white-100 h4, .bg-white-100 h5, .bg-white-100 h6 {
  color: #494949;
}

.bg-white-100 .nav .open > a, .bg-white-100 .nav .open > a:focus, .bg-white-100 .nav .open > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white-100 .nav > li > a:focus, .bg-white-100 .nav > li > a:hover {
  background-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white-100 .navbar-nav > li > a {
  color: #494949;
}

.bg-white-100.small-nav:hover .child-nav {
  background-color: white;
}

.bg-white-100.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: white;
}

.bg-white-500 {
  background-color: #f2f2f2;
  border-color: #f2f2f2;
  color: #494949 !important;
}

.bg-white-500 h1, .bg-white-500 h2, .bg-white-500 h3, .bg-white-500 h4, .bg-white-500 h5, .bg-white-500 h6 {
  color: #494949;
}

.bg-white-500 .nav .open > a, .bg-white-500 .nav .open > a:focus, .bg-white-500 .nav .open > a:hover {
  background-color: #e6e6e6;
  color: #494949 !important;
}

.bg-white-500 .nav > li > a:focus, .bg-white-500 .nav > li > a:hover {
  background-color: #e6e6e6;
  color: #494949 !important;
}

.bg-white-500 .navbar-nav > li > a {
  color: #494949;
}

.bg-white-500.small-nav:hover .child-nav {
  background-color: #f2f2f2;
}

.bg-white-500.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #f2f2f2;
}

.bg-white-600 {
  background-color: #e6e6e6;
  border-color: #e6e6e6;
  color: #494949 !important;
}

.bg-white-600 h1, .bg-white-600 h2, .bg-white-600 h3, .bg-white-600 h4, .bg-white-600 h5, .bg-white-600 h6 {
  color: #494949;
}

.bg-white-600 .nav .open > a, .bg-white-600 .nav .open > a:focus, .bg-white-600 .nav .open > a:hover {
  background-color: #d9d9d9;
  color: #494949 !important;
}

.bg-white-600 .nav > li > a:focus, .bg-white-600 .nav > li > a:hover {
  background-color: #d9d9d9;
  color: #494949 !important;
}

.bg-white-600 .navbar-nav > li > a {
  color: #494949;
}

.bg-white-600.small-nav:hover .child-nav {
  background-color: #e6e6e6;
}

.bg-white-600.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #e6e6e6;
}

.bg-white-700 {
  background-color: #d9d9d9;
  border-color: #d9d9d9;
  color: #494949 !important;
}

.bg-white-700 h1, .bg-white-700 h2, .bg-white-700 h3, .bg-white-700 h4, .bg-white-700 h5, .bg-white-700 h6 {
  color: #494949;
}

.bg-white-700 .nav .open > a, .bg-white-700 .nav .open > a:focus, .bg-white-700 .nav .open > a:hover {
  background-color: #cccccc;
  color: #494949 !important;
}

.bg-white-700 .nav > li > a:focus, .bg-white-700 .nav > li > a:hover {
  background-color: #cccccc;
  color: #494949 !important;
}

.bg-white-700 .navbar-nav > li > a {
  color: #494949;
}

.bg-white-700.small-nav:hover .child-nav {
  background-color: #d9d9d9;
}

.bg-white-700.small-nav:hover .side-nav > li:not(.has-children) > a > span {
  background-color: #d9d9d9;
}

/*--------------------------------------------------------------
# COLOR CLASSES
--------------------------------------------------------------*/
.color-primary {
  color: #3498db !important;
}

.color-danger {
  color: #e74c3c !important;
}

.color-success {
  color: #27ae60 !important;
}

.color-warning {
  color: #f39c12 !important;
}

.color-info {
  color: #5bc0de !important;
}

.color-black {
  color: #292929 !important;
}

.color-light-black {
  color: #494949 !important;
}

.color-gray {
  color: #f2f2f2 !important;
}

.color-white {
  color: #fff !important;
}

/*--------------------------------------------------------------
# BORDER COLORS
--------------------------------------------------------------*/
.border-primary {
  border-color: #3498db;
}

.border-primary-300 {
  border-color: #54a8e1;
}

.border-primary-100 {
  border-color: #75b9e7;
}

.border-primary-500 {
  border-color: #258cd1;
}

.border-primary-600 {
  border-color: #217dbb;
}

.border-primary-700 {
  border-color: #1d6fa5;
}

.border-danger {
  border-color: #e74c3c;
}

.border-danger-300 {
  border-color: #eb6b5e;
}

.border-danger-100 {
  border-color: #ef8b80;
}

.border-danger-500 {
  border-color: #e43725;
}

.border-danger-600 {
  border-color: #d62c1a;
}

.border-danger-700 {
  border-color: #bf2718;
}

.border-success {
  border-color: #27ae60;
}

.border-success-300 {
  border-color: #2ecd71;
}

.border-success-100 {
  border-color: #4bd786;
}

.border-success-500 {
  border-color: #229955;
}

.border-success-600 {
  border-color: #1e8449;
}

.border-success-700 {
  border-color: #19703e;
}

.border-warning {
  border-color: #f39c12;
}

.border-warning-300 {
  border-color: #f5ab36;
}

.border-warning-100 {
  border-color: #f7ba5b;
}

.border-warning-500 {
  border-color: #e08e0b;
}

.border-warning-600 {
  border-color: #c87f0a;
}

.border-warning-700 {
  border-color: #b06f09;
}

.border-info {
  border-color: #5bc0de;
}

.border-info-300 {
  border-color: #7bcce4;
}

.border-info-100 {
  border-color: #9bd8eb;
}

.border-info-500 {
  border-color: #46b8da;
}

.border-info-600 {
  border-color: #31b0d5;
}

.border-info-700 {
  border-color: #28a1c5;
}

.border-black {
  border-color: #292929;
}

.border-black-300 {
  border-color: #3c3c3c;
}

.border-black-100 {
  border-color: #4f4f4f;
}

.border-black-500 {
  border-color: #1c1c1c;
}

.border-black-600 {
  border-color: #101010;
}

.border-black-700 {
  border-color: #030303;
}

.border-gray {
  border-color: #f2f2f2;
}

.border-gray-300 {
  border-color: white;
}

.border-gray-100 {
  border-color: white;
}

.border-gray-500 {
  border-color: #e5e5e5;
}

.border-gray-600 {
  border-color: #d9d9d9;
}

.border-gray-700 {
  border-color: #cccccc;
}

.mt-n {
  margin-top: 0 !important;
}

.mt-5 {
  margin-top: 5px !important;
}

.mt-10 {
  margin-top: 10px !important;
}

.mt-15 {
  margin-top: 15px !important;
}

.mt-20 {
  margin-top: 20px !important;
}

.mt-25 {
  margin-top: 25px !important;
}

.mt-30 {
  margin-top: 30px !important;
}

.mt-35 {
  margin-top: 35px !important;
}

.mt-40 {
  margin-top: 40px !important;
}

.mt-45 {
  margin-top: 45px !important;
}

.mt-50 {
  margin-top: 50px !important;
}

.mb-n {
  margin-bottom: 0 !important;
}

.mb-5 {
  margin-bottom: 5px !important;
}

.mb-10 {
  margin-bottom: 10px !important;
}

.mb-15 {
  margin-bottom: 15px !important;
}

.mb-20 {
  margin-bottom: 20px !important;
}

.mb-25 {
  margin-bottom: 25px !important;
}

.mb-30 {
  margin-bottom: 30px !important;
}

.mb-35 {
  margin-bottom: 35px !important;
}

.mb-40 {
  margin-bottom: 40px !important;
}

.mb-45 {
  margin-bottom: 45px !important;
}

.mb-50 {
  margin-bottom: 50px !important;
}

.ml-n {
  margin-left: 0 !important;
}

.ml-5 {
  margin-left: 5px !important;
}

.ml-10 {
  margin-left: 10px !important;
}

.ml-15 {
  margin-left: 15px !important;
}

.ml-20 {
  margin-left: 20px !important;
}

.ml-25 {
  margin-left: 25px !important;
}

.ml-30 {
  margin-left: 30px !important;
}

.ml-35 {
  margin-left: 35px !important;
}

.ml-40 {
  margin-left: 40px !important;
}

.ml-45 {
  margin-left: 45px !important;
}

.ml-50 {
  margin-left: 50px !important;
}

.mr-n {
  margin-right: 0 !important;
}

.mr-5 {
  margin-right: 5px !important;
}

.mr-10 {
  margin-right: 10px !important;
}

.mr-15 {
  margin-right: 15px !important;
}

.mr-20 {
  margin-right: 20px !important;
}

.mr-25 {
  margin-right: 25px !important;
}

.mr-30 {
  margin-right: 30px !important;
}

.mr-35 {
  margin-right: 35px !important;
}

.mr-40 {
  margin-right: 40px !important;
}

.mr-45 {
  margin-right: 45px !important;
}

.mr-50 {
  margin-right: 50px !important;
}

.m-n {
  margin: 0 !important;
}

.m-5 {
  margin: 5px !important;
}

.m-10 {
  margin: 10px !important;
}

.m-15 {
  margin: 15px !important;
}

.m-20 {
  margin: 20px !important;
}

.m-25 {
  margin: 25px !important;
}

.m-30 {
  margin: 30px !important;
}

.m-35 {
  margin: 35px !important;
}

.m-40 {
  margin: 40px !important;
}

.m-45 {
  margin: 45px !important;
}

.m-50 {
  margin: 50px !important;
}

.pt-n {
  padding-top: 0 !important;
}

.pt-5 {
  padding-top: 5px !important;
}

.pt-10 {
  padding-top: 10px !important;
}

.pt-15 {
  padding-top: 15px !important;
}

.pt-20 {
  padding-top: 20px !important;
}

.pt-25 {
  padding-top: 25px !important;
}

.pt-30 {
  padding-top: 30px !important;
}

.pt-35 {
  padding-top: 35px !important;
}

.pt-40 {
  padding-top: 40px !important;
}

.pt-45 {
  padding-top: 45px !important;
}

.pt-50 {
  padding-top: 50px !important;
}

.pb-n {
  padding-bottom: 0 !important;
}

.pb-5 {
  padding-bottom: 5px !important;
}

.pb-10 {
  padding-bottom: 10px !important;
}

.pb-15 {
  padding-bottom: 15px !important;
}

.pb-20 {
  padding-bottom: 20px !important;
}

.pb-25 {
  padding-bottom: 25px !important;
}

.pb-30 {
  padding-bottom: 30px !important;
}

.pb-35 {
  padding-bottom: 35px !important;
}

.pb-40 {
  padding-bottom: 40px !important;
}

.pb-45 {
  padding-bottom: 45px !important;
}

.pb-50 {
  padding-bottom: 50px !important;
}

.pl-n {
  padding-left: 0 !important;
}

.pl-5 {
  padding-left: 5px !important;
}

.pl-10 {
  padding-left: 10px !important;
}

.pl-15 {
  padding-left: 15px !important;
}

.pl-20 {
  padding-left: 20px !important;
}

.pl-25 {
  padding-left: 25px !important;
}

.pl-30 {
  padding-left: 30px !important;
}

.pl-35 {
  padding-left: 35px !important;
}

.pl-40 {
  padding-left: 40px !important;
}

.pl-45 {
  padding-left: 45px !important;
}

.pl-50 {
  padding-left: 50px !important;
}

.pr-n {
  padding-right: 0 !important;
}

.pr-5 {
  padding-right: 5px !important;
}

.pr-10 {
  padding-right: 10px !important;
}

.pr-15 {
  padding-right: 15px !important;
}

.pr-20 {
  padding-right: 20px !important;
}

.pr-25 {
  padding-right: 25px !important;
}

.pr-30 {
  padding-right: 30px !important;
}

.pr-35 {
  padding-right: 35px !important;
}

.pr-40 {
  padding-right: 40px !important;
}

.pr-45 {
  padding-right: 45px !important;
}

.pr-50 {
  padding-right: 50px !important;
}

.p-n {
  padding: 0 !important;
}

.p-5 {
  padding: 5px !important;
}

.p-10 {
  padding: 10px !important;
}

.p-15 {
  padding: 15px !important;
}

.p-20 {
  padding: 20px !important;
}

.p-25 {
  padding: 25px !important;
}

.p-30 {
  padding: 30px !important;
}

.p-35 {
  padding: 35px !important;
}

.p-40 {
  padding: 40px !important;
}

.p-45 {
  padding: 45px !important;
}

.p-50 {
  padding: 50px !important;
}

/*--------------------------------------------------------------
# BORDERS
--------------------------------------------------------------*/
.no-border {
  border-width: 0px !important;
}

.no-border-top {
  border-top-width: 0px !important;
}

.no-border-bottom {
  border-bottom-width: 0px !important;
}

.no-border-left {
  border-left-width: 0px !important;
}

.no-border-right {
  border-right-width: 0px !important;
}

.border-1 {
  border-width: 1px !important;
}

.border-1-top {
  border-top-width: 1px !important;
}

.border-1-bottom {
  border-bottom-width: 1px !important;
}

.border-1-left {
  border-left-width: 1px !important;
}

.border-1-right {
  border-right-width: 1px !important;
}

.border-2 {
  border-width: 2px !important;
}

.border-2-top {
  border-top-width: 2px !important;
}

.border-2-bottom {
  border-bottom-width: 2px !important;
}

.border-2-left {
  border-left-width: 2px !important;
}

.border-2-right {
  border-right-width: 2px !important;
}

.border-3 {
  border-width: 3px !important;
}

.border-3-top {
  border-top-width: 3px !important;
}

.border-3-bottom {
  border-bottom-width: 3px !important;
}

.border-3-left {
  border-left-width: 3px !important;
}

.border-3-right {
  border-right-width: 3px !important;
}

/*--------------------------------------------------------------
# BORDER RADIUS
--------------------------------------------------------------*/
.no-radius {
  border-radius: 0px !important;
}

.no-radius-top-left {
  border-top-left-radius: 0px !important;
}

.no-radius-top-right {
  border-top-right-radius: 0px !important;
}

.no-radius-bottom-right {
  border-bottom-right-radius: 0px !important;
}

.no-radius-bottom-left {
  border-bottom-left-radius: 0px !important;
}

.border-rad-2 {
  border-radius: 2px !important;
}

.border-rad-2-top-left {
  border-top-left-radius: 2px !important;
}

.border-rad-2-top-right {
  border-top-right-radius: 2px !important;
}

.border-rad-2-bottom-right {
  border-bottom-right-radius: 2px !important;
}

.border-rad-2-bottom-left {
  border-bottom-left-radius: 2px !important;
}

.border-rad-4 {
  border-radius: 4px !important;
}

.border-rad-4-top-left {
  border-top-left-radius: 4px !important;
}

.border-rad-4-top-right {
  border-top-right-radius: 4px !important;
}

.border-rad-4-bottom-right {
  border-bottom-right-radius: 4px !important;
}

.border-rad-4-bottom-left {
  border-bottom-left-radius: 4px !important;
}

.border-rad-6 {
  border-radius: 6px !important;
}

.border-rad-6-top-left {
  border-top-left-radius: 6px !important;
}

.border-rad-6-top-right {
  border-top-right-radius: 6px !important;
}

.border-rad-6-bottom-right {
  border-bottom-right-radius: 6px !important;
}

.border-rad-6-bottom-left {
  border-bottom-left-radius: 6px !important;
}

/*--------------------------------------------------------------
# TOP NAVBAR
--------------------------------------------------------------*/
.navbar {
  border-radius: 0;
  border: 0px;
  margin-bottom: 0;
}

.navbar.box-shadow {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
  z-index: 10;
}

.navbar a:hover {
  text-decoration: none;
  color: #292929 !important;
}

.navbar-toggle {
  font-size: 20px;
}

.navbar-header {
  min-width: 270px;
  padding-left: 15px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
  overflow: hidden;
}

.navbar-header .navbar-brand {
  padding: 12px;
}

.navbar-header .logo {
  height: 26px;
}

.navbar-header.small-nav-header {
  min-width: 50px;
  width: 50px;
}

.navbar-header.small-nav-header .navbar-brand {
  display: none;
}

.small-nav-handle {
  display: inline-block;
  width: 50px;
  height: 50px;
  float: right;
  cursor: pointer;
  text-align: center;
}

.small-nav-handle .fa {
  line-height: 50px;
}

.dropdown-menu {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
  min-width: 220px;
  padding: 0;
  border: 0;
}

.dropdown-menu > li:first-child {
  padding-top: 8px;
}

.dropdown-menu > li > a {
  padding: 8px 20px;
}

.dropdown-menu > li > a .fa {
  margin-right: 5px;
}

.dropdown-menu .divider {
  margin: 5px 0;
}

.dropdown-menu .profile-menu {
  padding: 15px !important;
}

.dropdown-menu .profile-menu .profile-img {
  width: 50px;
}

.dropdown-menu .profile-menu .profile-name {
  width: 120px;
  float: right;
}

.dropdown-menu .profile-menu .profile-name h6 {
  margin-top: 0;
  margin-bottom: 5px;
  line-height: 1.75;
}

.dropdown-menu .profile-menu .profile-name a {
  font-size: 85%;
}

.dropdown-menu.animated {
  -webkit-animation-duration: 0.4s;
          animation-duration: 0.4s;
}

@media (min-width: 992px) {
  .top-navbar-fixed .top-navbar {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 10;
  }
  .top-navbar-fixed .content-wrapper {
    margin-top: 50px;
  }
}

/*--------------------------------------------------------------
# SIDEBARS
--------------------------------------------------------------*/
.content-wrapper {
  min-height: 100vh;
  position: relative;
}

@media (min-width: 769px) {
  .content-wrapper {
    display: table;
    width: 100%;
    table-layout: fixed;
  }
  .content-container {
    display: table-row;
  }
  .left-sidebar, .main-page, .right-sidebar {
    display: table-cell;
    vertical-align: top;
  }
  .right-sidebar {
    width: 400px;
    height: 100%;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
    position: absolute;
    right: -400px;
    z-index: 9;
    -webkit-transition: all 0.4s ease-in-out;
    transition: all 0.4s ease-in-out;
  }
  .left-sidebar {
    width: 270px;
    -webkit-transition: all 0.4s ease-in-out;
    transition: all 0.4s ease-in-out;
  }
}

.right-sidebar.fixed-sidebar .sidebar-content {
  position: fixed;
  width: 400px;
  height: calc(100% - 50px);
  overflow: scroll;
  right: -400px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.right-sidebar .close-icon {
  float: right;
  cursor: pointer;
}

.left-sidebar {
  position: relative;
}

.left-sidebar .user-info {
  text-align: center;
  padding-top: 15px;
  overflow: hidden;
  height: 170px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.left-sidebar .user-info .title {
  margin: 0;
  margin-top: 5px;
  line-height: 1.75;
  color: inherit !important;
}

.left-sidebar .user-info.closed {
  height: 0px;
}

.left-sidebar .purchase-btn {
  margin-bottom: 30px;
  text-align: center;
}

.left-sidebar .side-nav {
  list-style: none;
  padding-left: 0;
}

.left-sidebar .side-nav .nav-header {
  font-size: 80%;
  text-transform: uppercase;
  padding-left: 15px;
  padding-top: 10px;
  opacity: 0.8;
}

.left-sidebar .side-nav .nav-header:first-child {
  padding-top: 0;
}

.left-sidebar .side-nav a {
  color: inherit;
}

.left-sidebar .side-nav li {
  position: relative;
}

.left-sidebar .side-nav li .fa {
  width: 25px;
  display: inline-block;
}

.left-sidebar .side-nav li.has-children .arrow {
  float: right;
  padding: 5px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.left-sidebar .side-nav li a {
  padding: 10px 0;
  padding-left: 15px;
  display: block;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.left-sidebar .side-nav li a:hover {
  background: rgba(0, 0, 0, 0.15);
  color: inherit;
}

.left-sidebar .side-nav li.active {
  background: rgba(0, 0, 0, 0.15);
}

.left-sidebar .side-nav .child-nav {
  list-style: none;
  padding-left: 0;
}

.left-sidebar .side-nav .child-nav a {
  padding-left: 40px;
}

.left-sidebar .side-nav .has-children.open {
  background: rgba(0, 0, 0, 0.15);
}

.left-sidebar .side-nav .has-children.open .arrow {
  -webkit-transform: rotate(90deg);
          transform: rotate(90deg);
  padding-top: 15px;
}

.left-sidebar.small-nav {
  width: 50px;
  z-index: 8;
}

.left-sidebar.small-nav .user-info {
  display: none;
}

.left-sidebar.small-nav li span {
  display: none;
}

.left-sidebar.small-nav .arrow {
  display: none !important;
}

.left-sidebar.small-nav .sidebar-content {
  width: 50px;
}

.left-sidebar.small-nav .child-nav {
  display: none !important;
  position: absolute;
  top: 0;
  left: 50px;
  width: 270px;
  z-index: 9;
}

.left-sidebar.small-nav .side-nav > li {
  position: relative;
}

.left-sidebar.small-nav .side-nav > li:hover > a > span {
  display: block;
  position: absolute;
  top: 0;
  left: 50px;
  width: 270px;
  padding: 10px 0;
  padding-left: 15px;
}

.left-sidebar.small-nav .purchase-btn {
  display: none;
}

.left-sidebar.small-nav .has-children {
  position: relative;
}

.left-sidebar.small-nav .has-children:hover .child-nav {
  display: block !important;
}

.left-sidebar.small-nav .has-children:hover .child-nav a {
  padding-left: 20px;
}

.left-sidebar.small-nav .has-children:hover .child-nav span {
  display: inline-block;
}

.left-sidebar.small-nav:hover .sidebar-content {
  width: 270px;
}

@media (max-width: 991px) {
  .left-sidebar {
    display: none;
  }
}

@media (min-width: 991px) {
  .left-sidebar.fixed-sidebar .sidebar-content {
    position: fixed;
    width: 270px;
    height: calc(100% - 50px);
    overflow: scroll;
  }
}

/*--------------------------------------------------------------
# LAYOUT
--------------------------------------------------------------*/
.main-page {
  width: 100%;
}

.main-page a:not(.btn) {
  color: inherit;
}

.page-title-div {
  background: #fff;
  padding: 15px;
}

.page-title-div .title {
  margin-top: 10px;
}

.page-title-div .sub-title {
  color: #767676;
  margin-bottom: 0;
}

.page-title-div .right-side {
  text-align: right;
}

.page-title-div .right-side .btn {
  margin-top: 12px;
}

.page-title-div.dark-title {
  background: #292929;
}

.page-title-div.dark-title .title {
  color: #fff !important;
}

.breadcrumb-div {
  background-color: #fff;
  padding: 8px 15px;
  border-top: 1px solid #f2f2f2;
  border-bottom: 1px solid #f2f2f2;
  font-size: 90%;
  color: #767676;
}

.breadcrumb-div a {
  color: inherit;
}

.breadcrumb-div a:hover {
  color: #3498db !important;
}

.breadcrumb-div .breadcrumb {
  background: transparent;
  padding: 0;
  margin: 0;
}

.breadcrumb-div .breadcrumb .fa {
  margin-right: 5px;
}

.breadcrumb-div .text-right a .fa {
  margin-right: 2px;
}

.content-internal {
  margin-right: -280px;
  width: 100%;
  float: left;
}

.content-internal .content {
  margin-right: 280px;
  background: #fff;
  padding: 15px;
}

.sidebar-internal {
  float: right;
}

.sidebar-internal.affix {
  right: 15px;
  top: 80px;
  position: fixed !important;
}

.sidebar-internal .sidebar {
  width: 260px;
  background: #fff;
  padding: 15px;
}

/*--------------------------------------------------------------
# PANELS
--------------------------------------------------------------*/
.panel {
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
}

.panel .panel-title h1, .panel .panel-title h2, .panel .panel-title h3, .panel .panel-title h4, .panel .panel-title h5, .panel .panel-title h6 {
  color: inherit !important;
  margin: 0;
  line-height: 30px;
}

.panel-heading {
  padding: 5px;
}

.panel-heading .panel-title {
  margin-top: 10px;
  padding-left: 15px;
}

.panel-heading .panel-title small {
  color: #767676;
  font-size: 75%;
  font-style: italic;
  margin-left: 5px;
}

.lobipanel {
  margin-bottom: 20px;
}

.lobipanel > .panel-heading > .panel-title h1, .lobipanel > .panel-heading > .panel-title h2, .lobipanel > .panel-heading > .panel-title h3, .lobipanel > .panel-heading > .panel-title h4, .lobipanel > .panel-heading > .panel-title h5, .lobipanel > .panel-heading > .panel-title h6 {
  line-height: inherit;
  margin-top: 0px;
}

.lobipanel > .panel-heading .dropdown .dropdown-toggle .panel-control-icon {
  line-height: inherit;
  margin-top: 10px;
}

.lobipanel .panel-heading .dropdown .dropdown-menu > li > a {
  font-size: 12px;
}

.lobipanel .panel-heading .dropdown .dropdown-menu > li > a:focus:hover, .lobipanel .panel-heading .dropdown .dropdown-menu > li > a:hover {
  text-shadow: none;
  background-color: rgba(0, 0, 0, 0.1);
}

.lobipanel > .panel-heading > .panel-title input {
  background-color: rgba(0, 0, 0, 0.1);
  border: 0;
}

.lobipanel > .panel-heading > .panel-title {
  margin-top: 10px;
}

.lobipanel.panel-expanded {
  border-radius: 0;
}

.lobipanel.panel-unpin {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
}

.lobipanel > .panel-heading {
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
}

.panel-default {
  border-color: #e5e5e5;
}

.panel-default .panel-heading {
  color: #292929;
  background-color: #f2f2f2;
  border-color: #e5e5e5;
}

.panel-default .panel-heading small {
  color: #292929;
}

.panel-primary {
  border-color: #258cd1;
}

.panel-primary .panel-heading {
  color: #fff;
  background-color: #3498db;
  border-color: #258cd1;
}

.panel-primary .panel-heading small {
  color: #fff;
}

.panel-danger {
  border-color: #e43725;
}

.panel-danger .panel-heading {
  color: #fff;
  background-color: #e74c3c;
  border-color: #e43725;
}

.panel-danger .panel-heading small {
  color: #fff;
}

.panel-success {
  border-color: #229955;
}

.panel-success .panel-heading {
  color: #fff;
  background-color: #27ae60;
  border-color: #229955;
}

.panel-success .panel-heading small {
  color: #fff;
}

.panel-warning {
  border-color: #e08e0b;
}

.panel-warning .panel-heading {
  color: #fff;
  background-color: #f39c12;
  border-color: #e08e0b;
}

.panel-warning .panel-heading small {
  color: #fff;
}

.panel-info {
  border-color: #46b8da;
}

.panel-info .panel-heading {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}

.panel-info .panel-heading small {
  color: #fff;
}

.panel-black {
  border-color: #1c1c1c;
}

.panel-black .panel-heading {
  color: #fff;
  background-color: #292929;
  border-color: #1c1c1c;
}

.panel-black .panel-heading small {
  color: #fff;
}

.panel-light-black {
  border-color: #3c3c3c;
}

.panel-light-black .panel-heading {
  color: #fff;
  background-color: #494949;
  border-color: #3c3c3c;
}

.panel-light-black .panel-heading small {
  color: #fff;
}

.acc-panels .panel-heading .panel-title {
  margin-top: 5px;
}

.acc-panels .panel-heading .panel-title a {
  display: block;
}

.acc-panels .panel-heading .panel-title a .icon-plus {
  margin-right: 5px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.acc-panels .panel-heading .panel-title a .icon-plus-right {
  float: right;
  margin-top: 5px;
  margin-right: 5px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.acc-panels .panel-heading .panel-title a[aria-expanded=true] .icon-plus {
  margin-right: 5px;
  -webkit-transform: rotate(135deg);
          transform: rotate(135deg);
}

.acc-panels .panel-heading .panel-title a[aria-expanded=true] .icon-plus-right {
  -webkit-transform: rotate(135deg);
          transform: rotate(135deg);
}

/*--------------------------------------------------------------
# TABS
--------------------------------------------------------------*/
.nav-tabs.right-aligned li {
  float: right;
}

.nav-tabs .dropdown-menu > .active > a, .nav-tabs .dropdown-menu > .active > a:hover, .nav-tabs .dropdown-menu > .active > a:focus {
  color: #fff;
}

.nav-tabs > li > a {
  opacity: 0.4;
}

.nav-tabs > li.active > a {
  opacity: 1;
}

.nav-tabs.border-bottom > li.active > a, .nav-tabs.border-bottom > li.active > a:hover, .nav-tabs.border-bottom > li.active > a:focus {
  border: 0 !important;
  border-bottom: 4px solid #ddd !important;
}

.nav-tabs.border-bottom > li > a {
  border: 0 !important;
}

.nav-tabs.border-bottom.border-primary > li.active > a, .nav-tabs.border-bottom.border-primary > li.active > a:hover, .nav-tabs.border-bottom.border-primary > li.active > a:focus {
  border-bottom: 4px solid #3498db !important;
}

.nav-tabs.border-bottom.border-danger > li.active > a, .nav-tabs.border-bottom.border-danger > li.active > a:hover, .nav-tabs.border-bottom.border-danger > li.active > a:focus {
  border-bottom: 4px solid #e74c3c !important;
}

.nav-tabs.border-bottom.border-success > li.active > a, .nav-tabs.border-bottom.border-success > li.active > a:hover, .nav-tabs.border-bottom.border-success > li.active > a:focus {
  border-bottom: 4px solid #27ae60 !important;
}

.nav-tabs.border-bottom.border-warning > li.active > a, .nav-tabs.border-bottom.border-warning > li.active > a:hover, .nav-tabs.border-bottom.border-warning > li.active > a:focus {
  border-bottom: 4px solid #f39c12 !important;
}

.nav-tabs.border-bottom.border-black > li.active > a, .nav-tabs.border-bottom.border-black > li.active > a:hover, .nav-tabs.border-bottom.border-black > li.active > a:focus {
  border-bottom: 4px solid #292929 !important;
}

.nav-tabs.border-bottom.border-gray > li.active > a, .nav-tabs.border-bottom.border-gray > li.active > a:hover, .nav-tabs.border-bottom.border-gray > li.active > a:focus {
  border-bottom: 4px solid #f2f2f2 !important;
}

.tabs-left .nav-tabs {
  float: left;
  border-bottom: 0;
}

.tabs-left .nav-tabs li {
  float: none;
  margin: 0;
}

.tabs-left .nav-tabs li a {
  margin-right: 0;
  border: 0;
  background-color: #292929;
  color: #fff;
  border-radius: 0;
  opacity: 1;
}

.tabs-left .nav-tabs li a:hover {
  background-color: #494949;
}

.tabs-left .tab-content {
  margin-left: 45px;
}

.tabs-left .tab-content .tab-pane {
  display: none;
  background-color: #f2f2f2;
  padding: 15px;
  overflow-y: auto;
}

.tabs-left .tab-content .active {
  display: block;
}

.tabs-left .nav-tabs > li.active > a, .tabs-left .nav-tabs > li.active > a:hover, .tabs-left .nav-tabs > li.active > a:focus {
  border: 0;
  background: #f2f2f2;
  color: #292929;
}

.tabs-right .nav-tabs {
  float: right;
  border-bottom: 0;
}

.tabs-right .nav-tabs li {
  float: none;
  margin: 0;
}

.tabs-right .nav-tabs li a {
  margin-left: 0;
  border: 0;
  background-color: #292929;
  color: #fff;
  border-radius: 0;
  opacity: 1;
}

.tabs-right .nav-tabs li a:hover {
  background-color: #494949;
}

.tabs-right .tab-content {
  margin-right: 45px;
}

.tabs-right .tab-content .tab-pane {
  display: none;
  background-color: #f2f2f2;
  padding: 15px;
  overflow-y: auto;
}

.tabs-right .tab-content .active {
  display: block;
}

.tabs-right .nav-tabs > li.active > a, .tabs-right .nav-tabs > li.active > a:hover, .tabs-right .nav-tabs > li.active > a:focus {
  border: 0;
  background: #f2f2f2;
  color: #292929;
}

/*--------------------------------------------------------------
# LABELS & BADGES
--------------------------------------------------------------*/
.label {
  padding: 0.2em 0.6em;
}

.label-rounded {
  padding: .2em 1.2em .3em;
  border-radius: 20px;
}

.label-flat {
  border-radius: 0;
}

.label-wide {
  padding: .2em 1.2em .3em;
}

.label-bordered {
  background-color: #fff;
  border-width: 2px;
  border-style: solid;
}

.label-bordered.label-default {
  border-color: #777777;
  color: #777777 !important;
}

.label-bordered.label-primary {
  border-color: #3498db;
  color: #3498db !important;
}

.label-bordered.label-danger {
  border-color: #e74c3c;
  color: #e74c3c !important;
}

.label-bordered.label-success {
  border-color: #27ae60;
  color: #27ae60 !important;
}

.label-bordered.label-warning {
  border-color: #f39c12;
  color: #f39c12 !important;
}

.label-bordered.label-info {
  border-color: #5bc0de;
  color: #5bc0de !important;
}

.label-bordered.label-black {
  border-color: #292929;
  color: #292929 !important;
}

.label-bordered.label-gray {
  border-color: #f2f2f2;
  color: #f2f2f2 !important;
}

.badge.badge-default {
  background-color: #777777;
}

.badge.badge-primary {
  background-color: #3498db;
}

.badge.badge-danger {
  background-color: #e74c3c;
}

.badge.badge-success {
  background-color: #27ae60;
}

.badge.badge-warning {
  background-color: #f39c12;
}

.badge.badge-info {
  background-color: #5bc0de;
}

.badge.badge-black {
  background-color: #292929;
}

.badge.badge-gray {
  background-color: #f2f2f2;
  color: #292929;
}

.badge.badge-bordered {
  background-color: #fff;
  border-width: 2px;
  border-style: solid;
}

.badge.badge-bordered.badge-default {
  border-color: #777777;
  color: #777777 !important;
}

.badge.badge-bordered.badge-primary {
  border-color: #3498db;
  color: #3498db !important;
}

.badge.badge-bordered.badge-danger {
  border-color: #e74c3c;
  color: #e74c3c !important;
}

.badge.badge-bordered.badge-success {
  border-color: #27ae60;
  color: #27ae60 !important;
}

.badge.badge-bordered.badge-warning {
  border-color: #f39c12;
  color: #f39c12 !important;
}

.badge.badge-bordered.badge-info {
  border-color: #5bc0de;
  color: #5bc0de !important;
}

.badge.badge-bordered.badge-black {
  border-color: #292929;
  color: #292929 !important;
}

.badge.badge-bordered.badge-gray {
  border-color: #f2f2f2;
  color: #f2f2f2 !important;
}

/*--------------------------------------------------------------
# SECTIONS
--------------------------------------------------------------*/
.section {
  padding: 30px 0;
}

.section .section-title .title {
  margin-top: 0;
}

.section .section-title .sub-title {
  color: #767676;
}

.underline {
  position: relative;
  padding-bottom: 10px;
  margin-bottom: 12px;
}

.underline:after {
  content: "";
  width: 32px;
  height: 1px;
  background: #767676;
  position: absolute;
  bottom: 0;
  left: 0;
}

.text-center .underline::after {
  width: 4%;
  left: 48%;
}

/*--------------------------------------------------------------
# BUTTONS
--------------------------------------------------------------*/
.btn:focus, .btn.focus, .btn:active:focus, .btn:active.focus, .btn.active:focus, .btn.active.focus {
  outline: 0;
}

.btn-rounded {
  border-radius: 30px;
}

.btn-wide {
  padding: 6px 22px;
}

.btn .fa {
  margin-right: 6px;
}

.btn.btn-labeled {
  padding-top: 0;
  padding-bottom: 0;
}

.btn.btn-labeled .fa {
  margin-right: 0px;
}

.btn.btn-labeled .btn-label {
  position: relative;
  background: transparent;
  background: rgba(0, 0, 0, 0.15);
  display: inline-block;
  padding: 6px 12px;
  left: -12px;
  border-radius: 4px 0 0 4px;
}

.btn.btn-labeled .btn-label.btn-label-right {
  left: auto;
  right: -12px;
  border-radius: 0 4px 4px 0;
}

.btn.btn-labeled.btn-rounded .btn-label {
  border-radius: 30px 0 0 30px;
}

.btn.btn-labeled.btn-rounded .btn-label.btn-label-right {
  left: auto;
  right: -12px;
  border-radius: 0 30px 30px 0;
}

.btn.icon-only .fa {
  margin-right: 0;
}

.btn.btn-animated {
  position: relative;
  overflow: hidden;
}

.btn.btn-animated .hidden-content {
  position: absolute;
  width: 100%;
  right: -100%;
  text-align: center;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.btn.btn-animated .visible-content {
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.btn.btn-animated:hover .hidden-content {
  right: 0;
}

.btn.btn-animated:hover .visible-content {
  opacity: 0;
}

.btn.btn-lg.btn-labeled .btn-label {
  padding: 10px 16px;
  left: -16px;
}

.btn.btn-lg.btn-labeled .btn-label.btn-label-right {
  left: auto;
  right: -16px;
}

.btn.btn-sm.btn-labeled .btn-label {
  padding: 5px 10px;
  left: -10px;
}

.btn.btn-sm.btn-labeled .btn-label.btn-label-right {
  left: auto;
  right: -10px;
}

.btn.btn-xs.btn-labeled .btn-label {
  padding: 1px 5px;
  left: -5px;
}

.btn.btn-xs.btn-labeled .btn-label.btn-label-right {
  left: auto;
  right: -5px;
}

/*--------------------------------------------------------------
# MODALS
--------------------------------------------------------------*/
.modal-title small {
  color: #767676;
  font-size: 75%;
  font-style: italic;
  margin-left: 5px;
}

.modal-color-primary .modal-backdrop {
  background-color: #3498db;
}

.modal-color-danger .modal-backdrop {
  background-color: #e74c3c;
}

.modal-color-success .modal-backdrop {
  background-color: #27ae60;
}

.modal-color-black .modal-backdrop {
  background-color: #292929;
}

.modal-color-warning .modal-backdrop {
  background-color: #f39c12;
}

.modal-color-gray .modal-backdrop {
  background-color: #f2f2f2;
}

.modal-color-white .modal-backdrop {
  background-color: #fff;
}

.modal-color-info .modal-backdrop {
  background-color: #5bc0de;
}

.trans-modal .modal-content {
  background-color: transparent;
  box-shadow: none;
  border: 0;
  color: #fff;
}

.trans-modal .modal-content .close {
  color: #fff;
}

.trans-modal .modal-content h1, .trans-modal .modal-content h2, .trans-modal .modal-content h3, .trans-modal .modal-content h4, .trans-modal .modal-content h5, .trans-modal .modal-content h6, .trans-modal .modal-content .h1, .trans-modal .modal-content .h2, .trans-modal .modal-content .h3, .trans-modal .modal-content .h4, .trans-modal .modal-content .h5, .trans-modal .modal-content .h6 {
  color: #fff;
}

.trans-modal .modal-content .modal-header {
  border: 0px;
}

.trans-modal .modal-content .modal-footer {
  border: 0px;
}

.modal-footer.text-center {
  text-align: center !important;
}

.modal-title .fa {
  margin-right: 5px;
}

.modal.vert-center {
  text-align: center;
}

@media screen and (min-width: 768px) {
  .modal.vert-center:before {
    display: inline-block;
    vertical-align: middle;
    content: " ";
    height: 100%;
  }
}

.modal.vert-center .modal-dialog {
  display: inline-block;
  text-align: left;
  vertical-align: middle;
}

.modal.vert-top {
  text-align: center;
}

@media screen and (min-width: 768px) {
  .modal.vert-top:before {
    display: inline-block;
    vertical-align: middle;
    content: " ";
    height: 100%;
  }
}

.modal.vert-top .modal-dialog {
  display: inline-block;
  text-align: left;
  vertical-align: top;
  margin-top: 0;
}

.modal.vert-top .modal-content {
  border-top-left-radius: 0;
  border-top-right-radius: 0;
  border-top: 0px;
}

.modal.vert-bottom {
  text-align: center;
}

@media screen and (min-width: 768px) {
  .modal.vert-bottom:before {
    display: inline-block;
    vertical-align: middle;
    content: " ";
    height: 100%;
  }
}

.modal.vert-bottom .modal-dialog {
  display: inline-block;
  text-align: left;
  vertical-align: bottom;
  margin-bottom: 0;
}

.modal.vert-bottom .modal-content {
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
  border-bottom: 0px;
}

.modal.modal-full-screen .modal-dialog {
  width: 100%;
  height: 100%;
  margin-top: 0;
}

.modal.modal-full-screen .modal-content {
  height: 100%;
  border: 0;
  border-radius: 0;
}

.iziModal .iziModal-header-subtitle, .iziModal .iziModal-header-title {
  font-family: "Poppins", sans-serif;
  clear: none;
}

.iziModal-wrap {
  /* padding: 15px; */
}

.iziModal .iziModal-header {
  background: #3498db;
}

.iziModal .iziModal-header .fa {
  font-size: 30px;
}

.sweet-alert {
  font-family: "Poppins", sans-serif;
}

.sweet-alert h2 {
  font-family: "Poppins", sans-serif;
}

.sweet-alert input {
  display: none;
}

.sweet-alert fieldset {
  padding: 0;
}

/*--------------------------------------------------------------
# DASHBOARD STATS
--------------------------------------------------------------*/
.dashboard-stat {
  display: block;
  padding: 30px 15px;
  text-align: right;
  position: relative;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
  border-radius: 4px;
}

.dashboard-stat .number {
  font-size: 28px;
  display: block;
}

.dashboard-stat .bg-icon {
  position: absolute;
  font-size: 80px;
  opacity: 0.4;
  left: 0;
  bottom: 0;
}

.dashboard-stat:hover {
  background: #292929 !important;
}

.dashboard-stat-2 {
  display: block;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.1);
  border: 1px solid #e5e5e5;
  border-radius: 4px;
}

.dashboard-stat-2 .stat-content {
  padding: 20px 15px 15px;
  text-align: center;
  position: relative;
}

.dashboard-stat-2 .number {
  font-size: 28px;
  display: block;
}

.dashboard-stat-2 .stat-footer {
  background: #fff;
  color: #292929;
  text-align: center;
  display: block;
  padding: 8px;
  font-size: 90%;
}

.dashboard-stat-2:hover {
  background: #292929 !important;
}

@media (max-width: 768px) {
  .dashboard-stat {
    margin-bottom: 10px;
  }
  .dashboard-stat-2 {
    margin-bottom: 10px;
  }
}

/*--------------------------------------------------------------
# NOTIFICATIONS
--------------------------------------------------------------*/
.toast-success {
  background-color: #27ae60;
}

.toast-error {
  background-color: #e74c3c;
}

.toast-warning {
  background-color: #f39c12;
}

.toast-info {
  background-color: #5bc0de;
}

#toast-container > div {
  border-radius: 4px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
  opacity: 0.95;
}

#toast-container > div:hover {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.ui-pnotify .alert-warning {
  background-color: #f39c12;
  border-color: #f39c12;
  color: #fff;
}

.ui-pnotify .alert-info {
  background-color: #5bc0de;
  border-color: #5bc0de;
  color: #fff;
}

.ui-pnotify .alert-success {
  background-color: #27ae60;
  border-color: #27ae60;
  color: #fff;
}

.ui-pnotify .alert-danger {
  background-color: #e74c3c;
  border-color: #e74c3c;
  color: #fff;
}

.ui-pnotify .alert h4 {
  clear: none;
}

.ui-pnotify .ui-pnotify-icon, .ui-pnotify .ui-pnotify-icon span {
  margin-top: 5px;
  margin-right: 5px;
}

.ui-pnotify .ui-pnotify-icon.false, .ui-pnotify .ui-pnotify-icon span.false {
  margin: 0;
}

.ui-pnotify .ui-pnotify-closer, .ui-pnotify .ui-pnotify-sticker {
  margin-top: 5px;
  margin-left: 5px;
}

.ui-pnotify .ui-pnotify-closer:focus, .ui-pnotify .ui-pnotify-sticker:focus {
  outline: 0;
}

.ui-pnotify.alert-left-icon .alert-info {
  border-color: #28a1c5;
}

.ui-pnotify.alert-left-icon .alert-warning {
  border-color: #b06f09;
}

.ui-pnotify.alert-left-icon .alert-success {
  border-color: #19703e;
}

.ui-pnotify.alert-left-icon .alert-danger {
  border-color: #bf2718;
}

.ui-pnotify.alert-left-icon .ui-pnotify-container {
  border-left-width: 50px;
}

.ui-pnotify.alert-left-icon:after {
  left: 0;
  position: absolute;
  top: 50%;
  width: 50px;
  font: normal normal normal 14px/1 FontAwesome;
  content: "\f071";
  text-align: center;
  font-size: 18px;
  margin-top: -9px;
  line-height: 1;
  color: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.ui-pnotify.alert-right-icon .alert-info {
  border-color: #28a1c5;
}

.ui-pnotify.alert-right-icon .alert-warning {
  border-color: #b06f09;
}

.ui-pnotify.alert-right-icon .alert-success {
  border-color: #19703e;
}

.ui-pnotify.alert-right-icon .alert-danger {
  border-color: #bf2718;
}

.ui-pnotify.alert-right-icon .ui-pnotify-container {
  border-right-width: 50px;
}

.ui-pnotify.alert-right-icon:after {
  right: 0;
  position: absolute;
  top: 50%;
  width: 50px;
  font: normal normal normal 14px/1 FontAwesome;
  content: "\f071";
  text-align: center;
  font-size: 18px;
  margin-top: -9px;
  line-height: 1;
  color: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.ui-pnotify .ui-pnotify-shadow {
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
}

.left-icon-alert {
  border: 1px solid #f2f2f2;
  border-left-width: 50px;
  position: relative;
}

.left-icon-alert:after {
  left: -50px;
  position: absolute;
  top: 50%;
  width: 50px;
  font: normal normal normal 14px/1 FontAwesome;
  content: "\f071";
  text-align: center;
  font-size: 18px;
  margin-top: -9px;
  line-height: 1;
  color: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.left-icon-alert.alert-info {
  border-color: #28a1c5 !important;
}

.left-icon-alert.alert-info:after {
  content: "\f129";
}

.left-icon-alert.alert-warning {
  border-color: #b06f09 !important;
}

.left-icon-alert.alert-warning:after {
  content: "\f129";
}

.left-icon-alert.alert-success {
  border-color: #19703e !important;
}

.left-icon-alert.alert-success:after {
  content: "\f00c";
}

.left-icon-alert.alert-danger {
  border-color: #bf2718 !important;
}

.left-icon-alert.alert-danger:after {
  content: "\f00d";
}

.right-icon-alert {
  border: 1px solid #f2f2f2;
  border-right-width: 50px;
  position: relative;
}

.right-icon-alert:after {
  right: -50px;
  position: absolute;
  top: 50%;
  width: 50px;
  font: normal normal normal 14px/1 FontAwesome;
  content: "\f071";
  text-align: center;
  font-size: 18px;
  margin-top: -9px;
  line-height: 1;
  color: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.right-icon-alert.alert-info {
  border-color: #28a1c5 !important;
}

.right-icon-alert.alert-info:after {
  content: "\f129";
}

.right-icon-alert.alert-warning {
  border-color: #b06f09 !important;
}

.right-icon-alert.alert-warning:after {
  content: "\f129";
}

.right-icon-alert.alert-success {
  border-color: #19703e !important;
}

.right-icon-alert.alert-success:after {
  content: "\f00c";
}

.right-icon-alert.alert-danger {
  border-color: #bf2718 !important;
}

.right-icon-alert.alert-danger:after {
  content: "\f00d";
}

/*--------------------------------------------------------------
# PAGINATION
--------------------------------------------------------------*/
.pagination > .active > a, .pagination > .active > a:hover, .pagination > .active > a:focus, .pagination > .active > span, .pagination > .active > span:hover, .pagination > .active > span:focus {
  color: #fff !important;
}

.pagination.rounded-corners li:first-child > a, .pagination.rounded-corners li:first-child > span {
  border-top-left-radius: 20px;
  border-bottom-left-radius: 20px;
}

.pagination.rounded-corners li:last-child > a, .pagination.rounded-corners li:last-child > span {
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
}

.pagination.borderless li > a, .pagination.borderless li > span {
  border: 0px;
}

.pager .disabled > a, .pager .disabled > a:hover, .pager .disabled > a:focus, .pager .disabled > span {
  opacity: 0.5;
}

/*--------------------------------------------------------------
# FORMS
--------------------------------------------------------------*/
.form-group.left-icon {
  position: relative;
}

.form-group.left-icon .fa {
  line-height: 34px;
}

.form-group.left-icon .form-control {
  padding-left: 42.5px;
}

.form-group.left-icon .form-left-icon {
  position: absolute;
  left: 15px;
  top: 25px;
}

.form-group.left-icon .form-left-icon.icon-lg {
  top: 30px;
}

.form-group.left-icon .form-left-icon.icon-sm {
  top: 22px;
}

.form-group.has-feedback .fa {
  line-height: 34px;
}

.form-group input:focus, .form-group textarea:focus, .form-group select:focus {
  box-shadow: none;
  border-color: #292929;
}

.form-horizontal .form-group.left-icon {
  position: relative;
}

.form-horizontal .form-group.left-icon .fa, .form-horizontal .form-group.left-icon .glyphicon {
  line-height: 34px;
}

.form-horizontal .form-group.left-icon .form-control {
  padding-left: 42.5px;
}

.form-horizontal .form-group.left-icon .form-left-icon {
  position: absolute;
  left: 30px;
  top: 0px;
}

.form-horizontal .form-group.left-icon .form-left-icon.icon-lg {
  top: 5px;
}

.form-horizontal .form-group.left-icon .form-left-icon.icon-sm {
  top: 0px;
}

.form-group label {
  font-size: 95%;
}

.form-group .help-block {
  font-size: 84%;
  font-style: italic;
  margin-top: -5px;
}

.input-group {
  font-size: 14px;
  margin-bottom: 0.546875em;
}

.form-horizontal .control-label.text-left {
  text-align: left;
}

.radio-label {
  display: inline-block;
}

.select2-container .select2-selection--single {
  height: 34px;
}

.select2-container--default .select2-selection--single .select2-selection__rendered {
  line-height: 34px;
}

.select2-container--default .select2-selection--single .select2-selection__arrow {
  height: 34px;
}

.select2-results {
  font-size: 90%;
}

.select2-container--default .select2-search--inline .select2-search__field {
  margin-top: 0;
  margin-bottom: 0;
}

div.tagsinput span.tag {
  border-width: 0;
  background: #4aa3df;
  color: #16527a;
  padding: 2px 10px;
}

div.tagsinput span.tag a {
  color: #196090;
}

.form-link {
  display: inline-block;
  margin-top: 15px;
  color: #767676;
}

.op-check.checkbox label, .op-check.radio label {
  padding-left: 0;
}

/*--------------------------------------------------------------
# ERROR PAGES
--------------------------------------------------------------*/
.error-box {
  text-align: center;
}

.error-box .error-icon {
  font-size: 40px;
  color: #e74c3c;
}

.error-box .error-title {
  margin-top: 10px;
  font-size: 60px;
}

.error-box .sub-title {
  font-size: 18px;
  color: #767676;
}

/*--------------------------------------------------------------
# PRICING
--------------------------------------------------------------*/
.pricing-box {
  background: #fff;
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
}

.pricing-box .pricing-head {
  background-color: #f2f2f2;
  text-align: center;
  border-top: 3px solid #3498db;
  padding: 1.618em;
  position: relative;
  overflow: hidden;
  border-radius: 4px 4px 0 0;
}

.pricing-box .pricing-head h1, .pricing-box .pricing-head h2, .pricing-box .pricing-head h3, .pricing-box .pricing-head h4, .pricing-box .pricing-head h5, .pricing-box .pricing-head h6 {
  margin: 0;
}

.pricing-box .pricing-head .striked {
  text-decoration: line-through;
}

.pricing-box .pricing-head .bg-icon {
  position: absolute;
  bottom: -20px;
  left: -20px;
  font-size: 120px;
  color: #999999;
  opacity: 0.2;
}

.pricing-box .pricing-body {
  padding: 1em;
}

.pricing-box .pricing-body ul li {
  line-height: 2.25;
}

.pricing-box .pricing-body ul li .icon {
  float: right;
}

.pricing-box .pricing-foot a {
  display: block;
  padding: 1em;
  background: #f2f2f2;
  color: #292929;
  text-align: center;
  text-transform: uppercase;
  letter-spacing: 1px;
  border-radius: 0 0 4px 4px;
  -webkit-transition: all 0.4s ease-in-out;
  transition: all 0.4s ease-in-out;
}

.pricing-box .pricing-foot a:hover {
  background: #3498db;
  color: #fff !important;
}

.pricing-box.popular .pricing-head {
  background: #494949;
  color: #fff;
}

.pricing-box.popular .pricing-head h1, .pricing-box.popular .pricing-head h2, .pricing-box.popular .pricing-head h3, .pricing-box.popular .pricing-head h4, .pricing-box.popular .pricing-head h5, .pricing-box.popular .pricing-head h6 {
  color: #fff;
}

/*--------------------------------------------------------------
# LOGIN
--------------------------------------------------------------*/
.login-bg {
  background-image: url("../images/photo-2.jpg");
  background-size: cover;
  background-attachment: fixed;
  min-height: 100vh;
}

.login-bg .login-box {
  background: rgba(255, 255, 255, 0.8);
  padding: 20px;
  margin-top: 150px;
  border-radius: 4px;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.1);
}

.login-bg-color {
  min-height: 100vh;
}

.login-bg-color .login-box {
  color: #292929 !important;
  padding: 20px;
  margin-top: 125px;
  border-radius: 4px;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.1);
}

.login-bg-color .login-box h1, .login-bg-color .login-box h2, .login-bg-color .login-box h3, .login-bg-color .login-box h4, .login-bg-color .login-box h5, .login-bg-color .login-box h6 {
  color: #292929 !important;
}

/*--------------------------------------------------------------
# DROPZONE
--------------------------------------------------------------*/
.dropzone {
  background: #f2f2f2;
  border: 2px dashed #d9d9d9;
  min-height: 250px;
}

.dropzone .dz-message {
  font-size: 16px;
  font-weight: bold;
  margin: 4.5em 0;
}

.dropzone .dz-message .note {
  font-size: 13px;
  font-weight: normal;
  color: #494949;
  margin-top: 15px;
}

/*--------------------------------------------------------------
# BOOTSTRAP SWITCH
--------------------------------------------------------------*/
.bootstrap-switch .bootstrap-switch-handle-off.bootstrap-switch-primary, .bootstrap-switch .bootstrap-switch-handle-on.bootstrap-switch-primary {
  background: #3498db;
}

/*--------------------------------------------------------------
# JQUERY STEPS
--------------------------------------------------------------*/
.wizard > .steps .current a, .wizard > .steps .current a:hover, .wizard > .steps .current a:active {
  background: #3498db;
}

.wizard > .actions a, .wizard > .actions a:hover, .wizard > .actions a:active {
  background: #3498db;
  color: #fff;
}

.wizard > .content {
  min-height: 250px;
}

.wizard > .content > .body label.error {
  color: #e74c3c;
  font-size: 90%;
  font-weight: normal;
}

/*--------------------------------------------------------------
# DATATABLES
--------------------------------------------------------------*/
.pagination > .active > a, .pagination > .active > a:focus, .pagination > .active > a:hover, .pagination > .active > span, .pagination > .active > span:focus, .pagination > .active > span:hover {
  background-color: #3498db;
  border-color: #3498db;
}

div.dataTables_wrapper div.dataTables_filter label {
  text-align: right;
}

/*--------------------------------------------------------------
# MISCELLANEOUS
--------------------------------------------------------------*/
pre[class*="language-"] {
  border-left-width: 2px;
}

.src-btn {
  float: right;
}

.draggable-handle {
  cursor: move;
}

.panel-heading .dropdown .fa.dropdown-toggle {
  padding-right: 15px;
  padding-top: 15px;
}

.media-object {
  margin-top: 10px;
}

.media-bottom {
  padding-bottom: 1.75em;
}

.op-chart {
  width: 100%;
  height: 500px;
}

[class^="icheckbox_line"].checked {
  opacity: 0.6;
}

.browser {
  border: 2px solid #d9d9d9;
  border-top-width: 30px;
  width: 60%;
  margin: auto;
  border-radius: 6px;
}

.browser iframe {
  border: 0;
  width: 100%;
}

.popover.confirmation {
  max-width: 100%;
}

.dropdown .dropdown-toggle {
  cursor: pointer;
}

.dropdown .icon-right {
  margin-left: 15px;
  float: right;
  margin-top: 3px;
  margin-right: 0 !important;
}

.show-grid [class*="col-"] {
  border: 1px solid #cccccc;
  padding-top: 5px;
  padding-bottom: 5px;
  background: #d9d9d9;
}


/*# sourceMappingURL=data:application/json;charset=utf8;base64,eyJ2ZXJzaW9uIjozLCJzb3VyY2VzIjpbIm1haW4uc2NzcyIsInR5cG9ncmFwaGljL3R5cG9ncmFwaGljLnNjc3MiLCJtYWluLmNzcyIsImJvdXJib24vY3NzMy9fc2VsZWN0aW9uLnNjc3MiLCJib3VyYm9uL2FkZG9ucy9fcHJlZml4ZXIuc2NzcyIsIl9jb2xvci1jbGFzc2VzLnNjc3MiLCJfaGVscGVycy5zY3NzIl0sIm5hbWVzIjpbXSwibWFwcGluZ3MiOiJBQUFBOzs7Ozs7Ozs7Z0VBU2dFO0FBSWhFOzs7Ozs7Ozs7Ozs7Ozs7Ozs7Ozs7Ozs7O2dFQXlCZ0U7QUFJaEU7O2dFQUVnRTtBQUdoRSxzRUFBTztBQ2lpQkw7RUExVkEsbUNEbk1rQztFQ29NbEMsaUJEMUtvQjtFQzJLcEIsZURqTXlCO0VDbU16QixnQkR4S2E7RUN5S2Isb0JBQWE7Q0F1Vlo7O0FBclZEO0VBbVZBO0lBbFZFLHNFQUFlO0dBb1ZoQjtDQzloQkY7O0FENk1DO0VBK1VBO0lBOVVFLGdCRC9LVztHQytmWjtDQ3hoQkY7O0FEMGhCQzs7Ozs7Ozs7RUF6VUEsVUFBVTtFQUNWLFdBQVc7Q0FpVlY7O0FBRUQ7Ozs7RUEvVUEsc0JBQWU7Q0FvVmQ7O0FBRUQ7RUFsVkEsbUNEaE9xQztFQ2lPckMsaUJEck1zQjtFQ3NNdEIsZURoT21CO0VDaU9uQixZQUFZO0NBaVZYOztBQUVEO0VBNVVBLDJCQUgwQjtFQUt4QiwyQkFBZ0M7RUFDaEMsNEJBQWlDO0VBQ2pDLDhCQUFtQztDQTBVcEM7O0FBblVEO0VBaVVBO0lBaFVFLHVHQUFlO0dBa1VoQjtDQzNnQkY7O0FENE1DO0VBNlRBO0lBNVRFLDJCQWxCd0I7SUFvQnRCLDJCQUFnQztJQUNoQyw0QkFBaUM7SUFDakMsOEJBQW1DO0dBMFR0QztDQ2xnQkY7O0FEb2dCQztFQW5UQSwyQkFIMEI7RUFLeEIsMkJBQWdDO0VBQ2hDLDRCQUFpQztFQUNqQyw4QkFBbUM7Q0FpVHBDOztBQTFTRDtFQXdTQTtJQXZTRSx1R0FBZTtHQXlTaEI7Q0N6ZkY7O0FEbU5DO0VBb1NBO0lBblNFLDJCQWxCd0I7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RUFDYixnQkFBZ0I7RUFDaEIsMkJBQTJCO0NBQzlCOztBQUVMO0VBRVEsMEJBQXdCO0VBQ3hCLGlCQUFpQjtFQUNqQixvQkFBb0I7RUFDcEIsb0JBNXpEZ0I7Q0E2ekRuQiIsImZpbGUiOiJtYWluLmNzcyIsInNvdXJjZXNDb250ZW50IjpbIi8qIS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIG1haW4uc2Nzc1xuI1xuIyBTYXNzIGZpbGUgZm9yIE9wdGlvbnMtYWRtaW4gdGVtcGxhdGUuXG4jIEF1dGhvcjogU2FsdFRlY2hub1xuI1xuIyBUaGlzIGlzIGNvbXByZXNzZWQgQ1NTIGZpbGUuIFlvdSBnZXQgdW5jb21wcmVzc2VkIHZlcnNpb24gb2ZcbiMgdGhpcyBmaWxlIGFuZCBhbGwgc291cmNlIHNjc3MgZmlsZXMgd2l0aCBkb3dubG9hZC5cbiNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgW1RBQkxFIE9GIENPTlRFTlRTXVxuI1xuIyAxLiBWQVJJQUJMRVMgJiBNSVhJTlNcbiMgMi4gVE9QIE5BVkFCUlxuIyAzLiBTSURFQkFSU1xuIyA0LiBMQVlPVVRcbiMgNS4gUEFORUxTXG4jIDYuIFRBQlNcbiMgNy4gTEFCRUxTICYgQkFER0VTXG4jIDguIFNFQ1RJT05TXG4jIDkuIEJVVFRPTlNcbiMgMTAuIE1PREFMU1xuIyAxMS4gREFTSEJPQVJEIFNUQVRTXG4jIDEyLiBOT1RJRklDQVRJT05TXG4jIDEzLiBQQUdJTkFUSU9OXG4jIDE0LiBGT1JNU1xuIyAxNS4gRVJST1IgUEFHRVNcbiMgMTYuIFBSSUNJTkdcbiMgMTcuIExPR0lOXG4jIDE4LiBEUk9QWk9ORVxuIyAxOS4gQk9PVFNUUkFQIFNXSVRDSFxuIyAyMC4gSlFVRVJZIFNURVBTXG4jIDIxLiBEQVRBVEFCTEVTXG4jIDIyLiBNSVNDRUxMQU5FT1VTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIDEuIFZBUklBQkxFUyAmIE1JWElOU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuXG4vLyBJbXBvcnQgR29vZ2xlIEZvbnRzXG5AaW1wb3J0ICdodHRwczovL2ZvbnRzLmdvb2dsZWFwaXMuY29tL2Nzcz9mYW1pbHk9UG9wcGluczozMDAsNDAwLDYwMCc7XG5cblxuLy8gVmFyaWFibGVzXG4kc3QtYm9keS1mb250OiAnUG9wcGlucycsIHNhbnMtc2VyaWY7XG4kc3QtaGVhZGluZy1mb250OiAnUG9wcGlucycsIHNhbnMtc2VyaWY7XG4kZ3JheS1jb2xvcjogI2YyZjJmMjtcbiRibGFjay1jb2xvcjogIzI5MjkyOTtcbiRsaWdodC1ibGFjay1jb2xvcjogIzQ5NDk0OTtcbiRsaWdodGVyLWJsYWNrLWNvbG9yOiAjNzY3Njc2O1xuJHdoaXRlLWNvbG9yOiAjZmZmO1xuJGRhcmstZ3JheS1jb2xvcjogZGFya2VuKCRncmF5LWNvbG9yLCAxMCUpO1xuXG4vLyBQYWxsZXRlIGNvbG9yc1xuJHByaW1hcnktY29sb3I6ICMzNDk4ZGI7XG4kZGFuZ2VyLWNvbG9yOiAjZTc0YzNjO1xuJHN1Y2Nlc3MtY29sb3I6ICMyN2FlNjA7XG4kd2FybmluZy1jb2xvcjogI2YzOWMxMjtcbiRpbmZvLWNvbG9yOiAjNWJjMGRlO1xuXG4vLyBTaWRlYmFyIHdpZHRoc1xuJGxlZnQtc2lkZWJhci13aWR0aDogMjcwcHg7XG5cbi8vIEltcG9ydCBib3VyYm9uICYgdHlwb2dyYXBoaWNcbkBpbXBvcnQgXCJib3VyYm9uL2JvdXJib25cIjtcbkBpbXBvcnQgXCJ0eXBvZ3JhcGhpYy90eXBvZ3JhcGhpY1wiO1xuXG5cbi8vIFR5cG9ncmFwaGljIHNldHRpbmdzXG4kYm9keS1mb250OiAkc3QtYm9keS1mb250O1xuJGJvZHktZm9udC13ZWlnaHQ6IDQwMDtcbiRib2R5LWNvbG9yOiAkbGlnaHQtYmxhY2stY29sb3I7XG4kaGVhZGVyLWZvbnQ6ICRzdC1oZWFkaW5nLWZvbnQ7XG4kaGVhZGVyLWZvbnQtd2VpZ2h0OiA0MDA7XG4kaGVhZGVyLWNvbG9yOiAkYmxhY2stY29sb3I7XG4kbWluLWZvbnQ6IDEycHg7XG4kbWF4LWZvbnQ6IDE0cHg7XG5cblxuLy8gRmlyZSB1cCB0aGUgbWl4aW5cbkBpbmNsdWRlIHR5cG9ncmFwaGljO1xuXG5ib2R5e1xuICAgIGZvbnQtZmFtaWx5OiAkYm9keS1mb250O1xuICAgIC13ZWJraXQtZm9udC1zbW9vdGhpbmc6IGFudGlhbGlhc2VkO1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRncmF5LWNvbG9yO1xuICAgIGNvbG9yOiAkbGlnaHQtYmxhY2stY29sb3I7XG4gICAgdGV4dC1yZW5kZXJpbmc6IG9wdGltaXplTGVnaWJpbGl0eSAhaW1wb3J0YW50O1xuICAgIGxldHRlci1zcGFjaW5nOiAwLjVweDtcbiAgICBvdmVyZmxvdy14OiBoaWRkZW47XG59XG5AaW5jbHVkZSBzZWxlY3Rpb24ge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xufVxuYSB7XG4gICAgb3V0bGluZTogbm9uZSAhaW1wb3J0YW50O1xuICAgIHRleHQtZGVjb3JhdGlvbjogbm9uZSAhaW1wb3J0YW50O1xuICAgIGNvbG9yOiAkbGlnaHQtYmxhY2stY29sb3I7XG4gICAgQGluY2x1ZGUgdHJhbnNpdGlvbihhbGwgMC40cyBlYXNlLWluLW91dCk7XG59XG5jb2RlOm5vdCgubGFuZ3VhZ2UtaHRtbCkge1xuICAgIGZvbnQtd2VpZ2h0OiA2MDA7XG59XG5cbi8vIENPTE9SIFBBTEVUVEUgQ0xBU1NFU1xuQGltcG9ydCBcImNvbG9yLWNsYXNzZXNcIjtcblxuLy8gSEVMUEVSIENMQVNTRVNcbkBpbXBvcnQgXCJoZWxwZXJzXCI7XG5cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgVE9QIE5BVkJBUlxuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm5hdmJhciB7XG5cdGJvcmRlci1yYWRpdXM6IDA7XG5cdGJvcmRlcjogMHB4O1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG4gICAgJi5ib3gtc2hhZG93IHtcbiAgICAgICAgYm94LXNoYWRvdzogMCAycHggNXB4IHJnYmEoMCwgMCwgMCwgMC4xNSk7XG4gICAgICAgIHotaW5kZXg6IDEwO1xuICAgIH1cbiAgICBhOmhvdmVyIHtcbiAgICAgICAgdGV4dC1kZWNvcmF0aW9uOiBub25lO1xuICAgICAgICBjb2xvcjogJGJsYWNrLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxufVxuLm5hdmJhci10b2dnbGUge1xuXHRmb250LXNpemU6IDIwcHg7XG59XG4ubmF2YmFyLWhlYWRlciB7XG5cdG1pbi13aWR0aDogJGxlZnQtc2lkZWJhci13aWR0aDtcblx0cGFkZGluZy1sZWZ0OiAxNXB4O1xuICAgIEBpbmNsdWRlIHRyYW5zaXRpb24oYWxsIDAuNHMgZWFzZS1pbi1vdXQpO1xuICAgIG92ZXJmbG93OiBoaWRkZW47XG5cdC5uYXZiYXItYnJhbmQge1xuXHRcdHBhZGRpbmc6IDEycHg7XG5cdH1cblx0LmxvZ28ge1xuXHRcdGhlaWdodDogMjZweDtcblx0fVxuICAgICYuc21hbGwtbmF2LWhlYWRlciB7XG4gICAgICAgIG1pbi13aWR0aDogNTBweDtcbiAgICAgICAgd2lkdGg6IDUwcHg7XG4gICAgICAgIC5uYXZiYXItYnJhbmQge1xuICAgICAgICAgICAgZGlzcGxheTogbm9uZTtcbiAgICAgICAgfVxuICAgIH1cbn1cbi5zbWFsbC1uYXYtaGFuZGxlIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgd2lkdGg6IDUwcHg7XG4gICAgaGVpZ2h0OiA1MHB4O1xuICAgIGZsb2F0OiByaWdodDtcbiAgICBjdXJzb3I6IHBvaW50ZXI7XG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgIC5mYSB7XG4gICAgICAgIGxpbmUtaGVpZ2h0OiA1MHB4O1xuICAgIH1cbn1cbi5kcm9wZG93bi1tZW51IHtcblx0Ym94LXNoYWRvdzogMCAycHggNXB4IHJnYmEoMCwgMCwgMCwgMC4xNSk7XG5cdG1pbi13aWR0aDogMjIwcHg7XG5cdHBhZGRpbmc6IDA7XG5cdGJvcmRlcjogMDtcblx0Jj5saTpmaXJzdC1jaGlsZCB7XG5cdFx0cGFkZGluZy10b3A6IDhweDtcblx0fVxuXHQmPmxpPmEge1xuXHRcdHBhZGRpbmc6IDhweCAyMHB4O1xuXHRcdC5mYSB7XG5cdFx0XHRtYXJnaW4tcmlnaHQ6IDVweDtcblx0XHR9XG5cdH1cblx0LmRpdmlkZXIge1xuXHRcdG1hcmdpbjogNXB4IDA7XG5cdH1cblx0LnByb2ZpbGUtbWVudSB7XG5cdFx0cGFkZGluZzogMTVweCAhaW1wb3J0YW50O1xuXHRcdC5wcm9maWxlLWltZyB7XG5cdFx0XHR3aWR0aDogNTBweDtcblx0XHR9XG5cdFx0LnByb2ZpbGUtbmFtZSB7XG5cdFx0XHR3aWR0aDogMTIwcHg7XG5cdFx0XHRmbG9hdDogcmlnaHQ7XG5cdFx0XHRoNiB7XG5cdFx0XHRcdG1hcmdpbi10b3A6IDA7XG5cdFx0XHRcdG1hcmdpbi1ib3R0b206IDVweDtcblx0XHRcdFx0bGluZS1oZWlnaHQ6IDEuNzU7XG5cdFx0XHR9XG5cdFx0XHRhIHtcblx0XHRcdFx0Zm9udC1zaXplOiA4NSU7XG5cdFx0XHR9XG5cdFx0fVxuXHR9XG5cdCYuYW5pbWF0ZWQge1xuXHRcdGFuaW1hdGlvbi1kdXJhdGlvbjogMC40cztcblx0fVxufVxuQG1lZGlhIChtaW4td2lkdGg6IDk5MnB4KSB7XG4gICAgLnRvcC1uYXZiYXItZml4ZWQge1xuICAgICAgICAudG9wLW5hdmJhciB7XG4gICAgICAgICAgICBwb3NpdGlvbjogZml4ZWQ7XG4gICAgICAgICAgICB3aWR0aDogMTAwJTtcbiAgICAgICAgICAgIHRvcDogMDtcbiAgICAgICAgICAgIGxlZnQ6IDA7XG4gICAgICAgICAgICB6LWluZGV4OiAxMDtcbiAgICAgICAgfVxuICAgICAgICAuY29udGVudC13cmFwcGVyIHtcbiAgICAgICAgICAgIG1hcmdpbi10b3A6IDUwcHg7XG4gICAgICAgIH1cbiAgICB9XG59XG5cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgU0lERUJBUlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5jb250ZW50LXdyYXBwZXIge1xuICAgIG1pbi1oZWlnaHQ6IDEwMHZoO1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cbkBtZWRpYSAobWluLXdpZHRoOiA3NjlweCkge1xuICAgIC5jb250ZW50LXdyYXBwZXIge1xuICAgICAgICBkaXNwbGF5OiB0YWJsZTtcbiAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgICAgIHRhYmxlLWxheW91dDogZml4ZWQ7XG4gICAgfVxuICAgIC5jb250ZW50LWNvbnRhaW5lciB7XG4gICAgICAgIGRpc3BsYXk6IHRhYmxlLXJvdztcbiAgICB9XG4gICAgLmxlZnQtc2lkZWJhciwgLm1haW4tcGFnZSwgLnJpZ2h0LXNpZGViYXIge1xuICAgICAgICBkaXNwbGF5OiB0YWJsZS1jZWxsO1xuICAgICAgICB2ZXJ0aWNhbC1hbGlnbjogdG9wO1xuICAgIH1cbiAgICAucmlnaHQtc2lkZWJhciB7XG4gICAgICAgIHdpZHRoOiA0MDBweDtcbiAgICAgICAgaGVpZ2h0OiAxMDAlO1xuICAgICAgICBib3gtc2hhZG93OiAwIDJweCA1cHggcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICByaWdodDogLTQwMHB4O1xuICAgICAgICB6LWluZGV4OiA5O1xuICAgICAgICBAaW5jbHVkZSB0cmFuc2l0aW9uKGFsbCAwLjRzIGVhc2UtaW4tb3V0KTtcbiAgICB9XG4gICAgLmxlZnQtc2lkZWJhciB7XG4gICAgICAgIHdpZHRoOiAkbGVmdC1zaWRlYmFyLXdpZHRoO1xuICAgICAgICBAaW5jbHVkZSB0cmFuc2l0aW9uKGFsbCAwLjRzIGVhc2UtaW4tb3V0KTtcbiAgICB9XG59XG4ucmlnaHQtc2lkZWJhciB7XG4gICAgJi5maXhlZC1zaWRlYmFyIHtcbiAgICAgICAgLnNpZGViYXItY29udGVudCB7XG4gICAgICAgICAgICBwb3NpdGlvbjogZml4ZWQ7XG4gICAgICAgICAgICB3aWR0aDogNDAwcHg7XG4gICAgICAgICAgICBoZWlnaHQ6IGNhbGMoMTAwJSAtIDUwcHgpO1xuICAgICAgICAgICAgb3ZlcmZsb3c6IHNjcm9sbDtcbiAgICAgICAgICAgIHJpZ2h0OiAtNDAwcHg7XG4gICAgICAgICAgICBAaW5jbHVkZSB0cmFuc2l0aW9uKGFsbCAwLjRzIGVhc2UtaW4tb3V0KTtcbiAgICAgICAgfVxuICAgIH1cbiAgICAuY2xvc2UtaWNvbiB7XG4gICAgICAgIGZsb2F0OiByaWdodDtcbiAgICAgICAgY3Vyc29yOiBwb2ludGVyO1xuICAgIH1cbn1cbi5sZWZ0LXNpZGViYXIge1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICAudXNlci1pbmZvIHtcbiAgICAgICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgICAgICBwYWRkaW5nLXRvcDogMTVweDtcbiAgICAgICAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgICAgICAgaGVpZ2h0OiAxNzBweDtcbiAgICAgICAgQGluY2x1ZGUgdHJhbnNpdGlvbihhbGwgMC40cyBlYXNlLWluLW91dCk7XG4gICAgICAgIC50aXRsZSB7XG4gICAgICAgICAgICBtYXJnaW46IDA7XG4gICAgICAgICAgICBtYXJnaW4tdG9wOiA1cHg7XG4gICAgICAgICAgICBsaW5lLWhlaWdodDogMS43NTtcbiAgICAgICAgICAgIGNvbG9yOiBpbmhlcml0ICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgJi5jbG9zZWQge1xuICAgICAgICAgICAgaGVpZ2h0OiAwcHg7XG4gICAgICAgIH1cbiAgICB9XG4gICAgLnB1cmNoYXNlLWJ0biB7XG4gICAgICAgIG1hcmdpbi1ib3R0b206IDMwcHg7XG4gICAgICAgIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgICB9XG4gICAgLnNpZGUtbmF2IHtcbiAgICAgICAgbGlzdC1zdHlsZTogbm9uZTtcbiAgICAgICAgcGFkZGluZy1sZWZ0OiAwO1xuICAgICAgICAubmF2LWhlYWRlciB7XG4gICAgICAgICAgICBmb250LXNpemU6IDgwJTtcbiAgICAgICAgICAgIHRleHQtdHJhbnNmb3JtOiB1cHBlcmNhc2U7XG4gICAgICAgICAgICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gICAgICAgICAgICBwYWRkaW5nLXRvcDogMTBweDtcbiAgICAgICAgICAgIG9wYWNpdHk6IDAuODtcbiAgICAgICAgICAgICY6Zmlyc3QtY2hpbGQge1xuICAgICAgICAgICAgICAgIHBhZGRpbmctdG9wOiAwO1xuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgICAgIGEge1xuICAgICAgICAgICAgY29sb3I6IGluaGVyaXQ7XG4gICAgICAgIH1cbiAgICAgICAgbGkge1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICAgICAgLmZhIHtcbiAgICAgICAgICAgICAgICB3aWR0aDogMjVweDtcbiAgICAgICAgICAgICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAmLmhhcy1jaGlsZHJlbiB7XG4gICAgICAgICAgICAgICAgLmFycm93IHtcbiAgICAgICAgICAgICAgICAgICAgZmxvYXQ6IHJpZ2h0O1xuICAgICAgICAgICAgICAgICAgICBwYWRkaW5nOiA1cHg7XG4gICAgICAgICAgICAgICAgICAgIEBpbmNsdWRlIHRyYW5zaXRpb24oYWxsIDAuNHMgZWFzZS1pbi1vdXQpO1xuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgIH1cbiAgICAgICAgICAgIGEge1xuICAgICAgICAgICAgICAgIHBhZGRpbmc6IDEwcHggMDtcbiAgICAgICAgICAgICAgICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gICAgICAgICAgICAgICAgZGlzcGxheTogYmxvY2s7XG4gICAgICAgICAgICAgICAgQGluY2x1ZGUgdHJhbnNpdGlvbihhbGwgMC40cyBlYXNlLWluLW91dCk7XG4gICAgICAgICAgICAgICAgJjpob3ZlciB7XG4gICAgICAgICAgICAgICAgICAgIGJhY2tncm91bmQ6IHJnYmEoMCwwLDAsMC4xNSk7XG4gICAgICAgICAgICAgICAgICAgIGNvbG9yOiBpbmhlcml0O1xuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgIH1cbiAgICAgICAgICAgICYuYWN0aXZlIHtcbiAgICAgICAgICAgICAgICBiYWNrZ3JvdW5kOiByZ2JhKDAsMCwwLDAuMTUpO1xuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgICAgIC5jaGlsZC1uYXYge1xuICAgICAgICAgICAgbGlzdC1zdHlsZTogbm9uZTtcbiAgICAgICAgICAgIHBhZGRpbmctbGVmdDogMDtcbiAgICAgICAgICAgIGEge1xuICAgICAgICAgICAgICAgIHBhZGRpbmctbGVmdDogNDBweDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgICAgICAuaGFzLWNoaWxkcmVuIHtcbiAgICAgICAgICAgICYub3BlbiB7XG4gICAgICAgICAgICAgICAgYmFja2dyb3VuZDogcmdiYSgwLDAsMCwwLjE1KTtcbiAgICAgICAgICAgICAgICAuYXJyb3cge1xuICAgICAgICAgICAgICAgICAgICB0cmFuc2Zvcm06IHJvdGF0ZSg5MGRlZyk7XG4gICAgICAgICAgICAgICAgICAgIHBhZGRpbmctdG9wOiAxNXB4O1xuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbiAgICAmLnNtYWxsLW5hdiB7XG4gICAgICAgIHdpZHRoOiA1MHB4O1xuICAgICAgICB6LWluZGV4OiA4O1xuICAgICAgICAudXNlci1pbmZvIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IG5vbmU7XG4gICAgICAgIH1cbiAgICAgICAgbGkgc3BhbiB7XG4gICAgICAgICAgICBkaXNwbGF5OiBub25lO1xuICAgICAgICB9XG4gICAgICAgIC5hcnJvdyB7XG4gICAgICAgICAgICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgLnNpZGViYXItY29udGVudCB7XG4gICAgICAgICAgICB3aWR0aDogNTBweDtcbiAgICAgICAgfVxuICAgICAgICAuY2hpbGQtbmF2IHtcbiAgICAgICAgICAgIGRpc3BsYXk6IG5vbmUgIWltcG9ydGFudDtcbiAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgIHRvcDogMDtcbiAgICAgICAgICAgIGxlZnQ6IDUwcHg7XG4gICAgICAgICAgICB3aWR0aDogJGxlZnQtc2lkZWJhci13aWR0aDtcbiAgICAgICAgICAgIHotaW5kZXg6IDk7XG4gICAgICAgIH1cbiAgICAgICAgLnNpZGUtbmF2ID4gbGkge1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICAgICAgJjpob3ZlciB7XG4gICAgICAgICAgICAgICAgJj5hPnNwYW4ge1xuICAgICAgICAgICAgICAgICAgICBkaXNwbGF5OiBibG9jaztcbiAgICAgICAgICAgICAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICAgICAgICAgICAgICB0b3A6IDA7XG4gICAgICAgICAgICAgICAgICAgIGxlZnQ6IDUwcHg7XG4gICAgICAgICAgICAgICAgICAgIHdpZHRoOiAkbGVmdC1zaWRlYmFyLXdpZHRoO1xuICAgICAgICAgICAgICAgICAgICBwYWRkaW5nOiAxMHB4IDA7XG4gICAgICAgICAgICAgICAgICAgIHBhZGRpbmctbGVmdDogMTVweDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICAgICAgLnB1cmNoYXNlLWJ0biB7XG4gICAgICAgICAgICBkaXNwbGF5OiBub25lO1xuICAgICAgICB9XG4gICAgICAgIC5oYXMtY2hpbGRyZW4ge1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICAgICAgJjpob3ZlciB7XG4gICAgICAgICAgICAgICAgLmNoaWxkLW5hdiB7XG4gICAgICAgICAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrICFpbXBvcnRhbnQ7XG4gICAgICAgICAgICAgICAgICAgIGEge1xuICAgICAgICAgICAgICAgICAgICAgICAgcGFkZGluZy1sZWZ0OiAyMHB4O1xuICAgICAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICAgICAgICAgIHNwYW4ge1xuICAgICAgICAgICAgICAgICAgICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgICAgICY6aG92ZXIge1xuICAgICAgICAgICAgLnNpZGViYXItY29udGVudCB7XG4gICAgICAgICAgICAgICAgd2lkdGg6ICRsZWZ0LXNpZGViYXItd2lkdGg7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG59XG5AbWVkaWEgKG1heC13aWR0aDogOTkxcHgpIHtcbiAgICAubGVmdC1zaWRlYmFyIHtcbiAgICAgICAgZGlzcGxheTogbm9uZTtcbiAgICB9XG59XG5AbWVkaWEgKG1pbi13aWR0aDogOTkxcHgpIHtcbiAgICAubGVmdC1zaWRlYmFyIHtcbiAgICAgICAgJi5maXhlZC1zaWRlYmFyIHtcbiAgICAgICAgICAgIC5zaWRlYmFyLWNvbnRlbnQge1xuICAgICAgICAgICAgICAgIHBvc2l0aW9uOiBmaXhlZDtcbiAgICAgICAgICAgICAgICB3aWR0aDogJGxlZnQtc2lkZWJhci13aWR0aDtcbiAgICAgICAgICAgICAgICBoZWlnaHQ6IGNhbGMoMTAwJSAtIDUwcHgpO1xuICAgICAgICAgICAgICAgIG92ZXJmbG93OiBzY3JvbGw7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG59XG5cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTEFZT1VUXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ubWFpbi1wYWdlIHtcbiAgICB3aWR0aDogMTAwJTtcbiAgICBhOm5vdCguYnRuKSB7XG4gICAgICAgIGNvbG9yOiBpbmhlcml0O1xuICAgIH1cbn1cbi5wYWdlLXRpdGxlLWRpdiB7XG4gICAgYmFja2dyb3VuZDogJHdoaXRlLWNvbG9yO1xuICAgIHBhZGRpbmc6IDE1cHg7XG4gICAgLnRpdGxlIHtcbiAgICAgICAgbWFyZ2luLXRvcDogMTBweDtcbiAgICB9XG4gICAgLnN1Yi10aXRsZSB7XG4gICAgICAgIGNvbG9yOiAkbGlnaHRlci1ibGFjay1jb2xvcjtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMDtcbiAgICB9XG4gICAgLnJpZ2h0LXNpZGUge1xuICAgICAgICB0ZXh0LWFsaWduOiByaWdodDtcbiAgICAgICAgLmJ0biB7XG4gICAgICAgICAgICBtYXJnaW4tdG9wOiAxMnB4O1xuICAgICAgICB9XG4gICAgfVxuICAgICYuZGFyay10aXRsZSB7XG4gICAgICAgIGJhY2tncm91bmQ6ICRibGFjay1jb2xvcjtcbiAgICAgICAgLnRpdGxlIHtcbiAgICAgICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgIH1cbn1cbi5icmVhZGNydW1iLWRpdiB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgIHBhZGRpbmc6IDhweCAxNXB4O1xuICAgIGJvcmRlci10b3A6IDFweCBzb2xpZCAkZ3JheS1jb2xvcjtcbiAgICBib3JkZXItYm90dG9tOiAxcHggc29saWQgJGdyYXktY29sb3I7XG4gICAgZm9udC1zaXplOiA5MCU7XG4gICAgY29sb3I6ICRsaWdodGVyLWJsYWNrLWNvbG9yO1xuICAgIGEge1xuICAgICAgICBjb2xvcjogaW5oZXJpdDtcbiAgICAgICAgJjpob3ZlciB7XG4gICAgICAgICAgICBjb2xvcjogJHByaW1hcnktY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgIH1cbiAgICAuYnJlYWRjcnVtYiB7XG4gICAgICAgIGJhY2tncm91bmQ6IHRyYW5zcGFyZW50O1xuICAgICAgICBwYWRkaW5nOiAwO1xuICAgICAgICBtYXJnaW46IDA7XG4gICAgICAgIC5mYSB7XG4gICAgICAgICAgICBtYXJnaW4tcmlnaHQ6IDVweDtcbiAgICAgICAgfVxuICAgIH1cbiAgICAudGV4dC1yaWdodCB7XG4gICAgICAgIGEge1xuICAgICAgICAgICAgLmZhIHtcbiAgICAgICAgICAgICAgICBtYXJnaW4tcmlnaHQ6IDJweDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbn1cbi5jb250ZW50LWludGVybmFsIHtcbiAgICBtYXJnaW4tcmlnaHQ6IC0yODBweDtcbiAgICB3aWR0aDogMTAwJTtcbiAgICBmbG9hdDogbGVmdDtcbiAgICAuY29udGVudCB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogMjgwcHg7XG4gICAgICAgIGJhY2tncm91bmQ6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgcGFkZGluZzogMTVweDtcbiAgICB9XG59XG4uc2lkZWJhci1pbnRlcm5hbCB7XG4gICAgZmxvYXQ6IHJpZ2h0O1xuICAgICYuYWZmaXgge1xuICAgICAgICByaWdodDogMTVweDtcbiAgICAgICAgdG9wOiA4MHB4O1xuICAgICAgICBwb3NpdGlvbjogZml4ZWQgIWltcG9ydGFudDtcbiAgICB9XG4gICAgLnNpZGViYXIge1xuICAgICAgICB3aWR0aDogMjYwcHg7XG4gICAgICAgIGJhY2tncm91bmQ6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgcGFkZGluZzogMTVweDtcbiAgICB9XG59XG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFBBTkVMU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLnBhbmVsIHtcbiAgICBib3gtc2hhZG93OiAwIDFweCAycHggcmdiYSgwLDAsMCwwLjEpO1xuICAgIC5wYW5lbC10aXRsZSB7XG4gICAgICAgIGgxLCBoMiwgaDMsIGg0LCBoNSwgaDYge1xuICAgICAgICAgICAgY29sb3I6IGluaGVyaXQgIWltcG9ydGFudDtcbiAgICAgICAgICAgIG1hcmdpbjogMDtcbiAgICAgICAgICAgIGxpbmUtaGVpZ2h0OiAzMHB4O1xuICAgICAgICB9XG4gICAgfVxufVxuLnBhbmVsLWhlYWRpbmcge1xuICAgIHBhZGRpbmc6IDVweDtcbiAgICAucGFuZWwtdGl0bGUge1xuICAgICAgICBtYXJnaW4tdG9wOiAxMHB4O1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gICAgICAgIHNtYWxsIHtcbiAgICAgICAgICAgIGNvbG9yOiAkbGlnaHRlci1ibGFjay1jb2xvcjtcbiAgICAgICAgICAgIGZvbnQtc2l6ZTogNzUlO1xuICAgICAgICAgICAgZm9udC1zdHlsZTogaXRhbGljO1xuICAgICAgICAgICAgbWFyZ2luLWxlZnQ6IDVweDtcbiAgICAgICAgfVxuICAgIH1cbn1cbi5sb2JpcGFuZWwge1xuICAgIG1hcmdpbi1ib3R0b206IDIwcHg7XG59XG4ubG9iaXBhbmVsPi5wYW5lbC1oZWFkaW5nPi5wYW5lbC10aXRsZSBoMSwgLmxvYmlwYW5lbD4ucGFuZWwtaGVhZGluZz4ucGFuZWwtdGl0bGUgaDIsIC5sb2JpcGFuZWw+LnBhbmVsLWhlYWRpbmc+LnBhbmVsLXRpdGxlIGgzLCAubG9iaXBhbmVsPi5wYW5lbC1oZWFkaW5nPi5wYW5lbC10aXRsZSBoNCwgLmxvYmlwYW5lbD4ucGFuZWwtaGVhZGluZz4ucGFuZWwtdGl0bGUgaDUsIC5sb2JpcGFuZWw+LnBhbmVsLWhlYWRpbmc+LnBhbmVsLXRpdGxlIGg2IHtcbiAgICBsaW5lLWhlaWdodDogaW5oZXJpdDtcbiAgICBtYXJnaW4tdG9wOiAwcHg7XG59XG4ubG9iaXBhbmVsPi5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tdG9nZ2xlIC5wYW5lbC1jb250cm9sLWljb24ge1xuICAgIGxpbmUtaGVpZ2h0OiBpbmhlcml0O1xuICAgIG1hcmdpbi10b3A6IDEwcHg7XG59XG4ubG9iaXBhbmVsIC5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tbWVudT5saT5hIHtcbiAgICBmb250LXNpemU6IDEycHg7XG59XG4ubG9iaXBhbmVsIC5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tbWVudT5saT5hOmZvY3VzOmhvdmVyLCAubG9iaXBhbmVsIC5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tbWVudT5saT5hOmhvdmVyIHtcbiAgICB0ZXh0LXNoYWRvdzogbm9uZTtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsMCwwLC4xKTtcbn1cbi5sb2JpcGFuZWw+LnBhbmVsLWhlYWRpbmc+LnBhbmVsLXRpdGxlIGlucHV0IHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsMCwwLDAuMSk7XG4gICAgYm9yZGVyOiAwO1xufVxuLmxvYmlwYW5lbD4ucGFuZWwtaGVhZGluZz4ucGFuZWwtdGl0bGUge1xuICAgIG1hcmdpbi10b3A6IDEwcHg7XG59XG4ubG9iaXBhbmVsLnBhbmVsLWV4cGFuZGVkIHtcbiAgICBib3JkZXItcmFkaXVzOiAwO1xufVxuLmxvYmlwYW5lbC5wYW5lbC11bnBpbiB7XG4gICAgYm94LXNoYWRvdzogMCAycHggNXB4IHJnYmEoMCwgMCwgMCwgMC4xNSk7XG59XG4ubG9iaXBhbmVsPi5wYW5lbC1oZWFkaW5nIHtcbiAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogNHB4O1xuICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDRweDtcbn1cbkBtaXhpbiBwYW5lbC1jb2xvcnMoJGJnY29sb3IsICR0eHRjb2xvcjogJHdoaXRlLWNvbG9yKSB7XG4gICAgLnBhbmVsLWhlYWRpbmcge1xuICAgICAgICBjb2xvcjogJHR4dGNvbG9yO1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkYmdjb2xvcjtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJGJnY29sb3IsIDUlKTtcbiAgICAgICAgc21hbGwge1xuICAgICAgICAgICAgY29sb3I6ICR0eHRjb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbiAgICBib3JkZXItY29sb3I6IGRhcmtlbigkYmdjb2xvciwgNSUpO1xufVxuLnBhbmVsIHtcbiAgICAmLWRlZmF1bHQge1xuICAgICAgICBAaW5jbHVkZSBwYW5lbC1jb2xvcnMoJGdyYXktY29sb3IsICRibGFjay1jb2xvcik7XG4gICAgfVxuICAgICYtcHJpbWFyeSB7XG4gICAgICAgIEBpbmNsdWRlIHBhbmVsLWNvbG9ycygkcHJpbWFyeS1jb2xvcik7XG4gICAgfVxuICAgICYtZGFuZ2VyIHtcbiAgICAgICAgQGluY2x1ZGUgcGFuZWwtY29sb3JzKCRkYW5nZXItY29sb3IpO1xuICAgIH1cbiAgICAmLXN1Y2Nlc3Mge1xuICAgICAgICBAaW5jbHVkZSBwYW5lbC1jb2xvcnMoJHN1Y2Nlc3MtY29sb3IpO1xuICAgIH1cbiAgICAmLXdhcm5pbmcge1xuICAgICAgICBAaW5jbHVkZSBwYW5lbC1jb2xvcnMoJHdhcm5pbmctY29sb3IpO1xuICAgIH1cbiAgICAmLWluZm8ge1xuICAgICAgICBAaW5jbHVkZSBwYW5lbC1jb2xvcnMoJGluZm8tY29sb3IpO1xuICAgIH1cbiAgICAmLWJsYWNrIHtcbiAgICAgICAgQGluY2x1ZGUgcGFuZWwtY29sb3JzKCRibGFjay1jb2xvcik7XG4gICAgfVxuICAgICYtbGlnaHQtYmxhY2sge1xuICAgICAgICBAaW5jbHVkZSBwYW5lbC1jb2xvcnMoJGxpZ2h0LWJsYWNrLWNvbG9yKTtcbiAgICB9XG59XG4uYWNjLXBhbmVscyB7XG4gICAgLnBhbmVsLWhlYWRpbmcgLnBhbmVsLXRpdGxlIHtcbiAgICAgICAgbWFyZ2luLXRvcDogNXB4O1xuICAgICAgICBhIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgICAgICAgLmljb24tcGx1cyB7XG4gICAgICAgICAgICAgICAgbWFyZ2luLXJpZ2h0OiA1cHg7XG4gICAgICAgICAgICAgICAgQGluY2x1ZGUgdHJhbnNpdGlvbihhbGwgMC40cyBlYXNlLWluLW91dCk7XG4gICAgICAgICAgICAgICAgJi1yaWdodCB7XG4gICAgICAgICAgICAgICAgICAgIGZsb2F0OiByaWdodDtcbiAgICAgICAgICAgICAgICAgICAgbWFyZ2luLXRvcDogNXB4O1xuICAgICAgICAgICAgICAgICAgICBtYXJnaW4tcmlnaHQ6IDVweDtcbiAgICAgICAgICAgICAgICAgICAgQGluY2x1ZGUgdHJhbnNpdGlvbihhbGwgMC40cyBlYXNlLWluLW91dCk7XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuICAgICAgICAgICAgJlthcmlhLWV4cGFuZGVkPXRydWVdIHtcbiAgICAgICAgICAgICAgICAuaWNvbi1wbHVzIHtcbiAgICAgICAgICAgICAgICAgICAgbWFyZ2luLXJpZ2h0OiA1cHg7XG4gICAgICAgICAgICAgICAgICAgIHRyYW5zZm9ybTogcm90YXRlKDEzNWRlZyk7XG4gICAgICAgICAgICAgICAgICAgICYtcmlnaHQge1xuICAgICAgICAgICAgICAgICAgICAgICAgdHJhbnNmb3JtOiByb3RhdGUoMTM1ZGVnKTtcbiAgICAgICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbn1cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgVEFCU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm5hdi10YWJzIHtcbiAgICAmLnJpZ2h0LWFsaWduZWQge1xuICAgICAgICBsaSB7XG4gICAgICAgICAgICBmbG9hdDogcmlnaHQ7XG4gICAgICAgIH1cbiAgICB9XG4gICAgLmRyb3Bkb3duLW1lbnUgPiAuYWN0aXZlID4gYSwgLmRyb3Bkb3duLW1lbnUgPiAuYWN0aXZlID4gYTpob3ZlciwgLmRyb3Bkb3duLW1lbnUgPiAuYWN0aXZlID4gYTpmb2N1cyB7XG4gICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgfVxufVxuLm5hdi10YWJzID4gbGkgPiBhIHtcbiAgICBvcGFjaXR5OiAwLjQ7XG59XG4ubmF2LXRhYnMgPiBsaS5hY3RpdmUgPiBhIHtcbiAgICBvcGFjaXR5OiAxO1xufVxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20gPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbSA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tID4gbGkuYWN0aXZlID4gYTpmb2N1cyB7XG4gICAgYm9yZGVyOiAwICFpbXBvcnRhbnQ7XG4gICAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICNkZGQgIWltcG9ydGFudDtcbn1cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tID4gbGkgPiBhIHtcbiAgICBib3JkZXI6IDAgIWltcG9ydGFudDtcbn1cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1wcmltYXJ5ID4gbGkuYWN0aXZlID4gYSwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXByaW1hcnkgPiBsaS5hY3RpdmUgPiBhOmhvdmVyLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItcHJpbWFyeSA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICAgIGJvcmRlci1ib3R0b206IDRweCBzb2xpZCAkcHJpbWFyeS1jb2xvciAhaW1wb3J0YW50O1xufVxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLWRhbmdlciA+IGxpLmFjdGl2ZSA+IGEsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1kYW5nZXIgPiBsaS5hY3RpdmUgPiBhOmhvdmVyLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItZGFuZ2VyID4gbGkuYWN0aXZlID4gYTpmb2N1cyB7XG4gICAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICRkYW5nZXItY29sb3IgIWltcG9ydGFudDtcbn1cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1zdWNjZXNzID4gbGkuYWN0aXZlID4gYSwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXN1Y2Nlc3MgPiBsaS5hY3RpdmUgPiBhOmhvdmVyLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItc3VjY2VzcyA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICAgIGJvcmRlci1ib3R0b206IDRweCBzb2xpZCAkc3VjY2Vzcy1jb2xvciAhaW1wb3J0YW50O1xufVxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXdhcm5pbmcgPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItd2FybmluZyA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci13YXJuaW5nID4gbGkuYWN0aXZlID4gYTpmb2N1cyB7XG4gICAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICR3YXJuaW5nLWNvbG9yICFpbXBvcnRhbnQ7XG59XG4ubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItYmxhY2sgPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItYmxhY2sgPiBsaS5hY3RpdmUgPiBhOmhvdmVyLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItYmxhY2sgPiBsaS5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgICBib3JkZXItYm90dG9tOiA0cHggc29saWQgJGJsYWNrLWNvbG9yICFpbXBvcnRhbnQ7XG59XG4ubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItZ3JheSA+IGxpLmFjdGl2ZSA+IGEsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1ncmF5ID4gbGkuYWN0aXZlID4gYTpob3ZlciwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLWdyYXkgPiBsaS5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgICBib3JkZXItYm90dG9tOiA0cHggc29saWQgJGdyYXktY29sb3IgIWltcG9ydGFudDtcbn1cbi50YWJzLWxlZnQge1xuXHQubmF2LXRhYnMge1xuXHRcdGZsb2F0OiBsZWZ0O1xuXHRcdGJvcmRlci1ib3R0b206IDA7XG5cdFx0bGkge1xuXHRcdFx0ZmxvYXQ6IG5vbmU7XG5cdFx0XHRtYXJnaW46IDA7XG5cdFx0XHRhIHtcblx0XHRcdFx0bWFyZ2luLXJpZ2h0OiAwO1xuXHRcdFx0XHRib3JkZXI6IDA7XG5cdFx0XHRcdGJhY2tncm91bmQtY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICAgICAgICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgICAgICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDA7XG4gICAgICAgICAgICAgICAgb3BhY2l0eTogMTtcblx0XHRcdFx0Jjpob3ZlciB7XG5cdFx0XHRcdFx0YmFja2dyb3VuZC1jb2xvcjogJGxpZ2h0LWJsYWNrLWNvbG9yO1xuXHRcdFx0XHR9XG5cdFx0XHR9XG5cdFx0fVxuXHR9XG4gICAgLnRhYi1jb250ZW50IHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDQ1cHg7XG4gICAgICAgIC50YWItcGFuZSB7XG4gICAgICAgICAgICBkaXNwbGF5OiBub25lO1xuICAgICAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGdyYXktY29sb3I7XG4gICAgICAgICAgICBwYWRkaW5nOiAxNXB4O1xuICAgICAgICAgICAgb3ZlcmZsb3cteTogYXV0bztcbiAgICAgICAgfVxuICAgICAgICAuYWN0aXZlIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgICB9XG4gICAgfVxuICAgIC5uYXYtdGFicz5saS5hY3RpdmU+YSwgLm5hdi10YWJzPmxpLmFjdGl2ZT5hOmhvdmVyLCAubmF2LXRhYnM+bGkuYWN0aXZlPmE6Zm9jdXMge1xuICAgICAgICBib3JkZXI6MDtcbiAgICAgICAgYmFja2dyb3VuZDogJGdyYXktY29sb3I7XG4gICAgICAgIGNvbG9yOiAkYmxhY2stY29sb3I7XG4gICAgfVxufVxuLnRhYnMtcmlnaHQge1xuXHQubmF2LXRhYnMge1xuXHRcdGZsb2F0OiByaWdodDtcblx0XHRib3JkZXItYm90dG9tOiAwO1xuXHRcdGxpIHtcblx0XHRcdGZsb2F0OiBub25lO1xuXHRcdFx0bWFyZ2luOiAwO1xuXHRcdFx0YSB7XG5cdFx0XHRcdG1hcmdpbi1sZWZ0OiAwO1xuXHRcdFx0XHRib3JkZXI6IDA7XG5cdFx0XHRcdGJhY2tncm91bmQtY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICAgICAgICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgICAgICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDA7XG4gICAgICAgICAgICAgICAgb3BhY2l0eTogMTtcblx0XHRcdFx0Jjpob3ZlciB7XG5cdFx0XHRcdFx0YmFja2dyb3VuZC1jb2xvcjogJGxpZ2h0LWJsYWNrLWNvbG9yO1xuXHRcdFx0XHR9XG5cdFx0XHR9XG5cdFx0fVxuXHR9XG4gICAgLnRhYi1jb250ZW50IHtcbiAgICAgICAgbWFyZ2luLXJpZ2h0OiA0NXB4O1xuICAgICAgICAudGFiLXBhbmUge1xuICAgICAgICAgICAgZGlzcGxheTogbm9uZTtcbiAgICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRncmF5LWNvbG9yO1xuICAgICAgICAgICAgcGFkZGluZzogMTVweDtcbiAgICAgICAgICAgIG92ZXJmbG93LXk6IGF1dG87XG4gICAgICAgIH1cbiAgICAgICAgLmFjdGl2ZSB7XG4gICAgICAgICAgICBkaXNwbGF5OiBibG9jaztcbiAgICAgICAgfVxuICAgIH1cbiAgICAubmF2LXRhYnM+bGkuYWN0aXZlPmEsIC5uYXYtdGFicz5saS5hY3RpdmU+YTpob3ZlciwgLm5hdi10YWJzPmxpLmFjdGl2ZT5hOmZvY3VzIHtcbiAgICAgICAgYm9yZGVyOjA7XG4gICAgICAgIGJhY2tncm91bmQ6ICRncmF5LWNvbG9yO1xuICAgICAgICBjb2xvcjogJGJsYWNrLWNvbG9yO1xuICAgIH1cbn1cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTEFCRUxTICYgQkFER0VTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ubGFiZWwge1xuICAgIHBhZGRpbmc6IDAuMmVtIDAuNmVtO1xufVxuLmxhYmVsLXJvdW5kZWQge1xuICAgIHBhZGRpbmc6IC4yZW0gMS4yZW0gLjNlbTtcbiAgICBib3JkZXItcmFkaXVzOiAyMHB4O1xufVxuLmxhYmVsLWZsYXQge1xuICAgIGJvcmRlci1yYWRpdXM6IDA7XG59XG4ubGFiZWwtd2lkZSB7XG4gICAgcGFkZGluZzogLjJlbSAxLjJlbSAuM2VtO1xufVxuLmxhYmVsLWJvcmRlcmVkIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgYm9yZGVyLXdpZHRoOiAycHg7XG4gICAgYm9yZGVyLXN0eWxlOiBzb2xpZDtcbiAgICAmLmxhYmVsLWRlZmF1bHQge1xuICAgICAgICBib3JkZXItY29sb3I6ICM3Nzc3Nzc7XG4gICAgICAgIGNvbG9yOiAjNzc3Nzc3ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYubGFiZWwtcHJpbWFyeSB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJHByaW1hcnktY29sb3I7XG4gICAgICAgIGNvbG9yOiAkcHJpbWFyeS1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLmxhYmVsLWRhbmdlciB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJGRhbmdlci1jb2xvcjtcbiAgICAgICAgY29sb3I6ICRkYW5nZXItY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi5sYWJlbC1zdWNjZXNzIHtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiAkc3VjY2Vzcy1jb2xvcjtcbiAgICAgICAgY29sb3I6ICRzdWNjZXNzLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYubGFiZWwtd2FybmluZyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJHdhcm5pbmctY29sb3I7XG4gICAgICAgIGNvbG9yOiAkd2FybmluZy1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLmxhYmVsLWluZm8ge1xuICAgICAgICBib3JkZXItY29sb3I6ICRpbmZvLWNvbG9yO1xuICAgICAgICBjb2xvcjogJGluZm8tY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi5sYWJlbC1ibGFjayB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJGJsYWNrLWNvbG9yO1xuICAgICAgICBjb2xvcjogJGJsYWNrLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYubGFiZWwtZ3JheSB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJGdyYXktY29sb3I7XG4gICAgICAgIGNvbG9yOiAkZ3JheS1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbn1cbi5iYWRnZSB7XG4gICAgJi5iYWRnZS1kZWZhdWx0IHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogIzc3Nzc3NztcbiAgICB9XG4gICAgJi5iYWRnZS1wcmltYXJ5IHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJHByaW1hcnktY29sb3I7XG4gICAgfVxuICAgICYuYmFkZ2UtZGFuZ2VyIHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGRhbmdlci1jb2xvcjtcbiAgICB9XG4gICAgJi5iYWRnZS1zdWNjZXNzIHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJHN1Y2Nlc3MtY29sb3I7XG4gICAgfVxuICAgICYuYmFkZ2Utd2FybmluZyB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICR3YXJuaW5nLWNvbG9yO1xuICAgIH1cbiAgICAmLmJhZGdlLWluZm8ge1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkaW5mby1jb2xvcjtcbiAgICB9XG4gICAgJi5iYWRnZS1ibGFjayB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICB9XG4gICAgJi5iYWRnZS1ncmF5IHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGdyYXktY29sb3I7XG4gICAgICAgIGNvbG9yOiAkYmxhY2stY29sb3I7XG4gICAgfVxuICAgICYuYmFkZ2UtYm9yZGVyZWQge1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgICAgIGJvcmRlci13aWR0aDogMnB4O1xuICAgICAgICBib3JkZXItc3R5bGU6IHNvbGlkO1xuICAgICAgICAmLmJhZGdlLWRlZmF1bHQge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiAjNzc3Nzc3O1xuICAgICAgICAgICAgY29sb3I6ICM3Nzc3NzcgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgICAgICAmLmJhZGdlLXByaW1hcnkge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiAkcHJpbWFyeS1jb2xvcjtcbiAgICAgICAgICAgIGNvbG9yOiAkcHJpbWFyeS1jb2xvciAhaW1wb3J0YW50O1xuICAgICAgICB9XG4gICAgICAgICYuYmFkZ2UtZGFuZ2VyIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogJGRhbmdlci1jb2xvcjtcbiAgICAgICAgICAgIGNvbG9yOiAkZGFuZ2VyLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgJi5iYWRnZS1zdWNjZXNzIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogJHN1Y2Nlc3MtY29sb3I7XG4gICAgICAgICAgICBjb2xvcjogJHN1Y2Nlc3MtY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgICAgICAmLmJhZGdlLXdhcm5pbmcge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiAkd2FybmluZy1jb2xvcjtcbiAgICAgICAgICAgIGNvbG9yOiAkd2FybmluZy1jb2xvciAhaW1wb3J0YW50O1xuICAgICAgICB9XG4gICAgICAgICYuYmFkZ2UtaW5mbyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6ICRpbmZvLWNvbG9yO1xuICAgICAgICAgICAgY29sb3I6ICRpbmZvLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgICAgIH1cbiAgICAgICAgJi5iYWRnZS1ibGFjayB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICAgICAgICAgIGNvbG9yOiAkYmxhY2stY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgICAgICAmLmJhZGdlLWdyYXkge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiAkZ3JheS1jb2xvcjtcbiAgICAgICAgICAgIGNvbG9yOiAkZ3JheS1jb2xvciAhaW1wb3J0YW50O1xuICAgICAgICB9XG4gICAgfVxufVxuXG5cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgU0VDVElPTlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5zZWN0aW9uIHtcbiAgICBwYWRkaW5nOiAzMHB4IDA7XG4gICAgLnNlY3Rpb24tdGl0bGUge1xuICAgICAgICAudGl0bGUge1xuICAgICAgICAgICAgbWFyZ2luLXRvcDogMDtcbiAgICAgICAgfVxuICAgICAgICAuc3ViLXRpdGxlIHtcbiAgICAgICAgICAgIGNvbG9yOiAkbGlnaHRlci1ibGFjay1jb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbn1cbi51bmRlcmxpbmUge1xuXHRwb3NpdGlvbjogcmVsYXRpdmU7XG5cdHBhZGRpbmctYm90dG9tOiAxMHB4O1xuXHRtYXJnaW4tYm90dG9tOiAxMnB4O1xuXHQmOmFmdGVyIHtcblx0XHRjb250ZW50OiBcIlwiO1xuXHRcdHdpZHRoOiAzMnB4O1xuXHRcdGhlaWdodDogMXB4O1xuXHRcdGJhY2tncm91bmQ6ICRsaWdodGVyLWJsYWNrLWNvbG9yO1xuXHRcdHBvc2l0aW9uOiBhYnNvbHV0ZTtcblx0XHRib3R0b206IDA7XG5cdFx0bGVmdDogMDtcblx0fVxufVxuLnRleHQtY2VudGVyIC51bmRlcmxpbmU6OmFmdGVyIHtcbiAgICB3aWR0aDogNCU7XG4gICAgbGVmdDogNDglO1xufVxuXG5cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBCVVRUT05TXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4uYnRuOmZvY3VzLCAuYnRuLmZvY3VzLCAuYnRuOmFjdGl2ZTpmb2N1cywgLmJ0bjphY3RpdmUuZm9jdXMsIC5idG4uYWN0aXZlOmZvY3VzLCAuYnRuLmFjdGl2ZS5mb2N1cyB7XG4gICAgb3V0bGluZTogMDtcbn1cbi5idG4tcm91bmRlZCB7XG4gICAgYm9yZGVyLXJhZGl1czogMzBweDtcbn1cbi5idG4td2lkZSB7XG4gICAgcGFkZGluZzogNnB4IDIycHg7XG59XG4uYnRuIHtcbiAgICAuZmEge1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDZweDtcbiAgICB9XG4gICAgJi5idG4tbGFiZWxlZCB7XG4gICAgICAgIHBhZGRpbmctdG9wOiAwO1xuICAgICAgICBwYWRkaW5nLWJvdHRvbTogMDtcbiAgICAgICAgLmZhIHtcbiAgICAgICAgICAgIG1hcmdpbi1yaWdodDogMHB4O1xuICAgICAgICB9XG4gICAgICAgIC5idG4tbGFiZWwge1xuICAgICAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICAgICAgYmFja2dyb3VuZDogdHJhbnNwYXJlbnQ7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kOiByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICAgICAgICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgICAgICAgcGFkZGluZzogNnB4IDEycHg7XG4gICAgICAgICAgICBsZWZ0OiAtMTJweDtcbiAgICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDRweCAwIDAgNHB4O1xuICAgICAgICAgICAgJi5idG4tbGFiZWwtcmlnaHQge1xuICAgICAgICAgICAgICAgIGxlZnQ6IGF1dG87XG4gICAgICAgICAgICAgICAgcmlnaHQ6IC0xMnB4O1xuICAgICAgICAgICAgICAgIGJvcmRlci1yYWRpdXM6IDAgNHB4IDRweCAwO1xuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgICAgICYuYnRuLXJvdW5kZWQge1xuICAgICAgICAgICAgLmJ0bi1sYWJlbCB7XG4gICAgICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogMzBweCAwIDAgMzBweDtcbiAgICAgICAgICAgICAgICAmLmJ0bi1sYWJlbC1yaWdodCB7XG4gICAgICAgICAgICAgICAgICAgIGxlZnQ6IGF1dG87XG4gICAgICAgICAgICAgICAgICAgIHJpZ2h0OiAtMTJweDtcbiAgICAgICAgICAgICAgICAgICAgYm9yZGVyLXJhZGl1czogMCAzMHB4IDMwcHggMDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5pY29uLW9ubHkge1xuICAgICAgICAuZmEge1xuICAgICAgICAgICAgbWFyZ2luLXJpZ2h0OiAwO1xuICAgICAgICB9XG4gICAgfVxuICAgICYuYnRuLWFuaW1hdGVkIHtcbiAgICAgICAgcG9zaXRpb246IHJlbGF0aXZlO1xuICAgICAgICBvdmVyZmxvdzogaGlkZGVuO1xuICAgICAgICAuaGlkZGVuLWNvbnRlbnQge1xuICAgICAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgICAgICAgICByaWdodDogLTEwMCU7XG4gICAgICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgICAgICBAaW5jbHVkZSB0cmFuc2l0aW9uKGFsbCAwLjRzIGVhc2UtaW4tb3V0KTtcbiAgICAgICAgfVxuICAgICAgICAudmlzaWJsZS1jb250ZW50IHtcbiAgICAgICAgICAgIEBpbmNsdWRlIHRyYW5zaXRpb24oYWxsIDAuNHMgZWFzZS1pbi1vdXQpO1xuICAgICAgICB9XG4gICAgICAgICY6aG92ZXIge1xuICAgICAgICAgICAgLmhpZGRlbi1jb250ZW50IHtcbiAgICAgICAgICAgICAgICByaWdodDogMDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgICAgIC52aXNpYmxlLWNvbnRlbnQge1xuICAgICAgICAgICAgICAgIG9wYWNpdHk6IDA7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5idG4tbGcge1xuICAgICAgICAmLmJ0bi1sYWJlbGVkIHtcbiAgICAgICAgICAgIC5idG4tbGFiZWwge1xuICAgICAgICAgICAgICAgIHBhZGRpbmc6IDEwcHggMTZweDtcbiAgICAgICAgICAgICAgICBsZWZ0OiAtMTZweDtcbiAgICAgICAgICAgICAgICAmLmJ0bi1sYWJlbC1yaWdodCB7XG4gICAgICAgICAgICAgICAgICAgIGxlZnQ6IGF1dG87XG4gICAgICAgICAgICAgICAgICAgIHJpZ2h0OiAtMTZweDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5idG4tc20ge1xuICAgICAgICAmLmJ0bi1sYWJlbGVkIHtcbiAgICAgICAgICAgIC5idG4tbGFiZWwge1xuICAgICAgICAgICAgICAgIHBhZGRpbmc6IDVweCAxMHB4O1xuICAgICAgICAgICAgICAgIGxlZnQ6IC0xMHB4O1xuICAgICAgICAgICAgICAgICYuYnRuLWxhYmVsLXJpZ2h0IHtcbiAgICAgICAgICAgICAgICAgICAgbGVmdDogYXV0bztcbiAgICAgICAgICAgICAgICAgICAgcmlnaHQ6IC0xMHB4O1xuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbiAgICAmLmJ0bi14cyB7XG4gICAgICAgICYuYnRuLWxhYmVsZWQge1xuICAgICAgICAgICAgLmJ0bi1sYWJlbCB7XG4gICAgICAgICAgICAgICAgcGFkZGluZzogMXB4IDVweDtcbiAgICAgICAgICAgICAgICBsZWZ0OiAtNXB4O1xuICAgICAgICAgICAgICAgICYuYnRuLWxhYmVsLXJpZ2h0IHtcbiAgICAgICAgICAgICAgICAgICAgbGVmdDogYXV0bztcbiAgICAgICAgICAgICAgICAgICAgcmlnaHQ6IC01cHg7XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgfVxuXG59XG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIE1PREFMU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm1vZGFsLXRpdGxlIHtcbiAgICBzbWFsbCB7XG4gICAgICAgIGNvbG9yOiAkbGlnaHRlci1ibGFjay1jb2xvcjtcbiAgICAgICAgZm9udC1zaXplOiA3NSU7XG4gICAgICAgIGZvbnQtc3R5bGU6IGl0YWxpYztcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDVweDtcbiAgICB9XG59XG4ubW9kYWwtY29sb3Ige1xuICAgICYtcHJpbWFyeSB7XG4gICAgICAgIC5tb2RhbC1iYWNrZHJvcCB7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkcHJpbWFyeS1jb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLWRhbmdlciB7XG4gICAgICAgIC5tb2RhbC1iYWNrZHJvcCB7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkZGFuZ2VyLWNvbG9yO1xuICAgICAgICB9XG4gICAgfVxuICAgICYtc3VjY2VzcyB7XG4gICAgICAgIC5tb2RhbC1iYWNrZHJvcCB7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkc3VjY2Vzcy1jb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLWJsYWNrIHtcbiAgICAgICAgLm1vZGFsLWJhY2tkcm9wIHtcbiAgICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLXdhcm5pbmcge1xuICAgICAgICAubW9kYWwtYmFja2Ryb3Age1xuICAgICAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJHdhcm5pbmctY29sb3I7XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi1ncmF5IHtcbiAgICAgICAgLm1vZGFsLWJhY2tkcm9wIHtcbiAgICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRncmF5LWNvbG9yO1xuICAgICAgICB9XG4gICAgfVxuICAgICYtd2hpdGUge1xuICAgICAgICAubW9kYWwtYmFja2Ryb3Age1xuICAgICAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgICAgICB9XG4gICAgfVxuICAgICYtaW5mbyB7XG4gICAgICAgIC5tb2RhbC1iYWNrZHJvcCB7XG4gICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkaW5mby1jb2xvcjtcbiAgICAgICAgfVxuICAgIH1cbn1cbi50cmFucy1tb2RhbCB7XG4gICAgLm1vZGFsLWNvbnRlbnQge1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiB0cmFuc3BhcmVudDtcbiAgICAgICAgYm94LXNoYWRvdzogbm9uZTtcbiAgICAgICAgYm9yZGVyOiAwO1xuICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgICAgICAuY2xvc2Uge1xuICAgICAgICAgICAgY29sb3I6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgfVxuICAgICAgICBoMSwgaDIsIGgzLCBoNCwgaDUsIGg2LCAuaDEsIC5oMiwgLmgzLCAuaDQsIC5oNSwgLmg2IHtcbiAgICAgICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgICAgIH1cbiAgICAgICAgLm1vZGFsLWhlYWRlciB7XG4gICAgICAgICAgICBib3JkZXI6IDBweDtcbiAgICAgICAgfVxuICAgICAgICAubW9kYWwtZm9vdGVyIHtcbiAgICAgICAgICAgIGJvcmRlcjogMHB4O1xuICAgICAgICB9XG4gICAgfVxufVxuLm1vZGFsLWZvb3Rlci50ZXh0LWNlbnRlciB7XG4gICAgdGV4dC1hbGlnbjogY2VudGVyICFpbXBvcnRhbnQ7XG59XG4ubW9kYWwtdGl0bGUge1xuICAgIC5mYSB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogNXB4O1xuICAgIH1cbn1cbi5tb2RhbC52ZXJ0LWNlbnRlciB7XG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgIEBtZWRpYSBzY3JlZW4gYW5kIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gICAgICAgICY6YmVmb3JlIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgICAgICAgIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7XG4gICAgICAgICAgICBjb250ZW50OiBcIiBcIjtcbiAgICAgICAgICAgIGhlaWdodDogMTAwJTtcbiAgICAgICAgfVxuICAgIH1cbiAgICAubW9kYWwtZGlhbG9nIHtcbiAgICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgICB0ZXh0LWFsaWduOiBsZWZ0O1xuICAgICAgICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlO1xuICAgIH1cbn1cbi5tb2RhbC52ZXJ0LXRvcCB7XG4gICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgIEBtZWRpYSBzY3JlZW4gYW5kIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gICAgICAgICY6YmVmb3JlIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICAgICAgICAgIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7XG4gICAgICAgICAgICBjb250ZW50OiBcIiBcIjtcbiAgICAgICAgICAgIGhlaWdodDogMTAwJTtcbiAgICAgICAgfVxuICAgIH1cbiAgICAubW9kYWwtZGlhbG9nIHtcbiAgICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgICB0ZXh0LWFsaWduOiBsZWZ0O1xuICAgICAgICB2ZXJ0aWNhbC1hbGlnbjogdG9wO1xuICAgICAgICBtYXJnaW4tdG9wOiAwO1xuICAgIH1cbiAgICAubW9kYWwtY29udGVudCB7XG4gICAgICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDA7XG4gICAgICAgIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwO1xuICAgICAgICBib3JkZXItdG9wOiAwcHg7XG4gICAgfVxufVxuLm1vZGFsLnZlcnQtYm90dG9tIHtcbiAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgQG1lZGlhIHNjcmVlbiBhbmQgKG1pbi13aWR0aDogNzY4cHgpIHtcbiAgICAgICAgJjpiZWZvcmUge1xuICAgICAgICAgICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgICAgICAgICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgICAgICAgICAgIGNvbnRlbnQ6IFwiIFwiO1xuICAgICAgICAgICAgaGVpZ2h0OiAxMDAlO1xuICAgICAgICB9XG4gICAgfVxuICAgIC5tb2RhbC1kaWFsb2cge1xuICAgICAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgICAgIHRleHQtYWxpZ246IGxlZnQ7XG4gICAgICAgIHZlcnRpY2FsLWFsaWduOiBib3R0b207XG4gICAgICAgIG1hcmdpbi1ib3R0b206IDA7XG4gICAgfVxuICAgIC5tb2RhbC1jb250ZW50IHtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMDtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDA7XG4gICAgICAgIGJvcmRlci1ib3R0b206IDBweDtcbiAgICB9XG59XG4ubW9kYWwubW9kYWwtZnVsbC1zY3JlZW4ge1xuICAgIC5tb2RhbC1kaWFsb2cge1xuICAgICAgICB3aWR0aDogMTAwJTtcbiAgICAgICAgaGVpZ2h0OiAxMDAlO1xuICAgICAgICBtYXJnaW4tdG9wOiAwO1xuICAgIH1cbiAgICAubW9kYWwtY29udGVudCB7XG4gICAgICAgIGhlaWdodDogMTAwJTtcbiAgICAgICAgYm9yZGVyOiAwO1xuICAgICAgICBib3JkZXItcmFkaXVzOiAwO1xuICAgIH1cbn1cbi5pemlNb2RhbCAuaXppTW9kYWwtaGVhZGVyLXN1YnRpdGxlLCAuaXppTW9kYWwgLml6aU1vZGFsLWhlYWRlci10aXRsZSB7XG4gICAgZm9udC1mYW1pbHk6ICRzdC1ib2R5LWZvbnQ7XG4gICAgY2xlYXI6IG5vbmU7XG59XG4uaXppTW9kYWwtd3JhcCB7XG4gICAgLyogcGFkZGluZzogMTVweDsgKi9cbn1cbi5pemlNb2RhbCAuaXppTW9kYWwtaGVhZGVyIHtcbiAgICBiYWNrZ3JvdW5kOiAkcHJpbWFyeS1jb2xvcjtcbiAgICAuZmEge1xuICAgICAgICBmb250LXNpemU6IDMwcHg7XG4gICAgfVxufVxuLnN3ZWV0LWFsZXJ0IHtcbiAgICBmb250LWZhbWlseTogJHN0LWJvZHktZm9udDtcbiAgICBoMiB7XG4gICAgICAgIGZvbnQtZmFtaWx5OiAkc3QtaGVhZGluZy1mb250O1xuICAgIH1cbiAgICBpbnB1dCB7XG4gICAgICAgIGRpc3BsYXk6IG5vbmU7XG4gICAgfVxuICAgIGZpZWxkc2V0IHtcbiAgICAgICAgcGFkZGluZzogMDtcbiAgICB9XG59XG5cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBEQVNIQk9BUkQgU1RBVFNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5kYXNoYm9hcmQtc3RhdCB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgcGFkZGluZzogMzBweCAxNXB4O1xuICAgIHRleHQtYWxpZ246IHJpZ2h0O1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICBib3gtc2hhZG93OiAwIDFweCAycHggcmdiYSgwLDAsMCwwLjEpO1xuICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICAubnVtYmVyIHtcbiAgICAgICAgZm9udC1zaXplOiAyOHB4O1xuICAgICAgICBkaXNwbGF5OiBibG9jaztcbiAgICB9XG4gICAgLmJnLWljb24ge1xuICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgIGZvbnQtc2l6ZTogODBweDtcbiAgICAgICAgb3BhY2l0eTogMC40O1xuICAgICAgICBsZWZ0OiAwO1xuICAgICAgICBib3R0b206IDA7XG4gICAgfVxuICAgICY6aG92ZXIge1xuICAgICAgICBiYWNrZ3JvdW5kOiAkYmxhY2stY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG59XG4uZGFzaGJvYXJkLXN0YXQtMiB7XG4gICAgZGlzcGxheTogYmxvY2s7XG4gICAgLnN0YXQtY29udGVudCB7XG4gICAgICAgIHBhZGRpbmc6IDIwcHggMTVweCAxNXB4O1xuICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICB9XG4gICAgYm94LXNoYWRvdzogMHB4IDFweCAycHggcmdiYSgwLDAsMCwwLjEpO1xuICAgIGJvcmRlcjogMXB4IHNvbGlkIGRhcmtlbigkZ3JheS1jb2xvciwgNSUpO1xuICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICAubnVtYmVyIHtcbiAgICAgICAgZm9udC1zaXplOiAyOHB4O1xuICAgICAgICBkaXNwbGF5OiBibG9jaztcbiAgICB9XG4gICAgLnN0YXQtZm9vdGVyIHtcbiAgICAgICAgYmFja2dyb3VuZDogJHdoaXRlLWNvbG9yO1xuICAgICAgICBjb2xvcjogJGJsYWNrLWNvbG9yO1xuICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgICBwYWRkaW5nOiA4cHg7XG4gICAgICAgIGZvbnQtc2l6ZTogOTAlO1xuICAgIH1cbiAgICAmOmhvdmVyIHtcbiAgICAgICAgYmFja2dyb3VuZDogJGJsYWNrLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxufVxuQG1lZGlhIChtYXgtd2lkdGg6IDc2OHB4KSB7XG4gICAgLmRhc2hib2FyZC1zdGF0IHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMTBweDtcbiAgICB9XG4gICAgLmRhc2hib2FyZC1zdGF0LTIge1xuICAgICAgICBtYXJnaW4tYm90dG9tOiAxMHB4O1xuICAgIH1cbn1cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTk9USUZJQ0FUSU9OU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLnRvYXN0LXN1Y2Nlc3Mge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRzdWNjZXNzLWNvbG9yO1xufVxuLnRvYXN0LWVycm9yIHtcbiAgICBiYWNrZ3JvdW5kLWNvbG9yOiAkZGFuZ2VyLWNvbG9yO1xufVxuLnRvYXN0LXdhcm5pbmcge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICR3YXJuaW5nLWNvbG9yO1xufVxuLnRvYXN0LWluZm8ge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRpbmZvLWNvbG9yO1xufVxuI3RvYXN0LWNvbnRhaW5lcj5kaXYge1xuICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICBib3gtc2hhZG93OiAwIDJweCA1cHggcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgICBvcGFjaXR5OiAwLjk1O1xuICAgICY6aG92ZXIge1xuICAgICAgICBib3gtc2hhZG93OiAwIDJweCA1cHggcmdiYSgwLCAwLCAwLCAwLjIpO1xuICAgIH1cbn1cbi8vIFBOb3RpZnlcbi51aS1wbm90aWZ5IHtcbiAgICAuYWxlcnQtd2FybmluZyB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICR3YXJuaW5nLWNvbG9yO1xuICAgICAgICBib3JkZXItY29sb3I6ICR3YXJuaW5nLWNvbG9yO1xuICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgIH1cbiAgICAuYWxlcnQtaW5mbyB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRpbmZvLWNvbG9yO1xuICAgICAgICBib3JkZXItY29sb3I6ICRpbmZvLWNvbG9yO1xuICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgIH1cbiAgICAuYWxlcnQtc3VjY2VzcyB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6ICRzdWNjZXNzLWNvbG9yO1xuICAgICAgICBib3JkZXItY29sb3I6ICRzdWNjZXNzLWNvbG9yO1xuICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgIH1cbiAgICAuYWxlcnQtZGFuZ2VyIHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGRhbmdlci1jb2xvcjtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiAkZGFuZ2VyLWNvbG9yO1xuICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgIH1cbiAgICAuYWxlcnQgaDQge1xuICAgICAgICBjbGVhcjogbm9uZTtcbiAgICB9XG4gICAgLnVpLXBub3RpZnktaWNvbiwgLnVpLXBub3RpZnktaWNvbiBzcGFuIHtcbiAgICAgICAgbWFyZ2luLXRvcDogNXB4O1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDVweDtcbiAgICAgICAgJi5mYWxzZSB7XG4gICAgICAgICAgICBtYXJnaW46IDA7XG4gICAgICAgIH1cbiAgICB9XG4gICAgLnVpLXBub3RpZnktY2xvc2VyLCAudWktcG5vdGlmeS1zdGlja2VyIHtcbiAgICAgICAgbWFyZ2luLXRvcDogNXB4O1xuICAgICAgICBtYXJnaW4tbGVmdDogNXB4O1xuICAgICAgICAmOmZvY3VzIHtcbiAgICAgICAgICAgIG91dGxpbmU6IDA7XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5hbGVydC1sZWZ0LWljb24ge1xuICAgICAgICAuYWxlcnQtaW5mbyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkaW5mby1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtd2FybmluZyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkd2FybmluZy1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtc3VjY2VzcyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkc3VjY2Vzcy1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtZGFuZ2VyIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRkYW5nZXItY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICAgICAgLnVpLXBub3RpZnktY29udGFpbmVyIHtcbiAgICAgICAgICAgIGJvcmRlci1sZWZ0LXdpZHRoOiA1MHB4O1xuICAgICAgICB9XG4gICAgICAgICY6YWZ0ZXIge1xuICAgICAgICAgICAgbGVmdDogMDtcbiAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgIHRvcDogNTAlO1xuICAgICAgICAgICAgd2lkdGg6IDUwcHg7XG4gICAgICAgICAgICBmb250OiBub3JtYWwgbm9ybWFsIG5vcm1hbCAxNHB4LzEgRm9udEF3ZXNvbWU7XG4gICAgICAgICAgICBjb250ZW50OiBcIlxcZjA3MVwiO1xuICAgICAgICAgICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgICAgICAgICAgZm9udC1zaXplOiAxOHB4O1xuICAgICAgICAgICAgbWFyZ2luLXRvcDogLTlweDtcbiAgICAgICAgICAgIGxpbmUtaGVpZ2h0OiAxO1xuICAgICAgICAgICAgY29sb3I6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgICAgIC13ZWJraXQtZm9udC1zbW9vdGhpbmc6IGFudGlhbGlhc2VkO1xuICAgICAgICAgICAgLW1vei1vc3gtZm9udC1zbW9vdGhpbmc6IGdyYXlzY2FsZTtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLmFsZXJ0LXJpZ2h0LWljb24ge1xuICAgICAgICAuYWxlcnQtaW5mbyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkaW5mby1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtd2FybmluZyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkd2FybmluZy1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtc3VjY2VzcyB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkc3VjY2Vzcy1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAuYWxlcnQtZGFuZ2VyIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRkYW5nZXItY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICAgICAgLnVpLXBub3RpZnktY29udGFpbmVyIHtcbiAgICAgICAgICAgIGJvcmRlci1yaWdodC13aWR0aDogNTBweDtcbiAgICAgICAgfVxuICAgICAgICAmOmFmdGVyIHtcbiAgICAgICAgICAgIHJpZ2h0OiAwO1xuICAgICAgICAgICAgcG9zaXRpb246IGFic29sdXRlO1xuICAgICAgICAgICAgdG9wOiA1MCU7XG4gICAgICAgICAgICB3aWR0aDogNTBweDtcbiAgICAgICAgICAgIGZvbnQ6IG5vcm1hbCBub3JtYWwgbm9ybWFsIDE0cHgvMSBGb250QXdlc29tZTtcbiAgICAgICAgICAgIGNvbnRlbnQ6IFwiXFxmMDcxXCI7XG4gICAgICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgICAgICBmb250LXNpemU6IDE4cHg7XG4gICAgICAgICAgICBtYXJnaW4tdG9wOiAtOXB4O1xuICAgICAgICAgICAgbGluZS1oZWlnaHQ6IDE7XG4gICAgICAgICAgICBjb2xvcjogJHdoaXRlLWNvbG9yO1xuICAgICAgICAgICAgLXdlYmtpdC1mb250LXNtb290aGluZzogYW50aWFsaWFzZWQ7XG4gICAgICAgICAgICAtbW96LW9zeC1mb250LXNtb290aGluZzogZ3JheXNjYWxlO1xuICAgICAgICB9XG4gICAgfVxufVxuLnVpLXBub3RpZnkgLnVpLXBub3RpZnktc2hhZG93IHtcbiAgICBib3gtc2hhZG93OiAwIDJweCA1cHggcmdiYSgwLCAwLCAwLCAwLjE1KTtcbn1cbi5sZWZ0LWljb24tYWxlcnQge1xuICAgIGJvcmRlcjogMXB4IHNvbGlkICRncmF5LWNvbG9yO1xuICAgIGJvcmRlci1sZWZ0LXdpZHRoOiA1MHB4O1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICAmOmFmdGVyIHtcbiAgICAgICAgbGVmdDogLTUwcHg7XG4gICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgdG9wOiA1MCU7XG4gICAgICAgIHdpZHRoOiA1MHB4O1xuICAgICAgICBmb250OiBub3JtYWwgbm9ybWFsIG5vcm1hbCAxNHB4LzEgRm9udEF3ZXNvbWU7XG4gICAgICAgIGNvbnRlbnQ6IFwiXFxmMDcxXCI7XG4gICAgICAgIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgICAgICAgZm9udC1zaXplOiAxOHB4O1xuICAgICAgICBtYXJnaW4tdG9wOiAtOXB4O1xuICAgICAgICBsaW5lLWhlaWdodDogMTtcbiAgICAgICAgY29sb3I6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgLXdlYmtpdC1mb250LXNtb290aGluZzogYW50aWFsaWFzZWQ7XG4gICAgICAgIC1tb3otb3N4LWZvbnQtc21vb3RoaW5nOiBncmF5c2NhbGU7XG4gICAgfVxuICAgICYuYWxlcnQtaW5mbyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRpbmZvLWNvbG9yLCAxNSUpICFpbXBvcnRhbnQ7XG4gICAgICAgICY6YWZ0ZXIge1xuICAgICAgICAgICAgY29udGVudDogXCJcXGYxMjlcIjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLmFsZXJ0LXdhcm5pbmcge1xuICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkd2FybmluZy1jb2xvciwgMTUlKSAhaW1wb3J0YW50O1xuICAgICAgICAmOmFmdGVyIHtcbiAgICAgICAgICAgIGNvbnRlbnQ6IFwiXFxmMTI5XCI7XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5hbGVydC1zdWNjZXNzIHtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHN1Y2Nlc3MtY29sb3IsIDE1JSkgIWltcG9ydGFudDtcbiAgICAgICAgJjphZnRlciB7XG4gICAgICAgICAgICBjb250ZW50OiBcIlxcZjAwY1wiO1xuICAgICAgICB9XG4gICAgfVxuICAgICYuYWxlcnQtZGFuZ2VyIHtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJGRhbmdlci1jb2xvciwgMTUlKSAhaW1wb3J0YW50O1xuICAgICAgICAmOmFmdGVyIHtcbiAgICAgICAgICAgIGNvbnRlbnQ6IFwiXFxmMDBkXCI7XG4gICAgICAgIH1cbiAgICB9XG59XG4ucmlnaHQtaWNvbi1hbGVydCB7XG4gICAgYm9yZGVyOiAxcHggc29saWQgJGdyYXktY29sb3I7XG4gICAgYm9yZGVyLXJpZ2h0LXdpZHRoOiA1MHB4O1xuICAgIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgICAmOmFmdGVyIHtcbiAgICAgICAgcmlnaHQ6IC01MHB4O1xuICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgIHRvcDogNTAlO1xuICAgICAgICB3aWR0aDogNTBweDtcbiAgICAgICAgZm9udDogbm9ybWFsIG5vcm1hbCBub3JtYWwgMTRweC8xIEZvbnRBd2Vzb21lO1xuICAgICAgICBjb250ZW50OiBcIlxcZjA3MVwiO1xuICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gICAgICAgIGZvbnQtc2l6ZTogMThweDtcbiAgICAgICAgbWFyZ2luLXRvcDogLTlweDtcbiAgICAgICAgbGluZS1oZWlnaHQ6IDE7XG4gICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgICAgIC13ZWJraXQtZm9udC1zbW9vdGhpbmc6IGFudGlhbGlhc2VkO1xuICAgICAgICAtbW96LW9zeC1mb250LXNtb290aGluZzogZ3JheXNjYWxlO1xuICAgIH1cbiAgICAmLmFsZXJ0LWluZm8ge1xuICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkaW5mby1jb2xvciwgMTUlKSAhaW1wb3J0YW50O1xuICAgICAgICAmOmFmdGVyIHtcbiAgICAgICAgICAgIGNvbnRlbnQ6IFwiXFxmMTI5XCI7XG4gICAgICAgIH1cbiAgICB9XG4gICAgJi5hbGVydC13YXJuaW5nIHtcbiAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHdhcm5pbmctY29sb3IsIDE1JSkgIWltcG9ydGFudDtcbiAgICAgICAgJjphZnRlciB7XG4gICAgICAgICAgICBjb250ZW50OiBcIlxcZjEyOVwiO1xuICAgICAgICB9XG4gICAgfVxuICAgICYuYWxlcnQtc3VjY2VzcyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRzdWNjZXNzLWNvbG9yLCAxNSUpICFpbXBvcnRhbnQ7XG4gICAgICAgICY6YWZ0ZXIge1xuICAgICAgICAgICAgY29udGVudDogXCJcXGYwMGNcIjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAmLmFsZXJ0LWRhbmdlciB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRkYW5nZXItY29sb3IsIDE1JSkgIWltcG9ydGFudDtcbiAgICAgICAgJjphZnRlciB7XG4gICAgICAgICAgICBjb250ZW50OiBcIlxcZjAwZFwiO1xuICAgICAgICB9XG4gICAgfVxufVxuXG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFBBR0lOQVRJT05cbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGEsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6aG92ZXIsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6Zm9jdXMsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW4sIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46aG92ZXIsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46Zm9jdXMge1xuICAgIGNvbG9yOiAkd2hpdGUtY29sb3IgIWltcG9ydGFudDtcbn1cbi5wYWdpbmF0aW9uLnJvdW5kZWQtY29ybmVycyB7XG4gICAgbGk6Zmlyc3QtY2hpbGQgPiBhLCBsaTpmaXJzdC1jaGlsZCA+IHNwYW4ge1xuICAgICAgICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAyMHB4O1xuICAgICAgICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiAyMHB4O1xuICAgIH1cbiAgICBsaTpsYXN0LWNoaWxkID4gYSwgbGk6bGFzdC1jaGlsZCA+IHNwYW4ge1xuICAgICAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMjBweDtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDIwcHg7XG4gICAgfVxufVxuLnBhZ2luYXRpb24uYm9yZGVybGVzcyB7XG4gICAgbGkgPiBhLCBsaSA+IHNwYW4ge1xuICAgICAgICBib3JkZXI6IDBweDtcbiAgICB9XG59XG4ucGFnZXIgLmRpc2FibGVkID4gYSwgLnBhZ2VyIC5kaXNhYmxlZCA+IGE6aG92ZXIsIC5wYWdlciAuZGlzYWJsZWQgPiBhOmZvY3VzLCAucGFnZXIgLmRpc2FibGVkID4gc3BhbiB7XG4gICAgb3BhY2l0eTogMC41O1xufVxuXG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIEZPUk1TXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4uZm9ybS1ncm91cCB7XG4gICAgJi5sZWZ0LWljb24ge1xuICAgICAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgICAgIC5mYSB7XG4gICAgICAgICAgICBsaW5lLWhlaWdodDogMzRweDtcbiAgICAgICAgfVxuICAgICAgICAuZm9ybS1jb250cm9sIHtcbiAgICAgICAgICAgIHBhZGRpbmctbGVmdDogNDIuNXB4O1xuICAgICAgICB9XG4gICAgICAgIC5mb3JtLWxlZnQtaWNvbiB7XG4gICAgICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgICAgICBsZWZ0OiAxNXB4O1xuICAgICAgICAgICAgdG9wOiAyNXB4O1xuICAgICAgICAgICAgJi5pY29uLWxnIHtcbiAgICAgICAgICAgICAgICB0b3A6IDMwcHg7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAmLmljb24tc20ge1xuICAgICAgICAgICAgICAgIHRvcDogMjJweDtcbiAgICAgICAgICAgIH1cbiAgICAgICAgfVxuICAgIH1cbiAgICAmLmhhcy1mZWVkYmFjayB7XG4gICAgICAgIC5mYSB7XG4gICAgICAgICAgICBsaW5lLWhlaWdodDogMzRweDtcbiAgICAgICAgfVxuICAgIH1cbiAgICBpbnB1dCwgdGV4dGFyZWEsIHNlbGVjdCB7XG4gICAgICAgICY6Zm9jdXMge1xuICAgICAgICAgICAgYm94LXNoYWRvdzogbm9uZTtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogJGJsYWNrLWNvbG9yO1xuICAgICAgICB9XG4gICAgfVxufVxuLmZvcm0taG9yaXpvbnRhbCB7XG4gICAgLmZvcm0tZ3JvdXAge1xuICAgICAgICAmLmxlZnQtaWNvbiB7XG4gICAgICAgICAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgICAgICAgICAuZmEsIC5nbHlwaGljb24ge1xuICAgICAgICAgICAgICAgIGxpbmUtaGVpZ2h0OiAzNHB4O1xuICAgICAgICAgICAgfVxuICAgICAgICAgICAgLmZvcm0tY29udHJvbCB7XG4gICAgICAgICAgICAgICAgcGFkZGluZy1sZWZ0OiA0Mi41cHg7XG4gICAgICAgICAgICB9XG4gICAgICAgICAgICAuZm9ybS1sZWZ0LWljb24ge1xuICAgICAgICAgICAgICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICAgICAgICAgICAgICBsZWZ0OiAzMHB4O1xuICAgICAgICAgICAgICAgIHRvcDogMHB4O1xuICAgICAgICAgICAgICAgICYuaWNvbi1sZyB7XG4gICAgICAgICAgICAgICAgICAgIHRvcDogNXB4O1xuICAgICAgICAgICAgICAgIH1cbiAgICAgICAgICAgICAgICAmLmljb24tc20ge1xuICAgICAgICAgICAgICAgICAgICB0b3A6IDBweDtcbiAgICAgICAgICAgICAgICB9XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG59XG4uZm9ybS1ncm91cCB7XG4gICAgbGFiZWwge1xuICAgICAgICBmb250LXNpemU6IDk1JTtcbiAgICB9XG4gICAgLmhlbHAtYmxvY2sge1xuICAgICAgICBmb250LXNpemU6IDg0JTtcbiAgICAgICAgZm9udC1zdHlsZTogaXRhbGljO1xuICAgICAgICBtYXJnaW4tdG9wOiAtNXB4O1xuICAgIH1cbn1cbi5pbnB1dC1ncm91cCB7XG4gICAgZm9udC1zaXplOiAxNHB4O1xuICAgIG1hcmdpbi1ib3R0b206IDAuNTQ2ODc1ZW07XG59XG4uZm9ybS1ob3Jpem9udGFsIC5jb250cm9sLWxhYmVsIHtcbiAgICAmLnRleHQtbGVmdCB7XG4gICAgICAgIHRleHQtYWxpZ246IGxlZnQ7XG4gICAgfVxufVxuLnJhZGlvLWxhYmVsIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG59XG4uc2VsZWN0Mi1jb250YWluZXIgLnNlbGVjdDItc2VsZWN0aW9uLS1zaW5nbGUge1xuICAgIGhlaWdodDogMzRweDtcbn1cbi5zZWxlY3QyLWNvbnRhaW5lci0tZGVmYXVsdCAuc2VsZWN0Mi1zZWxlY3Rpb24tLXNpbmdsZSAuc2VsZWN0Mi1zZWxlY3Rpb25fX3JlbmRlcmVkIHtcbiAgICBsaW5lLWhlaWdodDogMzRweDtcbn1cbi5zZWxlY3QyLWNvbnRhaW5lci0tZGVmYXVsdCAuc2VsZWN0Mi1zZWxlY3Rpb24tLXNpbmdsZSAuc2VsZWN0Mi1zZWxlY3Rpb25fX2Fycm93IHtcbiAgICBoZWlnaHQ6IDM0cHg7XG59XG4uc2VsZWN0Mi1yZXN1bHRzIHtcbiAgICBmb250LXNpemU6IDkwJTtcbn1cbi5zZWxlY3QyLWNvbnRhaW5lci0tZGVmYXVsdCAuc2VsZWN0Mi1zZWFyY2gtLWlubGluZSAuc2VsZWN0Mi1zZWFyY2hfX2ZpZWxkIHtcbiAgICBtYXJnaW4tdG9wOiAwO1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG59XG5kaXYudGFnc2lucHV0IHNwYW4udGFnIHtcbiAgICBib3JkZXItd2lkdGg6IDA7XG4gICAgYmFja2dyb3VuZDogbGlnaHRlbigkcHJpbWFyeS1jb2xvciwgNSUpO1xuICAgIGNvbG9yOiBkYXJrZW4oJHByaW1hcnktY29sb3IsIDI1JSk7XG4gICAgcGFkZGluZzogMnB4IDEwcHg7XG59XG5kaXYudGFnc2lucHV0IHNwYW4udGFnIGEge1xuICAgIGNvbG9yOiBkYXJrZW4oJHByaW1hcnktY29sb3IsIDIwJSk7XG59XG4uZm9ybS1saW5rIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgbWFyZ2luLXRvcDogMTVweDtcbiAgICBjb2xvcjogJGxpZ2h0ZXItYmxhY2stY29sb3I7XG59XG4ub3AtY2hlY2sge1xuICAgICYuY2hlY2tib3ggbGFiZWwsICYucmFkaW8gbGFiZWwge1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDA7XG4gICAgfVxufVxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgRVJST1IgUEFHRVNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5lcnJvci1ib3gge1xuICAgIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgICAuZXJyb3ItaWNvbiB7XG4gICAgICAgIGZvbnQtc2l6ZTogNDBweDtcbiAgICAgICAgY29sb3I6ICRkYW5nZXItY29sb3I7XG4gICAgfVxuICAgIC5lcnJvci10aXRsZSB7XG4gICAgICAgIG1hcmdpbi10b3A6IDEwcHg7XG4gICAgICAgIGZvbnQtc2l6ZTogNjBweDtcbiAgICB9XG4gICAgLnN1Yi10aXRsZSB7XG4gICAgICAgIGZvbnQtc2l6ZTogMThweDtcbiAgICAgICAgY29sb3I6ICRsaWdodGVyLWJsYWNrLWNvbG9yO1xuICAgIH1cbn1cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFBSSUNJTkdcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5wcmljaW5nLWJveCB7XG4gICAgYmFja2dyb3VuZDogJHdoaXRlLWNvbG9yO1xuICAgIGJveC1zaGFkb3c6IDAgMnB4IDNweCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICAucHJpY2luZy1oZWFkIHtcbiAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGdyYXktY29sb3I7XG4gICAgICAgIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgICAgICAgYm9yZGVyLXRvcDogM3B4IHNvbGlkICRwcmltYXJ5LWNvbG9yO1xuICAgICAgICBwYWRkaW5nOiAxLjYxOGVtO1xuICAgICAgICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gICAgICAgIG92ZXJmbG93OiBoaWRkZW47XG4gICAgICAgIGJvcmRlci1yYWRpdXM6IDRweCA0cHggMCAwO1xuICAgICAgICBoMSwgaDIsIGgzLCBoNCwgaDUsIGg2IHtcbiAgICAgICAgICAgIG1hcmdpbjogMDtcbiAgICAgICAgfVxuICAgICAgICAuc3RyaWtlZCB7XG4gICAgICAgICAgICB0ZXh0LWRlY29yYXRpb246IGxpbmUtdGhyb3VnaDtcbiAgICAgICAgfVxuICAgICAgICAuYmctaWNvbiB7XG4gICAgICAgICAgICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gICAgICAgICAgICBib3R0b206IC0yMHB4O1xuICAgICAgICAgICAgbGVmdDogLTIwcHg7XG4gICAgICAgICAgICBmb250LXNpemU6IDEyMHB4O1xuICAgICAgICAgICAgY29sb3I6IGRhcmtlbigkZ3JheS1jb2xvciwgMzUlKTtcbiAgICAgICAgICAgIG9wYWNpdHk6IDAuMjtcbiAgICAgICAgfVxuICAgIH1cbiAgICAucHJpY2luZy1ib2R5IHtcbiAgICAgICAgcGFkZGluZzogMWVtO1xuICAgICAgICB1bCB7XG4gICAgICAgICAgICBsaSB7XG4gICAgICAgICAgICAgICAgbGluZS1oZWlnaHQ6IDIuMjU7XG4gICAgICAgICAgICAgICAgLmljb24ge1xuICAgICAgICAgICAgICAgICAgICBmbG9hdDogcmlnaHQ7XG4gICAgICAgICAgICAgICAgfVxuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgfVxuICAgIC5wcmljaW5nLWZvb3Qge1xuICAgICAgICBhIHtcbiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrO1xuICAgICAgICAgICAgcGFkZGluZzogMWVtO1xuICAgICAgICAgICAgYmFja2dyb3VuZDogJGdyYXktY29sb3I7XG4gICAgICAgICAgICBjb2xvcjogJGJsYWNrLWNvbG9yO1xuICAgICAgICAgICAgdGV4dC1hbGlnbjogY2VudGVyO1xuICAgICAgICAgICAgdGV4dC10cmFuc2Zvcm06IHVwcGVyY2FzZTtcbiAgICAgICAgICAgIGxldHRlci1zcGFjaW5nOiAxcHg7XG4gICAgICAgICAgICBib3JkZXItcmFkaXVzOiAwIDAgNHB4IDRweDtcbiAgICAgICAgICAgIEBpbmNsdWRlIHRyYW5zaXRpb24oYWxsIDAuNHMgZWFzZS1pbi1vdXQpO1xuICAgICAgICAgICAgJjpob3ZlciB7XG4gICAgICAgICAgICAgICAgYmFja2dyb3VuZDogJHByaW1hcnktY29sb3I7XG4gICAgICAgICAgICAgICAgY29sb3I6ICR3aGl0ZS1jb2xvciAhaW1wb3J0YW50O1xuICAgICAgICAgICAgfVxuICAgICAgICB9XG4gICAgfVxuICAgICYucG9wdWxhciB7XG4gICAgICAgIC5wcmljaW5nLWhlYWQge1xuICAgICAgICAgICAgYmFja2dyb3VuZDogJGxpZ2h0LWJsYWNrLWNvbG9yO1xuICAgICAgICAgICAgY29sb3I6ICR3aGl0ZS1jb2xvcjtcbiAgICAgICAgICAgIGgxLCBoMiwgaDMsIGg0LCBoNSwgaDYge1xuICAgICAgICAgICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3I7XG4gICAgICAgICAgICB9XG4gICAgICAgIH1cbiAgICB9XG59XG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIExPR0lOXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ubG9naW4tYmcge1xuICAgIGJhY2tncm91bmQtaW1hZ2U6IHVybCgnLi4vaW1hZ2VzL3Bob3RvLTIuanBnJyk7XG4gICAgYmFja2dyb3VuZC1zaXplOiBjb3ZlcjtcbiAgICBiYWNrZ3JvdW5kLWF0dGFjaG1lbnQ6IGZpeGVkO1xuICAgIG1pbi1oZWlnaHQ6IDEwMHZoO1xuICAgIC5sb2dpbi1ib3gge1xuICAgICAgICBiYWNrZ3JvdW5kOiByZ2JhKCR3aGl0ZS1jb2xvciwgMC44KTtcbiAgICAgICAgcGFkZGluZzogMjBweDtcbiAgICAgICAgbWFyZ2luLXRvcDogMTUwcHg7XG4gICAgICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICAgICAgYm94LXNoYWRvdzogMHB4IDFweCAycHggcmdiYSgwLDAsMCwwLjEpO1xuICAgIH1cbn1cbi5sb2dpbi1iZy1jb2xvciB7XG4gICAgbWluLWhlaWdodDogMTAwdmg7XG4gICAgLmxvZ2luLWJveCB7XG4gICAgICAgIGNvbG9yOiAkYmxhY2stY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgcGFkZGluZzogMjBweDtcbiAgICAgICAgbWFyZ2luLXRvcDogMTI1cHg7XG4gICAgICAgIGJvcmRlci1yYWRpdXM6IDRweDtcbiAgICAgICAgYm94LXNoYWRvdzogMHB4IDFweCAycHggcmdiYSgwLDAsMCwwLjEpO1xuICAgICAgICBoMSwgaDIsIGgzLCBoNCwgaDUsIGg2IHtcbiAgICAgICAgICAgIGNvbG9yOiAkYmxhY2stY29sb3IgIWltcG9ydGFudDtcbiAgICAgICAgfVxuICAgIH1cbn1cblxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgRFJPUFpPTkVcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5kcm9wem9uZSB7XG4gICAgYmFja2dyb3VuZDogJGdyYXktY29sb3I7XG4gICAgYm9yZGVyOiAycHggZGFzaGVkIGRhcmtlbigkZ3JheS1jb2xvciwgMTAlKTtcbiAgICBtaW4taGVpZ2h0OiAyNTBweDtcbiAgICAuZHotbWVzc2FnZSB7XG4gICAgICAgIGZvbnQtc2l6ZTogMTZweDtcbiAgICAgICAgZm9udC13ZWlnaHQ6IGJvbGQ7XG4gICAgICAgIG1hcmdpbjogNC41ZW0gMDtcbiAgICAgICAgLm5vdGUge1xuICAgICAgICAgICAgZm9udC1zaXplOiAxM3B4O1xuICAgICAgICAgICAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbiAgICAgICAgICAgIGNvbG9yOiAkbGlnaHQtYmxhY2stY29sb3I7XG4gICAgICAgICAgICBtYXJnaW4tdG9wOiAxNXB4O1xuICAgICAgICB9XG4gICAgfVxufVxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQk9PVFNUUkFQIFNXSVRDSFxuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmJvb3RzdHJhcC1zd2l0Y2ggLmJvb3RzdHJhcC1zd2l0Y2gtaGFuZGxlLW9mZi5ib290c3RyYXAtc3dpdGNoLXByaW1hcnksIC5ib290c3RyYXAtc3dpdGNoIC5ib290c3RyYXAtc3dpdGNoLWhhbmRsZS1vbi5ib290c3RyYXAtc3dpdGNoLXByaW1hcnkge1xuICAgIGJhY2tncm91bmQ6ICRwcmltYXJ5LWNvbG9yO1xufVxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgSlFVRVJZIFNURVBTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ud2l6YXJkID4gLnN0ZXBzIC5jdXJyZW50IGEsIC53aXphcmQgPiAuc3RlcHMgLmN1cnJlbnQgYTpob3ZlciwgLndpemFyZCA+IC5zdGVwcyAuY3VycmVudCBhOmFjdGl2ZSB7XG4gICAgYmFja2dyb3VuZDogJHByaW1hcnktY29sb3I7XG59XG4ud2l6YXJkID4gLmFjdGlvbnMgYSwgLndpemFyZCA+IC5hY3Rpb25zIGE6aG92ZXIsIC53aXphcmQgPiAuYWN0aW9ucyBhOmFjdGl2ZSB7XG4gICAgYmFja2dyb3VuZDogJHByaW1hcnktY29sb3I7XG4gICAgY29sb3I6ICR3aGl0ZS1jb2xvcjtcbn1cbi53aXphcmQgPiAuY29udGVudCB7XG4gICAgbWluLWhlaWdodDogMjUwcHg7XG59XG4ud2l6YXJkID4gLmNvbnRlbnQgPiAuYm9keSBsYWJlbC5lcnJvciB7XG4gICAgY29sb3I6ICRkYW5nZXItY29sb3I7XG4gICAgZm9udC1zaXplOiA5MCU7XG4gICAgZm9udC13ZWlnaHQ6IG5vcm1hbDtcbn1cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIERBVEFUQUJMRVNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5wYWdpbmF0aW9uPi5hY3RpdmU+YSwgLnBhZ2luYXRpb24+LmFjdGl2ZT5hOmZvY3VzLCAucGFnaW5hdGlvbj4uYWN0aXZlPmE6aG92ZXIsIC5wYWdpbmF0aW9uPi5hY3RpdmU+c3BhbiwgLnBhZ2luYXRpb24+LmFjdGl2ZT5zcGFuOmZvY3VzLCAucGFnaW5hdGlvbj4uYWN0aXZlPnNwYW46aG92ZXIge1xuICAgIGJhY2tncm91bmQtY29sb3I6ICRwcmltYXJ5LWNvbG9yO1xuICAgIGJvcmRlci1jb2xvcjogJHByaW1hcnktY29sb3I7XG59XG5kaXYuZGF0YVRhYmxlc193cmFwcGVyIGRpdi5kYXRhVGFibGVzX2ZpbHRlciBsYWJlbCB7XG4gICAgdGV4dC1hbGlnbjogcmlnaHQ7XG59XG5cblxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIE1JU0NFTExBTkVPVVNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbnByZVtjbGFzcyo9XCJsYW5ndWFnZS1cIl0ge1xuICAgIGJvcmRlci1sZWZ0LXdpZHRoOiAycHg7XG59XG4uc3JjLWJ0biB7XG4gICAgZmxvYXQ6IHJpZ2h0O1xufVxuLmRyYWdnYWJsZS1oYW5kbGUge1xuICAgIGN1cnNvcjogbW92ZTtcbn1cbi5wYW5lbC1oZWFkaW5nIHtcbiAgICAuZHJvcGRvd24ge1xuICAgICAgICAuZmEuZHJvcGRvd24tdG9nZ2xlIHtcbiAgICAgICAgICAgIHBhZGRpbmctcmlnaHQ6IDE1cHg7XG4gICAgICAgICAgICBwYWRkaW5nLXRvcDogMTVweDtcbiAgICAgICAgfVxuICAgIH1cbn1cbi5tZWRpYS1vYmplY3Qge1xuICAgIG1hcmdpbi10b3A6IDEwcHg7XG59XG4ubWVkaWEtYm90dG9tIHtcbiAgICBwYWRkaW5nLWJvdHRvbTogMS43NWVtO1xufVxuLm9wLWNoYXJ0IHtcbiAgICB3aWR0aDogMTAwJTtcbiAgICBoZWlnaHQ6IDUwMHB4O1xufVxuW2NsYXNzXj1cImljaGVja2JveF9saW5lXCJdLmNoZWNrZWQge1xuICAgIG9wYWNpdHk6IDAuNjtcbn1cbi5icm93c2VyIHtcbiAgICBib3JkZXI6IDJweCBzb2xpZCAkZGFyay1ncmF5LWNvbG9yO1xuICAgIGJvcmRlci10b3Atd2lkdGg6IDMwcHg7XG4gICAgd2lkdGg6IDYwJTtcbiAgICBtYXJnaW46IGF1dG87XG4gICAgYm9yZGVyLXJhZGl1czogNnB4O1xuICAgIGlmcmFtZSB7XG4gICAgICAgIGJvcmRlcjogMDtcbiAgICAgICAgd2lkdGg6IDEwMCU7XG4gICAgfVxufVxuLnBvcG92ZXIuY29uZmlybWF0aW9uIHtcbiAgICBtYXgtd2lkdGg6IDEwMCU7XG59XG4uZHJvcGRvd24ge1xuICAgIC5kcm9wZG93bi10b2dnbGUge1xuICAgICAgICBjdXJzb3I6IHBvaW50ZXI7XG4gICAgfVxuICAgIC5pY29uLXJpZ2h0IHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDE1cHg7XG4gICAgICAgIGZsb2F0OiByaWdodDtcbiAgICAgICAgbWFyZ2luLXRvcDogM3B4O1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDAgIWltcG9ydGFudDtcbiAgICB9XG59XG4uc2hvdy1ncmlkIHtcbiAgICBbY2xhc3MqPVwiY29sLVwiXSB7XG4gICAgICAgIGJvcmRlcjogMXB4IHNvbGlkIGRhcmtlbigkZGFyay1ncmF5LWNvbG9yLCA1JSk7XG4gICAgICAgIHBhZGRpbmctdG9wOiA1cHg7XG4gICAgICAgIHBhZGRpbmctYm90dG9tOiA1cHg7XG4gICAgICAgIGJhY2tncm91bmQ6ICRkYXJrLWdyYXktY29sb3I7XG4gICAgfVxufVxuIiwiLy8gVHlwb2dyYXBoaWMgdjIuOS4yIC0gaHR0cHM6Ly9naXRodWIuY29tL2NvcnlzaW1tb25zL3R5cG9ncmFwaGljXG5cblxuLy8gUmF0aW9zXG5cbiRtaW5vci1zZWNvbmQgICA6IDEuMDY3O1xuJG1ham9yLXNlY29uZCAgIDogMS4xMjU7XG4kbWlub3ItdGhpcmQgICAgOiAxLjI7XG4kbWFqb3ItdGhpcmQgICAgOiAxLjI1O1xuJHBlcmZlY3QtZm91cnRoIDogMS4zMzM7XG4kYXVnLWZvdXJ0aCAgICAgOiAxLjQxNDtcbiRwZXJmZWN0LWZpZnRoICA6IDEuNTtcbiRtaW5vci1zaXh0aCAgICA6IDEuNjtcbiRnb2xkZW4gICAgICAgICA6IDEuNjE4O1xuJG1ham9yLXNpeHRoICAgIDogMS42Njc7XG4kbWlub3Itc2V2ZW50aCAgOiAxLjc3ODtcbiRtYWpvci1zZXZlbnRoICA6IDEuODc1O1xuJG9jdGF2ZSAgICAgICAgIDogMjtcbiRtYWpvci10ZW50aCAgICA6IDIuNTtcbiRtYWpvci1lbGV2ZW50aCA6IDIuNjY3O1xuJG1ham9yLXR3ZWxmdGggIDogMztcbiRkb3VibGUtb2N0YXZlICA6IDQ7XG5cblxuLy8gU2Fucy1zZXJpZlxuXG4kY2FsaWJyaSAgICAgICA6ICdDYWxpYnJpJywgJ0NhbmRhcmEnLCAnU2Vnb2UnLCAnU2Vnb2UgVUknLCAnT3B0aW1hJywgJ0FyaWFsJywgJ3NhbnMtc2VyaWYnO1xuJGNhbmRhcmEgICAgICAgOiAnQ2FuZGFyYScsICdDYWxpYnJpJywgJ1NlZ29lJywgJ1NlZ29lIFVJJywgJ09wdGltYScsICdBcmlhbCcsICdzYW5zLXNlcmlmJztcbiRjb3VyaWVyICAgICAgIDogJ0NvdXJpZXIgTmV3JywgJ0NvdXJpZXInLCAnTHVjaWRhIFNhbnMgVHlwZXdyaXRlcicsICdMdWNpZGEgVHlwZXdyaXRlcicsICdtb25vc3BhY2UnO1xuJGZyYW5rbGluICAgICAgOiAnRnJhbmtsaW4gR290aGljIE1lZGl1bScsICdBcmlhbCcsICdzYW5zLXNlcmlmJztcbiRmdXR1cmEgICAgICAgIDogJ0Z1dHVyYScsICdUcmVidWNoZXQgTVMnLCAnQXJpYWwnLCAnc2Fucy1zZXJpZic7XG4kZ2VuZXZhICAgICAgICA6ICdHZW5ldmEnLCAnVGFob21hJywgJ1ZlcmRhbmEnLCAnc2Fucy1zZXJpZic7XG4kZ2lsbC1zYW5zICAgICA6ICdHaWxsIFNhbnMnLCAnR2lsbCBTYW5zIE1UJywgJ0NhbGlicmknLCAnc2Fucy1zZXJpZic7XG4kaGVsdmV0aWNhICAgICA6ICdIZWx2ZXRpY2EgTmV1ZScsICdIZWx2ZXRpY2EnLCAnQXJpYWwnLCAnc2Fucy1zZXJpZic7XG4kbHVjaWRhLWdyYW5kZSA6ICdMdWNpZGEgR3JhbmRlJywgJ0x1Y2lkYSBTYW5zIFVuaWNvZGUnLCAnTHVjaWRhIFNhbnMnLCAnR2VuZXZhJywgJ1ZlcmRhbmEnLCAnc2Fucy1zZXJpZic7XG4kb3B0aW1hICAgICAgICA6ICdPcHRpbWEnLCAnU2Vnb2UnLCAnU2Vnb2UgVUknLCAnQ2FuZGFyYScsICdDYWxpYnJpJywgJ0FyaWFsJywgJ3NhbnMtc2VyaWYnO1xuJHNlZ29lICAgICAgICAgOiAnU2Vnb2UnLCAnU2Vnb2UgVUknLCAnSGVsdmV0aWNhIE5ldWUnLCAnQXJpYWwnLCAnc2Fucy1zZXJpZic7XG4kdGFob21hICAgICAgICA6ICdUYWhvbWEnLCAnR2VuZXZhJywgJ1ZlcmRhbmEnLCAnc2Fucy1zZXJpZic7XG4kdHJlYnVjaGV0ICAgICA6ICdUcmVidWNoZXQgTVMnLCAnTHVjaWRhIEdyYW5kZScsICdMdWNpZGEgU2FucyBVbmljb2RlJywgJ0x1Y2lkYSBTYW5zJywgJ1RhaG9tYScsICdzYW5zLXNlcmlmJztcbiR2ZXJkYW5hICAgICAgIDogJ1ZlcmRhbmEnLCAnR2VuZXZhJywgJ3NhbnMtc2VyaWYnO1xuXG5cbi8vIFNlcmlmXG5cbiRhbnRpcXVhICAgICAgIDogJ0Jvb2sgQW50aXF1YScsICdQYWxhdGlubycsICdQYWxhdGlubyBMaW5vdHlwZScsICdQYWxhdGlubyBMVCBTVEQnLCAnR2VvcmdpYScsICdzZXJpZic7XG4kYmFza2VydmlsbGUgICA6ICdCYXNrZXJ2aWxsZScsICdCYXNrZXJ2aWxsZSBvbGQgZmFjZScsICdIb2VmbGVyIFRleHQnLCAnR2FyYW1vbmQnLCAnVGltZXMgTmV3IFJvbWFuJywgJ3NlcmlmJztcbiRib2RvbmkgICAgICAgIDogJ0JvZG9uaSBNVCcsICdEaWRvdCcsICdEaWRvdCBMVCBTVEQnLCAnSG9lZmxlciBUZXh0JywgJ0dhcmFtb25kJywgJ1RpbWVzIE5ldyBSb21hbicsICdzZXJpZic7XG4kY2FtYnJpYSAgICAgICA6ICdDYW1icmlhJywgJ0dlb3JnaWEnLCAnc2VyaWYnO1xuJGNhc2xvbiAgICAgICAgOiAnQmlnIENhc2xvbicsICdCb29rIEFudGlxdWEnLCAnUGFsYXRpbm8gTGlub3R5cGUnLCAnR2VvcmdpYScsICdzZXJpZic7XG4kY29uc3RhbnRpYSAgICA6ICdDb25zdGFudGlhJywgJ1BhbGF0aW5vJywgJ1BhbGF0aW5vIExpbm90eXBlJywgJ1BhbGF0aW5vIExUIFNURCcsICdHZW9yZ2lhJywgJ3NlcmlmJztcbiRkaWRvdCAgICAgICAgIDogJ0RpZG90JywgJ0RpZG90IExUIFNURCcsICdIb2VmbGVyIFRleHQnLCAnR2FyYW1vbmQnLCAnVGltZXMgTmV3IFJvbWFuJywgJ3NlcmlmJztcbiRnYXJhbW9uZCAgICAgIDogJ0dhcmFtb25kJywgJ0Jhc2tlcnZpbGxlJywgJ0Jhc2tlcnZpbGxlIE9sZCBGYWNlJywgJ0hvZWZsZXIgVGV4dCcsICdUaW1lcyBOZXcgUm9tYW4nLCAnc2VyaWYnO1xuJGdvdWR5ICAgICAgICAgOiAnR291ZHkgT2xkIFN0eWxlJywgJ0dhcmFtb25kJywgJ0JpZyBDYXNsb24nLCAnVGltZXMgTmV3IFJvbWFuJywgJ3NlcmlmJztcbiRob2VmbGVyICAgICAgIDogJ0hvZWZsZXIgVGV4dCcsICdCYXNrZXJ2aWxsZSBvbGQgZmFjZScsICdHYXJhbW9uZCcsICdUaW1lcyBOZXcgUm9tYW4nLCAnc2VyaWYnO1xuJGx1Y2lkYS1icmlnaHQgOiAnTHVjaWRhIEJyaWdodCcsICdHZW9yZ2lhJywgJ3NlcmlmJztcbiRwYWxhdGlubyAgICAgIDogJ1BhbGF0aW5vJywgJ1BhbGF0aW5vIExpbm90eXBlJywgJ1BhbGF0aW5vIExUIFNURCcsIFwiQm9vayBBbnRpcXVhXCIsICdHZW9yZ2lhJywgJ3NlcmlmJztcblxuXG4vLyBTZXR0aW5nc1xuXG4kbGluZS1oZWlnaHQtcmF0aW8gIDogMS43NSAhZGVmYXVsdDtcbiRoZWFkZXItcmF0aW8gICAgICAgOiAkZ29sZGVuICFkZWZhdWx0O1xuJGJvZHktZm9udCAgICAgICAgICA6ICRoZWx2ZXRpY2EgIWRlZmF1bHQ7XG4kYm9keS1mb250LXdlaWdodCAgIDogMzAwICFkZWZhdWx0O1xuJGJvZHktY29sb3IgICAgICAgICA6ICM2NjYgIWRlZmF1bHQ7XG4kaGVhZGVyLWZvbnQgICAgICAgIDogJGhlbHZldGljYSAhZGVmYXVsdDtcbiRoZWFkZXItZm9udC13ZWlnaHQgOiA1MDAgIWRlZmF1bHQ7XG4kaGVhZGVyLWNvbG9yICAgICAgIDogIzExMSAhZGVmYXVsdDtcbiRtaW4tZm9udCAgICAgICAgICAgOiAxMnB4ICFkZWZhdWx0O1xuJG1heC1mb250ICAgICAgICAgICA6IDIwcHggIWRlZmF1bHQ7XG4kbWluLXdpZHRoICAgICAgICAgIDogNjAwcHggIWRlZmF1bHQ7XG4kbWF4LXdpZHRoICAgICAgICAgIDogMTE0MHB4ICFkZWZhdWx0O1xuJHZlcnRpY2FsLXJoeXRobSAgICA6IHRydWUgIWRlZmF1bHQ7XG5cblxuLy8gSGVscGVyc1xuXG4vLy8gQSBmdW5jdGlvbiB0byByZW1vdmUgdGhlIHVuaXQgZnJvbSBhIG51bWJlci5cbi8vL1xuLy8vIEBwYXJhbSB7dW5pdH0gJHVuaXQgLSBBIHVuaXQgd2l0aCBhIHVuaXQgdmFsdWUuXG4vLy9cbi8vLyBAZXhhbXBsZVxuLy8vICAgX3N0cmlwLXVuaXRzKDFweClcbi8vL1xuLy8vIEBhY2Nlc3MgcHJpdmF0ZVxuXG5AZnVuY3Rpb24gX3N0cmlwLXVuaXRzKCR1bml0KSB7XG4gIEByZXR1cm4gJHVuaXQgLyAoJHVuaXQgKiAwICsgMSk7XG59XG5cblxuLy8vIENyZWF0ZXMgYSBiYXNlbGluZSBncmlkIGJhc2VkIG9mZiB5b3VyICRsaW5lLWhlaWdodC1yYXRpbyB0byBoZWxwIHZpc3VhbGl6ZSB5b3VyIHZlcnRpY2FsIHJoeXRobSBncmlkLiBZb3UgY2FuIG9mZnNldCB0aGUgZ3JpZCBieSBuZWdhdGl2ZSBvciBwb3NpdGl2ZSBwaXhlbHMgdG8gbGluZSBpdCB1cCBwZXJmZWN0bHkgd2l0aCB0aGUgYm90dG9tIG9mIHlvdXIgdGV4dC5cbi8vL1xuLy8vIEBwYXJhbSB7Y29sb3J9ICRjb2xvciBbYmxhY2tdIC0gQSBjb2xvciB0byBiZSBsaWdodGVuZWQgYW5kIHVzZWQgYXMgdGhlIGNvbG9yIGZvciB0aGUgZ3JpZC5cbi8vLyBAcGFyYW0ge251bWJlcn0gJHB4LW9mZnNldCBbZmFsc2VdIC0gQSBwb3NpdGl2ZSBvciBuZWdhdGl2ZSBudW1iZXIgb2YgcGl4ZWxzIHRvIG9mZnNldCB0aGUgZ3JpZCBieS4gVXNlZnVsIGZvciBsaW5pbmcgdGhlIGJvdHRvbSBvZiB0aGUgZ3JpZGxpbmVzIHVwIHdpdGggeW91ciB0ZXh0LlxuLy8vXG4vLy8gQGV4YW1wbGVcbi8vLyAgIEBpbmNsdWRlIGdyaWQtb3ZlcmxheShibHVlLCAyKTtcblxuQG1peGluIGdyaWQtb3ZlcmxheSgkY29sb3I6IGJsYWNrLCAkcHgtb2Zmc2V0OiBmYWxzZSkge1xuICBib2R5IHtcbiAgICBiYWNrZ3JvdW5kOiBsaW5lYXItZ3JhZGllbnQodG8gdG9wLCByZ2JhKCRjb2xvciwgLjEpIDUlLCB3aGl0ZSA1JSk7XG4gICAgYmFja2dyb3VuZC1zaXplOiAxMDAlICgkbGluZS1oZWlnaHQtcmF0aW8pICsgZW07XG4gICAgQGlmKCRweC1vZmZzZXQpIHtcbiAgICAgIGJhY2tncm91bmQtcG9zaXRpb246IDAgJHB4LW9mZnNldCArIHB4O1xuICAgIH1cbiAgfVxufVxuXG5cbi8vLyBSZXR1cm5zIGEgXCJ2ZXJ0aWNhbCB1bml0XCIuIFVzZWZ1bCBmb3Igc3BlY2lmeWluZyB0aGUgaGVpZ2h0IGFuZCBtYXJnaW5zIG9mIG5vbi10ZXh0IGVsZW1lbnRzIGxpa2UgaW1hZ2VzIGFuZCBzdWNoLlxuLy8vXG4vLy8gQHBhcmFtIHtudW1iZXJ9ICR1bml0cyBbMV0gLSBOdW1iZXIgb2YgdW5pdHMuIEFjY2VwdHMgZmxvYXRlZCBudW1iZXJzIGFzIHdlbGwuXG4vLy8gQHBhcmFtIHtudW1iZXJ9ICRweC1vZmZzZXQgW2ZhbHNlXSAtIEEgcG9zaXRpdmUgb3IgbmVnYXRpdmUgbnVtYmVyIG9mIHBpeGVscyB0byBvZmZzZXQgdGhlIGdyaWQgYnkuIFVzZWZ1bCBmb3IgbGluaW5nIHRoZSBib3R0b20gb2YgdGhlIGdyaWRsaW5lcyB1cCB3aXRoIHlvdXIgdGV4dC4gU2luY2UgdGhpcyBkb2Vzbid0IGNvbXB1dGUgYSBsaXRlcmFsIHBpeGVsIHlvdSBtYXkgbmVlZCB0byB1c2UgYSBmbG9hdGVkIG51bWJlciAobXVsdGlwbGVzIG9mIC4yNSB3b3JrIHdlbGwpIHRvIGtlZXAgeW91ciByaHl0aG0gb24gdHJhY2suXG4vLy9cbi8vLyBAZXhhbXBsZVxuLy8vICAgaW1nIHtcbi8vLyAgICAgaGVpZ2h0OiB2ci1ibG9jayg1LjI1KTtcbi8vLyAgICAgbWFyZ2luLWJvdHRvbTogdnItYmxvY2soLjI1KTtcbi8vLyAgIH1cblxuQGZ1bmN0aW9uIHZyLWJsb2NrKCR1bml0czogMSwgJHB4LW9mZnNldDogZmFsc2UpIHtcbiAgQGlmKCRweC1vZmZzZXQpIHtcbiAgICBAcmV0dXJuICggKCgkbGluZS1oZWlnaHQtcmF0aW8gKiBfc3RyaXAtdW5pdHMoJG1heC1mb250KSkgLyAoX3N0cmlwLXVuaXRzKCRtYXgtZm9udCkgLyAyKSkgKiAoJHVuaXRzIC8gMikgKiAoMSArICgkcHgtb2Zmc2V0IC8gX3N0cmlwLXVuaXRzKCRtYXgtZm9udCkpKSApICsgZW07XG4gIH0gQGVsc2Uge1xuICAgIEByZXR1cm4gKCAoKCRsaW5lLWhlaWdodC1yYXRpbyAqIF9zdHJpcC11bml0cygkbWF4LWZvbnQpKSAvIChfc3RyaXAtdW5pdHMoJG1heC1mb250KSAvIDIpKSAqICgkdW5pdHMgLyAyKSApICsgZW07XG4gIH1cbn1cblxuXG4vLy8gUGVyZm9ybXMgZXhwb25lbnQgbWF0aCBvbiBmbG9hdGVkIG51bWJlcnMuXG4vLy9cbi8vLyBAZXhhbXBsZVxuLy8vICAgbWF0aC1wb3coMywgMylcbi8vL1xuLy8vIEBhY2Nlc3MgcHJpdmF0ZVxuXG5AZnVuY3Rpb24gbWF0aC1wb3coJG51bWJlciwgJGV4cCkge1xuICAgIEBpZiAocm91bmQoJGV4cCkgIT0gJGV4cCkge1xuICAgICAgQHJldHVybiBtYXRoLWV4cCgkZXhwICogbWF0aC1sbigkbnVtYmVyKSk7XG4gICAgfVxuXG4gICAgJHZhbHVlOiAxO1xuXG4gICAgQGlmICRleHAgPiAwIHtcbiAgICAgICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAkZXhwIHtcbiAgICAgICAgICAgJHZhbHVlOiAkdmFsdWUgKiAkbnVtYmVyO1xuICAgICAgICB9XG4gICAgfVxuICAgIEBlbHNlIGlmICRleHAgPCAwIHtcbiAgICAgICAgQGZvciAkaSBmcm9tIDEgdGhyb3VnaCAtJGV4cCB7XG4gICAgICAgICAgICAkdmFsdWU6ICR2YWx1ZSAvICRudW1iZXI7XG4gICAgICAgIH1cbiAgICB9XG5cbiAgICBAcmV0dXJuICR2YWx1ZTtcbn1cblxuXG4vLy8gSGVscHMgd2l0aCBtYXRoLXBvdygpIGZ1bmN0aW9uXG4vLy9cbi8vLyBAYWNjZXNzIHByaXZhdGVcblxuQGZ1bmN0aW9uIG1hdGgtZmFjdG9yaWFsKCR2YWx1ZSkge1xuICBAaWYgJHZhbHVlID09IDAge1xuICAgIEByZXR1cm4gMTtcbiAgfVxuXG4gICRyZXN1bHQ6IDE7XG5cbiAgQGZvciAkaW5kZXggZnJvbSAxIHRocm91Z2ggJHZhbHVlIHtcbiAgICAkcmVzdWx0OiAkcmVzdWx0ICogJGluZGV4O1xuICB9XG5cbiAgQHJldHVybiAkcmVzdWx0O1xufVxuXG5cbi8vLyBIZWxwcyB3aXRoIG1hdGgtcG93KCkgZnVuY3Rpb25cbi8vL1xuLy8vIEBhY2Nlc3MgcHJpdmF0ZVxuXG5AZnVuY3Rpb24gbWF0aC1zdW1tYXRpb24oJGl0ZXJhdGVlLCAkaW5wdXQsICRpbml0aWFsOiAwLCAkbGltaXQ6IDEwMCkge1xuICAkc3VtOiAwO1xuXG4gIEBmb3IgJGluZGV4IGZyb20gJGluaXRpYWwgdG8gJGxpbWl0IHtcbiAgICAkc3VtOiAkc3VtICsgY2FsbCgkaXRlcmF0ZWUsICRpbnB1dCwgJGluZGV4KTtcbiAgfVxuXG4gIEByZXR1cm4gJHN1bTtcbn1cblxuXG4vLy8gSGVscHMgd2l0aCBtYXRoLXBvdygpIGZ1bmN0aW9uXG4vLy9cbi8vLyBAYWNjZXNzIHByaXZhdGVcblxuQGZ1bmN0aW9uIG1hdGgtZXhwLW1hY2xhdXJpbigkeCwgJG4pIHtcbiAgJHJlc3VsdDogbWF0aC1wb3coJHgsICRuKSAvIG1hdGgtZmFjdG9yaWFsKCRuKTtcbiAgQHJldHVybiAkcmVzdWx0O1xufVxuXG5cbi8vLyBIZWxwcyB3aXRoIG1hdGgtcG93KCkgZnVuY3Rpb25cbi8vL1xuLy8vIEBhY2Nlc3MgcHJpdmF0ZVxuXG5AZnVuY3Rpb24gbWF0aC1leHAoJHZhbHVlKSB7XG4gICRyZXN1bHQ6IG1hdGgtc3VtbWF0aW9uKG1hdGgtZXhwLW1hY2xhdXJpbiwgJHZhbHVlLCAwLCAxMDApO1xuICBAcmV0dXJuICRyZXN1bHQ7XG59XG5cblxuLy8vIEhlbHBzIHdpdGggbWF0aC1wb3coKSBmdW5jdGlvblxuLy8vXG4vLy8gQGFjY2VzcyBwcml2YXRlXG5cbkBmdW5jdGlvbiBtYXRoLWxuLW1hY2xhdXJpbigkeCwgJG4pIHtcbiAgJHJlc3VsdDogKG1hdGgtcG93KC0xLCAkbiArIDEpIC8gJG4pICogKG1hdGgtcG93KCR4IC0gMSwgJG4pKTtcbiAgQHJldHVybiAkcmVzdWx0O1xufVxuXG5cbi8vLyBIZWxwcyB3aXRoIG1hdGgtcG93KCkgZnVuY3Rpb25cbi8vL1xuLy8vIEBhY2Nlc3MgcHJpdmF0ZVxuXG5AZnVuY3Rpb24gbWF0aC1sbigkdmFsdWUpIHtcbiAgJHRlbi1leHA6IDE7XG4gICRsbi10ZW46IDIuMzAyNTg1MDk7XG5cbiAgQHdoaWxlICgkdmFsdWUgPiBtYXRoLXBvdygxMCwgJHRlbi1leHApKSB7XG4gICAgJHRlbi1leHA6ICR0ZW4tZXhwICsgMTtcbiAgfVxuXG4gICR2YWx1ZTogJHZhbHVlIC8gbWF0aC1wb3coMTAsICR0ZW4tZXhwKTtcblxuICAkcmVzdWx0OiBtYXRoLXN1bW1hdGlvbihtYXRoLWxuLW1hY2xhdXJpbiwgJHZhbHVlLCAxLCAxMDApO1xuXG4gIEByZXR1cm4gJHJlc3VsdCArICR0ZW4tZXhwICogJGxuLXRlbjtcbn1cblxuXG4vLyBUeXBvZ3JhcGh5IE1peGluc1xuXG5AbWl4aW4gdC1odG1sKCkge1xuICBmb250LWZhbWlseTogJGJvZHktZm9udDtcbiAgZm9udC13ZWlnaHQ6ICRib2R5LWZvbnQtd2VpZ2h0O1xuICBjb2xvcjogJGJvZHktY29sb3I7XG5cbiAgZm9udC1zaXplOiAkbWluLWZvbnQ7XG4gIGxpbmUtaGVpZ2h0OiAjeyRsaW5lLWhlaWdodC1yYXRpb31lbTtcblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1pbi13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggI3skbWluLWZvbnR9ICsgKCN7X3N0cmlwLXVuaXRzKCRtYXgtZm9udCl9IC0gI3tfc3RyaXAtdW5pdHMoJG1pbi1mb250KX0pICogKCgxMDB2dyAtICN7JG1pbi13aWR0aH0pIC8gKCN7X3N0cmlwLXVuaXRzKCRtYXgtd2lkdGgpfSAtICN7X3N0cmlwLXVuaXRzKCRtaW4td2lkdGgpfSkpICk7XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogJG1heC1mb250O1xuICB9XG59XG5cbkBtaXhpbiB0LXAoKSB7XG4gIEBpbmNsdWRlIHQtaHRtbDtcbn1cblxuQG1peGluIHQtcmVzZXQoKSB7XG4gIG1hcmdpbjogMDtcbiAgcGFkZGluZzogMDtcbn1cblxuQG1peGluIHQtYmxvY2soKSB7XG4gIG1hcmdpbi1ib3R0b206ICN7JGxpbmUtaGVpZ2h0LXJhdGlvfWVtO1xufVxuXG5AbWl4aW4gdC1oZWFkZXIoKSB7XG4gIGZvbnQtZmFtaWx5OiAkaGVhZGVyLWZvbnQ7XG4gIGZvbnQtd2VpZ2h0OiAkaGVhZGVyLWZvbnQtd2VpZ2h0O1xuICBjb2xvcjogJGhlYWRlci1jb2xvcjtcbiAgY2xlYXI6IGJvdGg7XG59XG5cbkBtaXhpbiB0LWgxKCkge1xuICAkbG9jYWwtbWluLWZvbnQ6ICRtaW4tZm9udCAqIChtYXRoLXBvdygkaGVhZGVyLXJhdGlvLCAxLjc1KSk7XG4gICRsb2NhbC1tYXgtZm9udDogJG1heC1mb250ICogKG1hdGgtcG93KCRoZWFkZXItcmF0aW8sIDEuNzUpKTtcblxuICBmb250LXNpemU6ICRsb2NhbC1taW4tZm9udDtcbiAgQGlmICgkdmVydGljYWwtcmh5dGhtKSB7XG4gICAgbWFyZ2luLXRvcDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuMjUpKSArIGVtO1xuICAgIGxpbmUtaGVpZ2h0OiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtaW4tZm9udCkgLyAoJGxvY2FsLW1pbi1mb250IC8gMS41KSkgKyBlbTtcbiAgICBtYXJnaW4tYm90dG9tOiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtaW4tZm9udCkgLyAoJGxvY2FsLW1pbi1mb250IC8gLjI1KSkgKyBlbTtcbiAgfSBAZWxzZSB7XG4gICAgbWFyZ2luLXRvcDogMDtcbiAgICBsaW5lLWhlaWdodDogMS4xZW07XG4gICAgbWFyZ2luLWJvdHRvbTogLjI1ZW07XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1pbi13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggI3skbG9jYWwtbWluLWZvbnR9ICsgKCN7X3N0cmlwLXVuaXRzKCRsb2NhbC1tYXgtZm9udCl9IC0gI3tfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KX0pICogKCgxMDB2dyAtICN7JG1pbi13aWR0aH0pIC8gKCN7X3N0cmlwLXVuaXRzKCRtYXgtd2lkdGgpfSAtICN7X3N0cmlwLXVuaXRzKCRtaW4td2lkdGgpfSkpICk7XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogJGxvY2FsLW1heC1mb250O1xuICAgIEBpZiAoJHZlcnRpY2FsLXJoeXRobSkge1xuICAgICAgbWFyZ2luLXRvcDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWF4LWZvbnQpIC8gKCRsb2NhbC1tYXgtZm9udCAvIDEuMjUpKSArIGVtO1xuICAgICAgbGluZS1oZWlnaHQ6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAxLjUpKSArIGVtO1xuICAgICAgbWFyZ2luLWJvdHRvbTogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWF4LWZvbnQpIC8gKCRsb2NhbC1tYXgtZm9udCAvIC4yNSkpICsgZW07XG4gICAgfVxuICB9XG59XG5cbkBtaXhpbiB0LWgyKCkge1xuICAkbG9jYWwtbWluLWZvbnQ6ICRtaW4tZm9udCAqIChtYXRoLXBvdygkaGVhZGVyLXJhdGlvLCAxLjQpKTtcbiAgJGxvY2FsLW1heC1mb250OiAkbWF4LWZvbnQgKiAobWF0aC1wb3coJGhlYWRlci1yYXRpbywgMS40KSk7XG5cbiAgZm9udC1zaXplOiAkbG9jYWwtbWluLWZvbnQ7XG4gIEBpZiAoJHZlcnRpY2FsLXJoeXRobSkge1xuICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1pbi1mb250KSAvICgkbG9jYWwtbWluLWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICBsaW5lLWhlaWdodDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuNSkpICsgZW07XG4gICAgbWFyZ2luLWJvdHRvbTogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiBfc3RyaXAtdW5pdHMoJG1pbi1mb250KSkgLyAoX3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCkgLyAuMjUpICogKDEgKyAoMyAvIF9zdHJpcC11bml0cygkbG9jYWwtbWluLWZvbnQpKSkpICsgZW07XG4gIH0gQGVsc2Uge1xuICAgIG1hcmdpbi10b3A6IDA7XG4gICAgbGluZS1oZWlnaHQ6IDEuMmVtO1xuICAgIG1hcmdpbi1ib3R0b206IC4yNWVtO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtaW4td2lkdGgpIHtcbiAgICBmb250LXNpemU6IGNhbGMoICN7JGxvY2FsLW1pbi1mb250fSArICgje19zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpfSAtICN7X3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCl9KSAqICgoMTAwdncgLSAjeyRtaW4td2lkdGh9KSAvICgje19zdHJpcC11bml0cygkbWF4LXdpZHRoKX0gLSAje19zdHJpcC11bml0cygkbWluLXdpZHRoKX0pKSApO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtYXgtd2lkdGgpIHtcbiAgICBmb250LXNpemU6ICRsb2NhbC1tYXgtZm9udDtcbiAgICBAaWYgKCR2ZXJ0aWNhbC1yaHl0aG0pIHtcbiAgICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICAgIGxpbmUtaGVpZ2h0OiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtYXgtZm9udCkgLyAoJGxvY2FsLW1heC1mb250IC8gMS41KSkgKyBlbTtcbiAgICAgIG1hcmdpbi1ib3R0b206ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogX3N0cmlwLXVuaXRzKCRtYXgtZm9udCkpIC8gKF9zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpIC8gLjI1KSAqICgxICsgKDMgLyBfc3RyaXAtdW5pdHMoJGxvY2FsLW1heC1mb250KSkpKSArIGVtO1xuICAgIH1cbiAgfVxufVxuXG5AbWl4aW4gdC1oMygpIHtcbiAgJGxvY2FsLW1pbi1mb250OiAkbWluLWZvbnQgKiAobWF0aC1wb3coJGhlYWRlci1yYXRpbywgMS4wNSkpO1xuICAkbG9jYWwtbWF4LWZvbnQ6ICRtYXgtZm9udCAqIChtYXRoLXBvdygkaGVhZGVyLXJhdGlvLCAxLjA1KSk7XG5cbiAgZm9udC1zaXplOiAkbG9jYWwtbWluLWZvbnQ7XG4gIEBpZiAoJHZlcnRpY2FsLXJoeXRobSkge1xuICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1pbi1mb250KSAvICgkbG9jYWwtbWluLWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICBsaW5lLWhlaWdodDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuNSkpICsgZW07XG4gICAgbWFyZ2luLWJvdHRvbTogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiBfc3RyaXAtdW5pdHMoJG1pbi1mb250KSkgLyAoX3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCkgLyAuMjUpICogKDEgKyAoMyAvIF9zdHJpcC11bml0cygkbG9jYWwtbWluLWZvbnQpKSkpICsgZW07XG4gIH0gQGVsc2Uge1xuICAgIG1hcmdpbi10b3A6IDA7XG4gICAgbGluZS1oZWlnaHQ6IDEuM2VtO1xuICAgIG1hcmdpbi1ib3R0b206IC4yNWVtO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtaW4td2lkdGgpIHtcbiAgICBmb250LXNpemU6IGNhbGMoICN7JGxvY2FsLW1pbi1mb250fSArICgje19zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpfSAtICN7X3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCl9KSAqICgoMTAwdncgLSAjeyRtaW4td2lkdGh9KSAvICgje19zdHJpcC11bml0cygkbWF4LXdpZHRoKX0gLSAje19zdHJpcC11bml0cygkbWluLXdpZHRoKX0pKSApO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtYXgtd2lkdGgpIHtcbiAgICBmb250LXNpemU6ICRsb2NhbC1tYXgtZm9udDtcbiAgICBAaWYgKCR2ZXJ0aWNhbC1yaHl0aG0pIHtcbiAgICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICAgIGxpbmUtaGVpZ2h0OiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtYXgtZm9udCkgLyAoJGxvY2FsLW1heC1mb250IC8gMS41KSkgKyBlbTtcbiAgICAgIG1hcmdpbi1ib3R0b206ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogX3N0cmlwLXVuaXRzKCRtYXgtZm9udCkpIC8gKF9zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpIC8gLjI1KSAqICgxICsgKDMgLyBfc3RyaXAtdW5pdHMoJGxvY2FsLW1heC1mb250KSkpKSArIGVtO1xuICAgIH1cbiAgfVxufVxuXG5AbWl4aW4gdC1oNCgpIHtcbiAgJGxvY2FsLW1pbi1mb250OiAkbWluLWZvbnQgKiAobWF0aC1wb3coJGhlYWRlci1yYXRpbywgLjcpKTtcbiAgJGxvY2FsLW1heC1mb250OiAkbWF4LWZvbnQgKiAobWF0aC1wb3coJGhlYWRlci1yYXRpbywgLjcpKTtcblxuICBmb250LXNpemU6ICRsb2NhbC1taW4tZm9udDtcbiAgQGlmICgkdmVydGljYWwtcmh5dGhtKSB7XG4gICAgbWFyZ2luLXRvcDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuMjUpKSArIGVtO1xuICAgIGxpbmUtaGVpZ2h0OiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtaW4tZm9udCkgLyAoJGxvY2FsLW1pbi1mb250IC8gMS41KSkgKyBlbTtcbiAgICBtYXJnaW4tYm90dG9tOiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqIF9zdHJpcC11bml0cygkbWluLWZvbnQpKSAvIChfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KSAvIC4yNSkgKiAoMSArICgzIC8gX3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCkpKSkgKyBlbTtcbiAgfSBAZWxzZSB7XG4gICAgbWFyZ2luLXRvcDogMDtcbiAgICBsaW5lLWhlaWdodDogMS40ZW07XG4gICAgbWFyZ2luLWJvdHRvbTogLjI1ZW07XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1pbi13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggI3skbG9jYWwtbWluLWZvbnR9ICsgKCN7X3N0cmlwLXVuaXRzKCRsb2NhbC1tYXgtZm9udCl9IC0gI3tfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KX0pICogKCgxMDB2dyAtICN7JG1pbi13aWR0aH0pIC8gKCN7X3N0cmlwLXVuaXRzKCRtYXgtd2lkdGgpfSAtICN7X3N0cmlwLXVuaXRzKCRtaW4td2lkdGgpfSkpICk7XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogJGxvY2FsLW1heC1mb250O1xuICAgIEBpZiAoJHZlcnRpY2FsLXJoeXRobSkge1xuICAgICAgbWFyZ2luLXRvcDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWF4LWZvbnQpIC8gKCRsb2NhbC1tYXgtZm9udCAvIDEuMjUpKSArIGVtO1xuICAgICAgbGluZS1oZWlnaHQ6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAxLjUpKSArIGVtO1xuICAgICAgbWFyZ2luLWJvdHRvbTogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiBfc3RyaXAtdW5pdHMoJG1heC1mb250KSkgLyAoX3N0cmlwLXVuaXRzKCRsb2NhbC1tYXgtZm9udCkgLyAuMjUpICogKDEgKyAoMyAvIF9zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpKSkpICsgZW07XG4gICAgfVxuICB9XG59XG5cbkBtaXhpbiB0LWg1KCkge1xuICAkbG9jYWwtbWluLWZvbnQ6ICRtaW4tZm9udCAqIChtYXRoLXBvdygkaGVhZGVyLXJhdGlvLCAuMzUpKTtcbiAgJGxvY2FsLW1heC1mb250OiAkbWF4LWZvbnQgKiAobWF0aC1wb3coJGhlYWRlci1yYXRpbywgLjM1KSk7XG5cbiAgZm9udC1zaXplOiAkbG9jYWwtbWluLWZvbnQ7XG4gIEBpZiAoJHZlcnRpY2FsLXJoeXRobSkge1xuICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1pbi1mb250KSAvICgkbG9jYWwtbWluLWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICBsaW5lLWhlaWdodDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuNSkpICsgZW07XG4gICAgbWFyZ2luLWJvdHRvbTogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIC4yNSkpICsgZW07XG4gIH0gQGVsc2Uge1xuICAgIG1hcmdpbi10b3A6IDA7XG4gICAgbGluZS1oZWlnaHQ6IDEuNWVtO1xuICAgIG1hcmdpbi1ib3R0b206IC4yNWVtO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtaW4td2lkdGgpIHtcbiAgICBmb250LXNpemU6IGNhbGMoICN7JGxvY2FsLW1pbi1mb250fSArICgje19zdHJpcC11bml0cygkbG9jYWwtbWF4LWZvbnQpfSAtICN7X3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCl9KSAqICgoMTAwdncgLSAjeyRtaW4td2lkdGh9KSAvICgje19zdHJpcC11bml0cygkbWF4LXdpZHRoKX0gLSAje19zdHJpcC11bml0cygkbWluLXdpZHRoKX0pKSApO1xuICB9XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtYXgtd2lkdGgpIHtcbiAgICBmb250LXNpemU6ICRsb2NhbC1tYXgtZm9udDtcbiAgICBAaWYgKCR2ZXJ0aWNhbC1yaHl0aG0pIHtcbiAgICAgIG1hcmdpbi10b3A6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAxLjI1KSkgKyBlbTtcbiAgICAgIGxpbmUtaGVpZ2h0OiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtYXgtZm9udCkgLyAoJGxvY2FsLW1heC1mb250IC8gMS41KSkgKyBlbTtcbiAgICAgIG1hcmdpbi1ib3R0b206ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1heC1mb250KSAvICgkbG9jYWwtbWF4LWZvbnQgLyAuMjUpKSArIGVtO1xuICAgIH1cbiAgfVxufVxuXG5AbWl4aW4gdC1oNigpIHtcbiAgJGxvY2FsLW1pbi1mb250OiAkbWluLWZvbnQ7XG4gICRsb2NhbC1tYXgtZm9udDogJG1heC1mb250O1xuXG4gIGZvbnQtc2l6ZTogJGxvY2FsLW1pbi1mb250O1xuICBAaWYgKCR2ZXJ0aWNhbC1yaHl0aG0pIHtcbiAgICBtYXJnaW4tdG9wOiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtaW4tZm9udCkgLyAoJGxvY2FsLW1pbi1mb250IC8gMS4yNSkpICsgZW07XG4gICAgbGluZS1oZWlnaHQ6ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogJG1pbi1mb250KSAvICgkbG9jYWwtbWluLWZvbnQgLyAxLjUpKSArIGVtO1xuICAgIG1hcmdpbi1ib3R0b206ICgoJGxpbmUtaGVpZ2h0LXJhdGlvICogX3N0cmlwLXVuaXRzKCRtaW4tZm9udCkpIC8gKF9zdHJpcC11bml0cygkbG9jYWwtbWluLWZvbnQpIC8gLjI1KSAqICgxICsgKDIgLyBfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KSkpKSArIGVtO1xuICB9IEBlbHNlIHtcbiAgICBtYXJnaW4tdG9wOiAwO1xuICAgIGxpbmUtaGVpZ2h0OiAxLjZlbTtcbiAgICBtYXJnaW4tYm90dG9tOiAuMjVlbTtcbiAgfVxuXG4gIEBtZWRpYSAobWluLXdpZHRoOiAkbWluLXdpZHRoKSB7XG4gICAgZm9udC1zaXplOiBjYWxjKCAjeyRsb2NhbC1taW4tZm9udH0gKyAoI3tfc3RyaXAtdW5pdHMoJGxvY2FsLW1heC1mb250KX0gLSAje19zdHJpcC11bml0cygkbG9jYWwtbWluLWZvbnQpfSkgKiAoKDEwMHZ3IC0gI3skbWluLXdpZHRofSkgLyAoI3tfc3RyaXAtdW5pdHMoJG1heC13aWR0aCl9IC0gI3tfc3RyaXAtdW5pdHMoJG1pbi13aWR0aCl9KSkgKTtcbiAgfVxuXG4gIEBtZWRpYSAobWluLXdpZHRoOiAkbWF4LXdpZHRoKSB7XG4gICAgZm9udC1zaXplOiAkbG9jYWwtbWF4LWZvbnQ7XG4gICAgQGlmICgkdmVydGljYWwtcmh5dGhtKSB7XG4gICAgICBtYXJnaW4tdG9wOiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqICRtaW4tZm9udCkgLyAoJGxvY2FsLW1pbi1mb250IC8gMS4yNSkpICsgZW07XG4gICAgICBsaW5lLWhlaWdodDogKCgkbGluZS1oZWlnaHQtcmF0aW8gKiAkbWluLWZvbnQpIC8gKCRsb2NhbC1taW4tZm9udCAvIDEuNSkpICsgZW07XG4gICAgICBtYXJnaW4tYm90dG9tOiAoKCRsaW5lLWhlaWdodC1yYXRpbyAqIF9zdHJpcC11bml0cygkbWluLWZvbnQpKSAvIChfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KSAvIC4yNSkgKiAoMSArICgxIC8gX3N0cmlwLXVuaXRzKCRsb2NhbC1taW4tZm9udCkpKSkgKyBlbTtcbiAgICB9XG4gIH1cbn1cblxuQG1peGluIHQtYmxvY2txdW90ZSgpIHtcbiAgZm9udC1zdHlsZTogaXRhbGljO1xuICBjaXRlIHtcbiAgICBmb250LXN0eWxlOiBub3JtYWw7XG4gIH1cbn1cblxuQG1peGluIHQtcHJlKCkge1xuICBwYWRkaW5nOiAoJGxpbmUtaGVpZ2h0LXJhdGlvICogLjUpICsgZW07XG4gIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKDEpO1xuICBjb2RlIHtcbiAgICBwYWRkaW5nOiAwO1xuICB9XG59XG5cbkBtaXhpbiB0LWNvZGUoKSB7XG4gIGZvbnQtZmFtaWx5OiAkY291cmllcjtcbiAgcGFkZGluZzogKCRsaW5lLWhlaWdodC1yYXRpbyAqIC4wNSkgKyBlbSAoJGxpbmUtaGVpZ2h0LXJhdGlvICogLjE1KSArIGVtO1xuICBsaW5lLWhlaWdodDogMDtcbn1cblxuQG1peGluIHQtYWJicigpIHtcbiAgYm9yZGVyLWJvdHRvbTogMXB4IGRvdHRlZCBjdXJyZW50Q29sb3I7XG4gIGN1cnNvcjogaGVscDtcbn1cblxuQG1peGluIHQtZHQoKSB7XG4gIGNvbG9yOiAkaGVhZGVyLWNvbG9yO1xuICBmb250LXdlaWdodDogYm9sZDtcbn1cblxuQG1peGluIHQtZmllbGRzZXQoKSB7XG4gIHBhZGRpbmc6IHZyLWJsb2NrKC41KSB2ci1ibG9jaygpIHZyLWJsb2NrKCk7XG4gIGJvcmRlci13aWR0aDogMXB4O1xuICBib3JkZXItc3R5bGU6IHNvbGlkO1xuICBtYXgtd2lkdGg6IDEwMCU7XG4gIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKDEsIDEpO1xuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKDEuMjUsIC0xKTtcbiAgfVxuICBidXR0b24sIGlucHV0W3R5cGU9XCJzdWJtaXRcIl0ge1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG4gIH1cbn1cblxuQG1peGluIHQtbGVnZW5kKCkge1xuICBjb2xvcjogJGhlYWRlci1jb2xvcjtcbiAgZm9udC13ZWlnaHQ6IGJvbGQ7XG59XG5cbkBtaXhpbiB0LWlucHV0KCkge1xuICAkbG9jYWwtbWluLWZvbnQ6ICRtaW4tZm9udDtcbiAgJGxvY2FsLW1heC1mb250OiAkbWF4LWZvbnQ7XG5cbiAgZGlzcGxheTogYmxvY2s7XG4gIG1heC13aWR0aDogMTAwJTtcbiAgcGFkZGluZzogdnItYmxvY2soLjI1KTtcblxuICBmb250LXNpemU6ICRsb2NhbC1taW4tZm9udDtcbiAgbWFyZ2luLWJvdHRvbTogdnItYmxvY2soLjUsIDcpO1xuXG4gIEBtZWRpYSAobWluLXdpZHRoOiAkbWluLXdpZHRoKSB7XG4gICAgZm9udC1zaXplOiBjYWxjKCAjeyRsb2NhbC1taW4tZm9udH0gKyAoI3tfc3RyaXAtdW5pdHMoJGxvY2FsLW1heC1mb250KX0gLSAje19zdHJpcC11bml0cygkbG9jYWwtbWluLWZvbnQpfSkgKiAoKDEwMHZ3IC0gI3skbWluLXdpZHRofSkgLyAoI3tfc3RyaXAtdW5pdHMoJG1heC13aWR0aCl9IC0gI3tfc3RyaXAtdW5pdHMoJG1pbi13aWR0aCl9KSkgKTtcbiAgfVxuXG4gIEBtZWRpYSAobWluLXdpZHRoOiAkbWF4LXdpZHRoKSB7XG4gICAgZm9udC1zaXplOiAkbG9jYWwtbWF4LWZvbnQ7XG4gICAgbWFyZ2luLWJvdHRvbTogdnItYmxvY2soLjI1LCAzLjUpO1xuICB9XG59XG5cbkBtaXhpbiB0LWJ1dHRvbigpIHtcbiAgJGxvY2FsLW1pbi1mb250OiAkbWluLWZvbnQ7XG4gICRsb2NhbC1tYXgtZm9udDogJG1heC1mb250O1xuXG4gIC8qIGRpc3BsYXk6IGJsb2NrOyAqL1xuICBjdXJzb3I6IHBvaW50ZXI7XG5cbiAgZm9udC1zaXplOiAkbG9jYWwtbWluLWZvbnQ7XG4gIHBhZGRpbmc6IHZyLWJsb2NrKC4yNSkgdnItYmxvY2soKTtcbiAgbWFyZ2luLWJvdHRvbTogMDtcblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1pbi13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggI3skbG9jYWwtbWluLWZvbnR9ICsgKCN7X3N0cmlwLXVuaXRzKCRsb2NhbC1tYXgtZm9udCl9IC0gI3tfc3RyaXAtdW5pdHMoJGxvY2FsLW1pbi1mb250KX0pICogKCgxMDB2dyAtICN7JG1pbi13aWR0aH0pIC8gKCN7X3N0cmlwLXVuaXRzKCRtYXgtd2lkdGgpfSAtICN7X3N0cmlwLXVuaXRzKCRtaW4td2lkdGgpfSkpICk7XG4gIH1cblxuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIGZvbnQtc2l6ZTogJGxvY2FsLW1heC1mb250O1xuICAgIG1hcmdpbi1ib3R0b206IDA7XG4gIH1cbn1cblxuQG1peGluIHQtbGFiZWwoKSB7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBwYWRkaW5nLWJvdHRvbTogdnItYmxvY2soLjEyNSk7XG4gIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKC0uMjUsIC0xMCk7XG59XG5cbkBtaXhpbiB0LXRhYmxlKCkge1xuICB3aWR0aDogMTAwJTtcbiAgYm9yZGVyLXNwYWNpbmc6IDA7XG4gIGJvcmRlci1jb2xsYXBzZTogY29sbGFwc2U7XG4gIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKDEsIDUpO1xuICBAbWVkaWEgKG1pbi13aWR0aDogJG1heC13aWR0aCkge1xuICAgIG1hcmdpbi1ib3R0b206IHZyLWJsb2NrKDEsIDMpO1xuICB9XG59XG5cbkBtaXhpbiB0LXRoKCkge1xuICB0ZXh0LWFsaWduOiBsZWZ0O1xuICBjb2xvcjogJGhlYWRlci1jb2xvcjtcblxuICBwYWRkaW5nOiB2ci1ibG9jayguMTI1KSB2ci1ibG9jayguNSk7XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtYXgtd2lkdGgpIHtcbiAgICBwYWRkaW5nOiB2ci1ibG9jayguMjUpIHZyLWJsb2NrKC41KTtcbiAgfVxufVxuXG5AbWl4aW4gdC10ZCgpIHtcbiAgcGFkZGluZzogKCRsaW5lLWhlaWdodC1yYXRpbyAqIC41KSArIGVtO1xuICBwYWRkaW5nOiB2ci1ibG9jayguMTI1KSB2ci1ibG9jayguNSk7XG5cbiAgQG1lZGlhIChtaW4td2lkdGg6ICRtYXgtd2lkdGgpIHtcbiAgICBwYWRkaW5nOiB2ci1ibG9jayguMjUpIHZyLWJsb2NrKC41KTtcbiAgfVxufVxuXG5cbi8vLyBUaGUgVHlwb2dyYXBoaWMgUmVzZXQuIFRoaXMgaXMgd2hlcmUgVHlwb2dyYXBoaWMgZ29lcyB0aHJvdWdoIGV2ZXJ5IG1hcmt1cCBlbGVtZW50IGFuZCBzdHlsZXMgaXQgdG8gYWRoZXJlIHRvIGEgdmVydGljYWwgcmh5dGhtLiBBZnRlciB5b3Ugc2V0IHlvdXIgdmFyaWFibGVzIGluIGEgc2V0dGluZ3MgZmlsZSBmaXJlIHRoaXMgbWl4aW4uXG4vLy9cbi8vLyBAZXhhbXBsZVxuLy8vICAgQGluY2x1ZGUgdHlwb2dyYXBoaWM7XG5cbkBtaXhpbiB0eXBvZ3JhcGhpYygpIHtcblxuICBodG1sLCBib2R5IHtcbiAgICBAaW5jbHVkZSB0LWh0bWw7XG4gIH1cblxuICBoMSwgaDIsIGgzLCBoNCwgaDUsIGg2LCBwLCBibG9ja3F1b3RlLCBwcmUsXG4gIGEsIGFiYnIsIGFjcm9ueW0sIGFkZHJlc3MsIGJpZywgY2l0ZSwgY29kZSxcbiAgZGVsLCBkZm4sIGVtLCBpbWcsIGlucywga2JkLCBxLCBzLCBzYW1wLFxuICBzbWFsbCwgc3RyaWtlLCBzdHJvbmcsIHN1Yiwgc3VwLCB0dCwgdmFyLFxuICBiLCB1LCBpLCBjZW50ZXIsXG4gIGRsLCBkdCwgZGQsIG9sLCB1bCwgbGksXG4gIGZpZWxkc2V0LCBmb3JtLCBsYWJlbCwgbGVnZW5kLFxuICB0YWJsZSwgY2FwdGlvbiwgdGJvZHksIHRmb290LCB0aGVhZCwgdHIsIHRoLCB0ZCB7XG4gICAgQGluY2x1ZGUgdC1yZXNldDtcbiAgfVxuXG4gIHAsIGJsb2NrcXVvdGUsIHByZSxcbiAgYWRkcmVzcyxcbiAgZGwsIG9sLCB1bCxcbiAgdGFibGUge1xuICAgIEBpbmNsdWRlIHQtYmxvY2s7XG4gIH1cblxuICBoMSwgaDIsIGgzLCBoNCwgaDUsIGg2LCAuaDEsIC5oMiwgLmgzLCAuaDQsIC5oNSwgLmg2IHtcbiAgICBAaW5jbHVkZSB0LWhlYWRlcjtcbiAgfVxuXG4gIGgxLCAuaDEge1xuICAgIEBpbmNsdWRlIHQtaDE7XG4gIH1cblxuICBoMiwgLmgyIHtcbiAgICBAaW5jbHVkZSB0LWgyO1xuICB9XG5cbiAgaDMsIC5oMyB7XG4gICAgQGluY2x1ZGUgdC1oMztcbiAgfVxuXG4gIGg0LCAuaDQge1xuICAgIEBpbmNsdWRlIHQtaDQ7XG4gIH1cblxuICBoNSwgLmg1IHtcbiAgICBAaW5jbHVkZSB0LWg1O1xuICB9XG5cbiAgaDYsIC5oNiB7XG4gICAgQGluY2x1ZGUgdC1oNjtcbiAgfVxuXG4gIGJsb2NrcXVvdGUge1xuICAgIEBpbmNsdWRlIHQtYmxvY2txdW90ZTtcbiAgfVxuXG4gIHByZSB7XG4gICAgQGluY2x1ZGUgdC1wcmU7XG4gIH1cblxuICBjb2RlIHtcbiAgICBAaW5jbHVkZSB0LWNvZGU7XG4gIH1cblxuICBiaWcsIHNtYWxsLCBzdWIsIHN1cCB7XG4gICAgbGluZS1oZWlnaHQ6IDA7XG4gIH1cblxuICBhYmJyLCBhY3JvbnltIHtcbiAgICBAaW5jbHVkZSB0LWFiYnI7XG4gIH1cblxuICBhZGRyZXNzIHtcbiAgICBmb250LXN0eWxlOiBub3JtYWw7XG4gIH1cblxuICBkdCB7XG4gICAgQGluY2x1ZGUgdC1kdDtcbiAgfVxuXG4gIHVsIHtcbiAgICBwYWRkaW5nLWxlZnQ6IDEuMWVtO1xuICB9XG5cbiAgb2wge1xuICAgIHBhZGRpbmctbGVmdDogMS40ZW07XG4gIH1cblxuICBmaWVsZHNldCB7XG4gICAgQGluY2x1ZGUgdC1maWVsZHNldDtcbiAgfVxuXG4gIGxlZ2VuZCB7XG4gICAgQGluY2x1ZGUgdC1sZWdlbmQ7XG4gIH1cblxuICBpbnB1dFt0eXBlPVwidGV4dFwiXSwgaW5wdXRbdHlwZT1cImVtYWlsXCJdLCBpbnB1dFt0eXBlPVwicGFzc3dvcmRcIl0sIGlucHV0W3R5cGU9XCJkYXRlXCJdLCBpbnB1dFt0eXBlPVwiZGF0ZXRpbWUtbG9jYWxcIl0sIGlucHV0W3R5cGU9XCJjb2xvclwiXSwgaW5wdXRbdHlwZT1cIm1vbnRoXCJdLCBpbnB1dFt0eXBlPVwidGltZVwiXSwgaW5wdXRbdHlwZT1cIndlZWtcIl0sIGlucHV0W3R5cGU9XCJudW1iZXJcIl0sIGlucHV0W3R5cGU9XCJ1cmxcIl0sIGlucHV0W3R5cGU9XCJzZWFyY2hcIl0sIHRleHRhcmVhIHtcbiAgICBAaW5jbHVkZSB0LWlucHV0O1xuICB9XG5cbiAgaW5wdXRbdHlwZT1cInN1Ym1pdFwiXSwgYnV0dG9uIHtcbiAgICBAaW5jbHVkZSB0LWJ1dHRvbjtcbiAgfVxuXG4gIGxhYmVsIHtcbiAgICBAaW5jbHVkZSB0LWxhYmVsO1xuICB9XG5cbiAgdGFibGUge1xuICAgIEBpbmNsdWRlIHQtdGFibGU7XG4gIH1cblxuICB0aCB7XG4gICAgQGluY2x1ZGUgdC10aDtcbiAgfVxuXG4gIHRkIHtcbiAgICBAaW5jbHVkZSB0LXRkO1xuICB9XG5cbn1cbiIsIi8qIS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIG1haW4uc2Nzc1xuI1xuIyBTYXNzIGZpbGUgZm9yIE9wdGlvbnMtYWRtaW4gdGVtcGxhdGUuXG4jIEF1dGhvcjogU2FsdFRlY2hub1xuI1xuIyBUaGlzIGlzIGNvbXByZXNzZWQgQ1NTIGZpbGUuIFlvdSBnZXQgdW5jb21wcmVzc2VkIHZlcnNpb24gb2ZcbiMgdGhpcyBmaWxlIGFuZCBhbGwgc291cmNlIHNjc3MgZmlsZXMgd2l0aCBkb3dubG9hZC5cbiNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgW1RBQkxFIE9GIENPTlRFTlRTXVxuI1xuIyAxLiBWQVJJQUJMRVMgJiBNSVhJTlNcbiMgMi4gVE9QIE5BVkFCUlxuIyAzLiBTSURFQkFSU1xuIyA0LiBMQVlPVVRcbiMgNS4gUEFORUxTXG4jIDYuIFRBQlNcbiMgNy4gTEFCRUxTICYgQkFER0VTXG4jIDguIFNFQ1RJT05TXG4jIDkuIEJVVFRPTlNcbiMgMTAuIE1PREFMU1xuIyAxMS4gREFTSEJPQVJEIFNUQVRTXG4jIDEyLiBOT1RJRklDQVRJT05TXG4jIDEzLiBQQUdJTkFUSU9OXG4jIDE0LiBGT1JNU1xuIyAxNS4gRVJST1IgUEFHRVNcbiMgMTYuIFBSSUNJTkdcbiMgMTcuIExPR0lOXG4jIDE4LiBEUk9QWk9ORVxuIyAxOS4gQk9PVFNUUkFQIFNXSVRDSFxuIyAyMC4gSlFVRVJZIFNURVBTXG4jIDIxLiBEQVRBVEFCTEVTXG4jIDIyLiBNSVNDRUxMQU5FT1VTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIDEuIFZBUklBQkxFUyAmIE1JWElOU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuQGltcG9ydCAnaHR0cHM6Ly9mb250cy5nb29nbGVhcGlzLmNvbS9jc3M/ZmFtaWx5PVBvcHBpbnM6MzAwLDQwMCw2MDAnO1xuaHRtbCwgYm9keSB7XG4gIGZvbnQtZmFtaWx5OiBcIlBvcHBpbnNcIiwgc2Fucy1zZXJpZjtcbiAgZm9udC13ZWlnaHQ6IDQwMDtcbiAgY29sb3I6ICM0OTQ5NDk7XG4gIGZvbnQtc2l6ZTogMTJweDtcbiAgbGluZS1oZWlnaHQ6IDEuNzVlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGh0bWwsIGJvZHkge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMTJweCArICgxNCAtIDEyKSAqICgoMTAwdncgLSA2MDBweCkgLyAoMTE0MCAtIDYwMCkpKTtcbiAgfVxufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTE0MHB4KSB7XG4gIGh0bWwsIGJvZHkge1xuICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgfVxufVxuXG5oMSwgaDIsIGgzLCBoNCwgaDUsIGg2LCBwLCBibG9ja3F1b3RlLCBwcmUsXG5hLCBhYmJyLCBhY3JvbnltLCBhZGRyZXNzLCBiaWcsIGNpdGUsIGNvZGUsXG5kZWwsIGRmbiwgZW0sIGltZywgaW5zLCBrYmQsIHEsIHMsIHNhbXAsXG5zbWFsbCwgc3RyaWtlLCBzdHJvbmcsIHN1Yiwgc3VwLCB0dCwgdmFyLFxuYiwgdSwgaSwgY2VudGVyLFxuZGwsIGR0LCBkZCwgb2wsIHVsLCBsaSxcbmZpZWxkc2V0LCBmb3JtLCBsYWJlbCwgbGVnZW5kLFxudGFibGUsIGNhcHRpb24sIHRib2R5LCB0Zm9vdCwgdGhlYWQsIHRyLCB0aCwgdGQge1xuICBtYXJnaW46IDA7XG4gIHBhZGRpbmc6IDA7XG59XG5cbnAsIGJsb2NrcXVvdGUsIHByZSxcbmFkZHJlc3MsXG5kbCwgb2wsIHVsLFxudGFibGUge1xuICBtYXJnaW4tYm90dG9tOiAxLjc1ZW07XG59XG5cbmgxLCBoMiwgaDMsIGg0LCBoNSwgaDYsIC5oMSwgLmgyLCAuaDMsIC5oNCwgLmg1LCAuaDYge1xuICBmb250LWZhbWlseTogXCJQb3BwaW5zXCIsIHNhbnMtc2VyaWY7XG4gIGZvbnQtd2VpZ2h0OiA0MDA7XG4gIGNvbG9yOiAjMjkyOTI5O1xuICBjbGVhcjogYm90aDtcbn1cblxuaDEsIC5oMSB7XG4gIGZvbnQtc2l6ZTogMjcuODU0Mzg5ODY4NXB4O1xuICBtYXJnaW4tdG9wOiAwLjk0MjQwMDgyNTNlbTtcbiAgbGluZS1oZWlnaHQ6IDEuMTMwODgwOTkwM2VtO1xuICBtYXJnaW4tYm90dG9tOiAwLjE4ODQ4MDE2NTFlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGgxLCAuaDEge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMjcuODU0Mzg5ODY4NXB4ICsgKDMyLjQ5Njc4ODE3OTkgLSAyNy44NTQzODk4Njg1KSAqICgoMTAwdncgLSA2MDBweCkgLyAoMTE0MCAtIDYwMCkpKTtcbiAgfVxufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTE0MHB4KSB7XG4gIGgxLCAuaDEge1xuICAgIGZvbnQtc2l6ZTogMzIuNDk2Nzg4MTc5OXB4O1xuICAgIG1hcmdpbi10b3A6IDAuOTQyNDAwODI1M2VtO1xuICAgIGxpbmUtaGVpZ2h0OiAxLjEzMDg4MDk5MDNlbTtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjE4ODQ4MDE2NTFlbTtcbiAgfVxufVxuXG5oMiwgLmgyIHtcbiAgZm9udC1zaXplOiAyMy41MzcwMDMzNTE5cHg7XG4gIG1hcmdpbi10b3A6IDEuMTE1MjY1MTY4MWVtO1xuICBsaW5lLWhlaWdodDogMS4zMzgzMTgyMDE3ZW07XG4gIG1hcmdpbi1ib3R0b206IDAuMjUxNDgzMTIyN2VtO1xufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNjAwcHgpIHtcbiAgaDIsIC5oMiB7XG4gICAgZm9udC1zaXplOiBjYWxjKCAyMy41MzcwMDMzNTE5cHggKyAoMjcuNDU5ODM3MjQzOSAtIDIzLjUzNzAwMzM1MTkpICogKCgxMDB2dyAtIDYwMHB4KSAvICgxMTQwIC0gNjAwKSkpO1xuICB9XG59XG5cbkBtZWRpYSAobWluLXdpZHRoOiAxMTQwcHgpIHtcbiAgaDIsIC5oMiB7XG4gICAgZm9udC1zaXplOiAyNy40NTk4MzcyNDM5cHg7XG4gICAgbWFyZ2luLXRvcDogMS4xMTUyNjUxNjgxZW07XG4gICAgbGluZS1oZWlnaHQ6IDEuMzM4MzE4MjAxN2VtO1xuICAgIG1hcmdpbi1ib3R0b206IDAuMjQ3NDIxNjgxNGVtO1xuICB9XG59XG5cbmgzLCAuaDMge1xuICBmb250LXNpemU6IDE5Ljg4ODgwNDkzOXB4O1xuICBtYXJnaW4tdG9wOiAxLjMxOTgzNzk3MzJlbTtcbiAgbGluZS1oZWlnaHQ6IDEuNTgzODA1NTY3OGVtO1xuICBtYXJnaW4tYm90dG9tOiAwLjMwMzc4NDEwMzhlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGgzLCAuaDMge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMTkuODg4ODA0OTM5cHggKyAoMjMuMjAzNjA1NzYyMSAtIDE5Ljg4ODgwNDkzOSkgKiAoKDEwMHZ3IC0gNjAwcHgpIC8gKDExNDAgLSA2MDApKSk7XG4gIH1cbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICBoMywgLmgzIHtcbiAgICBmb250LXNpemU6IDIzLjIwMzYwNTc2MjFweDtcbiAgICBtYXJnaW4tdG9wOiAxLjMxOTgzNzk3MzJlbTtcbiAgICBsaW5lLWhlaWdodDogMS41ODM4MDU1Njc4ZW07XG4gICAgbWFyZ2luLWJvdHRvbTogMC4yOTgwOTYwMzExZW07XG4gIH1cbn1cblxuaDQsIC5oNCB7XG4gIGZvbnQtc2l6ZTogMTYuODA2MDcxNTI4NnB4O1xuICBtYXJnaW4tdG9wOiAxLjU2MTkzNTUxNTdlbTtcbiAgbGluZS1oZWlnaHQ6IDEuODc0MzIyNjE4OWVtO1xuICBtYXJnaW4tYm90dG9tOiAwLjM2ODE1MDM2MTVlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGg0LCAuaDQge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMTYuODA2MDcxNTI4NnB4ICsgKDE5LjYwNzA4MzQ1IC0gMTYuODA2MDcxNTI4NikgKiAoKDEwMHZ3IC0gNjAwcHgpIC8gKDExNDAgLSA2MDApKSk7XG4gIH1cbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICBoNCwgLmg0IHtcbiAgICBmb250LXNpemU6IDE5LjYwNzA4MzQ1cHg7XG4gICAgbWFyZ2luLXRvcDogMS41NjE5MzU1MTU3ZW07XG4gICAgbGluZS1oZWlnaHQ6IDEuODc0MzIyNjE4OWVtO1xuICAgIG1hcmdpbi1ib3R0b206IDAuMzYwMTg0MTgxOGVtO1xuICB9XG59XG5cbmg1LCAuaDUge1xuICBmb250LXNpemU6IDE0LjIwMTE1NjkzNjhweDtcbiAgbWFyZ2luLXRvcDogMS44NDg0NDA5NDg2ZW07XG4gIGxpbmUtaGVpZ2h0OiAyLjIxODEyOTEzODRlbTtcbiAgbWFyZ2luLWJvdHRvbTogMC4zNjk2ODgxODk3ZW07XG59XG5cbkBtZWRpYSAobWluLXdpZHRoOiA2MDBweCkge1xuICBoNSwgLmg1IHtcbiAgICBmb250LXNpemU6IGNhbGMoIDE0LjIwMTE1NjkzNjhweCArICgxNi41NjgwMTY0MjYyIC0gMTQuMjAxMTU2OTM2OCkgKiAoKDEwMHZ3IC0gNjAwcHgpIC8gKDExNDAgLSA2MDApKSk7XG4gIH1cbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICBoNSwgLmg1IHtcbiAgICBmb250LXNpemU6IDE2LjU2ODAxNjQyNjJweDtcbiAgICBtYXJnaW4tdG9wOiAxLjg0ODQ0MDk0ODZlbTtcbiAgICBsaW5lLWhlaWdodDogMi4yMTgxMjkxMzg0ZW07XG4gICAgbWFyZ2luLWJvdHRvbTogMC4zNjk2ODgxODk3ZW07XG4gIH1cbn1cblxuaDYsIC5oNiB7XG4gIGZvbnQtc2l6ZTogMTJweDtcbiAgbWFyZ2luLXRvcDogMi4xODc1ZW07XG4gIGxpbmUtaGVpZ2h0OiAyLjYyNWVtO1xuICBtYXJnaW4tYm90dG9tOiAwLjUxMDQxNjY2NjdlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGg2LCAuaDYge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMTJweCArICgxNCAtIDEyKSAqICgoMTAwdncgLSA2MDBweCkgLyAoMTE0MCAtIDYwMCkpKTtcbiAgfVxufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTE0MHB4KSB7XG4gIGg2LCAuaDYge1xuICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICBtYXJnaW4tdG9wOiAyLjE4NzVlbTtcbiAgICBsaW5lLWhlaWdodDogMi42MjVlbTtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjQ3Mzk1ODMzMzNlbTtcbiAgfVxufVxuXG5ibG9ja3F1b3RlIHtcbiAgZm9udC1zdHlsZTogaXRhbGljO1xufVxuXG5ibG9ja3F1b3RlIGNpdGUge1xuICBmb250LXN0eWxlOiBub3JtYWw7XG59XG5cbnByZSB7XG4gIHBhZGRpbmc6IDAuODc1ZW07XG4gIG1hcmdpbi1ib3R0b206IDEuNzVlbTtcbn1cblxucHJlIGNvZGUge1xuICBwYWRkaW5nOiAwO1xufVxuXG5jb2RlIHtcbiAgZm9udC1mYW1pbHk6IFwiQ291cmllciBOZXdcIiwgXCJDb3VyaWVyXCIsIFwiTHVjaWRhIFNhbnMgVHlwZXdyaXRlclwiLCBcIkx1Y2lkYSBUeXBld3JpdGVyXCIsIFwibW9ub3NwYWNlXCI7XG4gIHBhZGRpbmc6IDAuMDg3NWVtIDAuMjYyNWVtO1xuICBsaW5lLWhlaWdodDogMDtcbn1cblxuYmlnLCBzbWFsbCwgc3ViLCBzdXAge1xuICBsaW5lLWhlaWdodDogMDtcbn1cblxuYWJiciwgYWNyb255bSB7XG4gIGJvcmRlci1ib3R0b206IDFweCBkb3R0ZWQgY3VycmVudENvbG9yO1xuICBjdXJzb3I6IGhlbHA7XG59XG5cbmFkZHJlc3Mge1xuICBmb250LXN0eWxlOiBub3JtYWw7XG59XG5cbmR0IHtcbiAgY29sb3I6ICMyOTI5Mjk7XG4gIGZvbnQtd2VpZ2h0OiBib2xkO1xufVxuXG51bCB7XG4gIHBhZGRpbmctbGVmdDogMS4xZW07XG59XG5cbm9sIHtcbiAgcGFkZGluZy1sZWZ0OiAxLjRlbTtcbn1cblxuZmllbGRzZXQge1xuICBwYWRkaW5nOiAwLjg3NWVtIDEuNzVlbSAxLjc1ZW07XG4gIGJvcmRlci13aWR0aDogMXB4O1xuICBib3JkZXItc3R5bGU6IHNvbGlkO1xuICBtYXgtd2lkdGg6IDEwMCU7XG4gIG1hcmdpbi1ib3R0b206IDEuODc1ZW07XG59XG5cbkBtZWRpYSAobWluLXdpZHRoOiAxMTQwcHgpIHtcbiAgZmllbGRzZXQge1xuICAgIG1hcmdpbi1ib3R0b206IDIuMDMxMjVlbTtcbiAgfVxufVxuXG5maWVsZHNldCBidXR0b24sIGZpZWxkc2V0IGlucHV0W3R5cGU9XCJzdWJtaXRcIl0ge1xuICBtYXJnaW4tYm90dG9tOiAwO1xufVxuXG5sZWdlbmQge1xuICBjb2xvcjogIzI5MjkyOTtcbiAgZm9udC13ZWlnaHQ6IGJvbGQ7XG59XG5cbmlucHV0W3R5cGU9XCJ0ZXh0XCJdLCBpbnB1dFt0eXBlPVwiZW1haWxcIl0sIGlucHV0W3R5cGU9XCJwYXNzd29yZFwiXSwgaW5wdXRbdHlwZT1cImRhdGVcIl0sIGlucHV0W3R5cGU9XCJkYXRldGltZS1sb2NhbFwiXSwgaW5wdXRbdHlwZT1cImNvbG9yXCJdLCBpbnB1dFt0eXBlPVwibW9udGhcIl0sIGlucHV0W3R5cGU9XCJ0aW1lXCJdLCBpbnB1dFt0eXBlPVwid2Vla1wiXSwgaW5wdXRbdHlwZT1cIm51bWJlclwiXSwgaW5wdXRbdHlwZT1cInVybFwiXSwgaW5wdXRbdHlwZT1cInNlYXJjaFwiXSwgdGV4dGFyZWEge1xuICBkaXNwbGF5OiBibG9jaztcbiAgbWF4LXdpZHRoOiAxMDAlO1xuICBwYWRkaW5nOiAwLjQzNzVlbTtcbiAgZm9udC1zaXplOiAxMnB4O1xuICBtYXJnaW4tYm90dG9tOiAxLjMxMjVlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDYwMHB4KSB7XG4gIGlucHV0W3R5cGU9XCJ0ZXh0XCJdLCBpbnB1dFt0eXBlPVwiZW1haWxcIl0sIGlucHV0W3R5cGU9XCJwYXNzd29yZFwiXSwgaW5wdXRbdHlwZT1cImRhdGVcIl0sIGlucHV0W3R5cGU9XCJkYXRldGltZS1sb2NhbFwiXSwgaW5wdXRbdHlwZT1cImNvbG9yXCJdLCBpbnB1dFt0eXBlPVwibW9udGhcIl0sIGlucHV0W3R5cGU9XCJ0aW1lXCJdLCBpbnB1dFt0eXBlPVwid2Vla1wiXSwgaW5wdXRbdHlwZT1cIm51bWJlclwiXSwgaW5wdXRbdHlwZT1cInVybFwiXSwgaW5wdXRbdHlwZT1cInNlYXJjaFwiXSwgdGV4dGFyZWEge1xuICAgIGZvbnQtc2l6ZTogY2FsYyggMTJweCArICgxNCAtIDEyKSAqICgoMTAwdncgLSA2MDBweCkgLyAoMTE0MCAtIDYwMCkpKTtcbiAgfVxufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTE0MHB4KSB7XG4gIGlucHV0W3R5cGU9XCJ0ZXh0XCJdLCBpbnB1dFt0eXBlPVwiZW1haWxcIl0sIGlucHV0W3R5cGU9XCJwYXNzd29yZFwiXSwgaW5wdXRbdHlwZT1cImRhdGVcIl0sIGlucHV0W3R5cGU9XCJkYXRldGltZS1sb2NhbFwiXSwgaW5wdXRbdHlwZT1cImNvbG9yXCJdLCBpbnB1dFt0eXBlPVwibW9udGhcIl0sIGlucHV0W3R5cGU9XCJ0aW1lXCJdLCBpbnB1dFt0eXBlPVwid2Vla1wiXSwgaW5wdXRbdHlwZT1cIm51bWJlclwiXSwgaW5wdXRbdHlwZT1cInVybFwiXSwgaW5wdXRbdHlwZT1cInNlYXJjaFwiXSwgdGV4dGFyZWEge1xuICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICBtYXJnaW4tYm90dG9tOiAwLjU0Njg3NWVtO1xuICB9XG59XG5cbmlucHV0W3R5cGU9XCJzdWJtaXRcIl0sIGJ1dHRvbiB7XG4gIC8qIGRpc3BsYXk6IGJsb2NrOyAqL1xuICBjdXJzb3I6IHBvaW50ZXI7XG4gIGZvbnQtc2l6ZTogMTJweDtcbiAgcGFkZGluZzogMC40Mzc1ZW0gMS43NWVtO1xuICBtYXJnaW4tYm90dG9tOiAwO1xufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNjAwcHgpIHtcbiAgaW5wdXRbdHlwZT1cInN1Ym1pdFwiXSwgYnV0dG9uIHtcbiAgICBmb250LXNpemU6IGNhbGMoIDEycHggKyAoMTQgLSAxMikgKiAoKDEwMHZ3IC0gNjAwcHgpIC8gKDExNDAgLSA2MDApKSk7XG4gIH1cbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICBpbnB1dFt0eXBlPVwic3VibWl0XCJdLCBidXR0b24ge1xuICAgIGZvbnQtc2l6ZTogMTRweDtcbiAgICBtYXJnaW4tYm90dG9tOiAwO1xuICB9XG59XG5cbmxhYmVsIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmctYm90dG9tOiAwLjIxODc1ZW07XG4gIG1hcmdpbi1ib3R0b206IC0wLjEyNWVtO1xufVxuXG50YWJsZSB7XG4gIHdpZHRoOiAxMDAlO1xuICBib3JkZXItc3BhY2luZzogMDtcbiAgYm9yZGVyLWNvbGxhcHNlOiBjb2xsYXBzZTtcbiAgbWFyZ2luLWJvdHRvbTogMi4zNzVlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICB0YWJsZSB7XG4gICAgbWFyZ2luLWJvdHRvbTogMi4xMjVlbTtcbiAgfVxufVxuXG50aCB7XG4gIHRleHQtYWxpZ246IGxlZnQ7XG4gIGNvbG9yOiAjMjkyOTI5O1xuICBwYWRkaW5nOiAwLjIxODc1ZW0gMC44NzVlbTtcbn1cblxuQG1lZGlhIChtaW4td2lkdGg6IDExNDBweCkge1xuICB0aCB7XG4gICAgcGFkZGluZzogMC40Mzc1ZW0gMC44NzVlbTtcbiAgfVxufVxuXG50ZCB7XG4gIHBhZGRpbmc6IDAuODc1ZW07XG4gIHBhZGRpbmc6IDAuMjE4NzVlbSAwLjg3NWVtO1xufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogMTE0MHB4KSB7XG4gIHRkIHtcbiAgICBwYWRkaW5nOiAwLjQzNzVlbSAwLjg3NWVtO1xuICB9XG59XG5cbmJvZHkge1xuICBmb250LWZhbWlseTogXCJQb3BwaW5zXCIsIHNhbnMtc2VyaWY7XG4gIC13ZWJraXQtZm9udC1zbW9vdGhpbmc6IGFudGlhbGlhc2VkO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjJmMmYyO1xuICBjb2xvcjogIzQ5NDk0OTtcbiAgdGV4dC1yZW5kZXJpbmc6IG9wdGltaXplTGVnaWJpbGl0eSAhaW1wb3J0YW50O1xuICBsZXR0ZXItc3BhY2luZzogMC41cHg7XG4gIG92ZXJmbG93LXg6IGhpZGRlbjtcbn1cblxuOjotbW96LXNlbGVjdGlvbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG46OnNlbGVjdGlvbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG5hIHtcbiAgb3V0bGluZTogbm9uZSAhaW1wb3J0YW50O1xuICB0ZXh0LWRlY29yYXRpb246IG5vbmUgIWltcG9ydGFudDtcbiAgY29sb3I6ICM0OTQ5NDk7XG4gIC13ZWJraXQtdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xufVxuXG5jb2RlOm5vdCgubGFuZ3VhZ2UtaHRtbCkge1xuICBmb250LXdlaWdodDogNjAwO1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIE1JWElOIFRPIENPUlJFQ1QgTkFWQkFSIFdJVEggT1VSIENPTE9SIFBBTEVUVEVcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQkFDS0dST1VORCBDT0xPUiBQQUxMRVRFU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmJnLXByaW1hcnkge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzQ5OGRiO1xuICBib3JkZXItY29sb3I6ICMzNDk4ZGI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5IGgxLCAuYmctcHJpbWFyeSBoMiwgLmJnLXByaW1hcnkgaDMsIC5iZy1wcmltYXJ5IGg0LCAuYmctcHJpbWFyeSBoNSwgLmJnLXByaW1hcnkgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXByaW1hcnkgLm5hdiAub3BlbiA+IGEsIC5iZy1wcmltYXJ5IC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctcHJpbWFyeSAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyNThjZDE7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5IC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1wcmltYXJ5IC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjU4Y2QxO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctcHJpbWFyeSAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctcHJpbWFyeS5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzNDk4ZGI7XG59XG5cbi5iZy1wcmltYXJ5LnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzNDk4ZGI7XG59XG5cbi5iZy1wcmltYXJ5LTMwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1NGE4ZTE7XG4gIGJvcmRlci1jb2xvcjogIzU0YThlMTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktMzAwIGgxLCAuYmctcHJpbWFyeS0zMDAgaDIsIC5iZy1wcmltYXJ5LTMwMCBoMywgLmJnLXByaW1hcnktMzAwIGg0LCAuYmctcHJpbWFyeS0zMDAgaDUsIC5iZy1wcmltYXJ5LTMwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctcHJpbWFyeS0zMDAgLm5hdiAub3BlbiA+IGEsIC5iZy1wcmltYXJ5LTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXByaW1hcnktMzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzNmOWRkZDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktMzAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1wcmltYXJ5LTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzNmOWRkZDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktMzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1wcmltYXJ5LTMwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1NGE4ZTE7XG59XG5cbi5iZy1wcmltYXJ5LTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNTRhOGUxO1xufVxuXG4uYmctcHJpbWFyeS0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNzViOWU3O1xuICBib3JkZXItY29sb3I6ICM3NWI5ZTc7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTEwMCBoMSwgLmJnLXByaW1hcnktMTAwIGgyLCAuYmctcHJpbWFyeS0xMDAgaDMsIC5iZy1wcmltYXJ5LTEwMCBoNCwgLmJnLXByaW1hcnktMTAwIGg1LCAuYmctcHJpbWFyeS0xMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXByaW1hcnktMTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctcHJpbWFyeS0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1wcmltYXJ5LTEwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1ZmFlZTM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTEwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctcHJpbWFyeS0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1ZmFlZTM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTEwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctcHJpbWFyeS0xMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNzViOWU3O1xufVxuXG4uYmctcHJpbWFyeS0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzc1YjllNztcbn1cblxuLmJnLXByaW1hcnktNTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI1OGNkMTtcbiAgYm9yZGVyLWNvbG9yOiAjMjU4Y2QxO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctcHJpbWFyeS01MDAgaDEsIC5iZy1wcmltYXJ5LTUwMCBoMiwgLmJnLXByaW1hcnktNTAwIGgzLCAuYmctcHJpbWFyeS01MDAgaDQsIC5iZy1wcmltYXJ5LTUwMCBoNSwgLmJnLXByaW1hcnktNTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1wcmltYXJ5LTUwMCAubmF2IC5vcGVuID4gYSwgLmJnLXByaW1hcnktNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctcHJpbWFyeS01MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjE3ZGJiO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctcHJpbWFyeS01MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLXByaW1hcnktNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjE3ZGJiO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctcHJpbWFyeS01MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXByaW1hcnktNTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI1OGNkMTtcbn1cblxuLmJnLXByaW1hcnktNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyNThjZDE7XG59XG5cbi5iZy1wcmltYXJ5LTYwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMTdkYmI7XG4gIGJvcmRlci1jb2xvcjogIzIxN2RiYjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktNjAwIGgxLCAuYmctcHJpbWFyeS02MDAgaDIsIC5iZy1wcmltYXJ5LTYwMCBoMywgLmJnLXByaW1hcnktNjAwIGg0LCAuYmctcHJpbWFyeS02MDAgaDUsIC5iZy1wcmltYXJ5LTYwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctcHJpbWFyeS02MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1wcmltYXJ5LTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXByaW1hcnktNjAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzFkNmZhNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktNjAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1wcmltYXJ5LTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzFkNmZhNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXByaW1hcnktNjAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1wcmltYXJ5LTYwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMTdkYmI7XG59XG5cbi5iZy1wcmltYXJ5LTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjE3ZGJiO1xufVxuXG4uYmctcHJpbWFyeS03MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWQ2ZmE1O1xuICBib3JkZXItY29sb3I6ICMxZDZmYTU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTcwMCBoMSwgLmJnLXByaW1hcnktNzAwIGgyLCAuYmctcHJpbWFyeS03MDAgaDMsIC5iZy1wcmltYXJ5LTcwMCBoNCwgLmJnLXByaW1hcnktNzAwIGg1LCAuYmctcHJpbWFyeS03MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXByaW1hcnktNzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctcHJpbWFyeS03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1wcmltYXJ5LTcwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxOTYwOTA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTcwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctcHJpbWFyeS03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxOTYwOTA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1wcmltYXJ5LTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctcHJpbWFyeS03MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWQ2ZmE1O1xufVxuXG4uYmctcHJpbWFyeS03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzFkNmZhNTtcbn1cblxuLmJnLWRhbmdlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNzRjM2M7XG4gIGJvcmRlci1jb2xvcjogI2U3NGMzYztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlciBoMSwgLmJnLWRhbmdlciBoMiwgLmJnLWRhbmdlciBoMywgLmJnLWRhbmdlciBoNCwgLmJnLWRhbmdlciBoNSwgLmJnLWRhbmdlciBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctZGFuZ2VyIC5uYXYgLm9wZW4gPiBhLCAuYmctZGFuZ2VyIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctZGFuZ2VyIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U0MzcyNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlciAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctZGFuZ2VyIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTQzNzI1O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1kYW5nZXIuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTc0YzNjO1xufVxuXG4uYmctZGFuZ2VyLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNzRjM2M7XG59XG5cbi5iZy1kYW5nZXItMzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ViNmI1ZTtcbiAgYm9yZGVyLWNvbG9yOiAjZWI2YjVlO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyLTMwMCBoMSwgLmJnLWRhbmdlci0zMDAgaDIsIC5iZy1kYW5nZXItMzAwIGgzLCAuYmctZGFuZ2VyLTMwMCBoNCwgLmJnLWRhbmdlci0zMDAgaDUsIC5iZy1kYW5nZXItMzAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1kYW5nZXItMzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctZGFuZ2VyLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWRhbmdlci0zMDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTg1NjQ3O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyLTMwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctZGFuZ2VyLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U4NTY0NztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci0zMDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWRhbmdlci0zMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZWI2YjVlO1xufVxuXG4uYmctZGFuZ2VyLTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZWI2YjVlO1xufVxuXG4uYmctZGFuZ2VyLTEwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlZjhiODA7XG4gIGJvcmRlci1jb2xvcjogI2VmOGI4MDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci0xMDAgaDEsIC5iZy1kYW5nZXItMTAwIGgyLCAuYmctZGFuZ2VyLTEwMCBoMywgLmJnLWRhbmdlci0xMDAgaDQsIC5iZy1kYW5nZXItMTAwIGg1LCAuYmctZGFuZ2VyLTEwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctZGFuZ2VyLTEwMCAubmF2IC5vcGVuID4gYSwgLmJnLWRhbmdlci0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1kYW5nZXItMTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2VkNzY2OTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci0xMDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWRhbmdlci0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlZDc2Njk7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1kYW5nZXItMTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1kYW5nZXItMTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2VmOGI4MDtcbn1cblxuLmJnLWRhbmdlci0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2VmOGI4MDtcbn1cblxuLmJnLWRhbmdlci01MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTQzNzI1O1xuICBib3JkZXItY29sb3I6ICNlNDM3MjU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1kYW5nZXItNTAwIGgxLCAuYmctZGFuZ2VyLTUwMCBoMiwgLmJnLWRhbmdlci01MDAgaDMsIC5iZy1kYW5nZXItNTAwIGg0LCAuYmctZGFuZ2VyLTUwMCBoNSwgLmJnLWRhbmdlci01MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWRhbmdlci01MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1kYW5nZXItNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctZGFuZ2VyLTUwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkNjJjMWE7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1kYW5nZXItNTAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1kYW5nZXItNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDYyYzFhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyLTUwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctZGFuZ2VyLTUwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNDM3MjU7XG59XG5cbi5iZy1kYW5nZXItNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNDM3MjU7XG59XG5cbi5iZy1kYW5nZXItNjAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q2MmMxYTtcbiAgYm9yZGVyLWNvbG9yOiAjZDYyYzFhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyLTYwMCBoMSwgLmJnLWRhbmdlci02MDAgaDIsIC5iZy1kYW5nZXItNjAwIGgzLCAuYmctZGFuZ2VyLTYwMCBoNCwgLmJnLWRhbmdlci02MDAgaDUsIC5iZy1kYW5nZXItNjAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1kYW5nZXItNjAwIC5uYXYgLm9wZW4gPiBhLCAuYmctZGFuZ2VyLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWRhbmdlci02MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYmYyNzE4O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctZGFuZ2VyLTYwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctZGFuZ2VyLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2JmMjcxODtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci02MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWRhbmdlci02MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDYyYzFhO1xufVxuXG4uYmctZGFuZ2VyLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDYyYzFhO1xufVxuXG4uYmctZGFuZ2VyLTcwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNiZjI3MTg7XG4gIGJvcmRlci1jb2xvcjogI2JmMjcxODtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci03MDAgaDEsIC5iZy1kYW5nZXItNzAwIGgyLCAuYmctZGFuZ2VyLTcwMCBoMywgLmJnLWRhbmdlci03MDAgaDQsIC5iZy1kYW5nZXItNzAwIGg1LCAuYmctZGFuZ2VyLTcwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctZGFuZ2VyLTcwMCAubmF2IC5vcGVuID4gYSwgLmJnLWRhbmdlci03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1kYW5nZXItNzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2E4MjMxNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWRhbmdlci03MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWRhbmdlci03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNhODIzMTU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1kYW5nZXItNzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1kYW5nZXItNzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2JmMjcxODtcbn1cblxuLmJnLWRhbmdlci03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2JmMjcxODtcbn1cblxuLmJnLXN1Y2Nlc3Mge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjdhZTYwO1xuICBib3JkZXItY29sb3I6ICMyN2FlNjA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzIGgxLCAuYmctc3VjY2VzcyBoMiwgLmJnLXN1Y2Nlc3MgaDMsIC5iZy1zdWNjZXNzIGg0LCAuYmctc3VjY2VzcyBoNSwgLmJnLXN1Y2Nlc3MgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXN1Y2Nlc3MgLm5hdiAub3BlbiA+IGEsIC5iZy1zdWNjZXNzIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctc3VjY2VzcyAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMjk5NTU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1zdWNjZXNzIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjI5OTU1O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctc3VjY2VzcyAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctc3VjY2Vzcy5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyN2FlNjA7XG59XG5cbi5iZy1zdWNjZXNzLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyN2FlNjA7XG59XG5cbi5iZy1zdWNjZXNzLTMwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyZWNkNzE7XG4gIGJvcmRlci1jb2xvcjogIzJlY2Q3MTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtMzAwIGgxLCAuYmctc3VjY2Vzcy0zMDAgaDIsIC5iZy1zdWNjZXNzLTMwMCBoMywgLmJnLXN1Y2Nlc3MtMzAwIGg0LCAuYmctc3VjY2Vzcy0zMDAgaDUsIC5iZy1zdWNjZXNzLTMwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctc3VjY2Vzcy0zMDAgLm5hdiAub3BlbiA+IGEsIC5iZy1zdWNjZXNzLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXN1Y2Nlc3MtMzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI5Yjg2NjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtMzAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1zdWNjZXNzLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI5Yjg2NjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtMzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1zdWNjZXNzLTMwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyZWNkNzE7XG59XG5cbi5iZy1zdWNjZXNzLTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMmVjZDcxO1xufVxuXG4uYmctc3VjY2Vzcy0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNGJkNzg2O1xuICBib3JkZXItY29sb3I6ICM0YmQ3ODY7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTEwMCBoMSwgLmJnLXN1Y2Nlc3MtMTAwIGgyLCAuYmctc3VjY2Vzcy0xMDAgaDMsIC5iZy1zdWNjZXNzLTEwMCBoNCwgLmJnLXN1Y2Nlc3MtMTAwIGg1LCAuYmctc3VjY2Vzcy0xMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXN1Y2Nlc3MtMTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctc3VjY2Vzcy0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1zdWNjZXNzLTEwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzNmQyNzg7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTEwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctc3VjY2Vzcy0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzNmQyNzg7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTEwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctc3VjY2Vzcy0xMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNGJkNzg2O1xufVxuXG4uYmctc3VjY2Vzcy0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzRiZDc4Njtcbn1cblxuLmJnLXN1Y2Nlc3MtNTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzIyOTk1NTtcbiAgYm9yZGVyLWNvbG9yOiAjMjI5OTU1O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctc3VjY2Vzcy01MDAgaDEsIC5iZy1zdWNjZXNzLTUwMCBoMiwgLmJnLXN1Y2Nlc3MtNTAwIGgzLCAuYmctc3VjY2Vzcy01MDAgaDQsIC5iZy1zdWNjZXNzLTUwMCBoNSwgLmJnLXN1Y2Nlc3MtNTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1zdWNjZXNzLTUwMCAubmF2IC5vcGVuID4gYSwgLmJnLXN1Y2Nlc3MtNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctc3VjY2Vzcy01MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWU4NDQ5O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctc3VjY2Vzcy01MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLXN1Y2Nlc3MtNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWU4NDQ5O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctc3VjY2Vzcy01MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXN1Y2Nlc3MtNTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzIyOTk1NTtcbn1cblxuLmJnLXN1Y2Nlc3MtNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMjk5NTU7XG59XG5cbi5iZy1zdWNjZXNzLTYwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxZTg0NDk7XG4gIGJvcmRlci1jb2xvcjogIzFlODQ0OTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtNjAwIGgxLCAuYmctc3VjY2Vzcy02MDAgaDIsIC5iZy1zdWNjZXNzLTYwMCBoMywgLmJnLXN1Y2Nlc3MtNjAwIGg0LCAuYmctc3VjY2Vzcy02MDAgaDUsIC5iZy1zdWNjZXNzLTYwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctc3VjY2Vzcy02MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1zdWNjZXNzLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXN1Y2Nlc3MtNjAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzE5NzAzZTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtNjAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1zdWNjZXNzLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzE5NzAzZTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXN1Y2Nlc3MtNjAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1zdWNjZXNzLTYwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxZTg0NDk7XG59XG5cbi5iZy1zdWNjZXNzLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWU4NDQ5O1xufVxuXG4uYmctc3VjY2Vzcy03MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTk3MDNlO1xuICBib3JkZXItY29sb3I6ICMxOTcwM2U7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTcwMCBoMSwgLmJnLXN1Y2Nlc3MtNzAwIGgyLCAuYmctc3VjY2Vzcy03MDAgaDMsIC5iZy1zdWNjZXNzLTcwMCBoNCwgLmJnLXN1Y2Nlc3MtNzAwIGg1LCAuYmctc3VjY2Vzcy03MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXN1Y2Nlc3MtNzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctc3VjY2Vzcy03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1zdWNjZXNzLTcwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxNDViMzI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTcwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctc3VjY2Vzcy03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxNDViMzI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1zdWNjZXNzLTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctc3VjY2Vzcy03MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTk3MDNlO1xufVxuXG4uYmctc3VjY2Vzcy03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzE5NzAzZTtcbn1cblxuLmJnLXdhcm5pbmcge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjM5YzEyO1xuICBib3JkZXItY29sb3I6ICNmMzljMTI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nIGgxLCAuYmctd2FybmluZyBoMiwgLmJnLXdhcm5pbmcgaDMsIC5iZy13YXJuaW5nIGg0LCAuYmctd2FybmluZyBoNSwgLmJnLXdhcm5pbmcgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXdhcm5pbmcgLm5hdiAub3BlbiA+IGEsIC5iZy13YXJuaW5nIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctd2FybmluZyAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlMDhlMGI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy13YXJuaW5nIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTA4ZTBiO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctd2FybmluZyAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2FybmluZy5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMzljMTI7XG59XG5cbi5iZy13YXJuaW5nLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMzljMTI7XG59XG5cbi5iZy13YXJuaW5nLTMwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmNWFiMzY7XG4gIGJvcmRlci1jb2xvcjogI2Y1YWIzNjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctMzAwIGgxLCAuYmctd2FybmluZy0zMDAgaDIsIC5iZy13YXJuaW5nLTMwMCBoMywgLmJnLXdhcm5pbmctMzAwIGg0LCAuYmctd2FybmluZy0zMDAgaDUsIC5iZy13YXJuaW5nLTMwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2FybmluZy0zMDAgLm5hdiAub3BlbiA+IGEsIC5iZy13YXJuaW5nLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXdhcm5pbmctMzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Y0YTExZTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctMzAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy13YXJuaW5nLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Y0YTExZTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctMzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy13YXJuaW5nLTMwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmNWFiMzY7XG59XG5cbi5iZy13YXJuaW5nLTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjVhYjM2O1xufVxuXG4uYmctd2FybmluZy0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjdiYTViO1xuICBib3JkZXItY29sb3I6ICNmN2JhNWI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTEwMCBoMSwgLmJnLXdhcm5pbmctMTAwIGgyLCAuYmctd2FybmluZy0xMDAgaDMsIC5iZy13YXJuaW5nLTEwMCBoNCwgLmJnLXdhcm5pbmctMTAwIGg1LCAuYmctd2FybmluZy0xMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXdhcm5pbmctMTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctd2FybmluZy0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy13YXJuaW5nLTEwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmNWIwNDM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTEwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctd2FybmluZy0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmNWIwNDM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTEwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2FybmluZy0xMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjdiYTViO1xufVxuXG4uYmctd2FybmluZy0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Y3YmE1Yjtcbn1cblxuLmJnLXdhcm5pbmctNTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2UwOGUwYjtcbiAgYm9yZGVyLWNvbG9yOiAjZTA4ZTBiO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctd2FybmluZy01MDAgaDEsIC5iZy13YXJuaW5nLTUwMCBoMiwgLmJnLXdhcm5pbmctNTAwIGgzLCAuYmctd2FybmluZy01MDAgaDQsIC5iZy13YXJuaW5nLTUwMCBoNSwgLmJnLXdhcm5pbmctNTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy13YXJuaW5nLTUwMCAubmF2IC5vcGVuID4gYSwgLmJnLXdhcm5pbmctNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctd2FybmluZy01MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYzg3ZjBhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctd2FybmluZy01MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLXdhcm5pbmctNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYzg3ZjBhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctd2FybmluZy01MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXdhcm5pbmctNTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2UwOGUwYjtcbn1cblxuLmJnLXdhcm5pbmctNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlMDhlMGI7XG59XG5cbi5iZy13YXJuaW5nLTYwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjODdmMGE7XG4gIGJvcmRlci1jb2xvcjogI2M4N2YwYTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctNjAwIGgxLCAuYmctd2FybmluZy02MDAgaDIsIC5iZy13YXJuaW5nLTYwMCBoMywgLmJnLXdhcm5pbmctNjAwIGg0LCAuYmctd2FybmluZy02MDAgaDUsIC5iZy13YXJuaW5nLTYwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2FybmluZy02MDAgLm5hdiAub3BlbiA+IGEsIC5iZy13YXJuaW5nLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXdhcm5pbmctNjAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2IwNmYwOTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctNjAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy13YXJuaW5nLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2IwNmYwOTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLXdhcm5pbmctNjAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy13YXJuaW5nLTYwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjODdmMGE7XG59XG5cbi5iZy13YXJuaW5nLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYzg3ZjBhO1xufVxuXG4uYmctd2FybmluZy03MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjA2ZjA5O1xuICBib3JkZXItY29sb3I6ICNiMDZmMDk7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTcwMCBoMSwgLmJnLXdhcm5pbmctNzAwIGgyLCAuYmctd2FybmluZy03MDAgaDMsIC5iZy13YXJuaW5nLTcwMCBoNCwgLmJnLXdhcm5pbmctNzAwIGg1LCAuYmctd2FybmluZy03MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLXdhcm5pbmctNzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctd2FybmluZy03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy13YXJuaW5nLTcwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM5NzYwMDg7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTcwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctd2FybmluZy03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM5NzYwMDg7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13YXJuaW5nLTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2FybmluZy03MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYjA2ZjA5O1xufVxuXG4uYmctd2FybmluZy03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2IwNmYwOTtcbn1cblxuLmJnLWluZm8ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNWJjMGRlO1xuICBib3JkZXItY29sb3I6ICM1YmMwZGU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvIGgxLCAuYmctaW5mbyBoMiwgLmJnLWluZm8gaDMsIC5iZy1pbmZvIGg0LCAuYmctaW5mbyBoNSwgLmJnLWluZm8gaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWluZm8gLm5hdiAub3BlbiA+IGEsIC5iZy1pbmZvIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctaW5mbyAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0NmI4ZGE7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1pbmZvIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNDZiOGRhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctaW5mbyAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctaW5mby5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG59XG5cbi5iZy1pbmZvLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG59XG5cbi5iZy1pbmZvLTMwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM3YmNjZTQ7XG4gIGJvcmRlci1jb2xvcjogIzdiY2NlNDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tMzAwIGgxLCAuYmctaW5mby0zMDAgaDIsIC5iZy1pbmZvLTMwMCBoMywgLmJnLWluZm8tMzAwIGg0LCAuYmctaW5mby0zMDAgaDUsIC5iZy1pbmZvLTMwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctaW5mby0zMDAgLm5hdiAub3BlbiA+IGEsIC5iZy1pbmZvLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWluZm8tMzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzY2YzRlMDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tMzAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1pbmZvLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzY2YzRlMDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tMzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1pbmZvLTMwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM3YmNjZTQ7XG59XG5cbi5iZy1pbmZvLTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjN2JjY2U0O1xufVxuXG4uYmctaW5mby0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjOWJkOGViO1xuICBib3JkZXItY29sb3I6ICM5YmQ4ZWI7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTEwMCBoMSwgLmJnLWluZm8tMTAwIGgyLCAuYmctaW5mby0xMDAgaDMsIC5iZy1pbmZvLTEwMCBoNCwgLmJnLWluZm8tMTAwIGg1LCAuYmctaW5mby0xMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWluZm8tMTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctaW5mby0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1pbmZvLTEwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM4NWQwZTc7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTEwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctaW5mby0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM4NWQwZTc7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTEwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctaW5mby0xMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjOWJkOGViO1xufVxuXG4uYmctaW5mby0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzliZDhlYjtcbn1cblxuLmJnLWluZm8tNTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzQ2YjhkYTtcbiAgYm9yZGVyLWNvbG9yOiAjNDZiOGRhO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctaW5mby01MDAgaDEsIC5iZy1pbmZvLTUwMCBoMiwgLmJnLWluZm8tNTAwIGgzLCAuYmctaW5mby01MDAgaDQsIC5iZy1pbmZvLTUwMCBoNSwgLmJnLWluZm8tNTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1pbmZvLTUwMCAubmF2IC5vcGVuID4gYSwgLmJnLWluZm8tNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctaW5mby01MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzFiMGQ1O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctaW5mby01MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWluZm8tNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzFiMGQ1O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctaW5mby01MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWluZm8tNTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzQ2YjhkYTtcbn1cblxuLmJnLWluZm8tNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0NmI4ZGE7XG59XG5cbi5iZy1pbmZvLTYwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzMWIwZDU7XG4gIGJvcmRlci1jb2xvcjogIzMxYjBkNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tNjAwIGgxLCAuYmctaW5mby02MDAgaDIsIC5iZy1pbmZvLTYwMCBoMywgLmJnLWluZm8tNjAwIGg0LCAuYmctaW5mby02MDAgaDUsIC5iZy1pbmZvLTYwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctaW5mby02MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1pbmZvLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWluZm8tNjAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI4YTFjNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tNjAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1pbmZvLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI4YTFjNTtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWluZm8tNjAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1pbmZvLTYwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzMWIwZDU7XG59XG5cbi5iZy1pbmZvLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzFiMGQ1O1xufVxuXG4uYmctaW5mby03MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjhhMWM1O1xuICBib3JkZXItY29sb3I6ICMyOGExYzU7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTcwMCBoMSwgLmJnLWluZm8tNzAwIGgyLCAuYmctaW5mby03MDAgaDMsIC5iZy1pbmZvLTcwMCBoNCwgLmJnLWluZm8tNzAwIGg1LCAuYmctaW5mby03MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWluZm8tNzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctaW5mby03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1pbmZvLTcwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMzkwYjA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTcwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctaW5mby03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyMzkwYjA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1pbmZvLTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctaW5mby03MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjhhMWM1O1xufVxuXG4uYmctaW5mby03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI4YTFjNTtcbn1cblxuLmJnLWJsYWNrIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI5MjkyOTtcbiAgYm9yZGVyLWNvbG9yOiAjMjkyOTI5O1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2sgaDEsIC5iZy1ibGFjayBoMiwgLmJnLWJsYWNrIGgzLCAuYmctYmxhY2sgaDQsIC5iZy1ibGFjayBoNSwgLmJnLWJsYWNrIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1ibGFjayAubmF2IC5vcGVuID4gYSwgLmJnLWJsYWNrIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctYmxhY2sgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWMxYzFjO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2sgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWJsYWNrIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWMxYzFjO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2sgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWJsYWNrLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI5MjkyOTtcbn1cblxuLmJnLWJsYWNrLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5iZy1ibGFjay0zMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjM2MzYzNjO1xuICBib3JkZXItY29sb3I6ICMzYzNjM2M7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ibGFjay0zMDAgaDEsIC5iZy1ibGFjay0zMDAgaDIsIC5iZy1ibGFjay0zMDAgaDMsIC5iZy1ibGFjay0zMDAgaDQsIC5iZy1ibGFjay0zMDAgaDUsIC5iZy1ibGFjay0zMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWJsYWNrLTMwMCAubmF2IC5vcGVuID4gYSwgLmJnLWJsYWNrLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWJsYWNrLTMwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyZjJmMmY7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ibGFjay0zMDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWJsYWNrLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzJmMmYyZjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTMwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctYmxhY2stMzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzNjM2MzYztcbn1cblxuLmJnLWJsYWNrLTMwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjM2MzYzNjO1xufVxuXG4uYmctYmxhY2stMTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzRmNGY0ZjtcbiAgYm9yZGVyLWNvbG9yOiAjNGY0ZjRmO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2stMTAwIGgxLCAuYmctYmxhY2stMTAwIGgyLCAuYmctYmxhY2stMTAwIGgzLCAuYmctYmxhY2stMTAwIGg0LCAuYmctYmxhY2stMTAwIGg1LCAuYmctYmxhY2stMTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1ibGFjay0xMDAgLm5hdiAub3BlbiA+IGEsIC5iZy1ibGFjay0xMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1ibGFjay0xMDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNDM0MzQzO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2stMTAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1ibGFjay0xMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0MzQzNDM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ibGFjay0xMDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWJsYWNrLTEwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0ZjRmNGY7XG59XG5cbi5iZy1ibGFjay0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzRmNGY0Zjtcbn1cblxuLmJnLWJsYWNrLTUwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxYzFjMWM7XG4gIGJvcmRlci1jb2xvcjogIzFjMWMxYztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTUwMCBoMSwgLmJnLWJsYWNrLTUwMCBoMiwgLmJnLWJsYWNrLTUwMCBoMywgLmJnLWJsYWNrLTUwMCBoNCwgLmJnLWJsYWNrLTUwMCBoNSwgLmJnLWJsYWNrLTUwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctYmxhY2stNTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctYmxhY2stNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctYmxhY2stNTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzEwMTAxMDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTUwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctYmxhY2stNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTAxMDEwO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2stNTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1ibGFjay01MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMWMxYzFjO1xufVxuXG4uYmctYmxhY2stNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxYzFjMWM7XG59XG5cbi5iZy1ibGFjay02MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTAxMDEwO1xuICBib3JkZXItY29sb3I6ICMxMDEwMTA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ibGFjay02MDAgaDEsIC5iZy1ibGFjay02MDAgaDIsIC5iZy1ibGFjay02MDAgaDMsIC5iZy1ibGFjay02MDAgaDQsIC5iZy1ibGFjay02MDAgaDUsIC5iZy1ibGFjay02MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWJsYWNrLTYwMCAubmF2IC5vcGVuID4gYSwgLmJnLWJsYWNrLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWJsYWNrLTYwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMwMzAzMDM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ibGFjay02MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWJsYWNrLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAzMDMwMztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTYwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctYmxhY2stNjAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzEwMTAxMDtcbn1cblxuLmJnLWJsYWNrLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMTAxMDEwO1xufVxuXG4uYmctYmxhY2stNzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAzMDMwMztcbiAgYm9yZGVyLWNvbG9yOiAjMDMwMzAzO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctYmxhY2stNzAwIGgxLCAuYmctYmxhY2stNzAwIGgyLCAuYmctYmxhY2stNzAwIGgzLCAuYmctYmxhY2stNzAwIGg0LCAuYmctYmxhY2stNzAwIGg1LCAuYmctYmxhY2stNzAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1ibGFjay03MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1ibGFjay03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1ibGFjay03MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiBibGFjaztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTcwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctYmxhY2stNzAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiBibGFjaztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWJsYWNrLTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctYmxhY2stNzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzAzMDMwMztcbn1cblxuLmJnLWJsYWNrLTcwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMDMwMzAzO1xufVxuXG4uYmctbGlnaHQtYmxhY2sge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNDk0OTQ5O1xuICBib3JkZXItY29sb3I6ICM0OTQ5NDk7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjayBoMSwgLmJnLWxpZ2h0LWJsYWNrIGgyLCAuYmctbGlnaHQtYmxhY2sgaDMsIC5iZy1saWdodC1ibGFjayBoNCwgLmJnLWxpZ2h0LWJsYWNrIGg1LCAuYmctbGlnaHQtYmxhY2sgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrIC5uYXYgLm9wZW4gPiBhLCAuYmctbGlnaHQtYmxhY2sgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1saWdodC1ibGFjayAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzYzNjM2M7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjayAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctbGlnaHQtYmxhY2sgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzYzNjM2M7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjayAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2suc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctbGlnaHQtYmxhY2suc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTMwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YzVjNWM7XG4gIGJvcmRlci1jb2xvcjogIzVjNWM1YztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTMwMCBoMSwgLmJnLWxpZ2h0LWJsYWNrLTMwMCBoMiwgLmJnLWxpZ2h0LWJsYWNrLTMwMCBoMywgLmJnLWxpZ2h0LWJsYWNrLTMwMCBoNCwgLmJnLWxpZ2h0LWJsYWNrLTMwMCBoNSwgLmJnLWxpZ2h0LWJsYWNrLTMwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2stMzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctbGlnaHQtYmxhY2stMzAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctbGlnaHQtYmxhY2stMzAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzRmNGY0ZjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTMwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctbGlnaHQtYmxhY2stMzAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNGY0ZjRmO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctbGlnaHQtYmxhY2stMzAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1saWdodC1ibGFjay0zMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNWM1YzVjO1xufVxuXG4uYmctbGlnaHQtYmxhY2stMzAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YzVjNWM7XG59XG5cbi5iZy1saWdodC1ibGFjay0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNmY2ZjZmO1xuICBib3JkZXItY29sb3I6ICM2ZjZmNmY7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjay0xMDAgaDEsIC5iZy1saWdodC1ibGFjay0xMDAgaDIsIC5iZy1saWdodC1ibGFjay0xMDAgaDMsIC5iZy1saWdodC1ibGFjay0xMDAgaDQsIC5iZy1saWdodC1ibGFjay0xMDAgaDUsIC5iZy1saWdodC1ibGFjay0xMDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTEwMCAubmF2IC5vcGVuID4gYSwgLmJnLWxpZ2h0LWJsYWNrLTEwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWxpZ2h0LWJsYWNrLTEwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM2MzYzNjM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjay0xMDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWxpZ2h0LWJsYWNrLTEwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzYzNjM2MztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTEwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2stMTAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzZmNmY2Zjtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTEwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNmY2ZjZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2stNTAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzNjM2MzYztcbiAgYm9yZGVyLWNvbG9yOiAjM2MzYzNjO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctbGlnaHQtYmxhY2stNTAwIGgxLCAuYmctbGlnaHQtYmxhY2stNTAwIGgyLCAuYmctbGlnaHQtYmxhY2stNTAwIGgzLCAuYmctbGlnaHQtYmxhY2stNTAwIGg0LCAuYmctbGlnaHQtYmxhY2stNTAwIGg1LCAuYmctbGlnaHQtYmxhY2stNTAwIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1saWdodC1ibGFjay01MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1saWdodC1ibGFjay01MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1saWdodC1ibGFjay01MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzAzMDMwO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctbGlnaHQtYmxhY2stNTAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1saWdodC1ibGFjay01MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzMDMwMzA7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjay01MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTUwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzYzNjM2M7XG59XG5cbi5iZy1saWdodC1ibGFjay01MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzNjM2MzYztcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTYwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzMDMwMzA7XG4gIGJvcmRlci1jb2xvcjogIzMwMzAzMDtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTYwMCBoMSwgLmJnLWxpZ2h0LWJsYWNrLTYwMCBoMiwgLmJnLWxpZ2h0LWJsYWNrLTYwMCBoMywgLmJnLWxpZ2h0LWJsYWNrLTYwMCBoNCwgLmJnLWxpZ2h0LWJsYWNrLTYwMCBoNSwgLmJnLWxpZ2h0LWJsYWNrLTYwMCBoNiB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2stNjAwIC5uYXYgLm9wZW4gPiBhLCAuYmctbGlnaHQtYmxhY2stNjAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctbGlnaHQtYmxhY2stNjAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzIzMjMyMztcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTYwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctbGlnaHQtYmxhY2stNjAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjMyMzIzO1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4uYmctbGlnaHQtYmxhY2stNjAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5iZy1saWdodC1ibGFjay02MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzAzMDMwO1xufVxuXG4uYmctbGlnaHQtYmxhY2stNjAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMzMDMwMzA7XG59XG5cbi5iZy1saWdodC1ibGFjay03MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjMyMzIzO1xuICBib3JkZXItY29sb3I6ICMyMzIzMjM7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjay03MDAgaDEsIC5iZy1saWdodC1ibGFjay03MDAgaDIsIC5iZy1saWdodC1ibGFjay03MDAgaDMsIC5iZy1saWdodC1ibGFjay03MDAgaDQsIC5iZy1saWdodC1ibGFjay03MDAgaDUsIC5iZy1saWdodC1ibGFjay03MDAgaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTcwMCAubmF2IC5vcGVuID4gYSwgLmJnLWxpZ2h0LWJsYWNrLTcwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWxpZ2h0LWJsYWNrLTcwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMxNjE2MTY7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1saWdodC1ibGFjay03MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWxpZ2h0LWJsYWNrLTcwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzE2MTYxNjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTcwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4uYmctbGlnaHQtYmxhY2stNzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzIzMjMyMztcbn1cblxuLmJnLWxpZ2h0LWJsYWNrLTcwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjMyMzIzO1xufVxuXG4uYmctZ3JheSB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIGJvcmRlci1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXkgaDEsIC5iZy1ncmF5IGgyLCAuYmctZ3JheSBoMywgLmJnLWdyYXkgaDQsIC5iZy1ncmF5IGg1LCAuYmctZ3JheSBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctZ3JheSAubmF2IC5vcGVuID4gYSwgLmJnLWdyYXkgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1ncmF5IC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U1ZTVlNTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXkgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWdyYXkgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNWU1ZTU7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5IC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy1ncmF5LnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbn1cblxuLmJnLWdyYXkuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbn1cblxuLmJnLWdyYXktMzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG4gIGJvcmRlci1jb2xvcjogd2hpdGU7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTMwMCBoMSwgLmJnLWdyYXktMzAwIGgyLCAuYmctZ3JheS0zMDAgaDMsIC5iZy1ncmF5LTMwMCBoNCwgLmJnLWdyYXktMzAwIGg1LCAuYmctZ3JheS0zMDAgaDYge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLWdyYXktMzAwIC5uYXYgLm9wZW4gPiBhLCAuYmctZ3JheS0zMDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1ncmF5LTMwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTMwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctZ3JheS0zMDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTMwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctZ3JheS0zMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB3aGl0ZTtcbn1cblxuLmJnLWdyYXktMzAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6IHdoaXRlO1xufVxuXG4uYmctZ3JheS0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB3aGl0ZTtcbiAgYm9yZGVyLWNvbG9yOiB3aGl0ZTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktMTAwIGgxLCAuYmctZ3JheS0xMDAgaDIsIC5iZy1ncmF5LTEwMCBoMywgLmJnLWdyYXktMTAwIGg0LCAuYmctZ3JheS0xMDAgaDUsIC5iZy1ncmF5LTEwMCBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctZ3JheS0xMDAgLm5hdiAub3BlbiA+IGEsIC5iZy1ncmF5LTEwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWdyYXktMTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktMTAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1ncmF5LTEwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktMTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy1ncmF5LTEwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6IHdoaXRlO1xufVxuXG4uYmctZ3JheS0xMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG59XG5cbi5iZy1ncmF5LTUwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNWU1ZTU7XG4gIGJvcmRlci1jb2xvcjogI2U1ZTVlNTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktNTAwIGgxLCAuYmctZ3JheS01MDAgaDIsIC5iZy1ncmF5LTUwMCBoMywgLmJnLWdyYXktNTAwIGg0LCAuYmctZ3JheS01MDAgaDUsIC5iZy1ncmF5LTUwMCBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctZ3JheS01MDAgLm5hdiAub3BlbiA+IGEsIC5iZy1ncmF5LTUwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLWdyYXktNTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktNTAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy1ncmF5LTUwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLWdyYXktNTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy1ncmF5LTUwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNWU1ZTU7XG59XG5cbi5iZy1ncmF5LTUwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTVlNWU1O1xufVxuXG4uYmctZ3JheS02MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDlkOWQ5O1xuICBib3JkZXItY29sb3I6ICNkOWQ5ZDk7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTYwMCBoMSwgLmJnLWdyYXktNjAwIGgyLCAuYmctZ3JheS02MDAgaDMsIC5iZy1ncmF5LTYwMCBoNCwgLmJnLWdyYXktNjAwIGg1LCAuYmctZ3JheS02MDAgaDYge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLWdyYXktNjAwIC5uYXYgLm9wZW4gPiBhLCAuYmctZ3JheS02MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy1ncmF5LTYwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjY2NjY2M7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTYwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctZ3JheS02MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjY2NjY2M7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy1ncmF5LTYwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctZ3JheS02MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZDlkOWQ5O1xufVxuXG4uYmctZ3JheS02MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbn1cblxuLmJnLWdyYXktNzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2NjY2NjYztcbiAgYm9yZGVyLWNvbG9yOiAjY2NjY2NjO1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctZ3JheS03MDAgaDEsIC5iZy1ncmF5LTcwMCBoMiwgLmJnLWdyYXktNzAwIGgzLCAuYmctZ3JheS03MDAgaDQsIC5iZy1ncmF5LTcwMCBoNSwgLmJnLWdyYXktNzAwIGg2IHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy1ncmF5LTcwMCAubmF2IC5vcGVuID4gYSwgLmJnLWdyYXktNzAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctZ3JheS03MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYmZiZmJmO1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctZ3JheS03MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLWdyYXktNzAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjYmZiZmJmO1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctZ3JheS03MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLWdyYXktNzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2NjY2NjYztcbn1cblxuLmJnLWdyYXktNzAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjY2NjY2M7XG59XG5cbi5iZy13aGl0ZSB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7XG4gIGJvcmRlci1jb2xvcjogI2ZmZjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlIGgxLCAuYmctd2hpdGUgaDIsIC5iZy13aGl0ZSBoMywgLmJnLXdoaXRlIGg0LCAuYmctd2hpdGUgaDUsIC5iZy13aGl0ZSBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctd2hpdGUgLm5hdiAub3BlbiA+IGEsIC5iZy13aGl0ZSAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXdoaXRlIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy13aGl0ZSAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy13aGl0ZS5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7XG59XG5cbi5iZy13aGl0ZS5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xufVxuXG4uYmctd2hpdGUtMzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG4gIGJvcmRlci1jb2xvcjogd2hpdGU7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13aGl0ZS0zMDAgaDEsIC5iZy13aGl0ZS0zMDAgaDIsIC5iZy13aGl0ZS0zMDAgaDMsIC5iZy13aGl0ZS0zMDAgaDQsIC5iZy13aGl0ZS0zMDAgaDUsIC5iZy13aGl0ZS0zMDAgaDYge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLXdoaXRlLTMwMCAubmF2IC5vcGVuID4gYSwgLmJnLXdoaXRlLTMwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXdoaXRlLTMwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13aGl0ZS0zMDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLXdoaXRlLTMwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTMwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctd2hpdGUtMzAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG59XG5cbi5iZy13aGl0ZS0zMDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogd2hpdGU7XG59XG5cbi5iZy13aGl0ZS0xMDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB3aGl0ZTtcbiAgYm9yZGVyLWNvbG9yOiB3aGl0ZTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTEwMCBoMSwgLmJnLXdoaXRlLTEwMCBoMiwgLmJnLXdoaXRlLTEwMCBoMywgLmJnLXdoaXRlLTEwMCBoNCwgLmJnLXdoaXRlLTEwMCBoNSwgLmJnLXdoaXRlLTEwMCBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctd2hpdGUtMTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctd2hpdGUtMTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctd2hpdGUtMTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTEwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctd2hpdGUtMTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjJmMmYyO1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctd2hpdGUtMTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy13aGl0ZS0xMDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB3aGl0ZTtcbn1cblxuLmJnLXdoaXRlLTEwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiB3aGl0ZTtcbn1cblxuLmJnLXdoaXRlLTUwMCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIGJvcmRlci1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTUwMCBoMSwgLmJnLXdoaXRlLTUwMCBoMiwgLmJnLXdoaXRlLTUwMCBoMywgLmJnLXdoaXRlLTUwMCBoNCwgLmJnLXdoaXRlLTUwMCBoNSwgLmJnLXdoaXRlLTUwMCBoNiB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctd2hpdGUtNTAwIC5uYXYgLm9wZW4gPiBhLCAuYmctd2hpdGUtNTAwIC5uYXYgLm9wZW4gPiBhOmZvY3VzLCAuYmctd2hpdGUtNTAwIC5uYXYgLm9wZW4gPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U2ZTZlNjtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTUwMCAubmF2ID4gbGkgPiBhOmZvY3VzLCAuYmctd2hpdGUtNTAwIC5uYXYgPiBsaSA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTZlNmU2O1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctd2hpdGUtNTAwIC5uYXZiYXItbmF2ID4gbGkgPiBhIHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy13aGl0ZS01MDAuc21hbGwtbmF2OmhvdmVyIC5jaGlsZC1uYXYge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjJmMmYyO1xufVxuXG4uYmctd2hpdGUtNTAwLnNtYWxsLW5hdjpob3ZlciAuc2lkZS1uYXYgPiBsaTpub3QoLmhhcy1jaGlsZHJlbikgPiBhID4gc3BhbiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG59XG5cbi5iZy13aGl0ZS02MDAge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTZlNmU2O1xuICBib3JkZXItY29sb3I6ICNlNmU2ZTY7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13aGl0ZS02MDAgaDEsIC5iZy13aGl0ZS02MDAgaDIsIC5iZy13aGl0ZS02MDAgaDMsIC5iZy13aGl0ZS02MDAgaDQsIC5iZy13aGl0ZS02MDAgaDUsIC5iZy13aGl0ZS02MDAgaDYge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLXdoaXRlLTYwMCAubmF2IC5vcGVuID4gYSwgLmJnLXdoaXRlLTYwMCAubmF2IC5vcGVuID4gYTpmb2N1cywgLmJnLXdoaXRlLTYwMCAubmF2IC5vcGVuID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkOWQ5ZDk7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13aGl0ZS02MDAgLm5hdiA+IGxpID4gYTpmb2N1cywgLmJnLXdoaXRlLTYwMCAubmF2ID4gbGkgPiBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbiAgY29sb3I6ICM0OTQ5NDkgIWltcG9ydGFudDtcbn1cblxuLmJnLXdoaXRlLTYwMCAubmF2YmFyLW5hdiA+IGxpID4gYSB7XG4gIGNvbG9yOiAjNDk0OTQ5O1xufVxuXG4uYmctd2hpdGUtNjAwLnNtYWxsLW5hdjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U2ZTZlNjtcbn1cblxuLmJnLXdoaXRlLTYwMC5zbWFsbC1uYXY6aG92ZXIgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTZlNmU2O1xufVxuXG4uYmctd2hpdGUtNzAwIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbiAgYm9yZGVyLWNvbG9yOiAjZDlkOWQ5O1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctd2hpdGUtNzAwIGgxLCAuYmctd2hpdGUtNzAwIGgyLCAuYmctd2hpdGUtNzAwIGgzLCAuYmctd2hpdGUtNzAwIGg0LCAuYmctd2hpdGUtNzAwIGg1LCAuYmctd2hpdGUtNzAwIGg2IHtcbiAgY29sb3I6ICM0OTQ5NDk7XG59XG5cbi5iZy13aGl0ZS03MDAgLm5hdiAub3BlbiA+IGEsIC5iZy13aGl0ZS03MDAgLm5hdiAub3BlbiA+IGE6Zm9jdXMsIC5iZy13aGl0ZS03MDAgLm5hdiAub3BlbiA+IGE6aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjY2NjY2NjO1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uYmctd2hpdGUtNzAwIC5uYXYgPiBsaSA+IGE6Zm9jdXMsIC5iZy13aGl0ZS03MDAgLm5hdiA+IGxpID4gYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNjY2NjY2M7XG4gIGNvbG9yOiAjNDk0OTQ5ICFpbXBvcnRhbnQ7XG59XG5cbi5iZy13aGl0ZS03MDAgLm5hdmJhci1uYXYgPiBsaSA+IGEge1xuICBjb2xvcjogIzQ5NDk0OTtcbn1cblxuLmJnLXdoaXRlLTcwMC5zbWFsbC1uYXY6aG92ZXIgLmNoaWxkLW5hdiB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNkOWQ5ZDk7XG59XG5cbi5iZy13aGl0ZS03MDAuc21hbGwtbmF2OmhvdmVyIC5zaWRlLW5hdiA+IGxpOm5vdCguaGFzLWNoaWxkcmVuKSA+IGEgPiBzcGFuIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2Q5ZDlkOTtcbn1cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBDT0xPUiBDTEFTU0VTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4uY29sb3ItcHJpbWFyeSB7XG4gIGNvbG9yOiAjMzQ5OGRiICFpbXBvcnRhbnQ7XG59XG5cbi5jb2xvci1kYW5nZXIge1xuICBjb2xvcjogI2U3NGMzYyAhaW1wb3J0YW50O1xufVxuXG4uY29sb3Itc3VjY2VzcyB7XG4gIGNvbG9yOiAjMjdhZTYwICFpbXBvcnRhbnQ7XG59XG5cbi5jb2xvci13YXJuaW5nIHtcbiAgY29sb3I6ICNmMzljMTIgIWltcG9ydGFudDtcbn1cblxuLmNvbG9yLWluZm8ge1xuICBjb2xvcjogIzViYzBkZSAhaW1wb3J0YW50O1xufVxuXG4uY29sb3ItYmxhY2sge1xuICBjb2xvcjogIzI5MjkyOSAhaW1wb3J0YW50O1xufVxuXG4uY29sb3ItbGlnaHQtYmxhY2sge1xuICBjb2xvcjogIzQ5NDk0OSAhaW1wb3J0YW50O1xufVxuXG4uY29sb3ItZ3JheSB7XG4gIGNvbG9yOiAjZjJmMmYyICFpbXBvcnRhbnQ7XG59XG5cbi5jb2xvci13aGl0ZSB7XG4gIGNvbG9yOiAjZmZmICFpbXBvcnRhbnQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQk9SREVSIENPTE9SU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmJvcmRlci1wcmltYXJ5IHtcbiAgYm9yZGVyLWNvbG9yOiAjMzQ5OGRiO1xufVxuXG4uYm9yZGVyLXByaW1hcnktMzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjNTRhOGUxO1xufVxuXG4uYm9yZGVyLXByaW1hcnktMTAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjNzViOWU3O1xufVxuXG4uYm9yZGVyLXByaW1hcnktNTAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjU4Y2QxO1xufVxuXG4uYm9yZGVyLXByaW1hcnktNjAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjE3ZGJiO1xufVxuXG4uYm9yZGVyLXByaW1hcnktNzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjMWQ2ZmE1O1xufVxuXG4uYm9yZGVyLWRhbmdlciB7XG4gIGJvcmRlci1jb2xvcjogI2U3NGMzYztcbn1cblxuLmJvcmRlci1kYW5nZXItMzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjZWI2YjVlO1xufVxuXG4uYm9yZGVyLWRhbmdlci0xMDAge1xuICBib3JkZXItY29sb3I6ICNlZjhiODA7XG59XG5cbi5ib3JkZXItZGFuZ2VyLTUwMCB7XG4gIGJvcmRlci1jb2xvcjogI2U0MzcyNTtcbn1cblxuLmJvcmRlci1kYW5nZXItNjAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjZDYyYzFhO1xufVxuXG4uYm9yZGVyLWRhbmdlci03MDAge1xuICBib3JkZXItY29sb3I6ICNiZjI3MTg7XG59XG5cbi5ib3JkZXItc3VjY2VzcyB7XG4gIGJvcmRlci1jb2xvcjogIzI3YWU2MDtcbn1cblxuLmJvcmRlci1zdWNjZXNzLTMwMCB7XG4gIGJvcmRlci1jb2xvcjogIzJlY2Q3MTtcbn1cblxuLmJvcmRlci1zdWNjZXNzLTEwMCB7XG4gIGJvcmRlci1jb2xvcjogIzRiZDc4Njtcbn1cblxuLmJvcmRlci1zdWNjZXNzLTUwMCB7XG4gIGJvcmRlci1jb2xvcjogIzIyOTk1NTtcbn1cblxuLmJvcmRlci1zdWNjZXNzLTYwMCB7XG4gIGJvcmRlci1jb2xvcjogIzFlODQ0OTtcbn1cblxuLmJvcmRlci1zdWNjZXNzLTcwMCB7XG4gIGJvcmRlci1jb2xvcjogIzE5NzAzZTtcbn1cblxuLmJvcmRlci13YXJuaW5nIHtcbiAgYm9yZGVyLWNvbG9yOiAjZjM5YzEyO1xufVxuXG4uYm9yZGVyLXdhcm5pbmctMzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjZjVhYjM2O1xufVxuXG4uYm9yZGVyLXdhcm5pbmctMTAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjZjdiYTViO1xufVxuXG4uYm9yZGVyLXdhcm5pbmctNTAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjZTA4ZTBiO1xufVxuXG4uYm9yZGVyLXdhcm5pbmctNjAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjYzg3ZjBhO1xufVxuXG4uYm9yZGVyLXdhcm5pbmctNzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjYjA2ZjA5O1xufVxuXG4uYm9yZGVyLWluZm8ge1xuICBib3JkZXItY29sb3I6ICM1YmMwZGU7XG59XG5cbi5ib3JkZXItaW5mby0zMDAge1xuICBib3JkZXItY29sb3I6ICM3YmNjZTQ7XG59XG5cbi5ib3JkZXItaW5mby0xMDAge1xuICBib3JkZXItY29sb3I6ICM5YmQ4ZWI7XG59XG5cbi5ib3JkZXItaW5mby01MDAge1xuICBib3JkZXItY29sb3I6ICM0NmI4ZGE7XG59XG5cbi5ib3JkZXItaW5mby02MDAge1xuICBib3JkZXItY29sb3I6ICMzMWIwZDU7XG59XG5cbi5ib3JkZXItaW5mby03MDAge1xuICBib3JkZXItY29sb3I6ICMyOGExYzU7XG59XG5cbi5ib3JkZXItYmxhY2sge1xuICBib3JkZXItY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5ib3JkZXItYmxhY2stMzAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjM2MzYzNjO1xufVxuXG4uYm9yZGVyLWJsYWNrLTEwMCB7XG4gIGJvcmRlci1jb2xvcjogIzRmNGY0Zjtcbn1cblxuLmJvcmRlci1ibGFjay01MDAge1xuICBib3JkZXItY29sb3I6ICMxYzFjMWM7XG59XG5cbi5ib3JkZXItYmxhY2stNjAwIHtcbiAgYm9yZGVyLWNvbG9yOiAjMTAxMDEwO1xufVxuXG4uYm9yZGVyLWJsYWNrLTcwMCB7XG4gIGJvcmRlci1jb2xvcjogIzAzMDMwMztcbn1cblxuLmJvcmRlci1ncmF5IHtcbiAgYm9yZGVyLWNvbG9yOiAjZjJmMmYyO1xufVxuXG4uYm9yZGVyLWdyYXktMzAwIHtcbiAgYm9yZGVyLWNvbG9yOiB3aGl0ZTtcbn1cblxuLmJvcmRlci1ncmF5LTEwMCB7XG4gIGJvcmRlci1jb2xvcjogd2hpdGU7XG59XG5cbi5ib3JkZXItZ3JheS01MDAge1xuICBib3JkZXItY29sb3I6ICNlNWU1ZTU7XG59XG5cbi5ib3JkZXItZ3JheS02MDAge1xuICBib3JkZXItY29sb3I6ICNkOWQ5ZDk7XG59XG5cbi5ib3JkZXItZ3JheS03MDAge1xuICBib3JkZXItY29sb3I6ICNjY2NjY2M7XG59XG5cbi5tdC1uIHtcbiAgbWFyZ2luLXRvcDogMCAhaW1wb3J0YW50O1xufVxuXG4ubXQtNSB7XG4gIG1hcmdpbi10b3A6IDVweCAhaW1wb3J0YW50O1xufVxuXG4ubXQtMTAge1xuICBtYXJnaW4tdG9wOiAxMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tdC0xNSB7XG4gIG1hcmdpbi10b3A6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLm10LTIwIHtcbiAgbWFyZ2luLXRvcDogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ubXQtMjUge1xuICBtYXJnaW4tdG9wOiAyNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tdC0zMCB7XG4gIG1hcmdpbi10b3A6IDMwcHggIWltcG9ydGFudDtcbn1cblxuLm10LTM1IHtcbiAgbWFyZ2luLXRvcDogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ubXQtNDAge1xuICBtYXJnaW4tdG9wOiA0MHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tdC00NSB7XG4gIG1hcmdpbi10b3A6IDQ1cHggIWltcG9ydGFudDtcbn1cblxuLm10LTUwIHtcbiAgbWFyZ2luLXRvcDogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ubWItbiB7XG4gIG1hcmdpbi1ib3R0b206IDAgIWltcG9ydGFudDtcbn1cblxuLm1iLTUge1xuICBtYXJnaW4tYm90dG9tOiA1cHggIWltcG9ydGFudDtcbn1cblxuLm1iLTEwIHtcbiAgbWFyZ2luLWJvdHRvbTogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ubWItMTUge1xuICBtYXJnaW4tYm90dG9tOiAxNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tYi0yMCB7XG4gIG1hcmdpbi1ib3R0b206IDIwcHggIWltcG9ydGFudDtcbn1cblxuLm1iLTI1IHtcbiAgbWFyZ2luLWJvdHRvbTogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ubWItMzAge1xuICBtYXJnaW4tYm90dG9tOiAzMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tYi0zNSB7XG4gIG1hcmdpbi1ib3R0b206IDM1cHggIWltcG9ydGFudDtcbn1cblxuLm1iLTQwIHtcbiAgbWFyZ2luLWJvdHRvbTogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ubWItNDUge1xuICBtYXJnaW4tYm90dG9tOiA0NXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tYi01MCB7XG4gIG1hcmdpbi1ib3R0b206IDUwcHggIWltcG9ydGFudDtcbn1cblxuLm1sLW4ge1xuICBtYXJnaW4tbGVmdDogMCAhaW1wb3J0YW50O1xufVxuXG4ubWwtNSB7XG4gIG1hcmdpbi1sZWZ0OiA1cHggIWltcG9ydGFudDtcbn1cblxuLm1sLTEwIHtcbiAgbWFyZ2luLWxlZnQ6IDEwcHggIWltcG9ydGFudDtcbn1cblxuLm1sLTE1IHtcbiAgbWFyZ2luLWxlZnQ6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLm1sLTIwIHtcbiAgbWFyZ2luLWxlZnQ6IDIwcHggIWltcG9ydGFudDtcbn1cblxuLm1sLTI1IHtcbiAgbWFyZ2luLWxlZnQ6IDI1cHggIWltcG9ydGFudDtcbn1cblxuLm1sLTMwIHtcbiAgbWFyZ2luLWxlZnQ6IDMwcHggIWltcG9ydGFudDtcbn1cblxuLm1sLTM1IHtcbiAgbWFyZ2luLWxlZnQ6IDM1cHggIWltcG9ydGFudDtcbn1cblxuLm1sLTQwIHtcbiAgbWFyZ2luLWxlZnQ6IDQwcHggIWltcG9ydGFudDtcbn1cblxuLm1sLTQ1IHtcbiAgbWFyZ2luLWxlZnQ6IDQ1cHggIWltcG9ydGFudDtcbn1cblxuLm1sLTUwIHtcbiAgbWFyZ2luLWxlZnQ6IDUwcHggIWltcG9ydGFudDtcbn1cblxuLm1yLW4ge1xuICBtYXJnaW4tcmlnaHQ6IDAgIWltcG9ydGFudDtcbn1cblxuLm1yLTUge1xuICBtYXJnaW4tcmlnaHQ6IDVweCAhaW1wb3J0YW50O1xufVxuXG4ubXItMTAge1xuICBtYXJnaW4tcmlnaHQ6IDEwcHggIWltcG9ydGFudDtcbn1cblxuLm1yLTE1IHtcbiAgbWFyZ2luLXJpZ2h0OiAxNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tci0yMCB7XG4gIG1hcmdpbi1yaWdodDogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ubXItMjUge1xuICBtYXJnaW4tcmlnaHQ6IDI1cHggIWltcG9ydGFudDtcbn1cblxuLm1yLTMwIHtcbiAgbWFyZ2luLXJpZ2h0OiAzMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tci0zNSB7XG4gIG1hcmdpbi1yaWdodDogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ubXItNDAge1xuICBtYXJnaW4tcmlnaHQ6IDQwcHggIWltcG9ydGFudDtcbn1cblxuLm1yLTQ1IHtcbiAgbWFyZ2luLXJpZ2h0OiA0NXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5tci01MCB7XG4gIG1hcmdpbi1yaWdodDogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ubS1uIHtcbiAgbWFyZ2luOiAwICFpbXBvcnRhbnQ7XG59XG5cbi5tLTUge1xuICBtYXJnaW46IDVweCAhaW1wb3J0YW50O1xufVxuXG4ubS0xMCB7XG4gIG1hcmdpbjogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ubS0xNSB7XG4gIG1hcmdpbjogMTVweCAhaW1wb3J0YW50O1xufVxuXG4ubS0yMCB7XG4gIG1hcmdpbjogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ubS0yNSB7XG4gIG1hcmdpbjogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ubS0zMCB7XG4gIG1hcmdpbjogMzBweCAhaW1wb3J0YW50O1xufVxuXG4ubS0zNSB7XG4gIG1hcmdpbjogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ubS00MCB7XG4gIG1hcmdpbjogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ubS00NSB7XG4gIG1hcmdpbjogNDVweCAhaW1wb3J0YW50O1xufVxuXG4ubS01MCB7XG4gIG1hcmdpbjogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtbiB7XG4gIHBhZGRpbmctdG9wOiAwICFpbXBvcnRhbnQ7XG59XG5cbi5wdC01IHtcbiAgcGFkZGluZy10b3A6IDVweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMTAge1xuICBwYWRkaW5nLXRvcDogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMTUge1xuICBwYWRkaW5nLXRvcDogMTVweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMjAge1xuICBwYWRkaW5nLXRvcDogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMjUge1xuICBwYWRkaW5nLXRvcDogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMzAge1xuICBwYWRkaW5nLXRvcDogMzBweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtMzUge1xuICBwYWRkaW5nLXRvcDogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtNDAge1xuICBwYWRkaW5nLXRvcDogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtNDUge1xuICBwYWRkaW5nLXRvcDogNDVweCAhaW1wb3J0YW50O1xufVxuXG4ucHQtNTAge1xuICBwYWRkaW5nLXRvcDogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ucGItbiB7XG4gIHBhZGRpbmctYm90dG9tOiAwICFpbXBvcnRhbnQ7XG59XG5cbi5wYi01IHtcbiAgcGFkZGluZy1ib3R0b206IDVweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMTAge1xuICBwYWRkaW5nLWJvdHRvbTogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMTUge1xuICBwYWRkaW5nLWJvdHRvbTogMTVweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMjAge1xuICBwYWRkaW5nLWJvdHRvbTogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMjUge1xuICBwYWRkaW5nLWJvdHRvbTogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMzAge1xuICBwYWRkaW5nLWJvdHRvbTogMzBweCAhaW1wb3J0YW50O1xufVxuXG4ucGItMzUge1xuICBwYWRkaW5nLWJvdHRvbTogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ucGItNDAge1xuICBwYWRkaW5nLWJvdHRvbTogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ucGItNDUge1xuICBwYWRkaW5nLWJvdHRvbTogNDVweCAhaW1wb3J0YW50O1xufVxuXG4ucGItNTAge1xuICBwYWRkaW5nLWJvdHRvbTogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ucGwtbiB7XG4gIHBhZGRpbmctbGVmdDogMCAhaW1wb3J0YW50O1xufVxuXG4ucGwtNSB7XG4gIHBhZGRpbmctbGVmdDogNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wbC0xMCB7XG4gIHBhZGRpbmctbGVmdDogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ucGwtMTUge1xuICBwYWRkaW5nLWxlZnQ6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLnBsLTIwIHtcbiAgcGFkZGluZy1sZWZ0OiAyMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wbC0yNSB7XG4gIHBhZGRpbmctbGVmdDogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ucGwtMzAge1xuICBwYWRkaW5nLWxlZnQ6IDMwcHggIWltcG9ydGFudDtcbn1cblxuLnBsLTM1IHtcbiAgcGFkZGluZy1sZWZ0OiAzNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wbC00MCB7XG4gIHBhZGRpbmctbGVmdDogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ucGwtNDUge1xuICBwYWRkaW5nLWxlZnQ6IDQ1cHggIWltcG9ydGFudDtcbn1cblxuLnBsLTUwIHtcbiAgcGFkZGluZy1sZWZ0OiA1MHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wci1uIHtcbiAgcGFkZGluZy1yaWdodDogMCAhaW1wb3J0YW50O1xufVxuXG4ucHItNSB7XG4gIHBhZGRpbmctcmlnaHQ6IDVweCAhaW1wb3J0YW50O1xufVxuXG4ucHItMTAge1xuICBwYWRkaW5nLXJpZ2h0OiAxMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wci0xNSB7XG4gIHBhZGRpbmctcmlnaHQ6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLnByLTIwIHtcbiAgcGFkZGluZy1yaWdodDogMjBweCAhaW1wb3J0YW50O1xufVxuXG4ucHItMjUge1xuICBwYWRkaW5nLXJpZ2h0OiAyNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wci0zMCB7XG4gIHBhZGRpbmctcmlnaHQ6IDMwcHggIWltcG9ydGFudDtcbn1cblxuLnByLTM1IHtcbiAgcGFkZGluZy1yaWdodDogMzVweCAhaW1wb3J0YW50O1xufVxuXG4ucHItNDAge1xuICBwYWRkaW5nLXJpZ2h0OiA0MHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wci00NSB7XG4gIHBhZGRpbmctcmlnaHQ6IDQ1cHggIWltcG9ydGFudDtcbn1cblxuLnByLTUwIHtcbiAgcGFkZGluZy1yaWdodDogNTBweCAhaW1wb3J0YW50O1xufVxuXG4ucC1uIHtcbiAgcGFkZGluZzogMCAhaW1wb3J0YW50O1xufVxuXG4ucC01IHtcbiAgcGFkZGluZzogNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wLTEwIHtcbiAgcGFkZGluZzogMTBweCAhaW1wb3J0YW50O1xufVxuXG4ucC0xNSB7XG4gIHBhZGRpbmc6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLnAtMjAge1xuICBwYWRkaW5nOiAyMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wLTI1IHtcbiAgcGFkZGluZzogMjVweCAhaW1wb3J0YW50O1xufVxuXG4ucC0zMCB7XG4gIHBhZGRpbmc6IDMwcHggIWltcG9ydGFudDtcbn1cblxuLnAtMzUge1xuICBwYWRkaW5nOiAzNXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5wLTQwIHtcbiAgcGFkZGluZzogNDBweCAhaW1wb3J0YW50O1xufVxuXG4ucC00NSB7XG4gIHBhZGRpbmc6IDQ1cHggIWltcG9ydGFudDtcbn1cblxuLnAtNTAge1xuICBwYWRkaW5nOiA1MHB4ICFpbXBvcnRhbnQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQk9SREVSU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm5vLWJvcmRlciB7XG4gIGJvcmRlci13aWR0aDogMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5uby1ib3JkZXItdG9wIHtcbiAgYm9yZGVyLXRvcC13aWR0aDogMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5uby1ib3JkZXItYm90dG9tIHtcbiAgYm9yZGVyLWJvdHRvbS13aWR0aDogMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5uby1ib3JkZXItbGVmdCB7XG4gIGJvcmRlci1sZWZ0LXdpZHRoOiAwcHggIWltcG9ydGFudDtcbn1cblxuLm5vLWJvcmRlci1yaWdodCB7XG4gIGJvcmRlci1yaWdodC13aWR0aDogMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItMSB7XG4gIGJvcmRlci13aWR0aDogMXB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItMS10b3Age1xuICBib3JkZXItdG9wLXdpZHRoOiAxcHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci0xLWJvdHRvbSB7XG4gIGJvcmRlci1ib3R0b20td2lkdGg6IDFweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLTEtbGVmdCB7XG4gIGJvcmRlci1sZWZ0LXdpZHRoOiAxcHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci0xLXJpZ2h0IHtcbiAgYm9yZGVyLXJpZ2h0LXdpZHRoOiAxcHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci0yIHtcbiAgYm9yZGVyLXdpZHRoOiAycHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci0yLXRvcCB7XG4gIGJvcmRlci10b3Atd2lkdGg6IDJweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLTItYm90dG9tIHtcbiAgYm9yZGVyLWJvdHRvbS13aWR0aDogMnB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItMi1sZWZ0IHtcbiAgYm9yZGVyLWxlZnQtd2lkdGg6IDJweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLTItcmlnaHQge1xuICBib3JkZXItcmlnaHQtd2lkdGg6IDJweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLTMge1xuICBib3JkZXItd2lkdGg6IDNweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLTMtdG9wIHtcbiAgYm9yZGVyLXRvcC13aWR0aDogM3B4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItMy1ib3R0b20ge1xuICBib3JkZXItYm90dG9tLXdpZHRoOiAzcHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci0zLWxlZnQge1xuICBib3JkZXItbGVmdC13aWR0aDogM3B4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItMy1yaWdodCB7XG4gIGJvcmRlci1yaWdodC13aWR0aDogM3B4ICFpbXBvcnRhbnQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQk9SREVSIFJBRElVU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm5vLXJhZGl1cyB7XG4gIGJvcmRlci1yYWRpdXM6IDBweCAhaW1wb3J0YW50O1xufVxuXG4ubm8tcmFkaXVzLXRvcC1sZWZ0IHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5uby1yYWRpdXMtdG9wLXJpZ2h0IHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDBweCAhaW1wb3J0YW50O1xufVxuXG4ubm8tcmFkaXVzLWJvdHRvbS1yaWdodCB7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwcHggIWltcG9ydGFudDtcbn1cblxuLm5vLXJhZGl1cy1ib3R0b20tbGVmdCB7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDBweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLXJhZC0yIHtcbiAgYm9yZGVyLXJhZGl1czogMnB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItcmFkLTItdG9wLWxlZnQge1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiAycHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci1yYWQtMi10b3AtcmlnaHQge1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMnB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItcmFkLTItYm90dG9tLXJpZ2h0IHtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDJweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLXJhZC0yLWJvdHRvbS1sZWZ0IHtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMnB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItcmFkLTQge1xuICBib3JkZXItcmFkaXVzOiA0cHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci1yYWQtNC10b3AtbGVmdCB7XG4gIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDRweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLXJhZC00LXRvcC1yaWdodCB7XG4gIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiA0cHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci1yYWQtNC1ib3R0b20tcmlnaHQge1xuICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogNHB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItcmFkLTQtYm90dG9tLWxlZnQge1xuICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiA0cHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci1yYWQtNiB7XG4gIGJvcmRlci1yYWRpdXM6IDZweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLXJhZC02LXRvcC1sZWZ0IHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogNnB4ICFpbXBvcnRhbnQ7XG59XG5cbi5ib3JkZXItcmFkLTYtdG9wLXJpZ2h0IHtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDZweCAhaW1wb3J0YW50O1xufVxuXG4uYm9yZGVyLXJhZC02LWJvdHRvbS1yaWdodCB7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiA2cHggIWltcG9ydGFudDtcbn1cblxuLmJvcmRlci1yYWQtNi1ib3R0b20tbGVmdCB7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDZweCAhaW1wb3J0YW50O1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFRPUCBOQVZCQVJcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5uYXZiYXIge1xuICBib3JkZXItcmFkaXVzOiAwO1xuICBib3JkZXI6IDBweDtcbiAgbWFyZ2luLWJvdHRvbTogMDtcbn1cblxuLm5hdmJhci5ib3gtc2hhZG93IHtcbiAgYm94LXNoYWRvdzogMCAycHggNXB4IHJnYmEoMCwgMCwgMCwgMC4xNSk7XG4gIHotaW5kZXg6IDEwO1xufVxuXG4ubmF2YmFyIGE6aG92ZXIge1xuICB0ZXh0LWRlY29yYXRpb246IG5vbmU7XG4gIGNvbG9yOiAjMjkyOTI5ICFpbXBvcnRhbnQ7XG59XG5cbi5uYXZiYXItdG9nZ2xlIHtcbiAgZm9udC1zaXplOiAyMHB4O1xufVxuXG4ubmF2YmFyLWhlYWRlciB7XG4gIG1pbi13aWR0aDogMjcwcHg7XG4gIHBhZGRpbmctbGVmdDogMTVweDtcbiAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgLW1vei10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIG92ZXJmbG93OiBoaWRkZW47XG59XG5cbi5uYXZiYXItaGVhZGVyIC5uYXZiYXItYnJhbmQge1xuICBwYWRkaW5nOiAxMnB4O1xufVxuXG4ubmF2YmFyLWhlYWRlciAubG9nbyB7XG4gIGhlaWdodDogMjZweDtcbn1cblxuLm5hdmJhci1oZWFkZXIuc21hbGwtbmF2LWhlYWRlciB7XG4gIG1pbi13aWR0aDogNTBweDtcbiAgd2lkdGg6IDUwcHg7XG59XG5cbi5uYXZiYXItaGVhZGVyLnNtYWxsLW5hdi1oZWFkZXIgLm5hdmJhci1icmFuZCB7XG4gIGRpc3BsYXk6IG5vbmU7XG59XG5cbi5zbWFsbC1uYXYtaGFuZGxlIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICB3aWR0aDogNTBweDtcbiAgaGVpZ2h0OiA1MHB4O1xuICBmbG9hdDogcmlnaHQ7XG4gIGN1cnNvcjogcG9pbnRlcjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xufVxuXG4uc21hbGwtbmF2LWhhbmRsZSAuZmEge1xuICBsaW5lLWhlaWdodDogNTBweDtcbn1cblxuLmRyb3Bkb3duLW1lbnUge1xuICBib3gtc2hhZG93OiAwIDJweCA1cHggcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgbWluLXdpZHRoOiAyMjBweDtcbiAgcGFkZGluZzogMDtcbiAgYm9yZGVyOiAwO1xufVxuXG4uZHJvcGRvd24tbWVudSA+IGxpOmZpcnN0LWNoaWxkIHtcbiAgcGFkZGluZy10b3A6IDhweDtcbn1cblxuLmRyb3Bkb3duLW1lbnUgPiBsaSA+IGEge1xuICBwYWRkaW5nOiA4cHggMjBweDtcbn1cblxuLmRyb3Bkb3duLW1lbnUgPiBsaSA+IGEgLmZhIHtcbiAgbWFyZ2luLXJpZ2h0OiA1cHg7XG59XG5cbi5kcm9wZG93bi1tZW51IC5kaXZpZGVyIHtcbiAgbWFyZ2luOiA1cHggMDtcbn1cblxuLmRyb3Bkb3duLW1lbnUgLnByb2ZpbGUtbWVudSB7XG4gIHBhZGRpbmc6IDE1cHggIWltcG9ydGFudDtcbn1cblxuLmRyb3Bkb3duLW1lbnUgLnByb2ZpbGUtbWVudSAucHJvZmlsZS1pbWcge1xuICB3aWR0aDogNTBweDtcbn1cblxuLmRyb3Bkb3duLW1lbnUgLnByb2ZpbGUtbWVudSAucHJvZmlsZS1uYW1lIHtcbiAgd2lkdGg6IDEyMHB4O1xuICBmbG9hdDogcmlnaHQ7XG59XG5cbi5kcm9wZG93bi1tZW51IC5wcm9maWxlLW1lbnUgLnByb2ZpbGUtbmFtZSBoNiB7XG4gIG1hcmdpbi10b3A6IDA7XG4gIG1hcmdpbi1ib3R0b206IDVweDtcbiAgbGluZS1oZWlnaHQ6IDEuNzU7XG59XG5cbi5kcm9wZG93bi1tZW51IC5wcm9maWxlLW1lbnUgLnByb2ZpbGUtbmFtZSBhIHtcbiAgZm9udC1zaXplOiA4NSU7XG59XG5cbi5kcm9wZG93bi1tZW51LmFuaW1hdGVkIHtcbiAgYW5pbWF0aW9uLWR1cmF0aW9uOiAwLjRzO1xufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogOTkycHgpIHtcbiAgLnRvcC1uYXZiYXItZml4ZWQgLnRvcC1uYXZiYXIge1xuICAgIHBvc2l0aW9uOiBmaXhlZDtcbiAgICB3aWR0aDogMTAwJTtcbiAgICB0b3A6IDA7XG4gICAgbGVmdDogMDtcbiAgICB6LWluZGV4OiAxMDtcbiAgfVxuICAudG9wLW5hdmJhci1maXhlZCAuY29udGVudC13cmFwcGVyIHtcbiAgICBtYXJnaW4tdG9wOiA1MHB4O1xuICB9XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgU0lERUJBUlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5jb250ZW50LXdyYXBwZXIge1xuICBtaW4taGVpZ2h0OiAxMDB2aDtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogNzY5cHgpIHtcbiAgLmNvbnRlbnQtd3JhcHBlciB7XG4gICAgZGlzcGxheTogdGFibGU7XG4gICAgd2lkdGg6IDEwMCU7XG4gICAgdGFibGUtbGF5b3V0OiBmaXhlZDtcbiAgfVxuICAuY29udGVudC1jb250YWluZXIge1xuICAgIGRpc3BsYXk6IHRhYmxlLXJvdztcbiAgfVxuICAubGVmdC1zaWRlYmFyLCAubWFpbi1wYWdlLCAucmlnaHQtc2lkZWJhciB7XG4gICAgZGlzcGxheTogdGFibGUtY2VsbDtcbiAgICB2ZXJ0aWNhbC1hbGlnbjogdG9wO1xuICB9XG4gIC5yaWdodC1zaWRlYmFyIHtcbiAgICB3aWR0aDogNDAwcHg7XG4gICAgaGVpZ2h0OiAxMDAlO1xuICAgIGJveC1zaGFkb3c6IDAgMnB4IDVweCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICAgIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgICByaWdodDogLTQwMHB4O1xuICAgIHotaW5kZXg6IDk7XG4gICAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgICAtbW96LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICAgIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICB9XG4gIC5sZWZ0LXNpZGViYXIge1xuICAgIHdpZHRoOiAyNzBweDtcbiAgICAtd2Via2l0LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICAgIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gICAgdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIH1cbn1cblxuLnJpZ2h0LXNpZGViYXIuZml4ZWQtc2lkZWJhciAuc2lkZWJhci1jb250ZW50IHtcbiAgcG9zaXRpb246IGZpeGVkO1xuICB3aWR0aDogNDAwcHg7XG4gIGhlaWdodDogY2FsYygxMDAlIC0gNTBweCk7XG4gIG92ZXJmbG93OiBzY3JvbGw7XG4gIHJpZ2h0OiAtNDAwcHg7XG4gIC13ZWJraXQtdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xufVxuXG4ucmlnaHQtc2lkZWJhciAuY2xvc2UtaWNvbiB7XG4gIGZsb2F0OiByaWdodDtcbiAgY3Vyc29yOiBwb2ludGVyO1xufVxuXG4ubGVmdC1zaWRlYmFyIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG4ubGVmdC1zaWRlYmFyIC51c2VyLWluZm8ge1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIHBhZGRpbmctdG9wOiAxNXB4O1xuICBvdmVyZmxvdzogaGlkZGVuO1xuICBoZWlnaHQ6IDE3MHB4O1xuICAtd2Via2l0LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICAtbW96LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICB0cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbn1cblxuLmxlZnQtc2lkZWJhciAudXNlci1pbmZvIC50aXRsZSB7XG4gIG1hcmdpbjogMDtcbiAgbWFyZ2luLXRvcDogNXB4O1xuICBsaW5lLWhlaWdodDogMS43NTtcbiAgY29sb3I6IGluaGVyaXQgIWltcG9ydGFudDtcbn1cblxuLmxlZnQtc2lkZWJhciAudXNlci1pbmZvLmNsb3NlZCB7XG4gIGhlaWdodDogMHB4O1xufVxuXG4ubGVmdC1zaWRlYmFyIC5wdXJjaGFzZS1idG4ge1xuICBtYXJnaW4tYm90dG9tOiAzMHB4O1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IHtcbiAgbGlzdC1zdHlsZTogbm9uZTtcbiAgcGFkZGluZy1sZWZ0OiAwO1xufVxuXG4ubGVmdC1zaWRlYmFyIC5zaWRlLW5hdiAubmF2LWhlYWRlciB7XG4gIGZvbnQtc2l6ZTogODAlO1xuICB0ZXh0LXRyYW5zZm9ybTogdXBwZXJjYXNlO1xuICBwYWRkaW5nLWxlZnQ6IDE1cHg7XG4gIHBhZGRpbmctdG9wOiAxMHB4O1xuICBvcGFjaXR5OiAwLjg7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IC5uYXYtaGVhZGVyOmZpcnN0LWNoaWxkIHtcbiAgcGFkZGluZy10b3A6IDA7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IGEge1xuICBjb2xvcjogaW5oZXJpdDtcbn1cblxuLmxlZnQtc2lkZWJhciAuc2lkZS1uYXYgbGkge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IGxpIC5mYSB7XG4gIHdpZHRoOiAyNXB4O1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IGxpLmhhcy1jaGlsZHJlbiAuYXJyb3cge1xuICBmbG9hdDogcmlnaHQ7XG4gIHBhZGRpbmc6IDVweDtcbiAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgLW1vei10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IGxpIGEge1xuICBwYWRkaW5nOiAxMHB4IDA7XG4gIHBhZGRpbmctbGVmdDogMTVweDtcbiAgZGlzcGxheTogYmxvY2s7XG4gIC13ZWJraXQtdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xufVxuXG4ubGVmdC1zaWRlYmFyIC5zaWRlLW5hdiBsaSBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZDogcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgY29sb3I6IGluaGVyaXQ7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IGxpLmFjdGl2ZSB7XG4gIGJhY2tncm91bmQ6IHJnYmEoMCwgMCwgMCwgMC4xNSk7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IC5jaGlsZC1uYXYge1xuICBsaXN0LXN0eWxlOiBub25lO1xuICBwYWRkaW5nLWxlZnQ6IDA7XG59XG5cbi5sZWZ0LXNpZGViYXIgLnNpZGUtbmF2IC5jaGlsZC1uYXYgYSB7XG4gIHBhZGRpbmctbGVmdDogNDBweDtcbn1cblxuLmxlZnQtc2lkZWJhciAuc2lkZS1uYXYgLmhhcy1jaGlsZHJlbi5vcGVuIHtcbiAgYmFja2dyb3VuZDogcmdiYSgwLCAwLCAwLCAwLjE1KTtcbn1cblxuLmxlZnQtc2lkZWJhciAuc2lkZS1uYXYgLmhhcy1jaGlsZHJlbi5vcGVuIC5hcnJvdyB7XG4gIHRyYW5zZm9ybTogcm90YXRlKDkwZGVnKTtcbiAgcGFkZGluZy10b3A6IDE1cHg7XG59XG5cbi5sZWZ0LXNpZGViYXIuc21hbGwtbmF2IHtcbiAgd2lkdGg6IDUwcHg7XG4gIHotaW5kZXg6IDg7XG59XG5cbi5sZWZ0LXNpZGViYXIuc21hbGwtbmF2IC51c2VyLWluZm8ge1xuICBkaXNwbGF5OiBub25lO1xufVxuXG4ubGVmdC1zaWRlYmFyLnNtYWxsLW5hdiBsaSBzcGFuIHtcbiAgZGlzcGxheTogbm9uZTtcbn1cblxuLmxlZnQtc2lkZWJhci5zbWFsbC1uYXYgLmFycm93IHtcbiAgZGlzcGxheTogbm9uZSAhaW1wb3J0YW50O1xufVxuXG4ubGVmdC1zaWRlYmFyLnNtYWxsLW5hdiAuc2lkZWJhci1jb250ZW50IHtcbiAgd2lkdGg6IDUwcHg7XG59XG5cbi5sZWZ0LXNpZGViYXIuc21hbGwtbmF2IC5jaGlsZC1uYXYge1xuICBkaXNwbGF5OiBub25lICFpbXBvcnRhbnQ7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgdG9wOiAwO1xuICBsZWZ0OiA1MHB4O1xuICB3aWR0aDogMjcwcHg7XG4gIHotaW5kZXg6IDk7XG59XG5cbi5sZWZ0LXNpZGViYXIuc21hbGwtbmF2IC5zaWRlLW5hdiA+IGxpIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG4ubGVmdC1zaWRlYmFyLnNtYWxsLW5hdiAuc2lkZS1uYXYgPiBsaTpob3ZlciA+IGEgPiBzcGFuIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgdG9wOiAwO1xuICBsZWZ0OiA1MHB4O1xuICB3aWR0aDogMjcwcHg7XG4gIHBhZGRpbmc6IDEwcHggMDtcbiAgcGFkZGluZy1sZWZ0OiAxNXB4O1xufVxuXG4ubGVmdC1zaWRlYmFyLnNtYWxsLW5hdiAucHVyY2hhc2UtYnRuIHtcbiAgZGlzcGxheTogbm9uZTtcbn1cblxuLmxlZnQtc2lkZWJhci5zbWFsbC1uYXYgLmhhcy1jaGlsZHJlbiB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cblxuLmxlZnQtc2lkZWJhci5zbWFsbC1uYXYgLmhhcy1jaGlsZHJlbjpob3ZlciAuY2hpbGQtbmF2IHtcbiAgZGlzcGxheTogYmxvY2sgIWltcG9ydGFudDtcbn1cblxuLmxlZnQtc2lkZWJhci5zbWFsbC1uYXYgLmhhcy1jaGlsZHJlbjpob3ZlciAuY2hpbGQtbmF2IGEge1xuICBwYWRkaW5nLWxlZnQ6IDIwcHg7XG59XG5cbi5sZWZ0LXNpZGViYXIuc21hbGwtbmF2IC5oYXMtY2hpbGRyZW46aG92ZXIgLmNoaWxkLW5hdiBzcGFuIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xufVxuXG4ubGVmdC1zaWRlYmFyLnNtYWxsLW5hdjpob3ZlciAuc2lkZWJhci1jb250ZW50IHtcbiAgd2lkdGg6IDI3MHB4O1xufVxuXG5AbWVkaWEgKG1heC13aWR0aDogOTkxcHgpIHtcbiAgLmxlZnQtc2lkZWJhciB7XG4gICAgZGlzcGxheTogbm9uZTtcbiAgfVxufVxuXG5AbWVkaWEgKG1pbi13aWR0aDogOTkxcHgpIHtcbiAgLmxlZnQtc2lkZWJhci5maXhlZC1zaWRlYmFyIC5zaWRlYmFyLWNvbnRlbnQge1xuICAgIHBvc2l0aW9uOiBmaXhlZDtcbiAgICB3aWR0aDogMjcwcHg7XG4gICAgaGVpZ2h0OiBjYWxjKDEwMCUgLSA1MHB4KTtcbiAgICBvdmVyZmxvdzogc2Nyb2xsO1xuICB9XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTEFZT1VUXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ubWFpbi1wYWdlIHtcbiAgd2lkdGg6IDEwMCU7XG59XG5cbi5tYWluLXBhZ2UgYTpub3QoLmJ0bikge1xuICBjb2xvcjogaW5oZXJpdDtcbn1cblxuLnBhZ2UtdGl0bGUtZGl2IHtcbiAgYmFja2dyb3VuZDogI2ZmZjtcbiAgcGFkZGluZzogMTVweDtcbn1cblxuLnBhZ2UtdGl0bGUtZGl2IC50aXRsZSB7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG59XG5cbi5wYWdlLXRpdGxlLWRpdiAuc3ViLXRpdGxlIHtcbiAgY29sb3I6ICM3Njc2NzY7XG4gIG1hcmdpbi1ib3R0b206IDA7XG59XG5cbi5wYWdlLXRpdGxlLWRpdiAucmlnaHQtc2lkZSB7XG4gIHRleHQtYWxpZ246IHJpZ2h0O1xufVxuXG4ucGFnZS10aXRsZS1kaXYgLnJpZ2h0LXNpZGUgLmJ0biB7XG4gIG1hcmdpbi10b3A6IDEycHg7XG59XG5cbi5wYWdlLXRpdGxlLWRpdi5kYXJrLXRpdGxlIHtcbiAgYmFja2dyb3VuZDogIzI5MjkyOTtcbn1cblxuLnBhZ2UtdGl0bGUtZGl2LmRhcmstdGl0bGUgLnRpdGxlIHtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLmJyZWFkY3J1bWItZGl2IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2ZmZjtcbiAgcGFkZGluZzogOHB4IDE1cHg7XG4gIGJvcmRlci10b3A6IDFweCBzb2xpZCAjZjJmMmYyO1xuICBib3JkZXItYm90dG9tOiAxcHggc29saWQgI2YyZjJmMjtcbiAgZm9udC1zaXplOiA5MCU7XG4gIGNvbG9yOiAjNzY3Njc2O1xufVxuXG4uYnJlYWRjcnVtYi1kaXYgYSB7XG4gIGNvbG9yOiBpbmhlcml0O1xufVxuXG4uYnJlYWRjcnVtYi1kaXYgYTpob3ZlciB7XG4gIGNvbG9yOiAjMzQ5OGRiICFpbXBvcnRhbnQ7XG59XG5cbi5icmVhZGNydW1iLWRpdiAuYnJlYWRjcnVtYiB7XG4gIGJhY2tncm91bmQ6IHRyYW5zcGFyZW50O1xuICBwYWRkaW5nOiAwO1xuICBtYXJnaW46IDA7XG59XG5cbi5icmVhZGNydW1iLWRpdiAuYnJlYWRjcnVtYiAuZmEge1xuICBtYXJnaW4tcmlnaHQ6IDVweDtcbn1cblxuLmJyZWFkY3J1bWItZGl2IC50ZXh0LXJpZ2h0IGEgLmZhIHtcbiAgbWFyZ2luLXJpZ2h0OiAycHg7XG59XG5cbi5jb250ZW50LWludGVybmFsIHtcbiAgbWFyZ2luLXJpZ2h0OiAtMjgwcHg7XG4gIHdpZHRoOiAxMDAlO1xuICBmbG9hdDogbGVmdDtcbn1cblxuLmNvbnRlbnQtaW50ZXJuYWwgLmNvbnRlbnQge1xuICBtYXJnaW4tcmlnaHQ6IDI4MHB4O1xuICBiYWNrZ3JvdW5kOiAjZmZmO1xuICBwYWRkaW5nOiAxNXB4O1xufVxuXG4uc2lkZWJhci1pbnRlcm5hbCB7XG4gIGZsb2F0OiByaWdodDtcbn1cblxuLnNpZGViYXItaW50ZXJuYWwuYWZmaXgge1xuICByaWdodDogMTVweDtcbiAgdG9wOiA4MHB4O1xuICBwb3NpdGlvbjogZml4ZWQgIWltcG9ydGFudDtcbn1cblxuLnNpZGViYXItaW50ZXJuYWwgLnNpZGViYXIge1xuICB3aWR0aDogMjYwcHg7XG4gIGJhY2tncm91bmQ6ICNmZmY7XG4gIHBhZGRpbmc6IDE1cHg7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgUEFORUxTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ucGFuZWwge1xuICBib3gtc2hhZG93OiAwIDFweCAycHggcmdiYSgwLCAwLCAwLCAwLjEpO1xufVxuXG4ucGFuZWwgLnBhbmVsLXRpdGxlIGgxLCAucGFuZWwgLnBhbmVsLXRpdGxlIGgyLCAucGFuZWwgLnBhbmVsLXRpdGxlIGgzLCAucGFuZWwgLnBhbmVsLXRpdGxlIGg0LCAucGFuZWwgLnBhbmVsLXRpdGxlIGg1LCAucGFuZWwgLnBhbmVsLXRpdGxlIGg2IHtcbiAgY29sb3I6IGluaGVyaXQgIWltcG9ydGFudDtcbiAgbWFyZ2luOiAwO1xuICBsaW5lLWhlaWdodDogMzBweDtcbn1cblxuLnBhbmVsLWhlYWRpbmcge1xuICBwYWRkaW5nOiA1cHg7XG59XG5cbi5wYW5lbC1oZWFkaW5nIC5wYW5lbC10aXRsZSB7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG4gIHBhZGRpbmctbGVmdDogMTVweDtcbn1cblxuLnBhbmVsLWhlYWRpbmcgLnBhbmVsLXRpdGxlIHNtYWxsIHtcbiAgY29sb3I6ICM3Njc2NzY7XG4gIGZvbnQtc2l6ZTogNzUlO1xuICBmb250LXN0eWxlOiBpdGFsaWM7XG4gIG1hcmdpbi1sZWZ0OiA1cHg7XG59XG5cbi5sb2JpcGFuZWwge1xuICBtYXJnaW4tYm90dG9tOiAyMHB4O1xufVxuXG4ubG9iaXBhbmVsID4gLnBhbmVsLWhlYWRpbmcgPiAucGFuZWwtdGl0bGUgaDEsIC5sb2JpcGFuZWwgPiAucGFuZWwtaGVhZGluZyA+IC5wYW5lbC10aXRsZSBoMiwgLmxvYmlwYW5lbCA+IC5wYW5lbC1oZWFkaW5nID4gLnBhbmVsLXRpdGxlIGgzLCAubG9iaXBhbmVsID4gLnBhbmVsLWhlYWRpbmcgPiAucGFuZWwtdGl0bGUgaDQsIC5sb2JpcGFuZWwgPiAucGFuZWwtaGVhZGluZyA+IC5wYW5lbC10aXRsZSBoNSwgLmxvYmlwYW5lbCA+IC5wYW5lbC1oZWFkaW5nID4gLnBhbmVsLXRpdGxlIGg2IHtcbiAgbGluZS1oZWlnaHQ6IGluaGVyaXQ7XG4gIG1hcmdpbi10b3A6IDBweDtcbn1cblxuLmxvYmlwYW5lbCA+IC5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tdG9nZ2xlIC5wYW5lbC1jb250cm9sLWljb24ge1xuICBsaW5lLWhlaWdodDogaW5oZXJpdDtcbiAgbWFyZ2luLXRvcDogMTBweDtcbn1cblxuLmxvYmlwYW5lbCAucGFuZWwtaGVhZGluZyAuZHJvcGRvd24gLmRyb3Bkb3duLW1lbnUgPiBsaSA+IGEge1xuICBmb250LXNpemU6IDEycHg7XG59XG5cbi5sb2JpcGFuZWwgLnBhbmVsLWhlYWRpbmcgLmRyb3Bkb3duIC5kcm9wZG93bi1tZW51ID4gbGkgPiBhOmZvY3VzOmhvdmVyLCAubG9iaXBhbmVsIC5wYW5lbC1oZWFkaW5nIC5kcm9wZG93biAuZHJvcGRvd24tbWVudSA+IGxpID4gYTpob3ZlciB7XG4gIHRleHQtc2hhZG93OiBub25lO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiByZ2JhKDAsIDAsIDAsIDAuMSk7XG59XG5cbi5sb2JpcGFuZWwgPiAucGFuZWwtaGVhZGluZyA+IC5wYW5lbC10aXRsZSBpbnB1dCB7XG4gIGJhY2tncm91bmQtY29sb3I6IHJnYmEoMCwgMCwgMCwgMC4xKTtcbiAgYm9yZGVyOiAwO1xufVxuXG4ubG9iaXBhbmVsID4gLnBhbmVsLWhlYWRpbmcgPiAucGFuZWwtdGl0bGUge1xuICBtYXJnaW4tdG9wOiAxMHB4O1xufVxuXG4ubG9iaXBhbmVsLnBhbmVsLWV4cGFuZGVkIHtcbiAgYm9yZGVyLXJhZGl1czogMDtcbn1cblxuLmxvYmlwYW5lbC5wYW5lbC11bnBpbiB7XG4gIGJveC1zaGFkb3c6IDAgMnB4IDVweCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xufVxuXG4ubG9iaXBhbmVsID4gLnBhbmVsLWhlYWRpbmcge1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogNHB4O1xuICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiA0cHg7XG59XG5cbi5wYW5lbC1kZWZhdWx0IHtcbiAgYm9yZGVyLWNvbG9yOiAjZTVlNWU1O1xufVxuXG4ucGFuZWwtZGVmYXVsdCAucGFuZWwtaGVhZGluZyB7XG4gIGNvbG9yOiAjMjkyOTI5O1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjJmMmYyO1xuICBib3JkZXItY29sb3I6ICNlNWU1ZTU7XG59XG5cbi5wYW5lbC1kZWZhdWx0IC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5wYW5lbC1wcmltYXJ5IHtcbiAgYm9yZGVyLWNvbG9yOiAjMjU4Y2QxO1xufVxuXG4ucGFuZWwtcHJpbWFyeSAucGFuZWwtaGVhZGluZyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzQ5OGRiO1xuICBib3JkZXItY29sb3I6ICMyNThjZDE7XG59XG5cbi5wYW5lbC1wcmltYXJ5IC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC1kYW5nZXIge1xuICBib3JkZXItY29sb3I6ICNlNDM3MjU7XG59XG5cbi5wYW5lbC1kYW5nZXIgLnBhbmVsLWhlYWRpbmcge1xuICBjb2xvcjogI2ZmZjtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U3NGMzYztcbiAgYm9yZGVyLWNvbG9yOiAjZTQzNzI1O1xufVxuXG4ucGFuZWwtZGFuZ2VyIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC1zdWNjZXNzIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjI5OTU1O1xufVxuXG4ucGFuZWwtc3VjY2VzcyAucGFuZWwtaGVhZGluZyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjdhZTYwO1xuICBib3JkZXItY29sb3I6ICMyMjk5NTU7XG59XG5cbi5wYW5lbC1zdWNjZXNzIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC13YXJuaW5nIHtcbiAgYm9yZGVyLWNvbG9yOiAjZTA4ZTBiO1xufVxuXG4ucGFuZWwtd2FybmluZyAucGFuZWwtaGVhZGluZyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjM5YzEyO1xuICBib3JkZXItY29sb3I6ICNlMDhlMGI7XG59XG5cbi5wYW5lbC13YXJuaW5nIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC1pbmZvIHtcbiAgYm9yZGVyLWNvbG9yOiAjNDZiOGRhO1xufVxuXG4ucGFuZWwtaW5mbyAucGFuZWwtaGVhZGluZyB7XG4gIGNvbG9yOiAjZmZmO1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjNWJjMGRlO1xuICBib3JkZXItY29sb3I6ICM0NmI4ZGE7XG59XG5cbi5wYW5lbC1pbmZvIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC1ibGFjayB7XG4gIGJvcmRlci1jb2xvcjogIzFjMWMxYztcbn1cblxuLnBhbmVsLWJsYWNrIC5wYW5lbC1oZWFkaW5nIHtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG4gIGJvcmRlci1jb2xvcjogIzFjMWMxYztcbn1cblxuLnBhbmVsLWJsYWNrIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5wYW5lbC1saWdodC1ibGFjayB7XG4gIGJvcmRlci1jb2xvcjogIzNjM2MzYztcbn1cblxuLnBhbmVsLWxpZ2h0LWJsYWNrIC5wYW5lbC1oZWFkaW5nIHtcbiAgY29sb3I6ICNmZmY7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0OTQ5NDk7XG4gIGJvcmRlci1jb2xvcjogIzNjM2MzYztcbn1cblxuLnBhbmVsLWxpZ2h0LWJsYWNrIC5wYW5lbC1oZWFkaW5nIHNtYWxsIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5hY2MtcGFuZWxzIC5wYW5lbC1oZWFkaW5nIC5wYW5lbC10aXRsZSB7XG4gIG1hcmdpbi10b3A6IDVweDtcbn1cblxuLmFjYy1wYW5lbHMgLnBhbmVsLWhlYWRpbmcgLnBhbmVsLXRpdGxlIGEge1xuICBkaXNwbGF5OiBibG9jaztcbn1cblxuLmFjYy1wYW5lbHMgLnBhbmVsLWhlYWRpbmcgLnBhbmVsLXRpdGxlIGEgLmljb24tcGx1cyB7XG4gIG1hcmdpbi1yaWdodDogNXB4O1xuICAtd2Via2l0LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICAtbW96LXRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xuICB0cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbn1cblxuLmFjYy1wYW5lbHMgLnBhbmVsLWhlYWRpbmcgLnBhbmVsLXRpdGxlIGEgLmljb24tcGx1cy1yaWdodCB7XG4gIGZsb2F0OiByaWdodDtcbiAgbWFyZ2luLXRvcDogNXB4O1xuICBtYXJnaW4tcmlnaHQ6IDVweDtcbiAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgLW1vei10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG59XG5cbi5hY2MtcGFuZWxzIC5wYW5lbC1oZWFkaW5nIC5wYW5lbC10aXRsZSBhW2FyaWEtZXhwYW5kZWQ9dHJ1ZV0gLmljb24tcGx1cyB7XG4gIG1hcmdpbi1yaWdodDogNXB4O1xuICB0cmFuc2Zvcm06IHJvdGF0ZSgxMzVkZWcpO1xufVxuXG4uYWNjLXBhbmVscyAucGFuZWwtaGVhZGluZyAucGFuZWwtdGl0bGUgYVthcmlhLWV4cGFuZGVkPXRydWVdIC5pY29uLXBsdXMtcmlnaHQge1xuICB0cmFuc2Zvcm06IHJvdGF0ZSgxMzVkZWcpO1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFRBQlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5uYXYtdGFicy5yaWdodC1hbGlnbmVkIGxpIHtcbiAgZmxvYXQ6IHJpZ2h0O1xufVxuXG4ubmF2LXRhYnMgLmRyb3Bkb3duLW1lbnUgPiAuYWN0aXZlID4gYSwgLm5hdi10YWJzIC5kcm9wZG93bi1tZW51ID4gLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicyAuZHJvcGRvd24tbWVudSA+IC5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi5uYXYtdGFicyA+IGxpID4gYSB7XG4gIG9wYWNpdHk6IDAuNDtcbn1cblxuLm5hdi10YWJzID4gbGkuYWN0aXZlID4gYSB7XG4gIG9wYWNpdHk6IDE7XG59XG5cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tID4gbGkuYWN0aXZlID4gYSwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20gPiBsaS5hY3RpdmUgPiBhOmhvdmVyLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbSA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICBib3JkZXI6IDAgIWltcG9ydGFudDtcbiAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICNkZGQgIWltcG9ydGFudDtcbn1cblxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20gPiBsaSA+IGEge1xuICBib3JkZXI6IDAgIWltcG9ydGFudDtcbn1cblxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXByaW1hcnkgPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItcHJpbWFyeSA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1wcmltYXJ5ID4gbGkuYWN0aXZlID4gYTpmb2N1cyB7XG4gIGJvcmRlci1ib3R0b206IDRweCBzb2xpZCAjMzQ5OGRiICFpbXBvcnRhbnQ7XG59XG5cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1kYW5nZXIgPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItZGFuZ2VyID4gbGkuYWN0aXZlID4gYTpob3ZlciwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLWRhbmdlciA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICBib3JkZXItYm90dG9tOiA0cHggc29saWQgI2U3NGMzYyAhaW1wb3J0YW50O1xufVxuXG4ubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItc3VjY2VzcyA+IGxpLmFjdGl2ZSA+IGEsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1zdWNjZXNzID4gbGkuYWN0aXZlID4gYTpob3ZlciwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXN1Y2Nlc3MgPiBsaS5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICMyN2FlNjAgIWltcG9ydGFudDtcbn1cblxuLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLXdhcm5pbmcgPiBsaS5hY3RpdmUgPiBhLCAubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItd2FybmluZyA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci13YXJuaW5nID4gbGkuYWN0aXZlID4gYTpmb2N1cyB7XG4gIGJvcmRlci1ib3R0b206IDRweCBzb2xpZCAjZjM5YzEyICFpbXBvcnRhbnQ7XG59XG5cbi5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1ibGFjayA+IGxpLmFjdGl2ZSA+IGEsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1ibGFjayA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1ibGFjayA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICBib3JkZXItYm90dG9tOiA0cHggc29saWQgIzI5MjkyOSAhaW1wb3J0YW50O1xufVxuXG4ubmF2LXRhYnMuYm9yZGVyLWJvdHRvbS5ib3JkZXItZ3JheSA+IGxpLmFjdGl2ZSA+IGEsIC5uYXYtdGFicy5ib3JkZXItYm90dG9tLmJvcmRlci1ncmF5ID4gbGkuYWN0aXZlID4gYTpob3ZlciwgLm5hdi10YWJzLmJvcmRlci1ib3R0b20uYm9yZGVyLWdyYXkgPiBsaS5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgYm9yZGVyLWJvdHRvbTogNHB4IHNvbGlkICNmMmYyZjIgIWltcG9ydGFudDtcbn1cblxuLnRhYnMtbGVmdCAubmF2LXRhYnMge1xuICBmbG9hdDogbGVmdDtcbiAgYm9yZGVyLWJvdHRvbTogMDtcbn1cblxuLnRhYnMtbGVmdCAubmF2LXRhYnMgbGkge1xuICBmbG9hdDogbm9uZTtcbiAgbWFyZ2luOiAwO1xufVxuXG4udGFicy1sZWZ0IC5uYXYtdGFicyBsaSBhIHtcbiAgbWFyZ2luLXJpZ2h0OiAwO1xuICBib3JkZXI6IDA7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG4gIGNvbG9yOiAjZmZmO1xuICBib3JkZXItcmFkaXVzOiAwO1xuICBvcGFjaXR5OiAxO1xufVxuXG4udGFicy1sZWZ0IC5uYXYtdGFicyBsaSBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzQ5NDk0OTtcbn1cblxuLnRhYnMtbGVmdCAudGFiLWNvbnRlbnQge1xuICBtYXJnaW4tbGVmdDogNDVweDtcbn1cblxuLnRhYnMtbGVmdCAudGFiLWNvbnRlbnQgLnRhYi1wYW5lIHtcbiAgZGlzcGxheTogbm9uZTtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgcGFkZGluZzogMTVweDtcbiAgb3ZlcmZsb3cteTogYXV0bztcbn1cblxuLnRhYnMtbGVmdCAudGFiLWNvbnRlbnQgLmFjdGl2ZSB7XG4gIGRpc3BsYXk6IGJsb2NrO1xufVxuXG4udGFicy1sZWZ0IC5uYXYtdGFicyA+IGxpLmFjdGl2ZSA+IGEsIC50YWJzLWxlZnQgLm5hdi10YWJzID4gbGkuYWN0aXZlID4gYTpob3ZlciwgLnRhYnMtbGVmdCAubmF2LXRhYnMgPiBsaS5hY3RpdmUgPiBhOmZvY3VzIHtcbiAgYm9yZGVyOiAwO1xuICBiYWNrZ3JvdW5kOiAjZjJmMmYyO1xuICBjb2xvcjogIzI5MjkyOTtcbn1cblxuLnRhYnMtcmlnaHQgLm5hdi10YWJzIHtcbiAgZmxvYXQ6IHJpZ2h0O1xuICBib3JkZXItYm90dG9tOiAwO1xufVxuXG4udGFicy1yaWdodCAubmF2LXRhYnMgbGkge1xuICBmbG9hdDogbm9uZTtcbiAgbWFyZ2luOiAwO1xufVxuXG4udGFicy1yaWdodCAubmF2LXRhYnMgbGkgYSB7XG4gIG1hcmdpbi1sZWZ0OiAwO1xuICBib3JkZXI6IDA7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG4gIGNvbG9yOiAjZmZmO1xuICBib3JkZXItcmFkaXVzOiAwO1xuICBvcGFjaXR5OiAxO1xufVxuXG4udGFicy1yaWdodCAubmF2LXRhYnMgbGkgYTpob3ZlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM0OTQ5NDk7XG59XG5cbi50YWJzLXJpZ2h0IC50YWItY29udGVudCB7XG4gIG1hcmdpbi1yaWdodDogNDVweDtcbn1cblxuLnRhYnMtcmlnaHQgLnRhYi1jb250ZW50IC50YWItcGFuZSB7XG4gIGRpc3BsYXk6IG5vbmU7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIHBhZGRpbmc6IDE1cHg7XG4gIG92ZXJmbG93LXk6IGF1dG87XG59XG5cbi50YWJzLXJpZ2h0IC50YWItY29udGVudCAuYWN0aXZlIHtcbiAgZGlzcGxheTogYmxvY2s7XG59XG5cbi50YWJzLXJpZ2h0IC5uYXYtdGFicyA+IGxpLmFjdGl2ZSA+IGEsIC50YWJzLXJpZ2h0IC5uYXYtdGFicyA+IGxpLmFjdGl2ZSA+IGE6aG92ZXIsIC50YWJzLXJpZ2h0IC5uYXYtdGFicyA+IGxpLmFjdGl2ZSA+IGE6Zm9jdXMge1xuICBib3JkZXI6IDA7XG4gIGJhY2tncm91bmQ6ICNmMmYyZjI7XG4gIGNvbG9yOiAjMjkyOTI5O1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIExBQkVMUyAmIEJBREdFU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmxhYmVsIHtcbiAgcGFkZGluZzogMC4yZW0gMC42ZW07XG59XG5cbi5sYWJlbC1yb3VuZGVkIHtcbiAgcGFkZGluZzogLjJlbSAxLjJlbSAuM2VtO1xuICBib3JkZXItcmFkaXVzOiAyMHB4O1xufVxuXG4ubGFiZWwtZmxhdCB7XG4gIGJvcmRlci1yYWRpdXM6IDA7XG59XG5cbi5sYWJlbC13aWRlIHtcbiAgcGFkZGluZzogLjJlbSAxLjJlbSAuM2VtO1xufVxuXG4ubGFiZWwtYm9yZGVyZWQge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZmO1xuICBib3JkZXItd2lkdGg6IDJweDtcbiAgYm9yZGVyLXN0eWxlOiBzb2xpZDtcbn1cblxuLmxhYmVsLWJvcmRlcmVkLmxhYmVsLWRlZmF1bHQge1xuICBib3JkZXItY29sb3I6ICM3Nzc3Nzc7XG4gIGNvbG9yOiAjNzc3Nzc3ICFpbXBvcnRhbnQ7XG59XG5cbi5sYWJlbC1ib3JkZXJlZC5sYWJlbC1wcmltYXJ5IHtcbiAgYm9yZGVyLWNvbG9yOiAjMzQ5OGRiO1xuICBjb2xvcjogIzM0OThkYiAhaW1wb3J0YW50O1xufVxuXG4ubGFiZWwtYm9yZGVyZWQubGFiZWwtZGFuZ2VyIHtcbiAgYm9yZGVyLWNvbG9yOiAjZTc0YzNjO1xuICBjb2xvcjogI2U3NGMzYyAhaW1wb3J0YW50O1xufVxuXG4ubGFiZWwtYm9yZGVyZWQubGFiZWwtc3VjY2VzcyB7XG4gIGJvcmRlci1jb2xvcjogIzI3YWU2MDtcbiAgY29sb3I6ICMyN2FlNjAgIWltcG9ydGFudDtcbn1cblxuLmxhYmVsLWJvcmRlcmVkLmxhYmVsLXdhcm5pbmcge1xuICBib3JkZXItY29sb3I6ICNmMzljMTI7XG4gIGNvbG9yOiAjZjM5YzEyICFpbXBvcnRhbnQ7XG59XG5cbi5sYWJlbC1ib3JkZXJlZC5sYWJlbC1pbmZvIHtcbiAgYm9yZGVyLWNvbG9yOiAjNWJjMGRlO1xuICBjb2xvcjogIzViYzBkZSAhaW1wb3J0YW50O1xufVxuXG4ubGFiZWwtYm9yZGVyZWQubGFiZWwtYmxhY2sge1xuICBib3JkZXItY29sb3I6ICMyOTI5Mjk7XG4gIGNvbG9yOiAjMjkyOTI5ICFpbXBvcnRhbnQ7XG59XG5cbi5sYWJlbC1ib3JkZXJlZC5sYWJlbC1ncmF5IHtcbiAgYm9yZGVyLWNvbG9yOiAjZjJmMmYyO1xuICBjb2xvcjogI2YyZjJmMiAhaW1wb3J0YW50O1xufVxuXG4uYmFkZ2UuYmFkZ2UtZGVmYXVsdCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM3Nzc3Nzc7XG59XG5cbi5iYWRnZS5iYWRnZS1wcmltYXJ5IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzM0OThkYjtcbn1cblxuLmJhZGdlLmJhZGdlLWRhbmdlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNzRjM2M7XG59XG5cbi5iYWRnZS5iYWRnZS1zdWNjZXNzIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI3YWU2MDtcbn1cblxuLmJhZGdlLmJhZGdlLXdhcm5pbmcge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjM5YzEyO1xufVxuXG4uYmFkZ2UuYmFkZ2UtaW5mbyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG59XG5cbi5iYWRnZS5iYWRnZS1ibGFjayB7XG4gIGJhY2tncm91bmQtY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5iYWRnZS5iYWRnZS1ncmF5IHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbiAgY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5iYWRnZS5iYWRnZS1ib3JkZXJlZCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7XG4gIGJvcmRlci13aWR0aDogMnB4O1xuICBib3JkZXItc3R5bGU6IHNvbGlkO1xufVxuXG4uYmFkZ2UuYmFkZ2UtYm9yZGVyZWQuYmFkZ2UtZGVmYXVsdCB7XG4gIGJvcmRlci1jb2xvcjogIzc3Nzc3NztcbiAgY29sb3I6ICM3Nzc3NzcgIWltcG9ydGFudDtcbn1cblxuLmJhZGdlLmJhZGdlLWJvcmRlcmVkLmJhZGdlLXByaW1hcnkge1xuICBib3JkZXItY29sb3I6ICMzNDk4ZGI7XG4gIGNvbG9yOiAjMzQ5OGRiICFpbXBvcnRhbnQ7XG59XG5cbi5iYWRnZS5iYWRnZS1ib3JkZXJlZC5iYWRnZS1kYW5nZXIge1xuICBib3JkZXItY29sb3I6ICNlNzRjM2M7XG4gIGNvbG9yOiAjZTc0YzNjICFpbXBvcnRhbnQ7XG59XG5cbi5iYWRnZS5iYWRnZS1ib3JkZXJlZC5iYWRnZS1zdWNjZXNzIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjdhZTYwO1xuICBjb2xvcjogIzI3YWU2MCAhaW1wb3J0YW50O1xufVxuXG4uYmFkZ2UuYmFkZ2UtYm9yZGVyZWQuYmFkZ2Utd2FybmluZyB7XG4gIGJvcmRlci1jb2xvcjogI2YzOWMxMjtcbiAgY29sb3I6ICNmMzljMTIgIWltcG9ydGFudDtcbn1cblxuLmJhZGdlLmJhZGdlLWJvcmRlcmVkLmJhZGdlLWluZm8ge1xuICBib3JkZXItY29sb3I6ICM1YmMwZGU7XG4gIGNvbG9yOiAjNWJjMGRlICFpbXBvcnRhbnQ7XG59XG5cbi5iYWRnZS5iYWRnZS1ib3JkZXJlZC5iYWRnZS1ibGFjayB7XG4gIGJvcmRlci1jb2xvcjogIzI5MjkyOTtcbiAgY29sb3I6ICMyOTI5MjkgIWltcG9ydGFudDtcbn1cblxuLmJhZGdlLmJhZGdlLWJvcmRlcmVkLmJhZGdlLWdyYXkge1xuICBib3JkZXItY29sb3I6ICNmMmYyZjI7XG4gIGNvbG9yOiAjZjJmMmYyICFpbXBvcnRhbnQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgU0VDVElPTlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5zZWN0aW9uIHtcbiAgcGFkZGluZzogMzBweCAwO1xufVxuXG4uc2VjdGlvbiAuc2VjdGlvbi10aXRsZSAudGl0bGUge1xuICBtYXJnaW4tdG9wOiAwO1xufVxuXG4uc2VjdGlvbiAuc2VjdGlvbi10aXRsZSAuc3ViLXRpdGxlIHtcbiAgY29sb3I6ICM3Njc2NzY7XG59XG5cbi51bmRlcmxpbmUge1xuICBwb3NpdGlvbjogcmVsYXRpdmU7XG4gIHBhZGRpbmctYm90dG9tOiAxMHB4O1xuICBtYXJnaW4tYm90dG9tOiAxMnB4O1xufVxuXG4udW5kZXJsaW5lOmFmdGVyIHtcbiAgY29udGVudDogXCJcIjtcbiAgd2lkdGg6IDMycHg7XG4gIGhlaWdodDogMXB4O1xuICBiYWNrZ3JvdW5kOiAjNzY3Njc2O1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIGJvdHRvbTogMDtcbiAgbGVmdDogMDtcbn1cblxuLnRleHQtY2VudGVyIC51bmRlcmxpbmU6OmFmdGVyIHtcbiAgd2lkdGg6IDQlO1xuICBsZWZ0OiA0OCU7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQlVUVE9OU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmJ0bjpmb2N1cywgLmJ0bi5mb2N1cywgLmJ0bjphY3RpdmU6Zm9jdXMsIC5idG46YWN0aXZlLmZvY3VzLCAuYnRuLmFjdGl2ZTpmb2N1cywgLmJ0bi5hY3RpdmUuZm9jdXMge1xuICBvdXRsaW5lOiAwO1xufVxuXG4uYnRuLXJvdW5kZWQge1xuICBib3JkZXItcmFkaXVzOiAzMHB4O1xufVxuXG4uYnRuLXdpZGUge1xuICBwYWRkaW5nOiA2cHggMjJweDtcbn1cblxuLmJ0biAuZmEge1xuICBtYXJnaW4tcmlnaHQ6IDZweDtcbn1cblxuLmJ0bi5idG4tbGFiZWxlZCB7XG4gIHBhZGRpbmctdG9wOiAwO1xuICBwYWRkaW5nLWJvdHRvbTogMDtcbn1cblxuLmJ0bi5idG4tbGFiZWxlZCAuZmEge1xuICBtYXJnaW4tcmlnaHQ6IDBweDtcbn1cblxuLmJ0bi5idG4tbGFiZWxlZCAuYnRuLWxhYmVsIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xuICBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudDtcbiAgYmFja2dyb3VuZDogcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBwYWRkaW5nOiA2cHggMTJweDtcbiAgbGVmdDogLTEycHg7XG4gIGJvcmRlci1yYWRpdXM6IDRweCAwIDAgNHB4O1xufVxuXG4uYnRuLmJ0bi1sYWJlbGVkIC5idG4tbGFiZWwuYnRuLWxhYmVsLXJpZ2h0IHtcbiAgbGVmdDogYXV0bztcbiAgcmlnaHQ6IC0xMnB4O1xuICBib3JkZXItcmFkaXVzOiAwIDRweCA0cHggMDtcbn1cblxuLmJ0bi5idG4tbGFiZWxlZC5idG4tcm91bmRlZCAuYnRuLWxhYmVsIHtcbiAgYm9yZGVyLXJhZGl1czogMzBweCAwIDAgMzBweDtcbn1cblxuLmJ0bi5idG4tbGFiZWxlZC5idG4tcm91bmRlZCAuYnRuLWxhYmVsLmJ0bi1sYWJlbC1yaWdodCB7XG4gIGxlZnQ6IGF1dG87XG4gIHJpZ2h0OiAtMTJweDtcbiAgYm9yZGVyLXJhZGl1czogMCAzMHB4IDMwcHggMDtcbn1cblxuLmJ0bi5pY29uLW9ubHkgLmZhIHtcbiAgbWFyZ2luLXJpZ2h0OiAwO1xufVxuXG4uYnRuLmJ0bi1hbmltYXRlZCB7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbn1cblxuLmJ0bi5idG4tYW5pbWF0ZWQgLmhpZGRlbi1jb250ZW50IHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB3aWR0aDogMTAwJTtcbiAgcmlnaHQ6IC0xMDAlO1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIC13ZWJraXQtdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xufVxuXG4uYnRuLmJ0bi1hbmltYXRlZCAudmlzaWJsZS1jb250ZW50IHtcbiAgLXdlYmtpdC10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgLW1vei10cmFuc2l0aW9uOiBhbGwgMC40cyBlYXNlLWluLW91dDtcbiAgdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG59XG5cbi5idG4uYnRuLWFuaW1hdGVkOmhvdmVyIC5oaWRkZW4tY29udGVudCB7XG4gIHJpZ2h0OiAwO1xufVxuXG4uYnRuLmJ0bi1hbmltYXRlZDpob3ZlciAudmlzaWJsZS1jb250ZW50IHtcbiAgb3BhY2l0eTogMDtcbn1cblxuLmJ0bi5idG4tbGcuYnRuLWxhYmVsZWQgLmJ0bi1sYWJlbCB7XG4gIHBhZGRpbmc6IDEwcHggMTZweDtcbiAgbGVmdDogLTE2cHg7XG59XG5cbi5idG4uYnRuLWxnLmJ0bi1sYWJlbGVkIC5idG4tbGFiZWwuYnRuLWxhYmVsLXJpZ2h0IHtcbiAgbGVmdDogYXV0bztcbiAgcmlnaHQ6IC0xNnB4O1xufVxuXG4uYnRuLmJ0bi1zbS5idG4tbGFiZWxlZCAuYnRuLWxhYmVsIHtcbiAgcGFkZGluZzogNXB4IDEwcHg7XG4gIGxlZnQ6IC0xMHB4O1xufVxuXG4uYnRuLmJ0bi1zbS5idG4tbGFiZWxlZCAuYnRuLWxhYmVsLmJ0bi1sYWJlbC1yaWdodCB7XG4gIGxlZnQ6IGF1dG87XG4gIHJpZ2h0OiAtMTBweDtcbn1cblxuLmJ0bi5idG4teHMuYnRuLWxhYmVsZWQgLmJ0bi1sYWJlbCB7XG4gIHBhZGRpbmc6IDFweCA1cHg7XG4gIGxlZnQ6IC01cHg7XG59XG5cbi5idG4uYnRuLXhzLmJ0bi1sYWJlbGVkIC5idG4tbGFiZWwuYnRuLWxhYmVsLXJpZ2h0IHtcbiAgbGVmdDogYXV0bztcbiAgcmlnaHQ6IC01cHg7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTU9EQUxTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ubW9kYWwtdGl0bGUgc21hbGwge1xuICBjb2xvcjogIzc2NzY3NjtcbiAgZm9udC1zaXplOiA3NSU7XG4gIGZvbnQtc3R5bGU6IGl0YWxpYztcbiAgbWFyZ2luLWxlZnQ6IDVweDtcbn1cblxuLm1vZGFsLWNvbG9yLXByaW1hcnkgLm1vZGFsLWJhY2tkcm9wIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzM0OThkYjtcbn1cblxuLm1vZGFsLWNvbG9yLWRhbmdlciAubW9kYWwtYmFja2Ryb3Age1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZTc0YzNjO1xufVxuXG4ubW9kYWwtY29sb3Itc3VjY2VzcyAubW9kYWwtYmFja2Ryb3Age1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMjdhZTYwO1xufVxuXG4ubW9kYWwtY29sb3ItYmxhY2sgLm1vZGFsLWJhY2tkcm9wIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI5MjkyOTtcbn1cblxuLm1vZGFsLWNvbG9yLXdhcm5pbmcgLm1vZGFsLWJhY2tkcm9wIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YzOWMxMjtcbn1cblxuLm1vZGFsLWNvbG9yLWdyYXkgLm1vZGFsLWJhY2tkcm9wIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2YyZjJmMjtcbn1cblxuLm1vZGFsLWNvbG9yLXdoaXRlIC5tb2RhbC1iYWNrZHJvcCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmZmY7XG59XG5cbi5tb2RhbC1jb2xvci1pbmZvIC5tb2RhbC1iYWNrZHJvcCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG59XG5cbi50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCB7XG4gIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50O1xuICBib3gtc2hhZG93OiBub25lO1xuICBib3JkZXI6IDA7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4udHJhbnMtbW9kYWwgLm1vZGFsLWNvbnRlbnQgLmNsb3NlIHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCBoMSwgLnRyYW5zLW1vZGFsIC5tb2RhbC1jb250ZW50IGgyLCAudHJhbnMtbW9kYWwgLm1vZGFsLWNvbnRlbnQgaDMsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCBoNCwgLnRyYW5zLW1vZGFsIC5tb2RhbC1jb250ZW50IGg1LCAudHJhbnMtbW9kYWwgLm1vZGFsLWNvbnRlbnQgaDYsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDEsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDIsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDMsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDQsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDUsIC50cmFucy1tb2RhbCAubW9kYWwtY29udGVudCAuaDYge1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLnRyYW5zLW1vZGFsIC5tb2RhbC1jb250ZW50IC5tb2RhbC1oZWFkZXIge1xuICBib3JkZXI6IDBweDtcbn1cblxuLnRyYW5zLW1vZGFsIC5tb2RhbC1jb250ZW50IC5tb2RhbC1mb290ZXIge1xuICBib3JkZXI6IDBweDtcbn1cblxuLm1vZGFsLWZvb3Rlci50ZXh0LWNlbnRlciB7XG4gIHRleHQtYWxpZ246IGNlbnRlciAhaW1wb3J0YW50O1xufVxuXG4ubW9kYWwtdGl0bGUgLmZhIHtcbiAgbWFyZ2luLXJpZ2h0OiA1cHg7XG59XG5cbi5tb2RhbC52ZXJ0LWNlbnRlciB7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbn1cblxuQG1lZGlhIHNjcmVlbiBhbmQgKG1pbi13aWR0aDogNzY4cHgpIHtcbiAgLm1vZGFsLnZlcnQtY2VudGVyOmJlZm9yZSB7XG4gICAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICAgIHZlcnRpY2FsLWFsaWduOiBtaWRkbGU7XG4gICAgY29udGVudDogXCIgXCI7XG4gICAgaGVpZ2h0OiAxMDAlO1xuICB9XG59XG5cbi5tb2RhbC52ZXJ0LWNlbnRlciAubW9kYWwtZGlhbG9nIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICB0ZXh0LWFsaWduOiBsZWZ0O1xuICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlO1xufVxuXG4ubW9kYWwudmVydC10b3Age1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG59XG5cbkBtZWRpYSBzY3JlZW4gYW5kIChtaW4td2lkdGg6IDc2OHB4KSB7XG4gIC5tb2RhbC52ZXJ0LXRvcDpiZWZvcmUge1xuICAgIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgICB2ZXJ0aWNhbC1hbGlnbjogbWlkZGxlO1xuICAgIGNvbnRlbnQ6IFwiIFwiO1xuICAgIGhlaWdodDogMTAwJTtcbiAgfVxufVxuXG4ubW9kYWwudmVydC10b3AgLm1vZGFsLWRpYWxvZyB7XG4gIGRpc3BsYXk6IGlubGluZS1ibG9jaztcbiAgdGV4dC1hbGlnbjogbGVmdDtcbiAgdmVydGljYWwtYWxpZ246IHRvcDtcbiAgbWFyZ2luLXRvcDogMDtcbn1cblxuLm1vZGFsLnZlcnQtdG9wIC5tb2RhbC1jb250ZW50IHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMDtcbiAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDA7XG4gIGJvcmRlci10b3A6IDBweDtcbn1cblxuLm1vZGFsLnZlcnQtYm90dG9tIHtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xufVxuXG5AbWVkaWEgc2NyZWVuIGFuZCAobWluLXdpZHRoOiA3NjhweCkge1xuICAubW9kYWwudmVydC1ib3R0b206YmVmb3JlIHtcbiAgICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gICAgdmVydGljYWwtYWxpZ246IG1pZGRsZTtcbiAgICBjb250ZW50OiBcIiBcIjtcbiAgICBoZWlnaHQ6IDEwMCU7XG4gIH1cbn1cblxuLm1vZGFsLnZlcnQtYm90dG9tIC5tb2RhbC1kaWFsb2cge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG4gIHRleHQtYWxpZ246IGxlZnQ7XG4gIHZlcnRpY2FsLWFsaWduOiBib3R0b207XG4gIG1hcmdpbi1ib3R0b206IDA7XG59XG5cbi5tb2RhbC52ZXJ0LWJvdHRvbSAubW9kYWwtY29udGVudCB7XG4gIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDA7XG4gIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAwO1xuICBib3JkZXItYm90dG9tOiAwcHg7XG59XG5cbi5tb2RhbC5tb2RhbC1mdWxsLXNjcmVlbiAubW9kYWwtZGlhbG9nIHtcbiAgd2lkdGg6IDEwMCU7XG4gIGhlaWdodDogMTAwJTtcbiAgbWFyZ2luLXRvcDogMDtcbn1cblxuLm1vZGFsLm1vZGFsLWZ1bGwtc2NyZWVuIC5tb2RhbC1jb250ZW50IHtcbiAgaGVpZ2h0OiAxMDAlO1xuICBib3JkZXI6IDA7XG4gIGJvcmRlci1yYWRpdXM6IDA7XG59XG5cbi5pemlNb2RhbCAuaXppTW9kYWwtaGVhZGVyLXN1YnRpdGxlLCAuaXppTW9kYWwgLml6aU1vZGFsLWhlYWRlci10aXRsZSB7XG4gIGZvbnQtZmFtaWx5OiBcIlBvcHBpbnNcIiwgc2Fucy1zZXJpZjtcbiAgY2xlYXI6IG5vbmU7XG59XG5cbi5pemlNb2RhbC13cmFwIHtcbiAgLyogcGFkZGluZzogMTVweDsgKi9cbn1cblxuLml6aU1vZGFsIC5pemlNb2RhbC1oZWFkZXIge1xuICBiYWNrZ3JvdW5kOiAjMzQ5OGRiO1xufVxuXG4uaXppTW9kYWwgLml6aU1vZGFsLWhlYWRlciAuZmEge1xuICBmb250LXNpemU6IDMwcHg7XG59XG5cbi5zd2VldC1hbGVydCB7XG4gIGZvbnQtZmFtaWx5OiBcIlBvcHBpbnNcIiwgc2Fucy1zZXJpZjtcbn1cblxuLnN3ZWV0LWFsZXJ0IGgyIHtcbiAgZm9udC1mYW1pbHk6IFwiUG9wcGluc1wiLCBzYW5zLXNlcmlmO1xufVxuXG4uc3dlZXQtYWxlcnQgaW5wdXQge1xuICBkaXNwbGF5OiBub25lO1xufVxuXG4uc3dlZXQtYWxlcnQgZmllbGRzZXQge1xuICBwYWRkaW5nOiAwO1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIERBU0hCT0FSRCBTVEFUU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmRhc2hib2FyZC1zdGF0IHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6IDMwcHggMTVweDtcbiAgdGV4dC1hbGlnbjogcmlnaHQ7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgYm94LXNoYWRvdzogMCAxcHggMnB4IHJnYmEoMCwgMCwgMCwgMC4xKTtcbiAgYm9yZGVyLXJhZGl1czogNHB4O1xufVxuXG4uZGFzaGJvYXJkLXN0YXQgLm51bWJlciB7XG4gIGZvbnQtc2l6ZTogMjhweDtcbiAgZGlzcGxheTogYmxvY2s7XG59XG5cbi5kYXNoYm9hcmQtc3RhdCAuYmctaWNvbiB7XG4gIHBvc2l0aW9uOiBhYnNvbHV0ZTtcbiAgZm9udC1zaXplOiA4MHB4O1xuICBvcGFjaXR5OiAwLjQ7XG4gIGxlZnQ6IDA7XG4gIGJvdHRvbTogMDtcbn1cblxuLmRhc2hib2FyZC1zdGF0OmhvdmVyIHtcbiAgYmFja2dyb3VuZDogIzI5MjkyOSAhaW1wb3J0YW50O1xufVxuXG4uZGFzaGJvYXJkLXN0YXQtMiB7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBib3gtc2hhZG93OiAwcHggMXB4IDJweCByZ2JhKDAsIDAsIDAsIDAuMSk7XG4gIGJvcmRlcjogMXB4IHNvbGlkICNlNWU1ZTU7XG4gIGJvcmRlci1yYWRpdXM6IDRweDtcbn1cblxuLmRhc2hib2FyZC1zdGF0LTIgLnN0YXQtY29udGVudCB7XG4gIHBhZGRpbmc6IDIwcHggMTVweCAxNXB4O1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cblxuLmRhc2hib2FyZC1zdGF0LTIgLm51bWJlciB7XG4gIGZvbnQtc2l6ZTogMjhweDtcbiAgZGlzcGxheTogYmxvY2s7XG59XG5cbi5kYXNoYm9hcmQtc3RhdC0yIC5zdGF0LWZvb3RlciB7XG4gIGJhY2tncm91bmQ6ICNmZmY7XG4gIGNvbG9yOiAjMjkyOTI5O1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIGRpc3BsYXk6IGJsb2NrO1xuICBwYWRkaW5nOiA4cHg7XG4gIGZvbnQtc2l6ZTogOTAlO1xufVxuXG4uZGFzaGJvYXJkLXN0YXQtMjpob3ZlciB7XG4gIGJhY2tncm91bmQ6ICMyOTI5MjkgIWltcG9ydGFudDtcbn1cblxuQG1lZGlhIChtYXgtd2lkdGg6IDc2OHB4KSB7XG4gIC5kYXNoYm9hcmQtc3RhdCB7XG4gICAgbWFyZ2luLWJvdHRvbTogMTBweDtcbiAgfVxuICAuZGFzaGJvYXJkLXN0YXQtMiB7XG4gICAgbWFyZ2luLWJvdHRvbTogMTBweDtcbiAgfVxufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIE5PVElGSUNBVElPTlNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi50b2FzdC1zdWNjZXNzIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI3YWU2MDtcbn1cblxuLnRvYXN0LWVycm9yIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogI2U3NGMzYztcbn1cblxuLnRvYXN0LXdhcm5pbmcge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjM5YzEyO1xufVxuXG4udG9hc3QtaW5mbyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG59XG5cbiN0b2FzdC1jb250YWluZXIgPiBkaXYge1xuICBib3JkZXItcmFkaXVzOiA0cHg7XG4gIGJveC1zaGFkb3c6IDAgMnB4IDVweCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xuICBvcGFjaXR5OiAwLjk1O1xufVxuXG4jdG9hc3QtY29udGFpbmVyID4gZGl2OmhvdmVyIHtcbiAgYm94LXNoYWRvdzogMCAycHggNXB4IHJnYmEoMCwgMCwgMCwgMC4yKTtcbn1cblxuLnVpLXBub3RpZnkgLmFsZXJ0LXdhcm5pbmcge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjM5YzEyO1xuICBib3JkZXItY29sb3I6ICNmMzljMTI7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4udWktcG5vdGlmeSAuYWxlcnQtaW5mbyB7XG4gIGJhY2tncm91bmQtY29sb3I6ICM1YmMwZGU7XG4gIGJvcmRlci1jb2xvcjogIzViYzBkZTtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi51aS1wbm90aWZ5IC5hbGVydC1zdWNjZXNzIHtcbiAgYmFja2dyb3VuZC1jb2xvcjogIzI3YWU2MDtcbiAgYm9yZGVyLWNvbG9yOiAjMjdhZTYwO1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLnVpLXBub3RpZnkgLmFsZXJ0LWRhbmdlciB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNlNzRjM2M7XG4gIGJvcmRlci1jb2xvcjogI2U3NGMzYztcbiAgY29sb3I6ICNmZmY7XG59XG5cbi51aS1wbm90aWZ5IC5hbGVydCBoNCB7XG4gIGNsZWFyOiBub25lO1xufVxuXG4udWktcG5vdGlmeSAudWktcG5vdGlmeS1pY29uLCAudWktcG5vdGlmeSAudWktcG5vdGlmeS1pY29uIHNwYW4ge1xuICBtYXJnaW4tdG9wOiA1cHg7XG4gIG1hcmdpbi1yaWdodDogNXB4O1xufVxuXG4udWktcG5vdGlmeSAudWktcG5vdGlmeS1pY29uLmZhbHNlLCAudWktcG5vdGlmeSAudWktcG5vdGlmeS1pY29uIHNwYW4uZmFsc2Uge1xuICBtYXJnaW46IDA7XG59XG5cbi51aS1wbm90aWZ5IC51aS1wbm90aWZ5LWNsb3NlciwgLnVpLXBub3RpZnkgLnVpLXBub3RpZnktc3RpY2tlciB7XG4gIG1hcmdpbi10b3A6IDVweDtcbiAgbWFyZ2luLWxlZnQ6IDVweDtcbn1cblxuLnVpLXBub3RpZnkgLnVpLXBub3RpZnktY2xvc2VyOmZvY3VzLCAudWktcG5vdGlmeSAudWktcG5vdGlmeS1zdGlja2VyOmZvY3VzIHtcbiAgb3V0bGluZTogMDtcbn1cblxuLnVpLXBub3RpZnkuYWxlcnQtbGVmdC1pY29uIC5hbGVydC1pbmZvIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjhhMWM1O1xufVxuXG4udWktcG5vdGlmeS5hbGVydC1sZWZ0LWljb24gLmFsZXJ0LXdhcm5pbmcge1xuICBib3JkZXItY29sb3I6ICNiMDZmMDk7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LWxlZnQtaWNvbiAuYWxlcnQtc3VjY2VzcyB7XG4gIGJvcmRlci1jb2xvcjogIzE5NzAzZTtcbn1cblxuLnVpLXBub3RpZnkuYWxlcnQtbGVmdC1pY29uIC5hbGVydC1kYW5nZXIge1xuICBib3JkZXItY29sb3I6ICNiZjI3MTg7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LWxlZnQtaWNvbiAudWktcG5vdGlmeS1jb250YWluZXIge1xuICBib3JkZXItbGVmdC13aWR0aDogNTBweDtcbn1cblxuLnVpLXBub3RpZnkuYWxlcnQtbGVmdC1pY29uOmFmdGVyIHtcbiAgbGVmdDogMDtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDUwJTtcbiAgd2lkdGg6IDUwcHg7XG4gIGZvbnQ6IG5vcm1hbCBub3JtYWwgbm9ybWFsIDE0cHgvMSBGb250QXdlc29tZTtcbiAgY29udGVudDogXCJcXGYwNzFcIjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBmb250LXNpemU6IDE4cHg7XG4gIG1hcmdpbi10b3A6IC05cHg7XG4gIGxpbmUtaGVpZ2h0OiAxO1xuICBjb2xvcjogI2ZmZjtcbiAgLXdlYmtpdC1mb250LXNtb290aGluZzogYW50aWFsaWFzZWQ7XG4gIC1tb3otb3N4LWZvbnQtc21vb3RoaW5nOiBncmF5c2NhbGU7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LXJpZ2h0LWljb24gLmFsZXJ0LWluZm8ge1xuICBib3JkZXItY29sb3I6ICMyOGExYzU7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LXJpZ2h0LWljb24gLmFsZXJ0LXdhcm5pbmcge1xuICBib3JkZXItY29sb3I6ICNiMDZmMDk7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LXJpZ2h0LWljb24gLmFsZXJ0LXN1Y2Nlc3Mge1xuICBib3JkZXItY29sb3I6ICMxOTcwM2U7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LXJpZ2h0LWljb24gLmFsZXJ0LWRhbmdlciB7XG4gIGJvcmRlci1jb2xvcjogI2JmMjcxODtcbn1cblxuLnVpLXBub3RpZnkuYWxlcnQtcmlnaHQtaWNvbiAudWktcG5vdGlmeS1jb250YWluZXIge1xuICBib3JkZXItcmlnaHQtd2lkdGg6IDUwcHg7XG59XG5cbi51aS1wbm90aWZ5LmFsZXJ0LXJpZ2h0LWljb246YWZ0ZXIge1xuICByaWdodDogMDtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDUwJTtcbiAgd2lkdGg6IDUwcHg7XG4gIGZvbnQ6IG5vcm1hbCBub3JtYWwgbm9ybWFsIDE0cHgvMSBGb250QXdlc29tZTtcbiAgY29udGVudDogXCJcXGYwNzFcIjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBmb250LXNpemU6IDE4cHg7XG4gIG1hcmdpbi10b3A6IC05cHg7XG4gIGxpbmUtaGVpZ2h0OiAxO1xuICBjb2xvcjogI2ZmZjtcbiAgLXdlYmtpdC1mb250LXNtb290aGluZzogYW50aWFsaWFzZWQ7XG4gIC1tb3otb3N4LWZvbnQtc21vb3RoaW5nOiBncmF5c2NhbGU7XG59XG5cbi51aS1wbm90aWZ5IC51aS1wbm90aWZ5LXNoYWRvdyB7XG4gIGJveC1zaGFkb3c6IDAgMnB4IDVweCByZ2JhKDAsIDAsIDAsIDAuMTUpO1xufVxuXG4ubGVmdC1pY29uLWFsZXJ0IHtcbiAgYm9yZGVyOiAxcHggc29saWQgI2YyZjJmMjtcbiAgYm9yZGVyLWxlZnQtd2lkdGg6IDUwcHg7XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbn1cblxuLmxlZnQtaWNvbi1hbGVydDphZnRlciB7XG4gIGxlZnQ6IC01MHB4O1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIHRvcDogNTAlO1xuICB3aWR0aDogNTBweDtcbiAgZm9udDogbm9ybWFsIG5vcm1hbCBub3JtYWwgMTRweC8xIEZvbnRBd2Vzb21lO1xuICBjb250ZW50OiBcIlxcZjA3MVwiO1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG4gIGZvbnQtc2l6ZTogMThweDtcbiAgbWFyZ2luLXRvcDogLTlweDtcbiAgbGluZS1oZWlnaHQ6IDE7XG4gIGNvbG9yOiAjZmZmO1xuICAtd2Via2l0LWZvbnQtc21vb3RoaW5nOiBhbnRpYWxpYXNlZDtcbiAgLW1vei1vc3gtZm9udC1zbW9vdGhpbmc6IGdyYXlzY2FsZTtcbn1cblxuLmxlZnQtaWNvbi1hbGVydC5hbGVydC1pbmZvIHtcbiAgYm9yZGVyLWNvbG9yOiAjMjhhMWM1ICFpbXBvcnRhbnQ7XG59XG5cbi5sZWZ0LWljb24tYWxlcnQuYWxlcnQtaW5mbzphZnRlciB7XG4gIGNvbnRlbnQ6IFwiXFxmMTI5XCI7XG59XG5cbi5sZWZ0LWljb24tYWxlcnQuYWxlcnQtd2FybmluZyB7XG4gIGJvcmRlci1jb2xvcjogI2IwNmYwOSAhaW1wb3J0YW50O1xufVxuXG4ubGVmdC1pY29uLWFsZXJ0LmFsZXJ0LXdhcm5pbmc6YWZ0ZXIge1xuICBjb250ZW50OiBcIlxcZjEyOVwiO1xufVxuXG4ubGVmdC1pY29uLWFsZXJ0LmFsZXJ0LXN1Y2Nlc3Mge1xuICBib3JkZXItY29sb3I6ICMxOTcwM2UgIWltcG9ydGFudDtcbn1cblxuLmxlZnQtaWNvbi1hbGVydC5hbGVydC1zdWNjZXNzOmFmdGVyIHtcbiAgY29udGVudDogXCJcXGYwMGNcIjtcbn1cblxuLmxlZnQtaWNvbi1hbGVydC5hbGVydC1kYW5nZXIge1xuICBib3JkZXItY29sb3I6ICNiZjI3MTggIWltcG9ydGFudDtcbn1cblxuLmxlZnQtaWNvbi1hbGVydC5hbGVydC1kYW5nZXI6YWZ0ZXIge1xuICBjb250ZW50OiBcIlxcZjAwZFwiO1xufVxuXG4ucmlnaHQtaWNvbi1hbGVydCB7XG4gIGJvcmRlcjogMXB4IHNvbGlkICNmMmYyZjI7XG4gIGJvcmRlci1yaWdodC13aWR0aDogNTBweDtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG4ucmlnaHQtaWNvbi1hbGVydDphZnRlciB7XG4gIHJpZ2h0OiAtNTBweDtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICB0b3A6IDUwJTtcbiAgd2lkdGg6IDUwcHg7XG4gIGZvbnQ6IG5vcm1hbCBub3JtYWwgbm9ybWFsIDE0cHgvMSBGb250QXdlc29tZTtcbiAgY29udGVudDogXCJcXGYwNzFcIjtcbiAgdGV4dC1hbGlnbjogY2VudGVyO1xuICBmb250LXNpemU6IDE4cHg7XG4gIG1hcmdpbi10b3A6IC05cHg7XG4gIGxpbmUtaGVpZ2h0OiAxO1xuICBjb2xvcjogI2ZmZjtcbiAgLXdlYmtpdC1mb250LXNtb290aGluZzogYW50aWFsaWFzZWQ7XG4gIC1tb3otb3N4LWZvbnQtc21vb3RoaW5nOiBncmF5c2NhbGU7XG59XG5cbi5yaWdodC1pY29uLWFsZXJ0LmFsZXJ0LWluZm8ge1xuICBib3JkZXItY29sb3I6ICMyOGExYzUgIWltcG9ydGFudDtcbn1cblxuLnJpZ2h0LWljb24tYWxlcnQuYWxlcnQtaW5mbzphZnRlciB7XG4gIGNvbnRlbnQ6IFwiXFxmMTI5XCI7XG59XG5cbi5yaWdodC1pY29uLWFsZXJ0LmFsZXJ0LXdhcm5pbmcge1xuICBib3JkZXItY29sb3I6ICNiMDZmMDkgIWltcG9ydGFudDtcbn1cblxuLnJpZ2h0LWljb24tYWxlcnQuYWxlcnQtd2FybmluZzphZnRlciB7XG4gIGNvbnRlbnQ6IFwiXFxmMTI5XCI7XG59XG5cbi5yaWdodC1pY29uLWFsZXJ0LmFsZXJ0LXN1Y2Nlc3Mge1xuICBib3JkZXItY29sb3I6ICMxOTcwM2UgIWltcG9ydGFudDtcbn1cblxuLnJpZ2h0LWljb24tYWxlcnQuYWxlcnQtc3VjY2VzczphZnRlciB7XG4gIGNvbnRlbnQ6IFwiXFxmMDBjXCI7XG59XG5cbi5yaWdodC1pY29uLWFsZXJ0LmFsZXJ0LWRhbmdlciB7XG4gIGJvcmRlci1jb2xvcjogI2JmMjcxOCAhaW1wb3J0YW50O1xufVxuXG4ucmlnaHQtaWNvbi1hbGVydC5hbGVydC1kYW5nZXI6YWZ0ZXIge1xuICBjb250ZW50OiBcIlxcZjAwZFwiO1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIFBBR0lOQVRJT05cbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGEsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6aG92ZXIsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6Zm9jdXMsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW4sIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46aG92ZXIsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46Zm9jdXMge1xuICBjb2xvcjogI2ZmZiAhaW1wb3J0YW50O1xufVxuXG4ucGFnaW5hdGlvbi5yb3VuZGVkLWNvcm5lcnMgbGk6Zmlyc3QtY2hpbGQgPiBhLCAucGFnaW5hdGlvbi5yb3VuZGVkLWNvcm5lcnMgbGk6Zmlyc3QtY2hpbGQgPiBzcGFuIHtcbiAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMjBweDtcbiAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogMjBweDtcbn1cblxuLnBhZ2luYXRpb24ucm91bmRlZC1jb3JuZXJzIGxpOmxhc3QtY2hpbGQgPiBhLCAucGFnaW5hdGlvbi5yb3VuZGVkLWNvcm5lcnMgbGk6bGFzdC1jaGlsZCA+IHNwYW4ge1xuICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogMjBweDtcbiAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDIwcHg7XG59XG5cbi5wYWdpbmF0aW9uLmJvcmRlcmxlc3MgbGkgPiBhLCAucGFnaW5hdGlvbi5ib3JkZXJsZXNzIGxpID4gc3BhbiB7XG4gIGJvcmRlcjogMHB4O1xufVxuXG4ucGFnZXIgLmRpc2FibGVkID4gYSwgLnBhZ2VyIC5kaXNhYmxlZCA+IGE6aG92ZXIsIC5wYWdlciAuZGlzYWJsZWQgPiBhOmZvY3VzLCAucGFnZXIgLmRpc2FibGVkID4gc3BhbiB7XG4gIG9wYWNpdHk6IDAuNTtcbn1cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBGT1JNU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmZvcm0tZ3JvdXAubGVmdC1pY29uIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG4uZm9ybS1ncm91cC5sZWZ0LWljb24gLmZhIHtcbiAgbGluZS1oZWlnaHQ6IDM0cHg7XG59XG5cbi5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZm9ybS1jb250cm9sIHtcbiAgcGFkZGluZy1sZWZ0OiA0Mi41cHg7XG59XG5cbi5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZm9ybS1sZWZ0LWljb24ge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIGxlZnQ6IDE1cHg7XG4gIHRvcDogMjVweDtcbn1cblxuLmZvcm0tZ3JvdXAubGVmdC1pY29uIC5mb3JtLWxlZnQtaWNvbi5pY29uLWxnIHtcbiAgdG9wOiAzMHB4O1xufVxuXG4uZm9ybS1ncm91cC5sZWZ0LWljb24gLmZvcm0tbGVmdC1pY29uLmljb24tc20ge1xuICB0b3A6IDIycHg7XG59XG5cbi5mb3JtLWdyb3VwLmhhcy1mZWVkYmFjayAuZmEge1xuICBsaW5lLWhlaWdodDogMzRweDtcbn1cblxuLmZvcm0tZ3JvdXAgaW5wdXQ6Zm9jdXMsIC5mb3JtLWdyb3VwIHRleHRhcmVhOmZvY3VzLCAuZm9ybS1ncm91cCBzZWxlY3Q6Zm9jdXMge1xuICBib3gtc2hhZG93OiBub25lO1xuICBib3JkZXItY29sb3I6ICMyOTI5Mjk7XG59XG5cbi5mb3JtLWhvcml6b250YWwgLmZvcm0tZ3JvdXAubGVmdC1pY29uIHtcbiAgcG9zaXRpb246IHJlbGF0aXZlO1xufVxuXG4uZm9ybS1ob3Jpem9udGFsIC5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZmEsIC5mb3JtLWhvcml6b250YWwgLmZvcm0tZ3JvdXAubGVmdC1pY29uIC5nbHlwaGljb24ge1xuICBsaW5lLWhlaWdodDogMzRweDtcbn1cblxuLmZvcm0taG9yaXpvbnRhbCAuZm9ybS1ncm91cC5sZWZ0LWljb24gLmZvcm0tY29udHJvbCB7XG4gIHBhZGRpbmctbGVmdDogNDIuNXB4O1xufVxuXG4uZm9ybS1ob3Jpem9udGFsIC5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZm9ybS1sZWZ0LWljb24ge1xuICBwb3NpdGlvbjogYWJzb2x1dGU7XG4gIGxlZnQ6IDMwcHg7XG4gIHRvcDogMHB4O1xufVxuXG4uZm9ybS1ob3Jpem9udGFsIC5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZm9ybS1sZWZ0LWljb24uaWNvbi1sZyB7XG4gIHRvcDogNXB4O1xufVxuXG4uZm9ybS1ob3Jpem9udGFsIC5mb3JtLWdyb3VwLmxlZnQtaWNvbiAuZm9ybS1sZWZ0LWljb24uaWNvbi1zbSB7XG4gIHRvcDogMHB4O1xufVxuXG4uZm9ybS1ncm91cCBsYWJlbCB7XG4gIGZvbnQtc2l6ZTogOTUlO1xufVxuXG4uZm9ybS1ncm91cCAuaGVscC1ibG9jayB7XG4gIGZvbnQtc2l6ZTogODQlO1xuICBmb250LXN0eWxlOiBpdGFsaWM7XG4gIG1hcmdpbi10b3A6IC01cHg7XG59XG5cbi5pbnB1dC1ncm91cCB7XG4gIGZvbnQtc2l6ZTogMTRweDtcbiAgbWFyZ2luLWJvdHRvbTogMC41NDY4NzVlbTtcbn1cblxuLmZvcm0taG9yaXpvbnRhbCAuY29udHJvbC1sYWJlbC50ZXh0LWxlZnQge1xuICB0ZXh0LWFsaWduOiBsZWZ0O1xufVxuXG4ucmFkaW8tbGFiZWwge1xuICBkaXNwbGF5OiBpbmxpbmUtYmxvY2s7XG59XG5cbi5zZWxlY3QyLWNvbnRhaW5lciAuc2VsZWN0Mi1zZWxlY3Rpb24tLXNpbmdsZSB7XG4gIGhlaWdodDogMzRweDtcbn1cblxuLnNlbGVjdDItY29udGFpbmVyLS1kZWZhdWx0IC5zZWxlY3QyLXNlbGVjdGlvbi0tc2luZ2xlIC5zZWxlY3QyLXNlbGVjdGlvbl9fcmVuZGVyZWQge1xuICBsaW5lLWhlaWdodDogMzRweDtcbn1cblxuLnNlbGVjdDItY29udGFpbmVyLS1kZWZhdWx0IC5zZWxlY3QyLXNlbGVjdGlvbi0tc2luZ2xlIC5zZWxlY3QyLXNlbGVjdGlvbl9fYXJyb3cge1xuICBoZWlnaHQ6IDM0cHg7XG59XG5cbi5zZWxlY3QyLXJlc3VsdHMge1xuICBmb250LXNpemU6IDkwJTtcbn1cblxuLnNlbGVjdDItY29udGFpbmVyLS1kZWZhdWx0IC5zZWxlY3QyLXNlYXJjaC0taW5saW5lIC5zZWxlY3QyLXNlYXJjaF9fZmllbGQge1xuICBtYXJnaW4tdG9wOiAwO1xuICBtYXJnaW4tYm90dG9tOiAwO1xufVxuXG5kaXYudGFnc2lucHV0IHNwYW4udGFnIHtcbiAgYm9yZGVyLXdpZHRoOiAwO1xuICBiYWNrZ3JvdW5kOiAjNGFhM2RmO1xuICBjb2xvcjogIzE2NTI3YTtcbiAgcGFkZGluZzogMnB4IDEwcHg7XG59XG5cbmRpdi50YWdzaW5wdXQgc3Bhbi50YWcgYSB7XG4gIGNvbG9yOiAjMTk2MDkwO1xufVxuXG4uZm9ybS1saW5rIHtcbiAgZGlzcGxheTogaW5saW5lLWJsb2NrO1xuICBtYXJnaW4tdG9wOiAxNXB4O1xuICBjb2xvcjogIzc2NzY3Njtcbn1cblxuLm9wLWNoZWNrLmNoZWNrYm94IGxhYmVsLCAub3AtY2hlY2sucmFkaW8gbGFiZWwge1xuICBwYWRkaW5nLWxlZnQ6IDA7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgRVJST1IgUEFHRVNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5lcnJvci1ib3gge1xuICB0ZXh0LWFsaWduOiBjZW50ZXI7XG59XG5cbi5lcnJvci1ib3ggLmVycm9yLWljb24ge1xuICBmb250LXNpemU6IDQwcHg7XG4gIGNvbG9yOiAjZTc0YzNjO1xufVxuXG4uZXJyb3ItYm94IC5lcnJvci10aXRsZSB7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG4gIGZvbnQtc2l6ZTogNjBweDtcbn1cblxuLmVycm9yLWJveCAuc3ViLXRpdGxlIHtcbiAgZm9udC1zaXplOiAxOHB4O1xuICBjb2xvcjogIzc2NzY3Njtcbn1cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBQUklDSU5HXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4ucHJpY2luZy1ib3gge1xuICBiYWNrZ3JvdW5kOiAjZmZmO1xuICBib3gtc2hhZG93OiAwIDJweCAzcHggcmdiYSgwLCAwLCAwLCAwLjE1KTtcbiAgYm9yZGVyLXJhZGl1czogNHB4O1xufVxuXG4ucHJpY2luZy1ib3ggLnByaWNpbmctaGVhZCB7XG4gIGJhY2tncm91bmQtY29sb3I6ICNmMmYyZjI7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgYm9yZGVyLXRvcDogM3B4IHNvbGlkICMzNDk4ZGI7XG4gIHBhZGRpbmc6IDEuNjE4ZW07XG4gIHBvc2l0aW9uOiByZWxhdGl2ZTtcbiAgb3ZlcmZsb3c6IGhpZGRlbjtcbiAgYm9yZGVyLXJhZGl1czogNHB4IDRweCAwIDA7XG59XG5cbi5wcmljaW5nLWJveCAucHJpY2luZy1oZWFkIGgxLCAucHJpY2luZy1ib3ggLnByaWNpbmctaGVhZCBoMiwgLnByaWNpbmctYm94IC5wcmljaW5nLWhlYWQgaDMsIC5wcmljaW5nLWJveCAucHJpY2luZy1oZWFkIGg0LCAucHJpY2luZy1ib3ggLnByaWNpbmctaGVhZCBoNSwgLnByaWNpbmctYm94IC5wcmljaW5nLWhlYWQgaDYge1xuICBtYXJnaW46IDA7XG59XG5cbi5wcmljaW5nLWJveCAucHJpY2luZy1oZWFkIC5zdHJpa2VkIHtcbiAgdGV4dC1kZWNvcmF0aW9uOiBsaW5lLXRocm91Z2g7XG59XG5cbi5wcmljaW5nLWJveCAucHJpY2luZy1oZWFkIC5iZy1pY29uIHtcbiAgcG9zaXRpb246IGFic29sdXRlO1xuICBib3R0b206IC0yMHB4O1xuICBsZWZ0OiAtMjBweDtcbiAgZm9udC1zaXplOiAxMjBweDtcbiAgY29sb3I6ICM5OTk5OTk7XG4gIG9wYWNpdHk6IDAuMjtcbn1cblxuLnByaWNpbmctYm94IC5wcmljaW5nLWJvZHkge1xuICBwYWRkaW5nOiAxZW07XG59XG5cbi5wcmljaW5nLWJveCAucHJpY2luZy1ib2R5IHVsIGxpIHtcbiAgbGluZS1oZWlnaHQ6IDIuMjU7XG59XG5cbi5wcmljaW5nLWJveCAucHJpY2luZy1ib2R5IHVsIGxpIC5pY29uIHtcbiAgZmxvYXQ6IHJpZ2h0O1xufVxuXG4ucHJpY2luZy1ib3ggLnByaWNpbmctZm9vdCBhIHtcbiAgZGlzcGxheTogYmxvY2s7XG4gIHBhZGRpbmc6IDFlbTtcbiAgYmFja2dyb3VuZDogI2YyZjJmMjtcbiAgY29sb3I6ICMyOTI5Mjk7XG4gIHRleHQtYWxpZ246IGNlbnRlcjtcbiAgdGV4dC10cmFuc2Zvcm06IHVwcGVyY2FzZTtcbiAgbGV0dGVyLXNwYWNpbmc6IDFweDtcbiAgYm9yZGVyLXJhZGl1czogMCAwIDRweCA0cHg7XG4gIC13ZWJraXQtdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIC1tb3otdHJhbnNpdGlvbjogYWxsIDAuNHMgZWFzZS1pbi1vdXQ7XG4gIHRyYW5zaXRpb246IGFsbCAwLjRzIGVhc2UtaW4tb3V0O1xufVxuXG4ucHJpY2luZy1ib3ggLnByaWNpbmctZm9vdCBhOmhvdmVyIHtcbiAgYmFja2dyb3VuZDogIzM0OThkYjtcbiAgY29sb3I6ICNmZmYgIWltcG9ydGFudDtcbn1cblxuLnByaWNpbmctYm94LnBvcHVsYXIgLnByaWNpbmctaGVhZCB7XG4gIGJhY2tncm91bmQ6ICM0OTQ5NDk7XG4gIGNvbG9yOiAjZmZmO1xufVxuXG4ucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGgxLCAucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGgyLCAucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGgzLCAucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGg0LCAucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGg1LCAucHJpY2luZy1ib3gucG9wdWxhciAucHJpY2luZy1oZWFkIGg2IHtcbiAgY29sb3I6ICNmZmY7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTE9HSU5cbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5sb2dpbi1iZyB7XG4gIGJhY2tncm91bmQtaW1hZ2U6IHVybChcIi4uL2ltYWdlcy9waG90by0yLmpwZ1wiKTtcbiAgYmFja2dyb3VuZC1zaXplOiBjb3ZlcjtcbiAgYmFja2dyb3VuZC1hdHRhY2htZW50OiBmaXhlZDtcbiAgbWluLWhlaWdodDogMTAwdmg7XG59XG5cbi5sb2dpbi1iZyAubG9naW4tYm94IHtcbiAgYmFja2dyb3VuZDogcmdiYSgyNTUsIDI1NSwgMjU1LCAwLjgpO1xuICBwYWRkaW5nOiAyMHB4O1xuICBtYXJnaW4tdG9wOiAxNTBweDtcbiAgYm9yZGVyLXJhZGl1czogNHB4O1xuICBib3gtc2hhZG93OiAwcHggMXB4IDJweCByZ2JhKDAsIDAsIDAsIDAuMSk7XG59XG5cbi5sb2dpbi1iZy1jb2xvciB7XG4gIG1pbi1oZWlnaHQ6IDEwMHZoO1xufVxuXG4ubG9naW4tYmctY29sb3IgLmxvZ2luLWJveCB7XG4gIGNvbG9yOiAjMjkyOTI5ICFpbXBvcnRhbnQ7XG4gIHBhZGRpbmc6IDIwcHg7XG4gIG1hcmdpbi10b3A6IDEyNXB4O1xuICBib3JkZXItcmFkaXVzOiA0cHg7XG4gIGJveC1zaGFkb3c6IDBweCAxcHggMnB4IHJnYmEoMCwgMCwgMCwgMC4xKTtcbn1cblxuLmxvZ2luLWJnLWNvbG9yIC5sb2dpbi1ib3ggaDEsIC5sb2dpbi1iZy1jb2xvciAubG9naW4tYm94IGgyLCAubG9naW4tYmctY29sb3IgLmxvZ2luLWJveCBoMywgLmxvZ2luLWJnLWNvbG9yIC5sb2dpbi1ib3ggaDQsIC5sb2dpbi1iZy1jb2xvciAubG9naW4tYm94IGg1LCAubG9naW4tYmctY29sb3IgLmxvZ2luLWJveCBoNiB7XG4gIGNvbG9yOiAjMjkyOTI5ICFpbXBvcnRhbnQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgRFJPUFpPTkVcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5kcm9wem9uZSB7XG4gIGJhY2tncm91bmQ6ICNmMmYyZjI7XG4gIGJvcmRlcjogMnB4IGRhc2hlZCAjZDlkOWQ5O1xuICBtaW4taGVpZ2h0OiAyNTBweDtcbn1cblxuLmRyb3B6b25lIC5kei1tZXNzYWdlIHtcbiAgZm9udC1zaXplOiAxNnB4O1xuICBmb250LXdlaWdodDogYm9sZDtcbiAgbWFyZ2luOiA0LjVlbSAwO1xufVxuXG4uZHJvcHpvbmUgLmR6LW1lc3NhZ2UgLm5vdGUge1xuICBmb250LXNpemU6IDEzcHg7XG4gIGZvbnQtd2VpZ2h0OiBub3JtYWw7XG4gIGNvbG9yOiAjNDk0OTQ5O1xuICBtYXJnaW4tdG9wOiAxNXB4O1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIEJPT1RTVFJBUCBTV0lUQ0hcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5ib290c3RyYXAtc3dpdGNoIC5ib290c3RyYXAtc3dpdGNoLWhhbmRsZS1vZmYuYm9vdHN0cmFwLXN3aXRjaC1wcmltYXJ5LCAuYm9vdHN0cmFwLXN3aXRjaCAuYm9vdHN0cmFwLXN3aXRjaC1oYW5kbGUtb24uYm9vdHN0cmFwLXN3aXRjaC1wcmltYXJ5IHtcbiAgYmFja2dyb3VuZDogIzM0OThkYjtcbn1cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBKUVVFUlkgU1RFUFNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi53aXphcmQgPiAuc3RlcHMgLmN1cnJlbnQgYSwgLndpemFyZCA+IC5zdGVwcyAuY3VycmVudCBhOmhvdmVyLCAud2l6YXJkID4gLnN0ZXBzIC5jdXJyZW50IGE6YWN0aXZlIHtcbiAgYmFja2dyb3VuZDogIzM0OThkYjtcbn1cblxuLndpemFyZCA+IC5hY3Rpb25zIGEsIC53aXphcmQgPiAuYWN0aW9ucyBhOmhvdmVyLCAud2l6YXJkID4gLmFjdGlvbnMgYTphY3RpdmUge1xuICBiYWNrZ3JvdW5kOiAjMzQ5OGRiO1xuICBjb2xvcjogI2ZmZjtcbn1cblxuLndpemFyZCA+IC5jb250ZW50IHtcbiAgbWluLWhlaWdodDogMjUwcHg7XG59XG5cbi53aXphcmQgPiAuY29udGVudCA+IC5ib2R5IGxhYmVsLmVycm9yIHtcbiAgY29sb3I6ICNlNzRjM2M7XG4gIGZvbnQtc2l6ZTogOTAlO1xuICBmb250LXdlaWdodDogbm9ybWFsO1xufVxuXG4vKi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tXG4jIERBVEFUQUJMRVNcbi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tKi9cbi5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGEsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6Zm9jdXMsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IGE6aG92ZXIsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW4sIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46Zm9jdXMsIC5wYWdpbmF0aW9uID4gLmFjdGl2ZSA+IHNwYW46aG92ZXIge1xuICBiYWNrZ3JvdW5kLWNvbG9yOiAjMzQ5OGRiO1xuICBib3JkZXItY29sb3I6ICMzNDk4ZGI7XG59XG5cbmRpdi5kYXRhVGFibGVzX3dyYXBwZXIgZGl2LmRhdGFUYWJsZXNfZmlsdGVyIGxhYmVsIHtcbiAgdGV4dC1hbGlnbjogcmlnaHQ7XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTUlTQ0VMTEFORU9VU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xucHJlW2NsYXNzKj1cImxhbmd1YWdlLVwiXSB7XG4gIGJvcmRlci1sZWZ0LXdpZHRoOiAycHg7XG59XG5cbi5zcmMtYnRuIHtcbiAgZmxvYXQ6IHJpZ2h0O1xufVxuXG4uZHJhZ2dhYmxlLWhhbmRsZSB7XG4gIGN1cnNvcjogbW92ZTtcbn1cblxuLnBhbmVsLWhlYWRpbmcgLmRyb3Bkb3duIC5mYS5kcm9wZG93bi10b2dnbGUge1xuICBwYWRkaW5nLXJpZ2h0OiAxNXB4O1xuICBwYWRkaW5nLXRvcDogMTVweDtcbn1cblxuLm1lZGlhLW9iamVjdCB7XG4gIG1hcmdpbi10b3A6IDEwcHg7XG59XG5cbi5tZWRpYS1ib3R0b20ge1xuICBwYWRkaW5nLWJvdHRvbTogMS43NWVtO1xufVxuXG4ub3AtY2hhcnQge1xuICB3aWR0aDogMTAwJTtcbiAgaGVpZ2h0OiA1MDBweDtcbn1cblxuW2NsYXNzXj1cImljaGVja2JveF9saW5lXCJdLmNoZWNrZWQge1xuICBvcGFjaXR5OiAwLjY7XG59XG5cbi5icm93c2VyIHtcbiAgYm9yZGVyOiAycHggc29saWQgI2Q5ZDlkOTtcbiAgYm9yZGVyLXRvcC13aWR0aDogMzBweDtcbiAgd2lkdGg6IDYwJTtcbiAgbWFyZ2luOiBhdXRvO1xuICBib3JkZXItcmFkaXVzOiA2cHg7XG59XG5cbi5icm93c2VyIGlmcmFtZSB7XG4gIGJvcmRlcjogMDtcbiAgd2lkdGg6IDEwMCU7XG59XG5cbi5wb3BvdmVyLmNvbmZpcm1hdGlvbiB7XG4gIG1heC13aWR0aDogMTAwJTtcbn1cblxuLmRyb3Bkb3duIC5kcm9wZG93bi10b2dnbGUge1xuICBjdXJzb3I6IHBvaW50ZXI7XG59XG5cbi5kcm9wZG93biAuaWNvbi1yaWdodCB7XG4gIG1hcmdpbi1sZWZ0OiAxNXB4O1xuICBmbG9hdDogcmlnaHQ7XG4gIG1hcmdpbi10b3A6IDNweDtcbiAgbWFyZ2luLXJpZ2h0OiAwICFpbXBvcnRhbnQ7XG59XG5cbi5zaG93LWdyaWQgW2NsYXNzKj1cImNvbC1cIl0ge1xuICBib3JkZXI6IDFweCBzb2xpZCAjY2NjY2NjO1xuICBwYWRkaW5nLXRvcDogNXB4O1xuICBwYWRkaW5nLWJvdHRvbTogNXB4O1xuICBiYWNrZ3JvdW5kOiAjZDlkOWQ5O1xufVxuIiwiQGNoYXJzZXQgXCJVVEYtOFwiO1xyXG5cclxuLy8vIE91dHB1dHMgdGhlIHNwZWMgYW5kIHByZWZpeGVkIHZlcnNpb25zIG9mIHRoZSBgOjpzZWxlY3Rpb25gIHBzZXVkby1lbGVtZW50LlxyXG4vLy9cclxuLy8vIEBwYXJhbSB7Qm9vbH0gJGN1cnJlbnQtc2VsZWN0b3IgW2ZhbHNlXVxyXG4vLy8gICBJZiBzZXQgdG8gYHRydWVgLCBpdCB0YWtlcyB0aGUgY3VycmVudCBlbGVtZW50IGludG8gY29uc2lkZXJhdGlvbi5cclxuLy8vXHJcbi8vLyBAZXhhbXBsZSBzY3NzIC0gVXNhZ2VcclxuLy8vICAgLmVsZW1lbnQge1xyXG4vLy8gICAgIEBpbmNsdWRlIHNlbGVjdGlvbih0cnVlKSB7XHJcbi8vLyAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZiYjUyO1xyXG4vLy8gICAgIH1cclxuLy8vICAgfVxyXG4vLy9cclxuLy8vIEBleGFtcGxlIGNzcyAtIENTUyBPdXRwdXRcclxuLy8vICAgLmVsZW1lbnQ6Oi1tb3otc2VsZWN0aW9uIHtcclxuLy8vICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZiYjUyO1xyXG4vLy8gICB9XHJcbi8vL1xyXG4vLy8gICAuZWxlbWVudDo6c2VsZWN0aW9uIHtcclxuLy8vICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZmZiYjUyO1xyXG4vLy8gICB9XHJcblxyXG5AbWl4aW4gc2VsZWN0aW9uKCRjdXJyZW50LXNlbGVjdG9yOiBmYWxzZSkge1xyXG4gIEBpZiAkY3VycmVudC1zZWxlY3RvciB7XHJcbiAgICAmOjotbW96LXNlbGVjdGlvbiB7XHJcbiAgICAgIEBjb250ZW50O1xyXG4gICAgfVxyXG5cclxuICAgICY6OnNlbGVjdGlvbiB7XHJcbiAgICAgIEBjb250ZW50O1xyXG4gICAgfVxyXG4gIH0gQGVsc2Uge1xyXG4gICAgOjotbW96LXNlbGVjdGlvbiB7XHJcbiAgICAgIEBjb250ZW50O1xyXG4gICAgfVxyXG5cclxuICAgIDo6c2VsZWN0aW9uIHtcclxuICAgICAgQGNvbnRlbnQ7XHJcbiAgICB9XHJcbiAgfVxyXG59XHJcbiIsIkBjaGFyc2V0IFwiVVRGLThcIjtcblxuLy8vIEEgbWl4aW4gZm9yIGdlbmVyYXRpbmcgdmVuZG9yIHByZWZpeGVzIG9uIG5vbi1zdGFuZGFyZGl6ZWQgcHJvcGVydGllcy5cbi8vL1xuLy8vIEBwYXJhbSB7U3RyaW5nfSAkcHJvcGVydHlcbi8vLyAgIFByb3BlcnR5IHRvIHByZWZpeFxuLy8vXG4vLy8gQHBhcmFtIHsqfSAkdmFsdWVcbi8vLyAgIFZhbHVlIHRvIHVzZVxuLy8vXG4vLy8gQHBhcmFtIHtMaXN0fSAkcHJlZml4ZXNcbi8vLyAgIFByZWZpeGVzIHRvIGRlZmluZVxuLy8vXG4vLy8gQGV4YW1wbGUgc2NzcyAtIFVzYWdlXG4vLy8gICAuZWxlbWVudCB7XG4vLy8gICAgIEBpbmNsdWRlIHByZWZpeGVyKGJvcmRlci1yYWRpdXMsIDEwcHgsIHdlYmtpdCBtcyBzcGVjKTtcbi8vLyAgIH1cbi8vL1xuLy8vIEBleGFtcGxlIGNzcyAtIENTUyBPdXRwdXRcbi8vLyAgIC5lbGVtZW50IHtcbi8vLyAgICAgLXdlYmtpdC1ib3JkZXItcmFkaXVzOiAxMHB4O1xuLy8vICAgICAtbW96LWJvcmRlci1yYWRpdXM6IDEwcHg7XG4vLy8gICAgIGJvcmRlci1yYWRpdXM6IDEwcHg7XG4vLy8gICB9XG4vLy9cbi8vLyBAcmVxdWlyZSB7dmFyaWFibGV9ICRwcmVmaXgtZm9yLXdlYmtpdFxuLy8vIEByZXF1aXJlIHt2YXJpYWJsZX0gJHByZWZpeC1mb3ItbW96aWxsYVxuLy8vIEByZXF1aXJlIHt2YXJpYWJsZX0gJHByZWZpeC1mb3ItbWljcm9zb2Z0XG4vLy8gQHJlcXVpcmUge3ZhcmlhYmxlfSAkcHJlZml4LWZvci1vcGVyYVxuLy8vIEByZXF1aXJlIHt2YXJpYWJsZX0gJHByZWZpeC1mb3Itc3BlY1xuXG5AbWl4aW4gcHJlZml4ZXIoJHByb3BlcnR5LCAkdmFsdWUsICRwcmVmaXhlcykge1xuICBAZWFjaCAkcHJlZml4IGluICRwcmVmaXhlcyB7XG4gICAgQGlmICRwcmVmaXggPT0gd2Via2l0IHtcbiAgICAgIEBpZiAkcHJlZml4LWZvci13ZWJraXQge1xuICAgICAgICAtd2Via2l0LSN7JHByb3BlcnR5fTogJHZhbHVlO1xuICAgICAgfVxuICAgIH0gQGVsc2UgaWYgJHByZWZpeCA9PSBtb3oge1xuICAgICAgQGlmICRwcmVmaXgtZm9yLW1vemlsbGEge1xuICAgICAgICAtbW96LSN7JHByb3BlcnR5fTogJHZhbHVlO1xuICAgICAgfVxuICAgIH0gQGVsc2UgaWYgJHByZWZpeCA9PSBtcyB7XG4gICAgICBAaWYgJHByZWZpeC1mb3ItbWljcm9zb2Z0IHtcbiAgICAgICAgLW1zLSN7JHByb3BlcnR5fTogJHZhbHVlO1xuICAgICAgfVxuICAgIH0gQGVsc2UgaWYgJHByZWZpeCA9PSBvIHtcbiAgICAgIEBpZiAkcHJlZml4LWZvci1vcGVyYSB7XG4gICAgICAgIC1vLSN7JHByb3BlcnR5fTogJHZhbHVlO1xuICAgICAgfVxuICAgIH0gQGVsc2UgaWYgJHByZWZpeCA9PSBzcGVjIHtcbiAgICAgIEBpZiAkcHJlZml4LWZvci1zcGVjIHtcbiAgICAgICAgI3skcHJvcGVydHl9OiAkdmFsdWU7XG4gICAgICB9XG4gICAgfSBAZWxzZSAge1xuICAgICAgQHdhcm4gXCJVbnJlY29nbml6ZWQgcHJlZml4OiAjeyRwcmVmaXh9XCI7XG4gICAgfVxuICB9XG59XG5cbkBtaXhpbiBkaXNhYmxlLXByZWZpeC1mb3ItYWxsKCkge1xuICAkcHJlZml4LWZvci13ZWJraXQ6ICAgIGZhbHNlICFnbG9iYWw7XG4gICRwcmVmaXgtZm9yLW1vemlsbGE6ICAgZmFsc2UgIWdsb2JhbDtcbiAgJHByZWZpeC1mb3ItbWljcm9zb2Z0OiBmYWxzZSAhZ2xvYmFsO1xuICAkcHJlZml4LWZvci1vcGVyYTogICAgIGZhbHNlICFnbG9iYWw7XG4gICRwcmVmaXgtZm9yLXNwZWM6ICAgICAgZmFsc2UgIWdsb2JhbDtcbn1cbiIsIi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgTUlYSU4gVE8gQ09SUkVDVCBOQVZCQVIgV0lUSCBPVVIgQ09MT1IgUEFMRVRURVxuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuQG1peGluIGNvbG9yLXBhbGV0dGUoJGJnY29sb3IsICR0eHRjb2xvcjogJHdoaXRlLWNvbG9yKSB7XG4gICAgYmFja2dyb3VuZC1jb2xvcjogJGJnY29sb3I7XG4gICAgYm9yZGVyLWNvbG9yOiAkYmdjb2xvcjtcbiAgICBjb2xvcjogJHR4dGNvbG9yICFpbXBvcnRhbnQ7XG4gICAgaDEsIGgyLCBoMywgaDQsIGg1LCBoNiB7XG4gICAgICAgIGNvbG9yOiAkdHh0Y29sb3I7XG4gICAgfVxuICAgIC5uYXYgLm9wZW4+YSwgLm5hdiAub3Blbj5hOmZvY3VzLCAubmF2IC5vcGVuPmE6aG92ZXIge1xuICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiBkYXJrZW4oJGJnY29sb3IsIDUlKTtcbiAgICAgICAgY29sb3I6ICR0eHRjb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAubmF2PmxpPmE6Zm9jdXMsIC5uYXY+bGk+YTpob3ZlciB7XG4gICAgICAgIGJhY2tncm91bmQtY29sb3I6IGRhcmtlbigkYmdjb2xvciwgNSUpO1xuICAgICAgICBjb2xvcjogJHR4dGNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgIC5uYXZiYXItbmF2PmxpPmEge1xuICAgICAgICBjb2xvcjogJHR4dGNvbG9yO1xuICAgIH1cbiAgICAmLnNtYWxsLW5hdjpob3ZlciB7XG4gICAgICAgIC5jaGlsZC1uYXYge1xuICAgICAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGJnY29sb3I7XG4gICAgICAgIH1cbiAgICAgICAgLnNpZGUtbmF2ID4gbGk6bm90KC5oYXMtY2hpbGRyZW4pID4gYSA+IHNwYW4ge1xuICAgICAgICAgICAgYmFja2dyb3VuZC1jb2xvcjogJGJnY29sb3I7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQkFDS0dST1VORCBDT0xPUiBQQUxMRVRFU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmJnIHtcbiAgICAmLXByaW1hcnkge1xuICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKCRwcmltYXJ5LWNvbG9yKTtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRwcmltYXJ5LWNvbG9yLCA3LjUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRwcmltYXJ5LWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkcHJpbWFyeS1jb2xvciwgNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkcHJpbWFyeS1jb2xvciwgMTAlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJHByaW1hcnktY29sb3IsIDE1JSkpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG4uYmcge1xuICAgICYtZGFuZ2VyIHtcbiAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZSgkZGFuZ2VyLWNvbG9yKTtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRkYW5nZXItY29sb3IsIDcuNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTEwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJGRhbmdlci1jb2xvciwgMTUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi01MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGRhbmdlci1jb2xvciwgNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkZGFuZ2VyLWNvbG9yLCAxMCUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTcwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkZGFuZ2VyLWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgIH1cbn1cblxuLmJnIHtcbiAgICAmLXN1Y2Nlc3Mge1xuICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKCRzdWNjZXNzLWNvbG9yKTtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRzdWNjZXNzLWNvbG9yLCA3LjUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRzdWNjZXNzLWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkc3VjY2Vzcy1jb2xvciwgNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkc3VjY2Vzcy1jb2xvciwgMTAlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJHN1Y2Nlc3MtY29sb3IsIDE1JSkpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG4uYmcge1xuICAgICYtd2FybmluZyB7XG4gICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoJHdhcm5pbmctY29sb3IpO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJHdhcm5pbmctY29sb3IsIDcuNSUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTEwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJHdhcm5pbmctY29sb3IsIDE1JSkpO1xuICAgICAgICB9XG4gICAgICAgICYtNTAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCR3YXJuaW5nLWNvbG9yLCA1JSkpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCR3YXJuaW5nLWNvbG9yLCAxMCUpKTtcbiAgICAgICAgfVxuICAgICAgICAmLTcwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkd2FybmluZy1jb2xvciwgMTUlKSk7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5iZyB7XG4gICAgJi1pbmZvIHtcbiAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZSgkaW5mby1jb2xvcik7XG4gICAgICAgICYtMzAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUobGlnaHRlbigkaW5mby1jb2xvciwgNy41JSkpO1xuICAgICAgICB9XG4gICAgICAgICYtMTAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUobGlnaHRlbigkaW5mby1jb2xvciwgMTUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi01MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGluZm8tY29sb3IsIDUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi02MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGluZm8tY29sb3IsIDEwJSkpO1xuICAgICAgICB9XG4gICAgICAgICYtNzAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCRpbmZvLWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgIH1cbn1cblxuLmJnIHtcbiAgICAmLWJsYWNrIHtcbiAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZSgkYmxhY2stY29sb3IpO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJGJsYWNrLWNvbG9yLCA3LjUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRibGFjay1jb2xvciwgMTUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi01MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGJsYWNrLWNvbG9yLCA1JSkpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCRibGFjay1jb2xvciwgMTAlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGJsYWNrLWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgIH1cbn1cblxuLmJnIHtcbiAgICAmLWxpZ2h0LWJsYWNrIHtcbiAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZSgkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJGxpZ2h0LWJsYWNrLWNvbG9yLCA3LjUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCRsaWdodC1ibGFjay1jb2xvciwgMTUlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi01MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGxpZ2h0LWJsYWNrLWNvbG9yLCA1JSkpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCRsaWdodC1ibGFjay1jb2xvciwgMTAlKSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJGxpZ2h0LWJsYWNrLWNvbG9yLCAxNSUpKTtcbiAgICAgICAgfVxuICAgIH1cbn1cblxuLmJnIHtcbiAgICAmLWdyYXkge1xuICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKCRncmF5LWNvbG9yLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGxpZ2h0ZW4oJGdyYXktY29sb3IsIDcuNSUpLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICB9XG4gICAgICAgICYtMTAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUobGlnaHRlbigkZ3JheS1jb2xvciwgMTUlKSwgJGxpZ2h0LWJsYWNrLWNvbG9yKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkZ3JheS1jb2xvciwgNSUpLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCRncmF5LWNvbG9yLCAxMCUpLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICB9XG4gICAgICAgICYtNzAwIHtcbiAgICAgICAgICAgIEBpbmNsdWRlIGNvbG9yLXBhbGV0dGUoZGFya2VuKCRncmF5LWNvbG9yLCAxNSUpLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG4uYmcge1xuICAgICYtd2hpdGUge1xuICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKCR3aGl0ZS1jb2xvciwgJGxpZ2h0LWJsYWNrLWNvbG9yKTtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCR3aGl0ZS1jb2xvciwgNy41JSksICRsaWdodC1ibGFjay1jb2xvcik7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShsaWdodGVuKCR3aGl0ZS1jb2xvciwgMTUlKSwgJGxpZ2h0LWJsYWNrLWNvbG9yKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkd2hpdGUtY29sb3IsIDUlKSwgJGxpZ2h0LWJsYWNrLWNvbG9yKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBAaW5jbHVkZSBjb2xvci1wYWxldHRlKGRhcmtlbigkd2hpdGUtY29sb3IsIDEwJSksICRsaWdodC1ibGFjay1jb2xvcik7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgQGluY2x1ZGUgY29sb3ItcGFsZXR0ZShkYXJrZW4oJHdoaXRlLWNvbG9yLCAxNSUpLCAkbGlnaHQtYmxhY2stY29sb3IpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQ09MT1IgQ0xBU1NFU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLmNvbG9yIHtcbiAgICAmLXByaW1hcnkge1xuICAgICAgICBjb2xvcjogJHByaW1hcnktY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1kYW5nZXIge1xuICAgICAgICBjb2xvcjogJGRhbmdlci1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLXN1Y2Nlc3Mge1xuICAgICAgICBjb2xvcjogJHN1Y2Nlc3MtY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi13YXJuaW5nIHtcbiAgICAgICAgY29sb3I6ICR3YXJuaW5nLWNvbG9yICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtaW5mbyB7XG4gICAgICAgIGNvbG9yOiAkaW5mby1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWJsYWNrIHtcbiAgICAgICAgY29sb3I6ICRibGFjay1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWxpZ2h0LWJsYWNrIHtcbiAgICAgICAgY29sb3I6ICRsaWdodC1ibGFjay1jb2xvciAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWdyYXkge1xuICAgICAgICBjb2xvcjogJGdyYXktY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi13aGl0ZSB7XG4gICAgICAgIGNvbG9yOiAkd2hpdGUtY29sb3IgIWltcG9ydGFudDtcbiAgICB9XG59XG5cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBCT1JERVIgQ09MT1JTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4uYm9yZGVyIHtcbiAgICAmLXByaW1hcnkge1xuICAgICAgICBib3JkZXItY29sb3I6ICRwcmltYXJ5LWNvbG9yO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGxpZ2h0ZW4oJHByaW1hcnktY29sb3IsIDcuNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtMTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkcHJpbWFyeS1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkcHJpbWFyeS1jb2xvciwgNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRwcmltYXJ5LWNvbG9yLCAxMCUpO1xuICAgICAgICB9XG4gICAgICAgICYtNzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRwcmltYXJ5LWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG4uYm9yZGVyIHtcbiAgICAmLWRhbmdlciB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJGRhbmdlci1jb2xvcjtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCRkYW5nZXItY29sb3IsIDcuNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtMTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkZGFuZ2VyLWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRkYW5nZXItY29sb3IsIDUlKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkZGFuZ2VyLWNvbG9yLCAxMCUpO1xuICAgICAgICB9XG4gICAgICAgICYtNzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRkYW5nZXItY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5ib3JkZXIge1xuICAgICYtc3VjY2VzcyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJHN1Y2Nlc3MtY29sb3I7XG4gICAgICAgICYtMzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkc3VjY2Vzcy1jb2xvciwgNy41JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCRzdWNjZXNzLWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRzdWNjZXNzLWNvbG9yLCA1JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi02MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHN1Y2Nlc3MtY29sb3IsIDEwJSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHN1Y2Nlc3MtY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5ib3JkZXIge1xuICAgICYtd2FybmluZyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJHdhcm5pbmctY29sb3I7XG4gICAgICAgICYtMzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkd2FybmluZy1jb2xvciwgNy41JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCR3YXJuaW5nLWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCR3YXJuaW5nLWNvbG9yLCA1JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi02MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHdhcm5pbmctY29sb3IsIDEwJSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJHdhcm5pbmctY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5ib3JkZXIge1xuICAgICYtaW5mbyB7XG4gICAgICAgIGJvcmRlci1jb2xvcjogJGluZm8tY29sb3I7XG4gICAgICAgICYtMzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkaW5mby1jb2xvciwgNy41JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCRpbmZvLWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRpbmZvLWNvbG9yLCA1JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi02MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJGluZm8tY29sb3IsIDEwJSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJGluZm8tY29sb3IsIDE1JSk7XG4gICAgICAgIH1cbiAgICB9XG59XG5cbi5ib3JkZXIge1xuICAgICYtYmxhY2sge1xuICAgICAgICBib3JkZXItY29sb3I6ICRibGFjay1jb2xvcjtcbiAgICAgICAgJi0zMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCRibGFjay1jb2xvciwgNy41JSk7XG4gICAgICAgIH1cbiAgICAgICAgJi0xMDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBsaWdodGVuKCRibGFjay1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkYmxhY2stY29sb3IsIDUlKTtcbiAgICAgICAgfVxuICAgICAgICAmLTYwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkYmxhY2stY29sb3IsIDEwJSk7XG4gICAgICAgIH1cbiAgICAgICAgJi03MDAge1xuICAgICAgICAgICAgYm9yZGVyLWNvbG9yOiBkYXJrZW4oJGJsYWNrLWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgfVxufVxuXG4uYm9yZGVyIHtcbiAgICAmLWdyYXkge1xuICAgICAgICBib3JkZXItY29sb3I6ICRncmF5LWNvbG9yO1xuICAgICAgICAmLTMwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGxpZ2h0ZW4oJGdyYXktY29sb3IsIDcuNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtMTAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogbGlnaHRlbigkZ3JheS1jb2xvciwgMTUlKTtcbiAgICAgICAgfVxuICAgICAgICAmLTUwMCB7XG4gICAgICAgICAgICBib3JkZXItY29sb3I6IGRhcmtlbigkZ3JheS1jb2xvciwgNSUpO1xuICAgICAgICB9XG4gICAgICAgICYtNjAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRncmF5LWNvbG9yLCAxMCUpO1xuICAgICAgICB9XG4gICAgICAgICYtNzAwIHtcbiAgICAgICAgICAgIGJvcmRlci1jb2xvcjogZGFya2VuKCRncmF5LWNvbG9yLCAxNSUpO1xuICAgICAgICB9XG4gICAgfVxufVxuIiwiLy8gTWFyZ2luIHRvcFxuLm10IHtcbiAgICAmLW4ge1xuICAgICAgICBtYXJnaW4tdG9wOiAwICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNSB7XG4gICAgICAgIG1hcmdpbi10b3A6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgbWFyZ2luLXRvcDogMTBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTE1IHtcbiAgICAgICAgbWFyZ2luLXRvcDogMTVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTIwIHtcbiAgICAgICAgbWFyZ2luLXRvcDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgbWFyZ2luLXRvcDogMjVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTMwIHtcbiAgICAgICAgbWFyZ2luLXRvcDogMzBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTM1IHtcbiAgICAgICAgbWFyZ2luLXRvcDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgbWFyZ2luLXRvcDogNDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQ1IHtcbiAgICAgICAgbWFyZ2luLXRvcDogNDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUwIHtcbiAgICAgICAgbWFyZ2luLXRvcDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gTWFyZ2luIGJvdHRvbVxuLm1iIHtcbiAgICAmLW4ge1xuICAgICAgICBtYXJnaW4tYm90dG9tOiAwICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNSB7XG4gICAgICAgIG1hcmdpbi1ib3R0b206IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMTBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTE1IHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMTVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTIwIHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMjVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTMwIHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMzBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTM1IHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogNDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQ1IHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogNDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUwIHtcbiAgICAgICAgbWFyZ2luLWJvdHRvbTogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gbWFyZ2luIGxlZnRcbi5tbCB7XG4gICAgJi1uIHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDAgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01IHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDEwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0xNSB7XG4gICAgICAgIG1hcmdpbi1sZWZ0OiAxNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMjAge1xuICAgICAgICBtYXJnaW4tbGVmdDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDI1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zMCB7XG4gICAgICAgIG1hcmdpbi1sZWZ0OiAzMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzUge1xuICAgICAgICBtYXJnaW4tbGVmdDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgbWFyZ2luLWxlZnQ6IDQwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi00NSB7XG4gICAgICAgIG1hcmdpbi1sZWZ0OiA0NXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNTAge1xuICAgICAgICBtYXJnaW4tbGVmdDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gTWFyZ2luIHJpZ2h0XG4ubXIge1xuICAgICYtbiB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogMCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUge1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgbWFyZ2luLXJpZ2h0OiAxMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMTUge1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDE1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0yMCB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgbWFyZ2luLXJpZ2h0OiAyNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzAge1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDMwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zNSB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgbWFyZ2luLXJpZ2h0OiA0MHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNDUge1xuICAgICAgICBtYXJnaW4tcmlnaHQ6IDQ1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01MCB7XG4gICAgICAgIG1hcmdpbi1yaWdodDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gTWFyZ2luIGFsbCBzaWRlc1xuLm0ge1xuICAgICYtbiB7XG4gICAgICAgIG1hcmdpbjogMCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUge1xuICAgICAgICBtYXJnaW46IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgbWFyZ2luOiAxMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMTUge1xuICAgICAgICBtYXJnaW46IDE1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0yMCB7XG4gICAgICAgIG1hcmdpbjogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgbWFyZ2luOiAyNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzAge1xuICAgICAgICBtYXJnaW46IDMwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zNSB7XG4gICAgICAgIG1hcmdpbjogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgbWFyZ2luOiA0MHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNDUge1xuICAgICAgICBtYXJnaW46IDQ1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01MCB7XG4gICAgICAgIG1hcmdpbjogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gUGFkZGluZyB0b3Bcbi5wdCB7XG4gICAgJi1uIHtcbiAgICAgICAgcGFkZGluZy10b3A6IDAgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01IHtcbiAgICAgICAgcGFkZGluZy10b3A6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgcGFkZGluZy10b3A6IDEwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0xNSB7XG4gICAgICAgIHBhZGRpbmctdG9wOiAxNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMjAge1xuICAgICAgICBwYWRkaW5nLXRvcDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgcGFkZGluZy10b3A6IDI1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zMCB7XG4gICAgICAgIHBhZGRpbmctdG9wOiAzMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzUge1xuICAgICAgICBwYWRkaW5nLXRvcDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgcGFkZGluZy10b3A6IDQwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi00NSB7XG4gICAgICAgIHBhZGRpbmctdG9wOiA0NXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNTAge1xuICAgICAgICBwYWRkaW5nLXRvcDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gUGFkZGluZyBib3R0b21cbi5wYiB7XG4gICAgJi1uIHtcbiAgICAgICAgcGFkZGluZy1ib3R0b206IDAgIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01IHtcbiAgICAgICAgcGFkZGluZy1ib3R0b206IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgcGFkZGluZy1ib3R0b206IDEwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0xNSB7XG4gICAgICAgIHBhZGRpbmctYm90dG9tOiAxNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMjAge1xuICAgICAgICBwYWRkaW5nLWJvdHRvbTogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgcGFkZGluZy1ib3R0b206IDI1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zMCB7XG4gICAgICAgIHBhZGRpbmctYm90dG9tOiAzMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzUge1xuICAgICAgICBwYWRkaW5nLWJvdHRvbTogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgcGFkZGluZy1ib3R0b206IDQwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi00NSB7XG4gICAgICAgIHBhZGRpbmctYm90dG9tOiA0NXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNTAge1xuICAgICAgICBwYWRkaW5nLWJvdHRvbTogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gcGFkZGluZyBsZWZ0XG4ucGwge1xuICAgICYtbiB7XG4gICAgICAgIHBhZGRpbmctbGVmdDogMCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUge1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgcGFkZGluZy1sZWZ0OiAxMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMTUge1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDE1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0yMCB7XG4gICAgICAgIHBhZGRpbmctbGVmdDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgcGFkZGluZy1sZWZ0OiAyNXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtMzAge1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDMwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi0zNSB7XG4gICAgICAgIHBhZGRpbmctbGVmdDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgcGFkZGluZy1sZWZ0OiA0MHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNDUge1xuICAgICAgICBwYWRkaW5nLWxlZnQ6IDQ1cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi01MCB7XG4gICAgICAgIHBhZGRpbmctbGVmdDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gUGFkZGluZyByaWdodFxuLnByIHtcbiAgICAmLW4ge1xuICAgICAgICBwYWRkaW5nLXJpZ2h0OiAwICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNSB7XG4gICAgICAgIHBhZGRpbmctcmlnaHQ6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMTBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTE1IHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMTVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTIwIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMjVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTMwIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMzBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTM1IHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogNDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQ1IHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogNDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUwIHtcbiAgICAgICAgcGFkZGluZy1yaWdodDogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gUGFkZGluZyBhbGwgc2lkZXNcbi5wIHtcbiAgICAmLW4ge1xuICAgICAgICBwYWRkaW5nOiAwICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtNSB7XG4gICAgICAgIHBhZGRpbmc6IDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTEwIHtcbiAgICAgICAgcGFkZGluZzogMTBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTE1IHtcbiAgICAgICAgcGFkZGluZzogMTVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTIwIHtcbiAgICAgICAgcGFkZGluZzogMjBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTI1IHtcbiAgICAgICAgcGFkZGluZzogMjVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTMwIHtcbiAgICAgICAgcGFkZGluZzogMzBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTM1IHtcbiAgICAgICAgcGFkZGluZzogMzVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQwIHtcbiAgICAgICAgcGFkZGluZzogNDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTQ1IHtcbiAgICAgICAgcGFkZGluZzogNDVweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLTUwIHtcbiAgICAgICAgcGFkZGluZzogNTBweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLyotLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLVxuIyBCT1JERVJTXG4tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSovXG4vLyBObyBib3JkZXJcbi5uby1ib3JkZXIge1xuICAgIGJvcmRlci13aWR0aDogMHB4ICFpbXBvcnRhbnQ7XG4gICAgJi10b3Age1xuICAgICAgICBib3JkZXItdG9wLXdpZHRoOiAwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1ib3R0b20ge1xuICAgICAgICBib3JkZXItYm90dG9tLXdpZHRoOiAwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1sZWZ0IHtcbiAgICAgICAgYm9yZGVyLWxlZnQtd2lkdGg6IDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLXJpZ2h0IHtcbiAgICAgICAgYm9yZGVyLXJpZ2h0LXdpZHRoOiAwcHggIWltcG9ydGFudDtcbiAgICB9XG59XG5cbi8vIEJvcmRlciAxcHhcbi5ib3JkZXItMSB7XG4gICAgYm9yZGVyLXdpZHRoOiAxcHggIWltcG9ydGFudDtcbiAgICAmLXRvcCB7XG4gICAgICAgIGJvcmRlci10b3Atd2lkdGg6IDFweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWJvdHRvbSB7XG4gICAgICAgIGJvcmRlci1ib3R0b20td2lkdGg6IDFweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWxlZnQge1xuICAgICAgICBib3JkZXItbGVmdC13aWR0aDogMXB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtcmlnaHQge1xuICAgICAgICBib3JkZXItcmlnaHQtd2lkdGg6IDFweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cblxuLy8gQm9yZGVyIDJweFxuLmJvcmRlci0yIHtcbiAgICBib3JkZXItd2lkdGg6IDJweCAhaW1wb3J0YW50O1xuICAgICYtdG9wIHtcbiAgICAgICAgYm9yZGVyLXRvcC13aWR0aDogMnB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtYm90dG9tIHtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS13aWR0aDogMnB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtbGVmdCB7XG4gICAgICAgIGJvcmRlci1sZWZ0LXdpZHRoOiAycHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1yaWdodCB7XG4gICAgICAgIGJvcmRlci1yaWdodC13aWR0aDogMnB4ICFpbXBvcnRhbnQ7XG4gICAgfVxufVxuXG4vLyBCb3JkZXIgM3B4XG4uYm9yZGVyLTMge1xuICAgIGJvcmRlci13aWR0aDogM3B4ICFpbXBvcnRhbnQ7XG4gICAgJi10b3Age1xuICAgICAgICBib3JkZXItdG9wLXdpZHRoOiAzcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1ib3R0b20ge1xuICAgICAgICBib3JkZXItYm90dG9tLXdpZHRoOiAzcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1sZWZ0IHtcbiAgICAgICAgYm9yZGVyLWxlZnQtd2lkdGg6IDNweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLXJpZ2h0IHtcbiAgICAgICAgYm9yZGVyLXJpZ2h0LXdpZHRoOiAzcHggIWltcG9ydGFudDtcbiAgICB9XG59XG5cbi8qLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS1cbiMgQk9SREVSIFJBRElVU1xuLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0qL1xuLm5vLXJhZGl1cyB7XG4gICAgYm9yZGVyLXJhZGl1czogMHB4ICFpbXBvcnRhbnQ7XG4gICAgJi10b3AtbGVmdCB7XG4gICAgICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDBweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLXRvcC1yaWdodCB7XG4gICAgICAgIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiAwcHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1ib3R0b20tcmlnaHQge1xuICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogMHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtYm90dG9tLWxlZnQge1xuICAgICAgICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiAwcHggIWltcG9ydGFudDtcbiAgICB9XG59XG4uYm9yZGVyLXJhZC0yIHtcbiAgICBib3JkZXItcmFkaXVzOiAycHggIWltcG9ydGFudDtcbiAgICAmLXRvcC1sZWZ0IHtcbiAgICAgICAgYm9yZGVyLXRvcC1sZWZ0LXJhZGl1czogMnB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtdG9wLXJpZ2h0IHtcbiAgICAgICAgYm9yZGVyLXRvcC1yaWdodC1yYWRpdXM6IDJweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWJvdHRvbS1yaWdodCB7XG4gICAgICAgIGJvcmRlci1ib3R0b20tcmlnaHQtcmFkaXVzOiAycHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1ib3R0b20tbGVmdCB7XG4gICAgICAgIGJvcmRlci1ib3R0b20tbGVmdC1yYWRpdXM6IDJweCAhaW1wb3J0YW50O1xuICAgIH1cbn1cbi5ib3JkZXItcmFkLTQge1xuICAgIGJvcmRlci1yYWRpdXM6IDRweCAhaW1wb3J0YW50O1xuICAgICYtdG9wLWxlZnQge1xuICAgICAgICBib3JkZXItdG9wLWxlZnQtcmFkaXVzOiA0cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi10b3AtcmlnaHQge1xuICAgICAgICBib3JkZXItdG9wLXJpZ2h0LXJhZGl1czogNHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtYm90dG9tLXJpZ2h0IHtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS1yaWdodC1yYWRpdXM6IDRweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLWJvdHRvbS1sZWZ0IHtcbiAgICAgICAgYm9yZGVyLWJvdHRvbS1sZWZ0LXJhZGl1czogNHB4ICFpbXBvcnRhbnQ7XG4gICAgfVxufVxuLmJvcmRlci1yYWQtNiB7XG4gICAgYm9yZGVyLXJhZGl1czogNnB4ICFpbXBvcnRhbnQ7XG4gICAgJi10b3AtbGVmdCB7XG4gICAgICAgIGJvcmRlci10b3AtbGVmdC1yYWRpdXM6IDZweCAhaW1wb3J0YW50O1xuICAgIH1cbiAgICAmLXRvcC1yaWdodCB7XG4gICAgICAgIGJvcmRlci10b3AtcmlnaHQtcmFkaXVzOiA2cHggIWltcG9ydGFudDtcbiAgICB9XG4gICAgJi1ib3R0b20tcmlnaHQge1xuICAgICAgICBib3JkZXItYm90dG9tLXJpZ2h0LXJhZGl1czogNnB4ICFpbXBvcnRhbnQ7XG4gICAgfVxuICAgICYtYm90dG9tLWxlZnQge1xuICAgICAgICBib3JkZXItYm90dG9tLWxlZnQtcmFkaXVzOiA2cHggIWltcG9ydGFudDtcbiAgICB9XG59XG4iXX0= */
