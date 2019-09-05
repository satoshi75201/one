/*

Timeless Template 

http://www.templatemo.com/tm-517-timeless

*/

body {
    background-color: #333333;
    color: #FFFFFF;
    font-family: 'Open Sans', Helvetica, Arial, sans-serif;
    font-weight: 300;
    overflow-x: hidden;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    font-weight: 300;
}

h3 {
    font-size: 1.3rem;
}

.tm-site-logo {
    width: 40px;
    height: 40px;
    border: 7px solid white;
    transform: rotate(45deg);
    display: inline-block;
    vertical-align: middle;
}

.tm-site-title {
    display: inline-block;
    vertical-align: middle;
    margin-bottom: 0;
}

.tm-site-header {
    padding-top: 45px;
    padding-bottom: 45px;
    margin-bottom: 0;
}

#tm-video-loader {
    border: 5px solid #f3f3f3;
    -webkit-animation: spin 1s linear infinite;
    animation: spin 1s linear infinite;
    border-top: 5px solid #555;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    position: absolute;
    top: 0; left: 0; bottom: 0; right: 0;
    margin: auto;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

.tm-video-container {
    position: relative;
    max-width: 1280px;
    max-height: 640px;
    overflow-y: hidden;
}

.tm-video-text {
    display: inline-block;
}

.tm-welcome-video {
    max-width: 100%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -100;
    background-color: black;
    background-size: cover;
    transition: 1s opacity;
}

.tm-video-text-overlay {
    position: absolute;
    left: 60%;
    bottom: 30px;
}
.tm-video-text-overlay h1 {
	font-size: 3.4rem;
}
.tm-welcome-text {
    margin-top: 65px;
    margin-bottom: 65px;
    font-size: 2.2rem;
}

.tm-font-400 {
    font-weight: 400;
}

.tm-text-light-gray {
    color: #CDCDCD;
}

.tm-text-gray {
    color: #CCCCCC;
}

.tm-text-white {
    color: #FFFFFF;
}

a.tm-text-white:hover,
a.tm-text-white:focus {
    color: #FFFFFF;
}

.tm-text-green {
    color: #99CC66;
}

.tm-text-cyan {
    color: #33CCCC;
}

.tm-text-yellow {
    color: #FFFF66;
}

.tm-text-orange {
    color: #CC9966;
}

.tm-bg-dark {
    background-color: #262626;
}

.tm-bg-dark-light {
    background-color: #404040;
}

hr {
    border-color: #666666;
    max-width: 70%;
}

.tm-video-iframe {
    height: auto;
}

.tm-timeline-item {
    margin-left: 70px;
}

.tm-timeline-item-inner {
    display: flex;
    align-items: center;
}

.tm-img-timeline {
    width: 160px;
    height: 160px;
    display: inline-block;
    vertical-align: middle;
}

.tm-timeline-connector {
    width: 55px;
    height: 3px;
    background-color: #404040;
}

.tm-timeline-connector-vertical {
    height: 60px;
    width: 3px;
    background-color: #404040;
    margin-left: 260px;
}

.tm-timeline-description {
    display: inline-block;
    vertical-align: middle;
    border-radius: 20px;
    padding: 35px 40px;
    max-width: 712px;
}

.tm-section-mb {
    margin-bottom: 85px;
}

.tm-section-mt {
    margin-top: 85px;
}

.tm-contact-form {
    max-width: 500px;
}

.form-control {
    border-radius: 0;
    border-color: #666666;
	color: #CCC;
    background: transparent;
    padding: 12px 15px;
}

.form-control::placeholder {
    /* Chrome, Firefox, Opera, Safari 10.1+ */
    color: #CCCCCC;
    opacity: 1;
    /* Firefox */
}

.form-control:-ms-input-placeholder {
    /* Internet Explorer 10-11 */
    color: #DDDDDD;
}

.form-control::-ms-input-placeholder {
    /* Microsoft Edge */
    color: #DDDDDD;
}

iframe {
    max-width: 100%;
}

#google-map {
    max-width: 500px;
    width: 100%;
    height: 300px;
}

.tm-btn-send {
    border-radius: 0;
    font-size: 1.1rem;
    padding: 12px 50px;
    background: transparent;
    border: 1px solid #CCCCCC;
    color: #CCCCCC;
}

.tm-btn-send:hover,
.tm-btn-send:focus {
    background: #CCCCCC;
    color: #333333;
}

.form-control:focus {
    background-color: transparent;
    border-color: #CCCCCC;
	color: #FFF;
    box-shadow: 0 0 0 0.2rem #cccccc14;
}

input,
textarea,
[contenteditable] {
    caret-color: #FFFFFF;
}

p {
    line-height: 1.9;
}

@media (min-width: 1200px) {
    .container {
        max-width: 1310px;
    }
    .tm-container-2 {
        max-width: 1170px;
    }
}

@media (max-width: 1199px) {
    .tm-video-container {
        max-width: 932px;
        max-height: 466px;
    }
    .tm-video-text-overlay {
        left: 60%;
    }
}

@media (max-width: 991px) {
    #google-map,
    .tm-contact-form {
        max-width: 100%;
    }
    .google-map-iframe {
        width: 100%;
    }
    .tm-video-container {
        max-width: 690px;
        max-height: 345px;
    }
    .tm-video-text-overlay {
        left: 45%;
    }
	.tm-video-text-overlay h1 {
		font-size: 2.8rem;
	}
    .tm-timeline-item {
        margin-left: 25px;
    }
}

@media (max-width: 767px) {
    .tm-timeline-item {
        margin-left: 0;
    }
    .tm-video-container {
        max-width: 510px;
        max-height: 255px;
    }
    .tm-video-container,
    .tm-welcome-video {
        min-height: 220px;
    }
    .tm-video-text-overlay {
        left: 25%;
    }
}

@media (max-width: 584px) {
    .tm-timeline-item-inner {
        flex-direction: column;
    }
    .tm-timeline-connector {
        width: 3px;
        height: 55px;
    }
    .tm-timeline-connector-vertical {
        margin-left: auto;
        margin-right: auto;
    }
}

@media (max-width: 575px) {
    .container {
        max-width: 540px;
    }
    .tm-video-text-overlay {
        left: 30%;
    }
    .tm-video-text-overlay h1 {
        font-size: 1.8rem;
    }
}


@media (max-width: 480px) {
    .tm-video-container {
        overflow-x: hidden;
    }
    .tm-welcome-video {
        min-width: auto;
        max-width: 125%;
    }
}
