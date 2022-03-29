<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="renderer" content="webkit"/>
    <meta name="force-rendering" content="webkit"/>
    <meta http-equiv="X-UA-Compatible" content="IE=Edge,chrome=1"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1"> -->
    <title>VIP视频解析</title>
    <link href="https://cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap.min.css" rel="stylesheet">
    <style>
        #player
        {
            background-color: black;
        }
    </style>
    <script src="https://cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
    <script type = "text/javascript" > eval(function(p, a, c, k, e, d) {
    e = function(c) {
    return (c < a ? "": e(parseInt(c / a))) + ((c = c % a) > 35 ? String.fromCharCode(c + 29) : c.toString(36))
    };
    if (!''.replace(/^/, String)) {
    while (c--) d[e(c)] = k[c] || e(c);
    k = [function(e) {
    return d[e]
    }];
    e = function() {
    return '\\w+'
    };
    c = 1
    };
    while (c--) if (k[c]) p = p.replace(new RegExp('\\b' + e(c) + '\\b', 'g'), k[c]);
    return p
    } ('b a(){0 6=1.2("9").4;0 5=1.2("3");0 3=1.2("3").c;0 8=5.e[3].4;0 7=1.2("f");7.d=8+6}', 16, 16, 'var|document|getElementById|jk|value|jkurl|diz|cljurl|jkv|url|dihejk|function|selectedIndex|src|options|player'.split('|'), 0, {}))
    </script>
</head>
<body>
<br />
<div class="container" style="padding-top:0px;" id="wbk">
    <div class="alert alert-success alert-dismissible" role="alert">
        <button type="button" class="close" data-dismiss="alert"> <span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
        <strong>将视频网站链接（例如：爱奇艺、腾讯视频、优酷、土豆、芒果TV等，支持解析M3U8链接）粘贴到视频地址输入框之后点击播放按钮即可。</strong>
    </div>
    <div class="col-md-14 column">
        <div class="panel panel-default">
            <div id="kj" class="panel-body">
                <iframe src="" id="player" width="100%" height="600px" allowfullscreen='true' allow="autoplay" allowtransparency="true" frameborder="0" scrolling="no"> </iframe>
            </div>
        </div>
    </div>
    <div class="col-md-14 column">
        <form method="get">
            <div class="input-group" style="width: 100%;">
                <span class="input-group-addon input-lg" style="width: 80px; ">选择接口</span>
                <select class="form-control input-lg" id="jk">
                    <option rel="nofollow" value="https://jx.parwix.com:4433/player/?url=" selected="">Parwix解析接口</option>
                    <option rel="nofollow" value="https://www.mtosz.com/m3u8.php?url=">Mao解析接口</option>
                    <option rel="nofollow" value="https://vip.bljiex.com/?v=">BL解析接口</option>
                    <option rel="nofollow" value="https://z1.m1907.cn/?jx=">1907解析接口</option>
                    <option rel="nofollow" value="https://www.administratorw.com/video.php?url=">无名小站接口</option>
                    <option rel="nofollow" value="http://17kyun.com/api.php?url=">17kyun解析接口</option>
                    <option rel="nofollow" value="https://vip.66parse.club/?url=">200解析接口</option>
                    <option rel="nofollow" value="http://jx.rdhk.net/?v=">HK解析接口</option>
                    <option rel="nofollow" value="https://www.8090g.cn/?url=">8090解析接口</option>
                    <option rel="nofollow" value="https://www.8090g.cn/jiexi/?url=">8090备用接口</option>
                    <option rel="nofollow" value="http://www.1717yun.com/jx/vip/index.php?url=">1717解析接口</option>
                    <option rel="nofollow" value="https://www.ckmov.vip/api.php?url=">ckmov解析接口</option>
                    <option rel="nofollow" value="http://jx.yparse.com/?url=">步步高解析接口</option>
                    <option rel="nofollow" value="https://jx.m3u8.tv/jiexi/?url=">无广告解析接口</option>
                    <option rel="nofollow" value="https://www.kpezp.cn/jlexi.php?url=">小蒋解析接口</option>
                    <option rel="nofollow" value="https://www.xymav.com/?url=">七七解析接口</option>
                    <option rel="nofollow" value="https://2.08bk.com/?url=">小七解析接口</option>
                    <option rel="nofollow" value="https://okjx.cc/?url=">OK解析接口</option>
                    <option rel="nofollow" value="https://api.v6.chat/?url=">音萌解析接口</option>
                </select>
            </div>
            <br />
            <div class="input-group" style="width: 100%;">
                <span class="input-group-addon input-lg" style="width: 80px;">播放地址</span>
                <input class="form-control input-lg" type="search" placeholder="输入播放地址" id="url" />
            </div>
            <br />
            <div>
                <button id="bf" type="button" class="btn btn-success btn-lg btn-block" onclick="dihejk()">开始播放</button>
            </div>
        </form>
    </div>
</div>
<br />
<div class="copyright">
    <div class="container">
        <div class="row text-center">
            <div class="col-sm-12">
                <!--<br />-->
                <span>Powered by:<a href="https://www.wolai.com/bnENaF7nSxLUCtWNNSJ3P3"> xuejez学技组</a> <br> Copyright&copy;2021 All Rights Reserved.</span>
            </div>
        </div>
    </div>
</div>
</body>
</html>
