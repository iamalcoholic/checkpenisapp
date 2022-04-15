
function check() {
  
var a
 a = document.getElementsByTagName('input')[0].value;
 if (isNaN(a)||a<=0) { 
   alert('Đéo có cu à mày?')
 } else {
alert('Chiều dài cu của bạn là ' + a + 'cm');
 } }

