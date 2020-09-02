<script type="text/javascript"> 
window.onload=function(){  
	setInterval(function(){   
	 var date = new Date();
	 var sign1 = "-";
	 var sign2 = ":";
	 var year = date.getFullYear()
	 var month = date.getMonth() + 1;
	 var day  = date.getDate();
	 var hour = date.getHours();
	 var minutes = date.getMinutes();
	 var seconds = date.getSeconds();
	 var week = weekArr[date.getDay()];
	 if (month >= 1 && month <= 9) {
	  month = "0" + month;
	 }
	 if (day >= 0 && day <= 9) {
	  day = "0" + day;
	 }
	 if (hour >= 0 && hour <= 9) {
	  hour = "0" + hour;
	 }
	 if (minutes >= 0 && minutes <= 9) {
	  minutes = "0" + minutes;
	 }
	 if (seconds >= 0 && seconds <= 9) {
	  seconds = "0" + seconds;
	 }
	 var d=document.getElementById('Date'); 
	 d.innerHTML=year + sign1 + month + sign1 + day + " " + hour + sign2 + minutes + sign2 + seconds + " " + week;},1000)};
</script>