---
layout: archive
permalink: /projects/
title: "📊PROJECTS"
author_profile: false
header:
  image: /assets/images/unsplash-image-16.jpeg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---
<html>
	<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
		<style>

		body {
		  color: #768390;
		  background: #FFF;
		  font-family: "Effra", Helvetica, sans-serif;
		  padding: 0;
		  -webkit-font-smoothing: antialiased; }

		h1, h2, h3, h4, h5, h6 {
		  color: #3D4351;
		  margin-top: 0; }

		a {
		  color: #FF6B6B; }
		  a:hover {
		    color: #ff9a9a;
		    text-decoration: none; }

		.example-header {
		  background: #3D4351;
		  color: #FFF;
		  font-weight: 300;
		  padding: 3em 1em;
		  text-align: center; }
		  .example-header h1 {
		    color: #FFF;
		    font-weight: 300;
		    margin-bottom: 20px; }
		  .example-header p {
		    font-size: 12px;
		    text-transform: uppercase;
		    letter-spacing: 3px;
		    font-weight: 700; }

		.container-fluid .row {
		  padding: 0 0 4em 0; }
		  .container-fluid .row:nth-child(even) {
		    background: #F1F4F5; }

		.example-title {
		  text-align: center;
		  margin-bottom: 60px;
		  padding: 3em 0;
		  border-bottom: 1px solid #E4EAEC; }
		  .example-title p {
		    margin: 0 auto;
		    font-size: 16px;
		    max-width: 400px; }

		/*==================================
		    TIMELINE
		==================================*/
		/*-- GENERAL STYLES
		    ------------------------------*/
		.timeline {
		  line-height: 1.5em;
		  list-style: none;
		  margin: 0;
		  padding: 0;
		  width: 100%; }
		  .timeline h1, .timeline h2, .timeline h3, .timeline h4, .timeline h5, .timeline h6 {
		    line-height: inherit; }

		/*----- TIMELINE ITEM -----*/
		.timeline-item {
		  padding-left: 30px;
		  position: relative; }
		  .timeline-item:last-child {
		    padding-bottom: 0; }

		/*----- TIMELINE INFO -----*/
		.timeline-info {
		  font-size: 12px;
		  font-weight: 700;
		  letter-spacing: 3px;
		  margin: 0 0 .5em 0;
		  text-transform: uppercase;
		  white-space: nowrap; }

		/*----- TIMELINE MARKER -----*/
		.timeline-marker {
		  position: absolute;
		  top: 0;
		  bottom: 0;
		  left: 0;
		  width: 15px; }
		  .timeline-marker:before {
		    background: #FF6B6B;
		    border: 3px solid transparent;
		    border-radius: 100%;
		    content: "";
		    display: block;
		    height: 8px;
		    position: absolute;
		    top: 4px;
		    left: 0;
		    width: 8px;
		    transition: background 0.2s ease-in-out, border 0.2s ease-in-out; }
		  .timeline-marker:after {
		    content: "";
		    width: 3px;
		    background: #CCD5DB;
		    display: block;
		    position: absolute;
		    top: 24px;
		    bottom: 0;
		    left: 6px; }
		  .timeline-item:last-child .timeline-marker:after {
		    content: none; }

		.timeline-item:not(.period):hover .timeline-marker:before {
		  background: transparent;
		  border: 3px solid #FF6B6B; }

		/*----- TIMELINE CONTENT -----*/
		.timeline-content {
		  padding-bottom: 40px; }
		  .timeline-content p:last-child {
		    margin-bottom: 0; }

		/*----- TIMELINE PERIOD -----*/
		.period {
		  padding: 0; }
		  .period .timeline-info {
		    display: none; }
		  .period .timeline-marker:before {
		    background: transparent;
		    content: "";
		    width: 15px;
		    height: auto;
		    border: none;
		    border-radius: 0;
		    top: 0;
		    bottom: 30px;
		    position: absolute;
		    border-top: 3px solid #CCD5DB;
		    border-bottom: 3px solid #CCD5DB; }
		  .period .timeline-marker:after {
		    content: "";
		    height: 32px;
		    top: auto; }
		  .period .timeline-content {
		    padding: 40px 0 70px; }
		  .period .timeline-title {
		    margin: 0; }

		/*----------------------------------------------
		        MOD: TIMELINE SPLIT
		    ----------------------------------------------*/
		@media (min-width: 768px) {
		  .timeline-split .timeline, .timeline-centered .timeline {
		    display: table; }
		  .timeline-split .timeline-item, .timeline-centered .timeline-item {
		    display: table-row;
		    padding: 0; }
		  .timeline-split .timeline-info, .timeline-centered .timeline-info,
		  .timeline-split .timeline-marker,
		  .timeline-centered .timeline-marker,
		  .timeline-split .timeline-content,
		  .timeline-centered .timeline-content,
		  .timeline-split .period .timeline-info,
		  .timeline-centered .period .timeline-info {
		    display: table-cell;
		    vertical-align: top; }
		  
		  .timeline-split .timeline-marker,
		  .timeline-centered .timeline-marker {
		    position: relative; }
		  
		  .timeline-split .timeline-content,
		  .timeline-centered .timeline-content {
		    padding-left: 30px; }
		  .timeline-split .timeline-info, .timeline-centered .timeline-info {
		    padding-right: 30px; }
		  .timeline-split .period .timeline-title, .timeline-centered .period .timeline-title {
		    position: relative;
		    left: -45px; } }

		/*----------------------------------------------
		        MOD: TIMELINE CENTERED
		    ----------------------------------------------*/
		@media (min-width: 992px) {
		  .timeline-centered,
		  .timeline-centered .timeline-item,
		  .timeline-centered .timeline-info,
		  .timeline-centered .timeline-marker,
		  .timeline-centered .timeline-content {
		    display: block;
		    margin: 0;
		    padding: 0; }
		  .timeline-centered .timeline-item {
		    padding-bottom: 40px;
		    overflow: hidden; }
		  .timeline-centered .timeline-marker {
		    position: absolute;
		    left: 50%;
		    margin-left: -7.5px; }
		  .timeline-centered .timeline-info,
		  .timeline-centered .timeline-content {
		    width: 50%; }
		  .timeline-centered > .timeline-item:nth-child(odd) .timeline-info {
		    float: left;
		    text-align: right;
		    padding-right: 30px; }
		  .timeline-centered > .timeline-item:nth-child(odd) .timeline-content {
		    float: right;
		    text-align: left;
		    padding-left: 30px; }
		  .timeline-centered > .timeline-item:nth-child(even) .timeline-info {
		    float: right;
		    text-align: left;
		    padding-left: 30px; }
		  .timeline-centered > .timeline-item:nth-child(even) .timeline-content {
		    float: left;
		    text-align: right;
		    padding-right: 30px; }
		  .timeline-centered > .timeline-item.period .timeline-content {
		    float: none;
		    padding: 0;
		    width: 100%;
		    text-align: center; }
		  .timeline-centered .timeline-item.period {
		    padding: 50px 0 90px; }
		  .timeline-centered .period .timeline-marker:after {
		    height: 30px;
		    bottom: 0;
		    top: auto; }
		  .timeline-centered .period .timeline-title {
		    left: auto; } }

		/*----------------------------------------------
		        MOD: MARKER OUTLINE
		    ----------------------------------------------*/
		.marker-outline .timeline-marker:before {
		  background: transparent;
		  border-color: #FF6B6B; }

		.marker-outline .timeline-item:hover .timeline-marker:before {
		  background: #FF6B6B; }


		</style>
	</head>

<body>
<script src="https://use.typekit.net/bkt6ydm.js"></script>
<script>try{Typekit.load({ async: true });}catch(e){}</script>

<div class="col">
<div class="container-fluid">
    <div class="row example-basic">
    	<div class="row example-basic">
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>Jenuary 2019 ~ December 2019</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Designing Interactive Contents on Smart Speaker<br>인터랙티브 콘텐츠 서비스 기획 및 제작</h3>
                        <p>- Project with <b>Korea Creative Content Agency, KOCCA</b>
                        <br>- My Role : service planning and development, user interaction data analysis and improvement
                        <br>Developing a smart speaker service that curates classical music, named <a href="https://assistant.google.com/services/a/uid/00000086a4223123?hl=ko">Classic Mate(CM)</a>. Each day one pair of classical musics are provided with simple explanations based on user's response. </p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>September 2018 ~ December 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Next step for Conversational Agents <br>Bixby 커뮤니케이션 UX</h3>
                        <p>- Project with <b>Samsung Electronics</b>
                        <br>- My Role : latest technology and trend research, developing conversational agent prototypes</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>May 2018 ~ September 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Culture Concierge & Preference Collection<br>AI 챗봇 서비스 디자인</h3>
                        <p>- Project with <b>Korea Creative Content Agency, KOCCA</b>
                        <br>- My Role : planning and conducting user research (desk research, semi-structured interviews, tool based survey)
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2018 ~ May 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Designing Home Entertainment AI Service Concept <br>AI 서비스 컨셉 제안</h3>
                        <p>- Project with <b>LG Electronics</b>
                        <br>- My Role : user needs and trend research, operation of an ideation workshop, conceptualization and suggestion</p>
                    </div>
                </li>
            </ul>
        </div>
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
        	<h1>📒PUBLICATION</h1>
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>August 2020</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">A Study on Managing No-response situations in Content driven Voice User Interface <a href="https://s-space.snu.ac.kr/handle/10371/170327">[LINK]</a></h3>
                        <p><b>Byunghi Ko</b></p>
                        <p><i>Master's Degree Thesis, Seoul National University</i></p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>February 2020</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">How do users react to interactive contents on smart speaker? <a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE10402797">[LINK]</a></h3>
                        <p><b>Byunghi Ko</b>, Jeongbok Lee, Soomin Lee, Joongseek Lee</p>
                        <p><i>In Proc. of the HCIK ’20: Human Computer Interaction Korea. 2020.</i></p>
                    </div>
                </li>
            </ul>
        </div>
        </div>
    </div>
 </div>
</div>

</body>
</html>