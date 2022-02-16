
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>微信支付</title>
    <script>
	

	window.onload = function(){
		var a=window.location.href;
		//alert(a);
		//console.log(a)
		let index = a.indexOf("=", 0)
		var str=a.substring(index+1,a.length);
		console.log(str)
		window.location.href=str;//"weixin://app/wxd7221fd161ef7d80/pay/?nonceStr=c37-3e44-4ecc-a11b-5&package=Sign%3DWXPay&partnerId=1604559626&prepayId=wx011406003251326a1708a850e0c6b20000&timeStamp=1638338760&sign=257EC7920FC7DD2236B8CADB8C47B7DF&signType=SHA1";


	}


	function getQueryString(name) {
		var reg = new RegExp('(^|&)' + name + '=([^&]*)(&|$)', 'i');
		var r = window.location.search.substr(1).match(reg);
		if (r != null) {
			return unescape(r[2]);
		}
		return null;
	}
			
	
	//window.location.href="weixin://app/wxd7221fd161ef7d80/pay/?nonceStr=c37-3e44-4ecc-a11b-5&package=Sign%3DWXPay&partnerId=1604559626&prepayId=wx011406003251326a1708a850e0c6b20000&timeStamp=1638338760&sign=257EC7920FC7DD2236B8CADB8C47B7DF&signType=SHA1"; 
    </script>
</head>
<body>
    
</body>
</html>


