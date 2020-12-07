---
layout: page
title: Portfolio
eleventyNavigation:
  key: Portfolio
  order: 2
---
<!DOCTYPE html>
<html>
<head>
 <title>Adobe Document Services PDF Embed API Sample</title>
 <meta charset="utf-8"/>
 <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
 <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1"/>
</head>
<body style="margin: 0px">
 <div id="adobe-dc-view"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<ba95a1476d7544178ed64a7b114493a7>"});
		adobeDCView.previewFile({
			content:{location: {url: "https://documentcloud.adobe.com/link/file/?x-product=CCHome%2F1.0&guid=a8f5049a-eace-442c-8107-4ab77ff10c25&x-location=Home&uri=urn%3Aaaid%3Asc%3Aus%3Aa24cf58a-a2ec-485b-8d63-bff2e94aa042&filetype=application%2Fpdf&size=28778611"}},
			metaData:{fileName: "Portfolio.pdf"}
		}, {embedMode: "LIGHT_BOX", defaultViewMode: "FIT_WIDTH"});
	});
</script>
</body>
</html>