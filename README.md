@font-face {
   font-family: 'SMB';
   src: local('Super Mario Bros.'),
        url('fonts/Super Mario Bros.ttf') format('truetype');
   font-style: normal;
}

#game {
	height: 480px; width: 640px; position: absolute; left: 50%; top: 50%;
	margin-left: -321px; margin-top: -241px; border: 1px solid #ccc; overflow: hidden;
}
#world { 
	margin: 0; padding: 0; height: 100%; width: 100%; position: absolute;
	bottom: 0; left: 0; z-index: 0;
}
.gauge {
	margin: 0; padding: 0; height: 50px; width: 70px; text-align: right; font-size: 2em;
	font-weight: bold; position: absolute; top: 17px; right: 52px; z-index: 1000;
	position: absolute; font-family: 'SMB';
}
.gaugeSprite {
	margin: 0; padding: 0; z-index: 1000; position: absolute;
}
#coinNumber {
	left: 0;
}
#liveNumber {
	right: 52px;
}
#coin {
	height: 32px; width: 32px; background-image : url(mario-objects.png);
	background-position: 0 0; top: 15px; left: 70px;
}
#live {
	height: 40px; width: 40px; background-image : url(mario-sprites.png);
	background-position : 0 -430px; top: 12px; right: 8px;
}
.figure {
	margin: 0; padding: 0; z-index: 99; position: absolute;
}
.matter {
	margin: 0; padding: 0; z-index: 95; position: absolute; width: 32px; height: 32px;
}
