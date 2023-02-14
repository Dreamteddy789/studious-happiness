# studious-happiness
Chatbot.me


html, body, div, span, object, iframe, h1, h2, p, a, img, ul, li, fieldset, form, label, legend, table, thead, tbody, tfoot, tr, th, td {
    border: 0;
    font-size: 100%;
    margin: 0;
    outline: 0;
    padding: 0;
    vertical-align: baseline;
}

body {
    background: #B4B4B4;
    font: normal normal normal 13px/1.231 Helvetica,Arial,sans-serif;
    text-shadow: 1px 1px #F9F8F8;
}

@font-face {
    font-family: opensans;
    src: url('../fonts/OpenSans-Semibold.ttf');
}

#titlebar {
    background: url(../img/titlebar.png) repeat-x;
    position: fixed;
    height: 65px;
    top: 0;
    right: 0;
    left: 0;
}

.title {
    font-size: 24px;
    line-height: 64px;
    margin: 16px;
}

#titlelogo {
    float: right;
    background: url(../img/logo.png);
    width: 27px;
    height: 27px;
    margin: 18px 24px;
}

#sidebar {
    background: #B4B4B4;
    position: fixed;
    width: 303px;
    top: 65px;
    bottom: 400px;
    left: 0;
}

#engine {
    background: #939393;
    position: fixed;
    top: 65px;
    bottom: 0;
    right: 0;
    left: 303px;
    border-left: 1px solid #898989;
}

#init-details {
    background: #DFDDDE;
    border-top: 1px solid #898989;
    padding: 0 32px;
    overflow: auto;
    position: fixed;
    top: 65px;
    bottom: 0;
    right: 0;
    left: 0;
}

#userdata-status {
    background: #DFDDDE;
    border-top: 1px solid #898989;
    padding: 0 32px;
    overflow: auto;
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
}

.scrollable {
    overflow: auto;
}

.html-control {
    background: url(../img/sidebar-item.png) #DFDDDE repeat-x;
    padding: 0;
    margin: 0;
    height: 48px;
}

.control-title {
    float: left;
    font-weight: bold;
    line-height: 48px;
    height: 16px;
    padding: 0;
    margin: 0 0 0 16px;
}

.control-output-pair {
    font-weight: bold;
    line-height: 48px;
    height: 48px;
    padding: 0 16px 0 16px;
    margin: 0;
}

.control-slider {
    background: url(../img/sidebar-item.png) #DFDDDE repeat-x;
    padding: 16px;
    height: 16px;
}

.control-output {
    float: right;
}

.control-textfield {
    float: right;
    height: 16px;
    margin: 13px 0;
}

.control-checkbox input {
    float: right;
    margin: 16px;
    padding: 0;
}

.control-button-pair input {
    float: right;
    font-size: 11px;
    padding: 0;
    width: 56px;
    margin-right: 16px;
    margin-top: 12px;
}

.control-button input {
    float: right;
    font-size: 11px;
    padding: 0;
    width: 96px;
    margin: 13px 16px 13px 0;
}

.control-radio {
    background: #DFDDDE;
    border-top: 1px solid #F6F6F6;
    border-bottom: 1px solid #898989;
    padding: 16px;
}

.control-radio form fieldset {
    padding: 6px 0 10px 0;
    line-height: 18px;
}

.control-radio form fieldset legend {
    font-weight: bold;
    padding: 4px 0;
}

.control-radio form fieldset input {
    float: right;
    padding: 0;
    margin: 0;
}

.control-textbox {
    background: #DFDDDE;
    border-top: 1px solid #F6F6F6;
    border-bottom: 1px solid #898989;
    height: auto;
    padding: 13px;
}

.control-hidden {
    display: none;
}

.engine-control {
    background: #DFDDDE;
    position: fixed;
    bottom: 0;
    width: 303px;
    min-height: 128px;
    height: auto;
    left: 0;
    margin: 1px;
    border-top: 1px solid #F6F6F6;
    border-bottom: 1px solid #898989;
    padding: 10px;
}

.engine-control p {
    width: 280px;
    text-align: justify;
    padding-bottom: 10px;
}

.engine-position {
    padding-top: 3px;
    text-align: center;
}

.engine-control table {
    font-size: 11px;
    margin: 6px 16px;
}

.engine-control table td {
    vertical-align:middle;
}

.engine-control table td.key {
    width: 80px;
}

.engine-control table td.mouse {
    width: 70px;
}

.engine-control table th {
    text-align: left;
    padding: 8px 0;
}
