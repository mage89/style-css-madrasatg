 
/* ----------------------------------------------
Name:madrasatg
Designer URL: madrasatg.blogspot.com
year:2021
----------------------------------------------- */
.blog-feeds,.post-feeds,#headads h5,#drop a::after,.date-header,.cnmunav,.cnmunav2{display:none}
 
:root {
    --color-header: #41274c;
    --color-hover: #cb0001;
    --color-Basics: linear-gradient(#371f41, #4e305a);
    --color-drop: #4d2f59;
    --color-buttons: linear-gradient(to left, #8415269c, rgb(111 55 125 / 80%));
    --colo-search: linear-gradient(to left, rgb(111 55 125 / 80%), #2d1c4257);
    --colo-title: linear-gradient(to left, #510936, #2d1c4257);
    --color-post: rgb(223 195 255);
    --color-sidebar: #A398B0;
    --color-footer: linear-gradient(#371f41, #4e305a);
    --color-cnmunav: linear-gradient(#422365,#920404);
    --color-body:linear-gradient(#371f41, #4e305a);
	--color-body: #382042
}

/*-- التسميات داخل المشاركة نفسها --*/
span.post-labels{font-family:droid arabic kufi;font-size:14px;padding:0;margin:0;float:right}
span.post-labels a{color:#0115FF}
span.post-labels a:hover{color:#CB0001}
p#sections{margin:0 0 0 6px;float:right}
/*-- نشر في --*/
span.post-timestamp{font-family:droid arabic kufi;font-size:14px;padding:0;margin:0;float:right}
span.post-timestamp a{color:#000}
span.post-timestamp a:hover{color:#CB0001}
/*------ منطقة الهيدر ---------*/
#outer-header-wrapper{margin:0}
/*الشريط العلوي*/
.nav-bar{height:40px;width:100%;background:var(--color-Basics);box-shadow:inset 0 1px 1px rgba(111,55,125,0.8),inset 0 -1px 0 rgba(63,59,113,0.2),0 9px 16px 0 rgba(0,0,0,0.3),0 4px 3px 0 rgba(0,0,0,0.3),0 0 0 1px #150a1e}
/*-- الهلال والتاريخ الإسلامي --*/
img#helal{width:25px;height:25px;float:right;margin:0;padding:5px 8px 0 0}
p#islamic-date{width:63px;float:right;margin:0;text-align:right;padding:0 10px 0 0;height:30px;line-height:38px;color:#fff;font-size:17px}
#w {
    width: auto;
    margin-left: auto;
    margin-right: auto;
    float: right;
    margin-top: 6px;
    background: var(--color-buttons);
    padding-right: 6px;
    padding-left: 6px;
    border-radius: 2px;
    padding-top: 1px;
    padding-bottom: 1px;
}
#w:hover {background: var(--color-hover)}
#w a {color:#fff}


/*محرك البحث*/
#search{float:left}
#search-text{background: var(--colo-search);border:0px solid #231544;color:#E5E7E8;font-size:12px;font-family:droid arabic kufi;height:28px;width:330px;margin-left:2px;margin-top:5px;padding-right:10px;border-radius:0 2px 2px 0}
#search-submit{background:var(--color-buttons);border:0;color:#fff;cursor:pointer;float:left;font-size:13px;font-family:droid arabic kufi;height:30px;width:55px;margin-top:5px;margin-left:4px;border-radius:3px 0 0 3px;transition:all 0.7s ease 0s}
#search-submit:hover {background: var(--color-hover)}
/*---هيدر كمبيوتر----*/
#header-wrapper{display:block;min-height:69px;padding:0 5px}
#header{float:none;width:initial;margin-left:-5px;margin-right:-5px;margin-top:-1px;background-color:var(--color-header)}
#header-inner img{height:auto;width:100%}
/*---- الهيدر موبايل ----*/
#header-mobile{display:none;min-height:69px;padding:0 5px}
#header2{float:none;width:initial;margin-left:-5px;margin-right:-5px;margin-top:-1px;background-color:var(--color-header)}
/*القائمة السفلية*/
#ras{background-color:#CB0001}
#b-Menu .fa.fa-home{color:#fff;float:right;font-size:32px;line-height:38px;padding:0 0 0}
.bottomenu{list-style:outside none none;margin:0;padding:0;background:var(--color-Basics);height:48px;border-bottom:1px solid #61605f;border-radius:0 0 0 50px;box-shadow:0 0 1px 1px rgb(0 0 0 / 75%), inset 0 1px 1px rgb(62 61 60), inset 0 -1px 0 rgb(63 59 113 / 20%), 0 5px 6px 0 rgb(0 0 0 / 30%), 0 4px 3px 0 rgb(0 0 0 / 30%), 0 0 0 1px #523305}
.bottomenu li{float:right}
.bottomenu a{color:#fff;display:block;font-size:15px;line-height:49px;padding:0 13px;border-right:2px solid #000}
.bottomenu a:hover{color:#efe906;background:var(--color-hover)}
#sub a::after{float:left;font-size:15px;margin-right:2px;margin-top:2px}
#sub a{cursor:pointer}
#drop{display:none;margin:0;padding:0;position:absolute;z-index:999}
#sub:hover #drop{display:block}
#drop li{float:none;list-style:outside none none}
#drop a{background-color:var(--color-drop);border-top:1px solid #fff;cursor:pointer;display:block;line-height:40px;margin:0;padding:0 7px;width:100%;border-radius:0 0 0 13px}
#drop a:hover{background-color:var(--color-hover);color:#fff}

/*------ منطقة الـ BODY ----*/
body {width:100%;color:#000;padding:0;margin:0 auto;font-size:14px;font-family:droid arabic kufi;height:initial;background: var(--color-body) url(https://1.bp.blogspot.com/-roDE_d1o0XY/YPDHLQ42HFI/AAAAAAAAEnw/VpNiVjQQwe4DejBzRN-v0FWRnV6gGzLtACLcBGAsYHQ/s1753/pattern.png) !important}
/*-----الروابط واللينكات---*/

/*تلقائي*/
a{color:#0115FF; text-decoration:none}
a:hover{color:#8F0707}
/*عنوان المشاركات على الصفحة الرئيسية*/
h1.post-title.entry-title a{font-weight:bold;color:#EFEBEB}
h1.post-title.entry-title a:hover{color:#B4D2EA}
/*الصفحة الرئيسية ورسائل أقدم */
a.home-link,a#Blog1_blog-pager-older-link,a#Blog1_blog-pager-newer-link{background:linear-gradient(#DA0F0F,#A22A06);color:#fff;padding:15px}
a.home-link:hover,a#Blog1_blog-pager-older-link:hover,a#Blog1_blog-pager-newer-link:hover{color:#FBEB00;background:linear-gradient(#9C27B0,#A22A06)}
/*----المواضيع------*/
#outer-wrapper{padding:10px 17px}
#main-wrapper{float:right;width:78%}
h2{color:#cc0808;text-align:center;padding:4px 8px 4px 8px}
h3{color:#072b92}
.post.hentry{display:block;margin-bottom:15px;padding:0 20px 8px 20px;position:relative;background-color:var(--color-post);border-radius:15px 0 0 6px;font-family:droid arabic kufi!important;font-size:18px}
.post-title{display:block;margin:0 -20px 10px;padding:7px 8px!important;background:var(--colo-title);border-radius:14px 0 0 0;color:#EFEBEB;border-top: 1px solid #5f5d5d}
.post h1{font-size:16px;font-family:droid arabic kufi}
.post h5{background-color:#2327A5;color:#fff;font-size:16px;font-family:droid arabic kufi;padding:4px 8px 5px}
.post h5::before{color:#00ab03;content:"\f058";float:right;font-size:22px;font-family:droid arabic kufi;margin-left:5px}
.post h5{color:#666;font-size:13px;font-family:droid arabic kufi;font-weight:bold;text-align:right!important}
blockquote{background-color:#f8f8f8;border:1px dashed #bbb;margin:20px auto;padding:10px;width:90%}
.post ol{counter-reset:li;list-style:none;*list-style:decimal;margin-right:0;padding-right:0}
.post ol li{font-size:13px;font-family:droid arabic kufi;list-style:outside none none;margin:0 15px 10px 0!important;padding:4px 10px 4px 5px!important;position:relative;text-indent:14px}
.post ol li:before{background-color:#2327A5;border-radius:2px;color:#fff;content:counter(li,decimal);counter-increment:li;font-size:14px;font-family:droid arabic kufi;font-weight:bold;margin:0 0 10px;padding:4px 4px 5px 3px!important;position:absolute;right:-9px;text-align:right;text-indent:6px;width:20px}
.post img{max-width:96%}
.posts-thumb img{height: auto;max-width:98%!important;transition:.9s all ease-in-out;border-radius:5px}
.posts-thumb img:hover{opacity:0.7}
.summary {
    font-family: droid arabic kufi;
    font-size: 13px;
    height: 122px;
    overflow: hidden;
    color: #320128;
    text-align: justify;
}


/*معلومات الموضوع*/
#footinfo{font-family:droid arabic kufi;line-height:35px;margin:0 5px 0 0;font-size:12px}
#footinfo .post-comment-link{float:right;margin-right:5px}
#footinfo .comment-link{font-family:droid arabic kufi;font-size:16px}
#footinfo .ramor{background:#66376017;float:left;font-size:13px;text-align:center;margin:0;border-radius:5px;padding:0 8px 0 7px;color:#530e3a}
#footinfo .ramor:hover{background:#DC0303;color:#fff}
.pincel{left:4px;position:absolute;top:0}
/*معلومات الموضوع الداخلية*/
#post-info{background: linear-gradient(to top, #a39f9f, #2d1c4200);;margin:0;padding:8px 10px 20px 10px;border-radius:0 0 13px 13px;border-top:1px solid #d0aecd}
p#published-in{margin:0;float:right}
#post-info .sharebuttons{float:left;margin-left:5px}
#post-info .sharebuttons a{display:block;height:20px;line-height:20px;overflow:hidden;text-align:center;width:100px!important}
#post-info .post-author::before{color:#555;float:right;font-size:16px;font-family:droid arabic kufi;margin:3px 0 0 5px}
#post-info .post-author span{float:right}
#post-info .post-timestamp::before{color:#555;float:right;font-size:16px;font-family:droid arabic kufi;margin:3px 4px}
#post-info .post-labels::before{color:#555;float:right;font-size:16px;font-family:droid arabic kufi;margin:4px 0 0 4px}
/*مواضيع ذات صلة*/
#related-posts{margin:0 0 10px;padding:0 0 5px;background-color:#d0cdcd}
#related-posts h1{font-size:16px;font-weight:normal;color:#fff;margin:0;padding:0 5px;background: linear-gradient(to left, #540606, #2d1c4200)}
#related-posts ul{list-style:outside none none;margin:0;padding:8px}
#related-posts a::before{float:right;font-size:16px;font-family:droid arabic kufi;margin:4px 0 0 5px;color:#444}
#related-posts a{display:block;float:right;width:100%}


/*التعليقات*/
#comment-t {background: linear-gradient(to left, #540606, #2d1c4200);color: #fff;float: right;font-size: 16px;font-weight: normal;width: 100%;padding: 6px 5px 7px 0}
.comments{padding-top: 0px;clear: both;margin-top: 10px;margin-bottom: 20px;font-family: droid arabic kufi!important;line-height: 18px;font-size: 13px;background-color: #d0cdcd;border-bottom-right-radius: 8px;border-bottom-left-radius: 8px}
.comments .comments-content{margin-bottom:16px;font-weight:normal;text-align:right}
.comments .comment .comment-actions a,.comments .comment .continue a{display:inline-block;margin:0 5px 10px 5px;padding:0 15px;color:#424242 !important;text-align:center;text-decoration:none;background:#E0DFDF;border:1px solid #A3A1A1;border-radius:2px;height:26px;line-height:28px;font-weight:normal;cursor:pointer}
.comments .comments-content .comment-thread ol{list-style-type:none;padding:0}
.comments .comments-content .inline-thread{padding:0}
.comments .comments-content .comment-thread{margin:8px 0}
.comments .comments-content .comment-thread:empty{display:none}
.comment-replies{
margin-right: 40px;
    margin-left: auto;
    padding: 1px;
    text-align: center;
    color: #000
}
.comments .comments-content .comment{margin-bottom:0;padding-bottom:0}
.comments .comments-content .comment:first-child{padding-top:16px}
.comments .comments-content .comment:last-child{border-bottom:0;padding-bottom:0}
.comments .comments-content .comment-body{position:relative}
.comments .comments-content .user{font-style:normal;font-weight:normal}
.comments .comments-content .user a{color:#801414;font-weight:bold;text-decoration:none}
 
.comments .comments-content .icon.blog-author{width:18px;height:18px;display:inline-block;margin:0 0 -4px 6px}
.comments .comments-content .datetime a{color:#000;font-size:9px;float:left;text-decoration:none}
.comment-content{margin:0 0 8px;padding:0 5px}
.comment-header{font-size: 11px;background-color: rgb(0 0 0 / 20%);border-bottom: 1px solid #908e8e;padding: 5px;font-weight: bold;border-top-left-radius: 10px;border-top-right-radius: 10px}
.comments .comments-content .owner-actions{position:absolute;left:0;top:0}
.comments .comments-replybox{border:none;height:230px;width:100%}
.comments .comment-replybox-thread{margin-top:0}
.comments .comment-replybox-single{margin-top:5px;margin-right:48px}
.comments .comments-content .loadmore a{display:block;padding:10px 16px;text-align:center}
.comments .thread-toggle{cursor:pointer;display:inline-block}
.comments .comments-content .loadmore{cursor:pointer;max-height:3em;margin-top:0}
.comments .comments-content .loadmore.loaded{max-height:0;opacity:0;overflow:hidden}
.comments .thread-chrome.thread-collapsed{display:none}
.comments .thread-toggle{display:inline-block}
.comments .thread-toggle .thread-arrow{display:inline-block;height:6px;width:7px;overflow:visible;margin:0.3em;padding-left:4px}
.comments .thread-expanded .thread-arrow{background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAc AAAAHCAYAAADEUlfTAAAAG0lEQVR42mNgwAfKy8v/48I4FeA0AacVDFQBAP9wJkE/KhUMAAAAAElFTkSuQmCC") no-repeat scroll 0 0 transparent}
.comments .thread-collapsed .thread-arrow{background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA AcAAAAHCAYAAADEUlfTAAAAJUlEQVR42mNgAILy8vL/DLgASBKnApgkVgXIkhgKiNKJ005s4gDLbCZBiSxfygAAAAB JRU5ErkJggg==") no-repeat scroll 0 0 transparent}
.avatar-image-container{background:url(https://lh5.googleusercontent.com/-1FOOK-wkThg/U4rEEaJBlLI/AAAAAAAAEMA/vAhBcNCkp_4/s51/arrow.png) top left no-repeat;float:right;vertical-align:middle;overflow:hidden;width:65px !important;height:51px !important;max-width:65px !important;max-height:51px !important}
.comments .avatar-image-container img{padding:2px;border:1px solid #ccc;width:45px !important;height:45px !important;max-width:45px !important;max-height:45px !important}
.comments .comment-block{margin-right: 65px;position: relative;
    border: 1px solid #880988;
    background-color: #e9e5e5;border-radius: 10px}



/*--------السايدبار-----*/
#sidebar-wrapper{float:left;width:20%}
#sidebar .widget{background-color:var(--color-sidebar);margin-bottom:10px;overflow:hidden;padding:0 9px 10px;text-align: center}
#sidebar h5{border-top: 2px solid #00000094;background:var(--color-Basics);color:#fff;font-size:15px;font-family:droid arabic kufi;font-weight:normal;height:41px;margin:0 -9px 8px;text-align:center;line-height:38px;border-radius:0 0 15px 0}
/*المشاركات الشائعة*/
.popular-posts ul{list-style:outside none none;margin:0;padding:0}
.PopularPosts ul li{border-bottom:1px solid rgba(64,36,94,0.5);height:70px;overflow:hidden;padding:5px 0;width:100%}
.item-title{text-align:justify}
.PopularPosts .item-title a{font-size:13px;color:#390577;width:97%}
.PopularPosts .item-title a:hover{color:#B50C45}
.PopularPosts .item-thumbnail{float:right;margin:0 0 5px 5px}
.PopularPosts .item-thumbnail img{height:60px;padding:1px;width:66px;border-radius: 8px}
.PopularPosts .item-thumbnail img:hover{opacity:0.4}
.popular-posts .item-snippet{display:none}
/*الأرشيف*/
.BlogArchive select{font-size:14px;font-family:droid arabic kufi;width:100%;color:#444;background-color:#ECDCFF}
/*التسميات*/
.Label ul{list-style:outside none none;margin:0;padding:0}
.Label li span{background:linear-gradient(rgb(144,173,187),#435D8E);border:1px solid #4C3863;display:block;float:right;font-size:12px;color:#fff;height:33px;line-height:34px;margin:0 2px 2px;width:96%;padding-right:3px;border-radius:5px}
.Label li a {background: var(--color-Basics);display:block;float:right;font-size:12px;color:#fff;height:33px;line-height:34px;margin:0 2px 3px;width:96%;padding-right:3px;border-radius:2px}
.Label li a:hover{background:var(--color-hover);color:#EEF2F3}
/*الترقيم*/
.showpageOf{background-color:#CB0001;color:#fff;box-shadow:0 0 0 1px #ddd inset;display:inline-block;float:right;height:30px;line-height:30px;margin-left:5px;padding:0 15px;border-radius:0 5px 5px 0}
.pagecurrent{background-color:#CB0001;color:#fff;float:right;height:30px;line-height:30px;margin:0 1px;text-align:center;width:30px;border-radius:3px}
.displaypageNum a{background-color:#f8f8f8;box-shadow:0 0 0 1px #ddd inset;display:inline-block;float:right;height:30px;line-height:30px;margin:0 3px;text-align:center;width:30px}
.firstpage,.lastpage,.prevnav,.nextpage{display:none}
.noqat1,.noqat2{float:right}
.displaypageNum a:hover{background-color:#9573BB;color:#fff}
/*قائمة الروابط*/
.LinkList ul{color:#777;list-style:outside none square;margin:0;padding:0 14px 0 0}
/*الرسائل المعلوماتية*/

.status-msg-wrap{font-size:14px;margin-right:auto;margin-left:auto;margin-bottom:9px;margin-top:0;width:98%;background-color:#A398B0;padding:0;border-radius:8px}



/* أيقونات مشاركة الموضوع الجديدة */
.post-share{width:100%;margin:0;text-align:center}
p#Share-this{font-size:14px;margin:0 0 5px 0;padding:0 6px 0 0;font-weight:bold;color:#CB0001;text-align: center}
.post-share a{width:20%;margin:0 8px;display:inline-block;cursor:pointer;text-align:center;color:#fff;line-height:35px;font-size:15px;border-radius:3px;font-family:droid arabic kufi;box-shadow:0 0 0 0 rgba(0,0,0,0.75),inset 0 0 0 rgba(111,55,125,0.8),inset 0 0 0 rgba(63,59,113,0.2),0 5px 6px 0 rgba(0,0,0,0.3),0 4px 3px 0 rgba(0,0,0,0.3),0 0 0 0 #150a1e}
.post-share a.whatsapp{background:#028948}
.post-share a.share-linkedin{background:#007bb6}
.post-share a.share-twitter{background:#00aced}
.post-share a.share-facebook{background:#073BA9}
.post-share a:hover{background-color:#CB0001}
.post-share i.fa.fa-linkedin{background:none}
.post-share i.fa.fa-twitter{background:none}
.post-share i.fa.fa-facebook{background:none}
.post-share i.fa.fa-whatsapp{background:none}
@media screen and (max-width:900px){.post-share{width:100%;margin:0;text-align:center}.post-share a{float:none;width:96%;font-size:17px;margin-bottom:5px;margin:5px auto!important;text-align:center;display:block}}
/* أزرار التحميل والانتقال داخل المشاركات*/

/*زر تحميل أساسي */
a#down2{background:#10B70D;margin-right:auto;margin-left:auto;padding:10px 40px 10px 40px;width:100px;color:#fff;border-radius:5px 5px 5px 5px;font-size:22px;text-align:center;box-shadow:0 0 0 0 rgba(255,238,170,0.4),inset 0 0 0 rgba(170,125,181,0.8),inset 0 0 0 rgba(63,59,113,0.2),0 5px 6px 0 rgba(0,0,0,0.3),0 4px 3px 0 rgba(0,0,0,0.3),0 0 0 0 #83649C}
a#down2:hover{background-color:#4d90fe;color:#fff}
/*زر انتقال موضوعي داخلي*/
a#bot90{background:#27828C;margin-right:auto;margin-left:auto;padding:6px 13px 6px 15px;width:100%;color:#fff;border-radius:5px 5px 5px 5px;font-size:15px;text-align:center;box-shadow:0 0 0 0 rgba(255,238,170,0.4),inset 0 0 0 rgba(170,125,181,0.8),inset 0 0 0 rgba(63,59,113,0.2),0 5px 6px 0 rgba(0,0,0,0.3),0 4px 3px 0 rgba(0,0,0,0.3),0 0 0 0 #83649C}
a#bot90:hover{background-color:#387CAD}
@media screen and (max-width:980px){a#bot90{width:90%;padding:3px 16px 1px 15px}}
/*زر انتقال خارجي - من هنا*/
a#go{background:#673AB7;margin-right:auto;margin-left:auto;padding:10px 40px 10px 40px;width:100px;color:#fff;border-radius:5px 5px 5px 5px;font-size:22px;text-align:center;box-shadow:0 0 0 0 rgba(255,238,170,0.4),inset 0 0 0 rgba(170,125,181,0.8),inset 0 0 0 rgba(63,59,113,0.2),0 5px 6px 0 rgba(0,0,0,0.3),0 4px 3px 0 rgba(0,0,0,0.3),0 0 0 0 #83649C}
a#go:hover{background-color:#6C65DA;color:#fff}
/*تنسيق الصوتيات داخل المشاركات*/
audio{width:95%}
.back-z{font-weight:bold;padding:11px 8px 10px 3px;background:#7E5AA7;border-radius:8px;width:95%}
a#bot89{background:#D1BCE8;padding:0 4px 2px 7px;border-radius:5px;font-size:14px}
input#ContactForm1_contact-form-submit{float:left;font-family:droid arabic kufi;font-size:11px;cursor:pointer}
/* كود الصعود والنزول   */
#scrollToTop{display:none;list-style:none;position:fixed;height:40px;bottom:0%;right:20px;cursor:pointer;-webkit-transform:translateZ(0);transform:translateZ(0);z-index:99}
#scrollToTop a{display:inline-block;background:rgba(108,123,152,0.72);color:#E0DBDB;font-size:.8rem;margin:0;padding:5px 8px;border-radius:10px;border:2px solid #E0DBDB;box-shadow:0 2px 3px rgba(0,0,0,0.06),0 2px 3px rgba(0,0,0,0.1)}
#scrollToTop a:hover{color:rgba(0,0,0,0.5);background-color:rgba(140,158,193,0.87)}
#top{position:absolute;top:0}
#scrollToTop{display:none;list-style:none;position:fixed;bottom:1px;right:-33px;cursor:pointer;-webkit-transform:translateZ(0);transform:translateZ(0);z-index:99}
#top{position:absolute;top:0}
@media screen and (max-width:980px){#scrollToTop{height:46px}}
@media screen and (max-width:320px){#scrollToTop{height:44px}#scrollToTop a{font-size:15px}}
/* زر انتقال */
div#titl-p{float:none;text-align:justify;color:#f1f1f1;background:#026473;border-radius:0 15px 0 15px;width:93%;margin-right:auto;margin-left:auto;margin-bottom:5px;padding:5px 10px 7px 10px;cursor:context-menu;font-weight:bold}
div#transition{width:95px;float:none;margin-right:auto;margin-left:auto}
input#trans{width:100%;cursor:pointer;font-size:17px;font-family:droid arabic kufi;color:#f1f1f1;border-radius:5px;border:2px solid #048194;background-color:#059AB1;margin-right:auto;margin-left:auto}
input#trans:hover{color:#FFFDFD;background-color:#B317F5;border:2px solid #B317F5}
@media screen and (max-width:340px){div#transition{width:50%}}
@media screen and (max-width:250px){input#trans{font-size:15px;font-family:droid arabic kufi}}
div#sorry{width:100%;height:100%;background-color:#F3A2A2;margin-top:2px;margin-right:0;color:#000;text-align:center}
/*الإعلانات السفلية*/
.Bottom-ads{width:96%;padding:0;text-align:center;margin:12px 0 20px 0}
.Bottom-ads img{transform:none}
.Bottom-ads img:hover{opacity:0.7;transform:scale(1.1)}
.Bottom-ads h5{background:linear-gradient(#3b2751,#422365);color:#fff;font-size:15px;font-family:droid arabic kufi;font-weight:normal;height:30px;margin:0 -8px 8px;text-align:center;line-height:32px;border-radius:0 0 11px 11px}
#ad1{width:20%;float:left;padding:0 7px 0 7px;background:#fff}
#ad2{width:20%;float:left;padding:0 7px 0 7px;margin:0 0 0 30px;background:#fff}
#ad3{width:20%;float:left;padding:0 7px 0 7px;margin:0 0 0 30px;background:#fff}
#ad4{width:20%;float:left;padding:0 7px 0 7px;margin:0 0 0 30px;background:#fff}
/*---سوشيال اسكويز ---*/
.social{width:100%;float:none;position:relative;height:50px;display:block;margin:0 auto;text-align:center;background:var(--color-Basics)}
ul.list-3{display:inline;line-height:57px;padding:0}
.social .list-3 li{vertical-align:top}
.social li{display:inline-block;margin:0 11px}
.list-3 li i{color:#fff;width:28px;height:28px;line-height:28px;margin-bottom:5px;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;display:inline-block;text-align:center;font-size:20px}
.social .fa-facebook,.fa-twitter {background:linear-gradient(#A468E6,#512484)}
.social .fa-rss:hover{background:linear-gradient(#F1861B,#D27009)}
.social .fa-twitter:hover{background:linear-gradient(#9CDCF5,#00ACED)}
.social .fa-facebook:hover{background:linear-gradient(#7B68E6,#073BA9)}
@media screen and (max-width:980px){ul.list-3{line-height:55px;padding:0 5px 0 5px}.social{height:45px}.list-3 li i{font-size:23px}}

#sharek{background-color:#cc0000;text-align:center;width:100%;font-size:15px;position:relative;bottom:0;padding-top:5px;padding-bottom:13px;color:#fff;border-top:1px solid}
img#emoge{width:30px;height:30px;margin:0}
/*زر تليجرام*/
 
div#telegram{bottom:1%;height:60px;position:fixed;left:10px;width:90px}
img#imgtelegram{width:60%;float:left;cursor:pointer}
@media screen and (max-width:980px){div#telegram{bottom:1%}}
/*إخفاء أداة اتصل بنا*/
#ContactForm1,#ContactForm1 br{display:none}
/*-----------*/
#scama {width: 100px; margin: auto;}
p#sh {text-align: center;color: #fff;}


/*---تذييل الموقع---*/
.footer {background:var(--color-footer)}
#credit{float:none;height:100px;line-height:45px;width:100%;margin:0 auto;padding-top:12px;text-align:center;color:#fff;font-size:18px}
#credit a{padding:0 8px 0 8px;border-radius:7px;display:inline;font-size:15px;color:#fff;background:var(--color-buttons)}
#credit a:hover{background:var(--color-hover)}
@media screen and (max-width:980px){#credit{font-size:15px}}
/*---تذييل الموقع---*/

/*التجاوب*/
@media screen and (max-width:980px){.bottomenu,.menu{display:none}#main-wrapper{width:100%}#sidebar-wrapper{float:left;width:100%}.section{width:100%}#header{float:none;width:100%}#outer-wrapper{padding:13px 3px}#header-wrapper{display:none}#header-mobile{display:block}.cnmunav,.cnmunav2{display:block}.cnmunav,.cnmunav2{color:#fff;background:var(--color-cnmunav);display:block;border: 1px solid #9d6e8b;float:right;font-size:15px;font-family:droid arabic kufi;width:99%;height:46px;text-align-last:center;border-radius:0 0 10px 10px}#cnmunav1{margin:0 2px 0 0}#cnmunav2{margin:2px 2px 0 0}div#ad1{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad2{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad3{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad4{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}h2{margin:0 0 10px 0}.nav-bar{height:35px;border-bottom:1px solid #A9A9A9}input#search-text{width:120px;height:28px;font-size:12px;border:0 solid #05741A;margin-left:2px;margin-top:3px}input#search-submit{height:30px;width:48px;border-radius:0 0 0 0;margin-top:3px;margin-left:1px}#b-Menu{height:0}img#Header1_headerimg{height:100%;max-width:100%}.post-body img{max-width:90%;height:inherit}#mov-text-1{display:none}
.thread-chrome .thread-expanded{margin-top:3px;margin-right:1%;padding:0 2px!important;width:95%} #w {margin-top: 4px}
.Label li a{width:40%}
.Label li span{width:40%}
}


/*---------*/
@media screen and (max-width:435px){.posts-thumb{float:none!important}.posts-thumb img{height:100%;width:100%;float:none}div#ad1{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad2{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad3{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad4{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}.saider-wrapper,.post-readmore a{display:none!important}
/*--------*/@media screen and (max-width:411px){.posts-thumb{float:none!important}.posts-thumb img{height:100%;width:100%;float:none}div#ad1{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad2{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad3{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad4{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}.post.hentry{font-size:19px}}
/*--------*/
@media screen and (max-width:320px){.posts-thumb{float:none!important}.posts-thumb img{height:100%;width: 100%;float:none}img#Image1_img{width:100%;height:100%}h5{height:30px;line-height:30px;font-size:12px}div#ad1{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad2{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad3{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}div#ad4{margin:0 0 10px 7px;width:40%;padding:0 7px 0 8px}input#search-text{width:144px;height:28px;font-size:12px;border:0 solid #05741A;border-radius:0 0 0 0;margin-left:2px;margin-top:2px}.post.hentry{font-size:18px}}
/*-------*/

/*------ تجاوب الفيديوهات start youtube responsive arabes1.com------*/
.post-body iframe{width:100%!important}
@media screen and (max-width:960px){.post-body iframe {max-height:90%!important}}
@media screen and (max-width:768px){.post-body iframe {max-height:75%!important}}
@media screen and (max-width:600px){.post-body iframe {max-height:60%!important}}
@media screen and (max-width:480px){.post-body iframe {height:0 auto!important;max-height:0 auto!important}}
@media screen and (max-width:640px){.post-body iframe {max-height:75%!important}}
}
 
