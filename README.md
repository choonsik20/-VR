<!DOCTYPE html>
<html>
<head>
	<title> 영남대학교박물관 | VR Content </title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, viewport-fit=cover" />
	<meta name="apple-mobile-web-app-capable" content="yes" />
	<meta name="apple-mobile-web-app-status-bar-style" content="black" />
	<meta name="mobile-web-app-capable" content="yes" />
	<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
	<meta http-equiv="x-ua-compatible" content="IE=edge" />
	<meta name="msapplication-TileColor" content="#FFFFFF">
	<meta name="msapplication-TileImage" content="favicon/favicon16.png">
	<link href="favicon/favicon16.png" rel="icon" type="image/png" sizes="16x16"/>
	<link href="favicon/favicon32.png" rel="icon" type="image/png" sizes="32x32"/>
	<link href="favicon/favicon70.png" rel="icon" type="image/png" sizes="70x70"/>
	<link href="favicon/favicon144.png" rel="icon" type="image/png" sizes="144x144"/>
	<meta property="og:title" content="  Yeungnam University MUSEUM | VR Content"/>
	<meta property="og:site_name" content="  Yeungnam University MUSEUM VR Content"/>
	<meta property="og:description" content="영남대학교 박물관 온라인전시 VR Content"/>
	<link rel="stylesheet" type="text/css" href="css/reset.css">
	<link rel="stylesheet" type="text/css" href="css/scroll.css">
	<link rel="stylesheet" type="text/css" href="css/bud_design.css">
	<link rel="stylesheet" type="text/css" href="css/bud_img_design.css">
	<link rel="stylesheet" type="text/css" href="css/design.css">
	<link rel="stylesheet" type="text/css" href="css/bmlayer.css">
	<style>
		html { height:100%; }
		body { height:100%; overflow:hidden; margin:0; padding:0; font-family:Arial, Helvetica, sans-serif; font-size:16px; color:#FFFFFF; background-color:#000000; }
	</style>
</head>
<body>

<script src="tour.js"></script>

<div id="pano" style="width:100%;height:100%;">
	<noscript><table style="width:100%;height:100%;"><tr style="vertical-align:middle;"><td><div style="text-align:center;">ERROR:<br/><br/>Javascript not activated<br/><br/></div></td></tr></table></noscript>
	<script>
		embedpano({xml:"tour.xml", target:"pano", html5:"only", mobilescale:1.0, passQueryParameters:"startscene,startlookat",
          onready: krpano_onready_callback,
          mwheel: true,
        });

        function krpano_onready_callback(krpano_interface) {
          krpano = krpano_interface;
        }
	</script>
</div>

</body>
</html>
