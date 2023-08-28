">Tạo VPS miễn phí sử dụng trong 6 giờ</h1><div class="entry-divider is-divider small"></div><div class="entry-meta uppercase is-xsmall">
<span class="posted-on">Posted on <a href="https://bankhonggioi.com/tao-vps-mien-phi/" rel="bookmark"><time class="entry-date published" datetime="2021-02-21T12:55:02+07:00">21/02/2021</time><time class="updated" datetime="2021-10-22T10:29:10+07:00">22/10/2021</time></a></span> <span class="byline">by <span class="meta-author vcard"><a class="url fn n" href="https://bankhonggioi.com/author/bkog/">BKoG</a></span></span></div></div></header><div class="entry-content single-page"><p style="text-align: justify;">VPS (Virtual Private Server) hoạt động giống như Laptop, máy tính cá nhân. Nó cũng bao gồm các thành phần cơ bản: CPU, Ram, ổ cứng và hệ điều hành. Thông thường, bạn có thể truy cập vào VPS để sử dụng nó như một máy tính thông thường bằng các thông số như: IP Address, tên đăng nhập và mật khẩu.</p><p style="text-align: justify;">Ưu điểm của VPS là có thể hoạt động liên tục 24/7, cấu hình mạnh, ổ đĩa nhanh, tốc độ mạng rất nhanh.</p><p style="text-align: justify;">Mọi yếu tố của VPS có thể được nhà cung cấp tuỳ chỉnh theo nhu cầu của bạn (tất nhiên là phải mất tiền, mà giá cả cũng khá đắt).</p><p style="text-align: justify;">Do đó, bài viết này mình sẽ giới thiệu với các bạn một cách để tận dụng các công cụ để tạo ra một VPS cấu hình tương đối ổn, sử dụng được trong <strong>tối đa 6 giờ</strong> và đặc biệt là <strong>hoàn toàn miễn phí</strong>.</p><h1>1. Các thứ cần chuẩn bị để tạo VPS miễn phí</h1><ul><li>Tài khoản <a href="https://github.com/" target="_blank" rel="noopener nofollow" data-schema-attribute>Github</a></li><li>Tài khoản Gmail</li></ul><h1>2. Các bước thực hiện tạo VPS miễn phí</h1><p><span style="text-decoration: underline;"><strong>Bước 1:</strong></span> Tạo các file cần thiết và upload lên Github.</p><p>Các mã code được mình mã hoá đơn giản, các bạn có thể giải mã tại <a href="https://bankhonggioi.com/ma_hoa/" rel="nofollow" data-schema-attribute>đây</a>.</p><ul><li>Tạo 2 file có tên và nội dung như sau:</li></ul><p>File thứ nhất, tên file: <strong>caidat.ps1 </strong>. Nội dung như sau:</p><pre class="EnlighterJSRAW" data-enlighter-language="generic" data-enlighter-linenumbers="false">Frg-ArgSverjnyyCebsvyr -Cebsvyr Qbznva,Choyvp,Cevingr -Ranoyrq Snyfr
&amp; {$C = $rai:GRZC + '\puebzrerzbgrqrfxgbcubfg.zfv'; Vaibxr-JroErdhrfg 'uggcf://qy.tbbtyr.pbz/rqtrqy/puebzr-erzbgr-qrfxgbc/puebzrerzbgrqrfxgbcubfg.zfv' -BhgSvyr $C; Fgneg-Cebprff $C -Jnvg; Erzbir-Vgrz $C}
&amp; {$C = $rai:GRZC + '\puebzr_vafgnyyre.rkr'; Vaibxr-JroErdhrfg 'uggcf://qy.tbbtyr.pbz/puebzr/vafgnyy/yngrfg/puebzr_vafgnyyre.rkr' -BhgSvyr $C; Fgneg-Cebprff -SvyrCngu $C -Netf '/vafgnyy' -Ireo EhaNf -Jnvg; Erzbir-Vgrz $C}</pre><p>File thứ hai, tên file: <strong>time.ps1 </strong>. Nội dung như sau:</p><pre class="EnlighterJSRAW" data-enlighter-language="generic" data-enlighter-linenumbers="false">$v = 360
qb {
Jevgr-Ubfg $v
Fyrrc 60
$v--
} juvyr ($v -tg 0)</pre><p>Tạo 1 Repository trên Github</p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.001.jpg"><img decoding="async" fetchpriority="high" class="alignnone size-full wp-image-1445" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.001.jpg" alt width="1222" height="551" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.001.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.001-800x361.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.001-768x346.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.002.jpg"><img decoding="async" class="alignnone size-full wp-image-1446" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.002.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.002.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.002-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.002-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a></p><p>Upload 2 file vừa tạo lên <strong>Repository</strong> vừa tạo trên github.</p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.003.jpg"><img decoding="async" class="alignnone size-full wp-image-1447" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.003.jpg" alt width="1222" height="554" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.003.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.003-800x363.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.003-768x348.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.004.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1448" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.004.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.004.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.004-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.004-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.005.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1449" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.005.jpg" alt width="1229" height="513" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.005.jpg 1229w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.005-800x334.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfreec2.005-768x321.jpg 768w" sizes="(max-width: 1229px) 100vw, 1229px" /></a><br/>
<span style="text-decoration: underline;"><strong>Bước 2:</strong></span> Khởi tạo VPS</p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.006.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1451" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.006.jpg" alt width="1222" height="559" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.006.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.006-800x366.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.006-768x351.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.007.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1452" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.007.jpg" alt width="1222" height="559" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.007.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.007-800x366.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.007-768x351.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a><br/>
Code mới cho Actions Github:</p><pre class="EnlighterJSRAW" data-enlighter-language="generic">name: TaoVPS

on: 
  workflow_dispatch:
    inputs:
      authcode:
        description: 'Nhập code'
        required: true
      pincode:
        description: 'Nhập mã pin tuỳ ý (6 số)'
        required: true
  
jobs:
  build:
    runs-on: windows-latest

    steps:
    - uses: actions/checkout@v2
    - name: Initializing Setup
      run: ./caidat.ps1
    - name: Khởi động VPS
      run: ${{ github.event.inputs.authcode }} -pin=${{ github.event.inputs.pincode }}
    - name: Keep Alive
      run: ./time.ps1</pre><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.008.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1453" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.008.jpg" alt width="1222" height="560" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.008.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.008-800x367.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.008-768x352.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.009.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1454" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.009.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.009.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.009-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.009-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.010.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1455" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.010.jpg" alt width="1222" height="556" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.010.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.010-800x364.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.010-768x349.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a></p><p>Ở hình bên trên, ô Nhập mã PIN là bạn lựa chọn 6 số tuỳ ý nhập vào và ghi nhớ để sau này truy cập vào VPS.</p><p>Còn ở ô Nhập code thì lấy như sau: Truy cập vào <a href="https://bankhonggioi.top/Q2eB" data-schema-attribute rel="nofollow noopener" target="_blank"><strong>trang web</strong></a> (lúc này bạn đã đăng nhập gmail rồi) và làm như hình bên dưới:</p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.011.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1457" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.011.jpg" alt width="1222" height="530" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.011.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.011-800x347.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.011-768x333.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.012.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1458" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.012.jpg" alt width="1222" height="533" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.012.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.012-800x349.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.012-768x335.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.013.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1459" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.013.jpg" alt width="1222" height="520" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.013.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.013-800x340.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.013-768x327.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.014.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1460" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.014.jpg" alt width="1215" height="548" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.014.jpg 1215w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.014-800x361.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.014-768x346.jpg 768w" sizes="(max-width: 1215px) 100vw, 1215px" /></a></p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.015.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1461" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.015.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.015.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.015-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.015-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.016.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1462" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.016.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.016.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.016-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.016-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.017.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1463" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.017.jpg" alt width="1222" height="597" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.017.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.017-800x391.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.017-768x375.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.018.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1464" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.018.jpg" alt width="1215" height="530" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.018.jpg 1215w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.018-800x349.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.018-768x335.jpg 768w" sizes="(max-width: 1215px) 100vw, 1215px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.019.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1465" src="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.019.jpg" alt width="1222" height="542" srcset="https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.019.jpg 1222w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.019-800x355.jpg 800w, https://bankhonggioi.com/wp-content/uploads/2021/03/vpsfreec2.019-768x341.jpg 768w" sizes="(max-width: 1222px) 100vw, 1222px" /></a></p><p>Như vậy là bạn tạo xong VPS và có thể truy cập sử dụng.</p><p>Cấu hình và tốc độ mạng của VPS</p><p><a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.cauhinh.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1392" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.cauhinh.jpg" alt width="1206" height="682" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.cauhinh.jpg 1206w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.cauhinh-707x400.jpg 707w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.cauhinh-768x434.jpg 768w" sizes="(max-width: 1206px) 100vw, 1206px" /></a> <a href="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.speed_.jpg"><img decoding="async" loading="lazy" class="alignnone size-full wp-image-1408" src="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.speed_.jpg" alt width="1206" height="678" srcset="https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.speed_.jpg 1206w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.speed_-712x400.jpg 712w, https://bankhonggioi.com/wp-content/uploads/2021/02/vpsfree.speed_-768x432.jpg 768w" sizes="(max-width: 1206px) 100vw, 1206px" /></a></p><h1 style="text-align: justify;">Video các bước thực hiện:</h1><p><iframe data-lazyloaded="1" src="about:blank" loading="lazy" data-src="//www.youtube.com/embed/VT0yiWP6Pwc" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe><noscript><iframe loading="lazy" src="//www.youtube.com/embed/VT0yiWP6Pwc" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe></noscript></p>
<details>
<summary><strong>Cập nhật bài viết</strong></summary><p>06/3/2021: Cập nhật code mới.<br/>
24/02/2021: Cập nhật code Github mới (nguồn: <a href="https://github.com/" 
<button title="In nghiêng" class="ql-italic"></button>
