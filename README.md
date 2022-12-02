# CSS-ANIMATION

<html>
    <head>
        <title> Demo Of CSS</title>
        <style type="text/css">
            div{
                height:200px;
                width:200px;
                transition:3s;
                font-size:25px;
                font-weight:bold;
                color:#000000;
                background-color:rgb(20, 206, 243);
            }
            #TranslateDiv:hover
            {
                -webkit-transform:translate(100px,100px);
                   -moz-transform:translate(100px,100px);
                    -ms-transform:translate(100px,100px);
                     -o-transform:translate(100px,100px);
                        transform:translate(100px,100px);
                      background-color:Blue;
                      color:Yellow; 
            }
			
            #RotateDiv:hover
            {
                -webkit-transform:rotate(360deg);
                   -moz-transform:rotate(360deg);
                    -ms-transform:rotate(360deg);
                     -o-transform:rotate(360deg);
                        transform:rotate(360deg);
                      background-color:Blue;
                      color:Yellow; 
         
            }
			#RotateDiv3D:hover{
				-webkit-transform:rotate3d(1,1,0,360deg);
                   -moz-transform:rotate3d(1,1,0,360deg);
                    -ms-transform:rotate3d(1,1,0,360deg);
                     -o-transform:rotate3d(1,1,0,360deg);
                        transform:rotate3d(1,1,0,360deg);
                      background-color:Blue;
                      color:Yellow; 
         
			}
            #SkewDiv:hover
            {
                -webkit-transform:skew(45deg);
                   -moz-transform:skew(45deg);
                    -ms-transform:skew(45deg);
                     -o-transform:skew(45deg);
                        transform:skew(45deg);
                      background-color:Blue;
                      color:Yellow; 
            }
            #ScaleDiv:hover
            {
                -webkit-transform:scale(1.5,0.5);
                   -moz-transform:scale(1.5,0.5);
                    -ms-transform:scale(1.5,0.5);
                     -o-transform:scale(1.5,0.5);
                        transform:scale(1.5,0.5);
                      background-color:Blue;
                      color:Yellow; 
            }
            #OpacityDiv:hover
            {
                opacity:0.6;
            }
            #RGBADiv:hover
            {
                background:rgba(128,128,0,0.5);
            }
            #BoxShadowDiv:hover
            {
                box-shadow:0px 0px 30px Blue;
            }
            #TextShadowDiv:hover
            {
                text-shadow:3px 3px 3px yellow;
            }
			#BorderRadiusDiv:hover
			{
				border-radius:50%;
			}
			#OverFlowDiv{overflow:auto;}
        </style>
    </head>
    <body>
        <div id="TranslateDiv">Translate</div><hr />
        <div id="RotateDiv">Rotate</div><hr />
		<div id="RotateDiv3D">Rotate 3d</div><hr />
        <div id="SkewDiv">Skew</div><hr />
        <div id="ScaleDiv">Scale</div><hr />
        <div id="OpacityDiv">Opacity</div><hr />
        <div id="RGBADiv">RGBA</div><hr />
        <div id="BoxShadowDiv">Box-Shadow</div><hr />
        <div id="TextShadowDiv">Text-Shadow</div><hr />
		<div id="BorderRadiusDiv">Border Radius</div><hr />
		<div id="OverFlowDiv">Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow Overflow </div><hr />
    </body>
</html>
