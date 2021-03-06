<!DOCTYPE html>
<!-- saved from url=(0053)https://www.kryptex.org/en/articles/radeon-rx-bios-en -->
<html lang="en" prefix="og: http://ogp.me/ns/website#" dir="ltr"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <title>⛏ Flashing AMD RX 470/480/570/580 BIOS | Kryptex</title>
  <meta name="author" content="Kryptex">
  <meta name="description" content="Learn how to safely boost your AMD GPU hashrates and profitability by up to 30%.">

  
  <link rel="canonical" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en">

  
  <meta property="vk:image" content="https://www.kryptex.org/static/images/vk_opengraph.35d5fadd710c.png">
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="Kryptex">
  <meta property="og:title" content="⛏ Flashing AMD RX 470/480/570/580 BIOS | Kryptex">
  <meta property="og:url" content="https://www.kryptex.org">
  <meta property="og:image" content="https://www.kryptex.org/static/images/opengraph.00a86b88cb1a.png">
  <meta property="og:description" content="Learn how to safely boost your AMD GPU hashrates and profitability by up to 30%.">

  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:site" content="@KryptexMining">
  <meta name="twitter:creator" content="@KryptexMining">
  <meta name="twitter:title" content="⛏ Flashing AMD RX 470/480/570/580 BIOS | Kryptex">
  <meta name="twitter:description" content="Learn how to safely boost your AMD GPU hashrates and profitability by up to 30%.">
  <meta name="twitter:image" content="https://www.kryptex.org/static/images/opengraph.00a86b88cb1a.png">
  <meta name="wot-verification" content="88b4a11fe3056a2e1d38">

  <link rel="stylesheet" href="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/public.3577e240670b.css">
  <link rel="stylesheet" href="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/css">

  <link rel="apple-touch-icon" sizes="180x180" href="https://www.kryptex.org/static/v2/favicons/apple-touch-icon.f078fb930f5c.png?v=2.0">
  <link rel="icon" type="image/png" sizes="32x32" href="https://www.kryptex.org/static/v2/favicons/favicon-32x32.0f654a027558.png?v=2.0">
  <link rel="icon" type="image/png" sizes="16x16" href="https://www.kryptex.org/static/v2/favicons/favicon-16x16.cbbdb19f46ea.png?v=2.0">
  <link rel="manifest" href="https://www.kryptex.org/static/v2/favicons/manifest.3af6346dc557.json?v=2.0">
  <link rel="shortcut icon" href="https://www.kryptex.org/static/v2/favicons/favicon.f584f0a8f436.ico?v=2.0">
  <meta name="msapplication-TileColor" content="#000000">
  <meta name="theme-color" content="#0173ec">

  
    <script async="" src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/fbevents.js.download"></script><script type="text/javascript" async="" src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/watch.js.download"></script><script async="" src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/analytics.js.download"></script><script async="" src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/gtm.js.download"></script><script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-KF8WWM5');</script>



    <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

        ga('create', 'UA-86497036-1', 'auto');
        
        ga('send', 'pageview');
        ga(function(tracker) {
            var clientId = tracker.get('clientId');
            document.cookie = 'GA_ClientId=' + clientId + "; path=/";
        });

    </script>



    <script type="text/javascript">
        (function (d, w, c) {
            (w[c] = w[c] || []).push(function() {
                try {
                    w.yaCounter40545065 = new Ya.Metrika({
                        id:40545065,
                        clickmap:true,
                        trackLinks:true,
                        accurateTrackBounce:true,
                        webvisor:true,
                        ut:"noindex"
                    });

                    
                } catch(e) { }
            });

            var n = d.getElementsByTagName("script")[0],
                s = d.createElement("script"),
                f = function () { n.parentNode.insertBefore(s, n); };
            s.type = "text/javascript";
            s.async = true;
            s.src = "https://mc.yandex.ru/metrika/watch.js";

            if (w.opera == "[object Opera]") {
                d.addEventListener("DOMContentLoaded", f, false);
            } else { f(); }
        })(document, window, "yandex_metrika_callbacks");
    </script>



  <script>
    window.mobilecheck = function () {
      var check = false;
      (function (a) { if (/(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(a) || /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(a.substr(0, 4))) check = true })(navigator.userAgent || navigator.vendor || window.opera)
      return check
    }

    function downloadGA(label, source) {
      ga('send', 'event', source, 'DownloadClick', label);

      if (!window.mobilecheck()) {
        window.setTimeout(function(){
          window.location.href = "/register?show_download_alert=true";
        }, 1000);
      }
    }
  </script>


  <noscript>
    <style type="text/css">
      [data-aos] {
        opacity: 1 !important;
        transform: none !important;
      }
    </style>
  </noscript>

  
    
    <link rel="alternate" hreflang="x-default" href="https://www.kryptex.org/articles/radeon-rx-bios-en">
<link rel="alternate" hreflang="en" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en">
<link rel="alternate" hreflang="es" href="https://www.kryptex.org/es/articles/radeon-rx-bios-en">
<link rel="alternate" hreflang="pt-br" href="https://www.kryptex.org/pt-br/articles/radeon-rx-bios-en">
<link rel="alternate" hreflang="ru" href="https://www.kryptex.org/ru/articles/radeon-rx-bios-en">
<link rel="alternate" hreflang="zh-hans" href="https://www.kryptex.org/zh-hans/articles/radeon-rx-bios-en">


<style type="text/css">.medium-zoom-overlay{position:fixed;top:0;right:0;bottom:0;left:0;opacity:0;transition:opacity .3s;will-change:opacity}.medium-zoom--opened .medium-zoom-overlay{cursor:pointer;cursor:zoom-out;opacity:1}.medium-zoom-image{cursor:pointer;cursor:zoom-in;transition:transform .3s cubic-bezier(.2,0,.2,1)!important}.medium-zoom-image--hidden{visibility:hidden}.medium-zoom-image--opened{position:relative;cursor:pointer;cursor:zoom-out;will-change:transform}</style></head>
<body class="bg-dark vsc-initialized">
  
  





<header class="page-header page-header--light">
  <div class="container">
    <div class="row justify-content-between justify-content-lg-start align-items-center page-header__content no-gutters">
      <div class="page-header__logo">
        <a class="logo" href="https://www.kryptex.org/en/" aria-label="Kryptex Home">
          <img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/kryptex-logo-theme-light.svg" alt="Kryptex">
        </a>
      </div>

      <div class="col page-header__nav ml-lg-5 ml-l-6" id="headerNav">
        <div class="page-header__main-nav pt-6 pt-lg-0">
          <nav class="page-header__nav-item" aria-labelledby="kryptex-nav">
            <div class="page-header-nav-tooltip tooltip tooltip--hover-mode">
              <div class="tooltip__single">
                <h2 class="page-header__nav-title mb-0" id="kryptex-nav">Products</h2>
                <svg><use xlink:href="/static/v2/dist/svg-shared-sprite.1201dc37fc91.svg#sprite-chevron-right"></use></svg>
              </div>
              <div class="tooltip__dropdown">
                <div class="tooltip__dropdown-inner">
                  <ul class="list-unstyled">
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/">Kryptex Miner</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/pro-app">Kryptex Pro</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/os">Kryptex OS</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/pools">Mining Pools</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/rent-cloud-gpus">Rent our GPUs</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/features">Features</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/fees">Fees</a></li>
                  </ul>
                </div>
              </div>
            </div>
          </nav>
          <nav class="page-header__nav-item" aria-labelledby="community-nav">
            <div class="page-header-nav-tooltip tooltip tooltip--hover-mode tooltip--arrow-helper-light">
              <div class="tooltip__single">
                <h2 class="page-header__nav-title mb-0" id="community-nav">Resources</h2>
                <svg><use xlink:href="/static/v2/dist/svg-shared-sprite.1201dc37fc91.svg#sprite-chevron-right"></use></svg>
              </div>
              <div class="tooltip__dropdown">
                <div class="tooltip__dropdown-inner">
                  <ul class="list-unstyled">
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/best-gpus-for-mining">Best Mining GPUs</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/mining-calculator">Mining Calculator</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/articles/">Articles</a></li>
                    <li><a class="page-header-nav-tooltip__link" href="https://www.kryptex.org/en/news/">News</a></li>
                  </ul>
                </div>
              </div>
            </div>
          </nav>
        </div>
        <nav class="page-header__sub-nav mb-5 mb-lg-0">
          <ul class="list-unstyled d-flex align-items-center justify-content-center">
            
              <li class="mx-3 mx-lg-2">
                <a href="https://www.kryptex.org/login" class="btn btn-sm btn-transparent btn-header-theme-light">Log In</a>
              </li>
              <li class="mx-3 mx-lg-2">
                <a href="https://www.kryptex.org/register" class="btn btn-sm btn-outline-primary px-4 btn-rounded btn-header-theme-light">Create Account</a>
              </li>
            
            <li style="font-size: 0">
              <div class="tooltip tooltip--lang-dropdown tooltip--arrow-helper tooltip--arrow-helper-light d-inline-block tooltip--hover-mode ml-lg-4">
                <div class="tooltip__single">
                  <div class="d-flex align-items-center">
                    
                    <svg class="flag-icon"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-en"></use></svg>
                  </div>
                </div>
                <div class="tooltip__dropdown">
                  <div class="tooltip__dropdown-inner">
                    <form class="p-2" action="https://www.kryptex.org/i18n/setlang/" method="post">
                      <div class="px-1 pt-1 pb-0">
                        <input type="hidden" name="csrfmiddlewaretoken" value="VkdpdVz5Ww0CnJz7HMKxv1bt9kJ6W5TErsl9HKRy1Ihnubor0fuN0XeobAdcW8Ig">
                        <input name="next" type="hidden" value="/articles/radeon-rx-bios-en">
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="en">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-en"></use></svg>
                            <span>English</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="es">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-es"></use></svg>
                            <span>Español</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="pt-br">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-pt-br"></use></svg>
                            <span>Português</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="ru">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-ru"></use></svg>
                            <span>Русский</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="zh-hans">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-zh-hans"></use></svg>
                            <span>简体中文</span>
                          </button>
                        
                      </div>
                    </form>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </nav>
      </div>

      <div class="d-flex justify-content-end d-lg-none">
        <button class="page-header__nav-icon nav-icon" type="button" id="headerNavToggle">
          <div class="nav-icon__inner">
            <span></span>
            <span></span>
          </div>
        </button>
      </div>
    </div>
  </div>
</header>



  <main class="page-main">
    
<div class="bg-white pb-6 pb-lg-7">
  <div class="border-bottom border-light-100">
    <div class="container">
      <div class="row">
        <div class="col-12 py-4">
          <ul class="breadcrumbs">
            <li><a href="https://www.kryptex.org/en/articles/" class="d-inline-block p-1">Articles</a></li>
            <li><a href="https://www.kryptex.org/en/articles/category/hardware" class="d-inline-block p-1">Hardware</a></li>
            <li>Flashing AMD RX 470/480/570/580 BIOS</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div class="container py-4 pb-md-7">
    <div class="row mt-4 mt-lg-6">
      <div class="col-md-3 mb-4">
        
        <h2 class="h4 mb-3"><b>This article is available in other languages:</b></h2>
        <ul class="mb-4 mb-lg-5 p-0 pb-2 pb-lg-0">
          
          <a href="https://www.kryptex.org/articles/radeon-rx-bios-en" lang="en" class="d-flex align-items-center mb-2">
            <svg class="icon icon--flag"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-en"></use></svg>
            <span class="ml-2">English</span>
          </a>
          
          <a href="https://www.kryptex.org/articles/radeon-rx-bios-ru" lang="ru" class="d-flex align-items-center mb-2">
            <svg class="icon icon--flag"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-ru"></use></svg>
            <span class="ml-2">Русский</span>
          </a>
          
        </ul>
        
        <h2 class="h4 mb-3"><b>Table of contents</b></h2>
        <nav>
          <ul class="list mr-lg-3 pr-lg-2">
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-0--Why-bother?">Why bother?</a></li>
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-1--Which-cards-can-be-reflashed-using-this-method?">Which cards can be reflashed using this method?</a></li>
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-2--Are-there-any-risks?">Are there any risks?</a></li>
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-3--Go-go,-Power-Flashers!">Go-go, Power Flashers!</a></li>
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-4--In-case-something-went-wrong">In case something went wrong 🛑</a></li>
            
              <li class="mb-2"><a class="text-link toc-link" href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#step-5--Troubles-flashing?-On-our-way-to-help!">Troubles flashing? On our way to help! 🚑</a></li>
            
          </ul>
        </nav>
      </div>

      <div class="col-md-9">
        <article class="page-article">
          <h1 class="mb-2">Flashing AMD RX 470/480/570/580 BIOS</h1>
          <div class="mb-3">
            <span class="text-dark-light">March 5, 2019, 10:25 p.m.</span>
          </div>
          <p>Stock AMD RX 470/480/570/580/590 are capable of 22-24 MHs/s mining Ethereum using DaggerHashimoto. You can push up to 25-27 Mh/s by tuning the memory clock. We covered this approach <a href="https://www.kryptex.org/en/articles/ethereum-gpu-overclocking-en">here</a>, yet, you still can squeeze some more by reflashing your GPU's BIOS with lower memory timings.</p>

<p>Lowering memory <em>timings</em> may help to push a card even further and provide up to 31 Mh/s — a 7-9Mh/s increase! The only way to do so with an AMD GPU is <strong>to flash BIOS</strong>. For Nvidia cards, there is <a href="https://www.kryptex.org/articles/ethlargementpill-en">"The Pill"</a>.</p>

<h2 id="step-0--Why-bother?">Why bother?</h2>

<p>RAM and VRAM are types of Dynamic Random-Access Memory. As a whole, it has two major parameters:</p>

<ol>
<li><p><strong>Frequency</strong>, which impacts the memory's speed. The higher the value, the faster the data is transferred.</p></li>
<li><p><strong>Timings</strong>, which define the latency between read and write operations. These latencies are crucial for stable memory performance, but they are not optimized with mining in mind. We can fix that 😏</p></li>
</ol>

<blockquote>
  <p>Imagine yourself driving a Ferrari. Your car can reach 250 Km/h of <em>frequency</em>. But, you are always stuck at traffic lights of <em>timing/latency</em> at every corner. So, what is the point of that <em>speed</em> limited by <em>obstacles</em>?</p>
</blockquote>

<p>There are three ways to boost DRAM chips:</p>

<ul>
<li>Raise frequency;</li>
<li>Lower timings;</li>
<li><strong>Or both</strong>. Why not?</li>
</ul>

<h2 id="step-1--Which-cards-can-be-reflashed-using-this-method?">Which cards can be reflashed using this method?</h2>

<p>Theoretically speaking, any kind. But most of the cards would require complicated microcode edits. AMD 400/500 series, on the other hand, allows you to use Polaris BIOS Editor app to apply custom modifications. It is a simple method which doesn't require any specialized hardware.</p>

<h2 id="step-2--Are-there-any-risks?">Are there any risks?</h2>

<p>Indeed, there <em>are</em> some risks associated with BIOS modifications, but with careful planning and following our instructions, those risks are easily avoidable.</p>

<h3>Warranty void</h3>

<p>No service center will provide you with free maintenance if they find out that any BIOS changes were applied. Reverse all the modifications before handing your GPU to a vendor.</p>

<h3>Potentially shorter life-span</h3>

<p>Manufacturers test their product using stock parameters and make assumptions about life-span, assuming that the product is working in the same conditions as a test bench. Pushing your GPU's capabilities beyond those may bring unpredictable consequences to card's work state and lifetime. Frankly, that applies to any overclocking and the mining process itself, so...</p>

<h3>Unstable mining</h3>

<p>Mining relies on long-term stability and reliability, not immediate blast power. The Ferrari example above is still applicable — there is no point of going lightning fast for a split second just to get stuck turning into a snail a moment later. <br>
It's not only about miner crashing or PC hanging. It's also about calculations precision. Overstressed GPU might think that <code>2+2=5</code>, thus generating an invalid share. Such shares do not get rewarded by a pool; therefore your profitability will decrease.</p>

<h3>Visual artifacts in games</h3>

<p>Flashed GPUs are prone to display random green lines or blinking noisy squares on a screen while playing games. Sometimes the driver can even stop responding, resulting in an immediate game crash or even a BSOD.</p>

<blockquote>
  <p><strong>Be conscious about the risks</strong> before considering modifying the timings. Test your GPU thoroughly after flashing or stick to a soft <a href="https://www.kryptex.org/en/articles/ethereum-gpu-overclocking-en">memory overclock</a> if in doubt.</p>
</blockquote>

<h2 id="step-3--Go-go,-Power-Flashers!">Go-go, Power Flashers!</h2>

<blockquote>
  <p>The process may seem complicated. But, if you'll carefully follow these steps, everything will work out. </p>
</blockquote>

<p>You will need to:</p>

<ol>
<li>Install an <a href="https://www.amd.com/en/support/kb/release-notes/rn-rad-win-blockchain-beta">AMD-blockchain-driver</a>. This driver is optimal for mining;</li>
<li>Apply <a href="https://www.monitortests.com/forum/Thread-AMD-ATI-Pixel-Clock-Patcher">atikmdag-patcher</a> to bypass driver's BIOS validation;</li>
<li>Figure out your memory's manufacturer and backup stock BIOS, both using <a href="https://www.techpowerup.com/download/techpowerup-gpu-z/">GPU-Z</a>;</li>
<li>Modify BIOS with <a href="https://github.com/vvaske/PolarisBiosEditor">Polaris BIOS Editor</a>;</li>
<li>Flash it with <a href="https://www.techpowerup.com/download/ati-winflash/">AtiWinFlash</a>;</li>
</ol>

<p class="page-article__img-wrap">The process for AMD 400 and 500 series is the same. In our example, we are using MSI RX480 GamingX with Samsung memory chips. Performance is measured for Ethereum mining. The stock performance is 24Mh/s.
<img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/JeRxXPe.png" alt="" class="medium-zoom-image">
We've got 27Mh/s after applying a memory overclock. That's 12% more than stock. All right, but not very impressive.
<img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/yySnbqy.png" alt="" class="medium-zoom-image"></p>

<h3>Install an optimal driver</h3>

<p>Install the special <a href="https://www.amd.com/en/support/kb/release-notes/rn-rad-win-blockchain-beta">AMD blockchain driver</a>. Reboot your PC after the installation is complete.</p>

<h3>Apply the patch</h3>

<p>Launch <a href="https://www.monitortests.com/forum/Thread-AMD-ATI-Pixel-Clock-Patcher">atikmdag-patcher.exe</a> to disable BIOS checksum check. A driver will be unable to detect your GPU after BIOS reflash if you skip this step.</p>

<p class="page-article__img-wrap"><img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/uHa5bz2.png" alt="" class="medium-zoom-image"></p>

<h3>Backup your stock BIOS</h3>

<p>Using <a href="https://www.techpowerup.com/download/techpowerup-gpu-z/">GPU-Z</a> do the following:</p>

<ul>
<li>Find out what memory chips are installed on your board;</li>
<li><p>Backup the stock BIOS:</p>

<ol>
<li>Click on the arrow under AMD Radeon logo;</li>
<li>"Save to file..." and choose the folder to backup your BIOS to.</li>
</ol>

<p class="page-article__img-wrap"><img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/JbHEqWc.png" alt="" class="medium-zoom-image"></p>

<blockquote>
  <p><strong>Copy the file to a secure place, i.e., Google Drive. You'll be able to safely revert any changes using the original BIOS.</strong></p>
</blockquote></li>
</ul>

<h3>Modify the BIOS</h3>

<p>Open <a href="https://github.com/vvaske/PolarisBiosEditor">Polaris Bios Editor</a>. It allows you to change clock speeds, voltages, TDP, temp limits and <strong>timings</strong> directly in BIOS.</p>

<p class="page-article__img-wrap">Click "OPEN BIOS" at the top left corner and select a file you have just dumped using GPU-Z.
<img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/0yrm7hV.png" alt="" class="medium-zoom-image"></p>

<p>Pay attention to a section in a lower-right. For each memory clock available for a GPU you'll find a <em>Timing Strap</em> value, which can be modified in three ways:</p>

<ul>
<li>Using "ONE CLICK TIMING PATCH" button. The app will automatically set timings from a safe built-in preset. Choose this option if you are not sure what timings you should set.</li>
<li><p class="page-article__img-wrap">Shift the values up and use N-th <em>timing strap</em> for an N-1 frequency, as shown in the picture below:
<img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/9zLhDZf.png" alt="" class="medium-zoom-image"></p></li>
<li><p>Find the best strap value for your card/memory vendor on the Internet. We consider this method the riskiest since a card might not boot up if the incorrect timings applied.</p></li>
</ul>

<p>After finishing all the manipulations, save your modified BIOS to a <strong>separate</strong> file.</p>

<blockquote>
  <p><strong>Do not overwrite stock BIOS! Use self-explanatory names to distinguish different BIOSes.</strong></p>
</blockquote>

<h3>Flash your new BIOS</h3>

<p>Launch <a href="https://www.techpowerup.com/download/ati-winflash/">AtiWinFlash</a> with an 🛡Administrator Privileges.</p>

<p class="page-article__img-wrap"><img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/rg7QTus.png" alt="" class="medium-zoom-image"></p>

<ol>
<li>Select the required card, if there are several in your PC;</li>
<li>Click on "Load Image" to select the <em>modified</em> BIOS file;</li>
<li>Finish with "Program" button, flashing the code to the memory;</li>
<li>Reboot your PC.</li>
</ol>

<h3>Who is awesome? You are awesome!</h3>

<p class="page-article__img-wrap">You got it! The GPU is ready to bring you millions... well, maybe not dollars, but hashes for sure!
Remember that RX480 from the beginning? <em>This is him now</em> at stock clocks:
<img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/0hNoBge.png" alt="" class="medium-zoom-image">
Overclocking helps to achieve up to 30-31 Mh/s. In total, that's a 25% boost compared to stock BIOS and clocks.</p>

<h2 id="step-4--In-case-something-went-wrong">In case something went wrong 🛑</h2>

<p>Flash your stock BIOS back if you notice some unusual behavior.</p>

<h3>Display goes blank</h3>

<p>Connect your output cable to an integrated graphics or to a different GPU if you have several. Use the same AtiWinFlash steps to revert your card to a stock BIOS.</p>

<h3>AtiWinFlash doesn't detect a card</h3>

<p>Contact the closest service center and ask a professional to use programmer hardware to flash your stock BIOS. Make sure to grab a thumb drive with BIOS dump.</p>

<h3>Card is not detected by a driver</h3>

<p>Run atikmdag-patcher one more time.</p>

<h3>Lost stock BIOS</h3>

<p>Try searching <a href="https://www.techpowerup.com/vgabios/">Techpowerup BIOS database</a>. Make sure BIOS you download corresponds to your GPU's memory vendor. For example, a GPU with Samsung's VRAM will not work with Micron's BIOS.</p>

<h2 id="step-5--Troubles-flashing?-On-our-way-to-help!">Troubles flashing? On our way to help! 🚑</h2>

<p>Fear not! Message us, we’ll help with any issue 💪🏻 Replies are given within one day.</p>

<ul>
<li><a href="https://www.kryptex.org/en/support/tickets">Via web form</a>;</li>
<li><a href="https://t.me/KryptexSupport">Via telegram</a>;</li>
<li><a href="https://www.facebook.com/kryptex.org/">On facebook</a>;</li>
<li>Or email us to support@kryptex.org directly.</li>
</ul>

        </article>

        <div style="max-width: 620px;">
          
          <div id="vk_comments"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
  function slugify(text) {
    return text.toString()
      .replace(/\s+/g, '-')
      .replace(/(\u00a9|\u00ae|[\u2000-\u3300]|\ud83c[\ud000-\udfff]|\ud83d[\ud000-\udfff]|\ud83e[\ud000-\udfff])/g, '')
      
      .replace(/\-\-+/g, '-')
      .replace(/^-+/, '')
      .replace(/-+$/, '');
  }

  window.addEventListener('load', function() {
    var headings = document.querySelectorAll('.page-article h2');
    var tocLinks = document.querySelectorAll('.toc-link');

    for(var i = 0; i < tocLinks.length; i++) {
      var url = 'step-'+ i + '--' + slugify(tocLinks[i].text)
      tocLinks[i].href = '#' + url
      headings[i].id = url
    }

    
    
  })
</script>

<!-- code highlight -->
<script src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/highlight.min.js.download"></script>
<script>hljs.initHighlightingOnLoad();</script>


  </main>

  
  





<footer class="page-footer bg-pattern">
  <div class="container">
    <div class="row">
      <div class="col-12">
        
          <div class="banner banner--footer">
            <div class="banner__inner row align-items-center py-4 py-md-0 px-3 px-md-4 px-lg-5">
              <div class="col-md-6 text-center text-md-left mb-3 pt-2 mb-md-0 pt-md-0">
                <h2 class="banner__title h4 text-white font-weight-semibold text-uppercase">
                  
                    <span>Ready to get started?</span>
                  
                </h2>
              </div>
              <div class="col-md-6 d-flex justify-content-center justify-content-md-end pb-2 pb-md-0">
                
                  <a href="https://www.kryptex.org/download?source=kb_article_v5" onclick="downloadGA(&#39;bottom&#39;, &#39;kb_article_v5&#39;)" class="btn btn--shiny banner__btn btn-lg text-white btn-icon btn-icon-md btn-icon-light btn-check-mobile">
                    <span class="btn-shine"></span>
                    <div class="btn-icon__wrap mr-3">
                      <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-arrow-down"></use></svg>
                    </div>
                    <span>Download Kryptex</span>
                  </a>
                
              </div>
            </div>
          </div>
        
      </div>


      <div class="col-12">
        <div class="row no-gutters pt-5 pt-md-7 pb-1">
          <div class="col-md-3 mb-5">
            <div class="page-footer__logo">
              <a class="logo" href="https://www.kryptex.org/en/" aria-label="Kryptex Home">
                <img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/kryptex-logo-theme-dark.svg" alt="Kryptex">
              </a>
            </div>
            <div class="d-inline-flex align-items-center mt-5">
              <span class="page-footer__nav-title mb-0 text-white font-weight-bold text-uppercase line-normal">Language</span>
              <div class="tooltip tooltip--lang-dropdown tooltip--arrow-helper tooltip--arrow-helper-light tooltip--hover-mode ml-3">
                <div class="tooltip__single">
                  <div class="d-flex align-items-center">
                    
                    <svg class="flag-icon"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-en"></use></svg>
                  </div>
                </div>
                <div class="tooltip__dropdown">
                  <div class="tooltip__dropdown-inner">
                    <form class="p-2" action="https://www.kryptex.org/i18n/setlang/" method="post">
                      <div class="px-1 pt-1 pb-0">
                        <input type="hidden" name="csrfmiddlewaretoken" value="VkdpdVz5Ww0CnJz7HMKxv1bt9kJ6W5TErsl9HKRy1Ihnubor0fuN0XeobAdcW8Ig">
                        <input name="next" type="hidden" value="/articles/radeon-rx-bios-en">
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="en">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-en"></use></svg>
                            <span>English</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="es">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-es"></use></svg>
                            <span>Español</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="pt-br">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-pt-br"></use></svg>
                            <span>Português</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="ru">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-ru"></use></svg>
                            <span>Русский</span>
                          </button>
                        
                          <button class="btn bg-transparent text-hover-primary d-flex align-items-center p-0 pb-1" type="submit" name="language" value="zh-hans">
                            <svg class="flag-icon mr-2"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-flag-zh-hans"></use></svg>
                            <span>简体中文</span>
                          </button>
                        
                      </div>
                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <nav class="page-footer__nav col-md-3 mb-5 mb-lg-0">
            <h2 class="page-footer__nav-title"><b>Products</b></h2>
            <ul class="page-footer__link-list">
              <li><a href="https://www.kryptex.org/en/">Kryptex Miner</a></li>
              <li><a href="https://www.kryptex.org/en/pro-app">Kryptex Pro</a></li>
              <li><a href="https://www.kryptex.org/en/os">Kryptex OS</a></li>
              <li><a href="https://www.kryptex.org/en/pools">Mining Pools</a></li>
              <li><a href="https://www.kryptex.org/en/rent-cloud-gpus">Rent our GPUs</a></li>
              <li><a href="https://www.kryptex.org/referral/" target="_blank">Referral program</a></li>
              <li><a href="https://www.kryptex.org/en/features">Features</a></li>
              <li><a href="https://www.kryptex.org/en/fees">Fees</a></li>
            </ul>
          </nav>

          <nav class="page-footer__nav col-md-3 mb-5 mb-lg-0">
            <h2 class="page-footer__nav-title"><b>Tools</b></h2>
            <ul class="page-footer__link-list">
              <li><a href="https://www.kryptex.org/en/best-gpus-for-mining">Best Mining GPUs</a></li>
              <li><a href="https://www.kryptex.org/en/mining-calculator">Mining Calculator</a></li>
              <li><a href="https://www.kryptex.org/en/articles/">Articles</a></li>
              <li><a href="https://www.kryptex.org/en/news/" target="_blank">News</a></li>
              <li><a href="https://www.kryptex.org/en/ideas" target="_blank">Ideas</a></li>
              <li><a href="https://www.kryptex.org/en/support/faq" target="_blank">FAQ</a></li>
            </ul>
          </nav>
          <nav class="page-footer__nav col-md-3 mb-5 mb-lg-0">
            <h2 class="page-footer__nav-title"><b>Resources</b></h2>
            <ul class="page-footer__link-list">
              <li><a href="https://www.kryptex.org/r/youtube-XYGWLW" target="_blank">Watch us on Youtube</a></li>
              <li><a href="mailto:partners@kryptex.org" target="_blank">Partnership inquiries</a></li>
              <li><a href="https://www.kryptex.org/terms-and-conditions" target="_blank">Terms of service</a></li>
              <li><a href="https://www.kryptex.org/en/support/tickets" target="_blank">Support</a></li>
              <li><a href="https://www.kryptex.org/site/dashboard" target="_blank">Statistics</a></li>
              <li><a href="https://www.kryptex.org/billing/payouts/request/btc" target="_blank">Payouts</a></li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </div>

  <div class="page-footer__bottom container-fluid">
    <div class="row no-gutters justify-content-md-end pr-5 pb-5">
      <a href="https://www.kryptex.org/en/articles/radeon-rx-bios-en#" data-smooth-scroll="" class="btn btn-sm px-2 scroll-up" aria-label="Go Up">top</a>
    </div>
    <div class="row no-gutters align-items-center py-4 p-lg-4 p-xl-5 border-top">
      <div class="col-md-6 order-1 order-md-0">
        <p class="text-middle font-weight-semibold text-center text-md-left mb-0">© 2020 Kryptex. All rights reserved.</p>
      </div>
      <div class="col-md-6 mb-3 mb-md-0">
        <ul class="social-list">
          <li class="social-list__link">
            <a href="https://t.me/kryptex_chat_en" target="_blank" aria-label="Telegram">
              <svg style="margin-left: -1px"><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-telegram"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://vk.com/kryptex" target="_blank" aria-label="VK">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-vk"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://www.facebook.com/kryptex.org" target="_blank" aria-label="Facebook">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-facebook"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://twitter.com/KryptexMining" target="_blank" aria-label="Twitter">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-twitter"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://www.instagram.com/kryptex" target="_blank" aria-label="Instagram">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-instagram"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://www.reddit.com/r/kryptex/" target="_blank" aria-label="Reddit">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-reddit"></use></svg>
            </a>
          </li>
          <li class="social-list__link">
            <a href="https://www.youtube.com/c/KryptexMining" target="_blank" aria-label="Youtube">
              <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-logo-youtube"></use></svg>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</footer>

<div class="mobile-alert">
  <div class="d-flex align-items-center justify-content-between">
    <a class="logo" href="https://www.kryptex.org/en" aria-label="Kryptex Home">
      <img src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/kryptex-logo-theme-dark.55088de914b9.svg" alt="Kryptex Logo">
    </a>
    <button class="mobile-alert__cross">
      <svg><use xlink:href="/static/v2/dist/svg-public-sprite.8165815aa3d1.svg#sprite-cross"></use></svg>
    </button>
  </div>
  <div>
    <img class="mobile-alert__image" src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/dead-pc.053801b7d65c.svg" alt="Dead-PC">
    <h2>Kryptex is a desktop application. Download the app to your PC after signing up.</h2>
  </div>
  <div>
    <a href="https://www.kryptex.org/register" class="btn btn-block btn-primary-gradient justify-content-center btn-lg text-white mb-1">
      <span>Register</span>
    </a>
  </div>
</div>

    <script type="application/ld+json">
    {
      "@context": "https://schema.org/",
      "@type": "Product",
      "name": "Flashing AMD RX 470/480/570/580 BIOS",
      "brand": {
        "@type": "Service",
        "name": "Kryptex"
      },
      "aggregateRating": {
        "@type": "AggregateRating",
        "ratingValue": "4.6",
        "ratingCount": "89"
      }
    }
  </script>

  



  <script src="./⛏ Flashing AMD RX 470_480_570_580 BIOS _ Kryptex_files/public.521262af4928.js.download"></script>
  <!-- VK Pixel Code -->
  <script type="text/javascript">(window.Image ? (new Image()) : document.createElement('img')).src = location.protocol + '//vk.com/rtrg?r=o3CgO3mu6WwYpFjWaMCcHx38Db28K*2vn7ZmKmWMVOik2*GbEhR5pAPtJKRN9PSuwMtbJh86ljttJ*Eipu3cEhFaLyz4LDSISGa2J00OmNWKF58vb/hlANW2SkldgbgNpCG9hSFU8DfX8hYxl/CY1bcuiFwNtxeKtW/e/me*uYU-&pixel_id=1000050327';</script>
  <!-- End of VK Pixel Code -->

  <!-- Facebook Pixel Code -->
  <script>
  !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
  n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
  document,'script','https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '241850522927872');
  fbq('track', 'PageView');
  </script>
  <!-- End of Facebook Pixel Code -->


</body></html>
