## 替换url字符串根域名
    <div id="url">http://xxxx.com/lx/point-page-good-view?id=13</div>

    var url = $('#url').html();
   
   	var url1 = 'http://www.baidu.com';
   
   	$('body').append(url.replace(/(http|https):\/\/([^\/]+)/,url1))
