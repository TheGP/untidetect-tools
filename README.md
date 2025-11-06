# Curated anti-detect tools list  
Just making a tools list for my project, feel free to send pull requests :) 
While looking around, it may be a good idea to sign up on all the Discord channels each product has to find some interesting insides from users.

<table>
  <tr>
    <td><img src="https://files.eugenebos.com/untidect-hub-circle-opt.png" width="150"/></td>
    <td>
Any questions? Please ask in <a href="https://t.me/UntidetectHub">UntidetectHub</a> instead of sending me private messages.
If you're working on anything related to anti-detection, feel free to join — others might be working on similar things too.
    </td>
  </tr>
</table>

✳️ checkout new [Proxy Providers List](https://github.com/TheGP/Proxy-Providers-List) and tell me if its sucks or star it if its useful 

😊 - automation supported on free plan 🙄 - not supported

# Anti-detect browsers
* [Gologin](https://go.gologin.com/secretbonus-IFOGFRB) - 3 free for 1 month, $24 for 100 profiles, no unlimited plan, free proxies 🙄
* [Undetectable](https://undetectable.io/?r=AXCFe) - 5 cloud profiles free, $49 for unlimited local with 25 "configs", 1 additional config $1 (API + driver automation) 🙄
* [NSTBrowser](https://app.nstbrowser.io/r/NZ0daY) - 10 profiles open/day free, $29(299) for 3000 open profiles per day, quite new on the market 😊
* [Multilogin](https://multilogin.com/#a_aid=secretbonus3) - starts from €74 for 100 profiles  
* [Incogniton](https://incogniton.com/aff/620515/) - 10 free for 2 months then 3 only, $29.99/Month for 50 🙄
* [AdsPower](https://share.adspower.net/YyHH9v) - 2 profiles free, $5.4 for 10 profiles, no unlimited plan 🙄
* [Morelogin](https://www.morelogin.com/?from=AAA2qquLhqBd) - 2 free, $9 for 10 profiles and 2 users 😊
* [Dolphin-anty](https://dolphin-anty.com/a/3047556) - 5 free, $89 for 100 😊
* [RoxyBrowser](https://roxybrowser.com?code=1105EASA) - 5 free, $0.03-0.8 profile, offers free Netflix
* [Octo Browser](https://go.octobrowser.net/signup/?p=10006676) - starts from €21 for 10  
* [Kameleo](https://kameleo.io/?ref=21669) - starts €59/user with unlimited profiles  
* [Vmlogin](https://www.vmlogin.us/) - $99 for 200 profiles  
* [Indigo](https://indigobrowser.com/) - €99 for 100 profiles  
* [GhostBrowser](https://ghostbrowser.com/) - 4 profiles free, $21 unlimited ?
* [Bablosoft](https://bablosoft.com/shop/BrowserAutomationStudio) - free browser automation studio, for Puppeteer look at [puppeteer-with-fingerprints](https://github.com/CheshireCaat/puppeteer-with-fingerprints), the only browser as I know that supports faking canvas (with [PerfectCanvas](https://wiki.bablosoft.com/doku.php?id=perfectcanvas). If you need a code for your website to generate own canvases I can sell you it. Then you can add it to your fingerprints (Their PerfectCanvas is very slow and you can get only 30-40 per day, otherwise you will need to buy CustomServer) 😊
* [ixBrowser](https://www.ixbrowser.com/code/FW89) - free 10/created a day, but doesn't mask everything (for example, no GPU masking) 🙄
* [Gpmlogin](https://gpmloginapp.com/en) - didn't check it yet, pricing is for unlimited use, for 1pc it is $125
* [VektorT13](https://detect.expert/antidetect/) - anti-detect based on virtual machines
* [Wade](https://wade.is/) - from $30/month, automation from $160 🙄
* [Camoufox](https://camoufox.com/) - launched via Python, based on Firefox 😊
* [BitBrowser](https://www.bitbrowser.net/) - 10 free, 50/$9, antidetect from Hong Kong 😊

Not checked yet:
* [HideMyAcc](https://go.hidemyacc.com/github) - 7 days free, $5 for 5 profiles
* [LightPanda](https://lightpanda.io/) - not anti-detect, but fast browser for scraping 😊
* [Whologin](https://whologin.com/) - free plan has unlimited profiles but no automation. paid - $89/everything 🙄
* [PotaBrowser](https://github.com/snaberino/pota-browser) - patched chromium
* [ChromePowerApp](https://github.com/zmzimpl/chrome-power-app) - chinese multiaccounter (but fingerprints are weak, cant change screen, fonts, GPU) 😊
* [0detect](http://0detect.com/en/auth/signup?refId=684ee1b890abd5c0fe3d9e51) - 5 free, 50/$14, automation from $111 🙄
* [ADBLogin](https://adblogin.com) - The First anti-detect browser free forever
* [LinkenSphere](https://linkensphere.info/en/) - $30+/month. One of people found hidden process that it runs, can anyone confirm it?
* [DisCloak](https://dicloak.com) - 5 free, $8/50 profiles
<!--* [Afina](https://afina.io/en) - from $35/m unlimited profiles-->

Useless:
* [AntBrowser](https://antbrowser.pro) - too many lies detected by CreepJS
* [Switch Antidetect](https://switch.mybot.su) - using Chrome 103 while 120 is out. Too slow updates.
* [GhostBrowser](https://ghostbrowser.com/) - only user-agent switch, easily fingerprinted
* [MarketerBrowser](https://www.marketerbrowser.com/) - can't even switch user-agent without detection

A bit old [article on how anti-detect browsers can be detected](https://cpa.rip/stati/antidetect-palivo/). Example from the article: `if( Object.getOwnPropertyNames(navigator)[0] ) alert('fake parameters detected');`
  
# Detection tests

* [Creep JS](https://abrahamjuliot.github.io/creepjs/) - the advanced detector
* [Brotector](https://kaliiiiiiiiii.github.io/brotector/) - the most advanced detector, crushes automation on detect
* [Pixelscan](https://pixelscan.net/) - simple fingerprint checker
* [F.vision](https://fv.pro/check-privacy/general) - old f.vision
* [NikolaiT/zardaxt](https://github.com/NikolaiT/zardaxt) - Passive TCP/IP fingerprinting (look for Live demo link)
* [Coveryourtracks](https://coveryourtracks.eff.org/) - test to see if you are protected from fingerprinting  
* [ReCaptha score](https://antcpt.com/score_detector/) - see you reCaptcha score  
* [AmIUnique Fingerprint](https://amiunique.org/fingerprint) - see your fingerprint  
* [Sannysoft Fingerprint](https://bot.sannysoft.com/) - check your fingerprint  
* [BrowserLeaks](https://browserleaks.com/)  
* [Extension-detector](https://z0ccc.github.io/extension-detector/)
* [Audio fingerprint](https://audiofingerprint.openwpm.com/)
* [Behavioral Bot Classification](https://bot.incolumitas.com/)
* [Canvas Tampering Detection](https://kkapsner.github.io/CanvasBlocker/test/detectionTest.html)
* [ProxyDetect](https://proxy.incolumitas.com/proxy_detect.html) - detection of proxy/vpn
* [WebbrowserTools](https://webbrowsertools.com/) - many tools to check fingerprint
* [My own tool](https://reviewer.eugenebos.com/test) - the only benefit the code is plain, so you can find very easily how everything is tested.
* [Rebrowser-bot-detector](https://bot-detector.rebrowser.net/) - interesting test where you have to do some automation tasks and it will try to detect you
* [BotChecker](https://botchecker.net/) 

Others:
* [BrowserScan](https://www.browserscan.net/en)
* [Iphey](https://iphey.com/)
* [Canvas inspector](https://data.bablosoft.com/canvas-inspector-3/distr/CanvasInspectorInstall.exe)
* [ipQualityScore](https://www.ipqualityscore.com/) - API for checking your IP reputation and other stuff. But it is dogshit, as I can't register there from real devices, it says Im using VPN/proxy. Maybe only for USA.
* [FingerBank](https://fingerbank.org/) - API for checking TCP fingerprints by signature
* [Cloudflare captcha](https://nowsecure.nl) - check if you are passing the captcha

Not recommended:
* [FpTing](https://fpting.com/fp.html) - made by students for a [study paper](https://www.mdpi.com/1424-8220/23/6/3087), lacks maintenance, and provides some incorrect data (e.g., 5 falsely detected lies for my Firefox on Linux).

More tools can be found at https://github.com/kkoooqq/fakebrowser  

# Anti-detect libs

[Privacy Manager](https://www.ivanovation.ro/modules/) - 12 modules to change fingerprint of your computer.

For Puppeteer:  
* [Imposter](https://github.com/TheGP/Imposter) - my package that emulates human actions on the page, currently in development, join me :)
* [Rebrowser](https://github.com/rebrowser/rebrowser-patches) - isolated environment
* [Secure-puppeteer](https://github.com/prescience-data/secure-puppeteer) - isolated environment, outdated, so XPath and some feautures doesnt work
* [Extra stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth) - trash, as easily detected by CreepJS  
* [Fingerprints from Bablosoft](http://fingerprints.bablosoft.com/) - free and paid fingerprints to use  
* [Perfect Canvas from Bablosft](https://wiki.bablosoft.com/doku.php?id=perfectcanvas) - emulating real canvas data

For Playwright:
* [Rebrowser](https://github.com/rebrowser/rebrowser-patches) - isolated environment
* [Playwrigh-ghost](https://github.com/regseb/playwright-ghost) - Playwright with plugins to be a ghost

For Selenium/Python:  
* [NoDriver](https://github.com/ultrafunkamsterdam/nodriver) - successor of Undetected-chromedriver
* [ZenDriver](https://github.com/stephanlensky/zendriver) - fork of NoDriver
* [Undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver) - outdated
* [Pyautogui](https://pyautogui.readthedocs.io/en/latest/) - control the mouse and keyboard to automate interactions with other applications
* [Selenium-Driverless](https://github.com/kaliiiiiiiiii/Selenium-Driverless) - use selenium without chromedriver

For request libs:
* [Curl-impersonate](https://github.com/lwthiker/curl-impersonate)
* [For GO](https://github.com/wangluozhe/requests)
* [CycleTLS for NodeJS/GO](https://github.com/Danny-Dasilva/CycleTLS)
* [curl_cffi for Python](https://github.com/yifeikong/curl_cffi)
* [Got-Scraping for NodeJS](https://github.com/apify/got-scraping)

Chrome [launch arguments](https://developer.chrome.com/docs/extensions/reference/api/i18n#concepts_and_usage):
* `--profile-directory=${dir_name}` // should be together with `userDataDir`
* `--accept-lang=en,en-US,` // th,en,en-GB,en-US works only on new profile dirs
* `--user-agent=${user_agent}` // properly changes user-agent in headers and JS runtime
* `--disable-extensions-except=${EXTENSION_PATH}`
* `--load-extension=${EXTENSION_PATH}`
* `--disable-site-isolation-trials` helps to detect all iframes on the page for Puppeteer, without it frames from another domain will be inaccessible
* `--aggressive-cache-discard` // useful in case u want more time for a debugger to attach or an extension to modify something
* `--disable-gpu` // less detectable canvas fingerprint, but GPU vendor/renderer still will be present

# Humanizing

* [Fake-browser](https://github.com/kkoooqq/fakebrowser) Based on Puppeteer, with human-like interactions  
* [Bezier mouse movements](https://github.com/Pomax/bezierjs)  
* [Definitely-not-a-robot](https://github.com/dougwithseismic/npm-definitely-not-a-robot)  
* [Puppeteer-Humanize](https://github.com/nicoandmee/puppeteer-humanize)  
* [Ghost-Cursor](https://github.com/Xetera/ghost-cursor) - generate realistic, human-like mouse movement data between coordinates

# Captha solvers
* [List of everything related to Captchas](https://github.com/TheGP/Everything-About-Captchas/)

# SMS confirmations
* [SmsActivate](https://sms-activate.io/?ref=8536388) - min top up ~$2.5, high commissions
* [VakSms](https://vak-sms.com/3b4308f6-b7ff-4085-a095-5e63f650fa7f) - not every country is available
* [SmsHub](https://smshub.org/) - looks like the cheapest but has a lot of low-quality numbers(at least in Thailand), sometimes specifying an operator helps
* [GrizzlySms](https://grizzlysms.com/registration?r=539140)
* [5Sim](https://5sim.net/) - expensive for some countries but has activation rate data available (Thailand for example)
* [OnlineSim](https://onlinesim.io/?bref=880810) - very expensive
* [SmsBower](https://smsbower.com/registration?ref=110541) - min top up $2.86, low commission
* [365sms](https://365sms.vip/?ref=626004) - top up from $1
* [Cyberyozh](https://app.cyberyozh.com/reception-sms/residential/) - virtual + residential, expensive

# Proxies
[List of proxy providers](https://github.com/TheGP/proxy-providers-list) - 25+ proxy providers with price comparison
[List of mobile proxies](https://github.com/TheGP/4g-proxies-providers) - including many small providers

* [BrightData](https://get.brightdata.com/jdpda3d3pu8n) - around $8/GB
* [DataImpulse](https://dataimpulse.com/?aff=10601) - from $1/GB (has $5/5Gb welcome package, but normally top-up is $50+). IMAP/SMTP blocked.
* [WebShare](https://www.webshare.io/?referral_code=r5ah58acc1n1) - $6/Gb (from 4.5), IPs: from $6/month per 20 (shared). IMAP/SMTP works.
* [Thordata](https://dashboard.thordata.com/register?invitation_code=PL3KADIY) - from $1.8/Gb residential, mobile from $2.2
* [GeoNode](https://geonode.com/?ref=152763) - $4/Gb (from $1.7)
* [LunaProxy](https://www.lunaproxy.com/register?Invitation_code=59NQELMK) - $3/Gb (from $0.8), has static too ($3/week, $5/month), IMAP/SMTP blocked.
* [Soax](https://soax.sjv.io/gONVj5) - starts at $6.6/GB and less
* [IPRoyal](https://iproyal.com/?r=381340) - starts at around 5.25/GB for 10GB, less too expensive (IMAP only if spending 5k)
* [922proxy](https://www.922proxy.com/index.html?inviter_code=eac554c7) - $3/GB (up to 60 min), $0.22/IP, $5/30 days
* [9proxy.com](https://9proxy.com/sign-up?inviteCode=9P_3YVqNdK8) - $0.07-0.2/IP
* [ProxyEmpire](https://proxyempire.io/?ref=ntayyzn) - $2-5.71/GB
* [FloppyData](https://floppydata.com/) - premium residential and mobile proxies

# Buying accounts
Hm. Cant get it right? You can always shortcut:
* [AccsMarket](https://accsmarket.com/en/?ref=631958) - en/ru, crypto
* [DarkStore](https://dark.shopping/?p=197898) - ru lang, crypto / local russian bank payment

Many other stuff can be found at [BlackHatWorld](blackhatworld.com) but usually more expensive.

# Other

* [Script to collect visitors' fingerprints](https://github.com/kkoooqq/fakebrowser/blob/main/script/dumpDD.js) on your website.
* Article [How to bypass “slider CAPTCHA” with JS and Puppeteer](https://filipvitas.medium.com/how-to-bypass-slider-captcha-with-js-and-puppeteer-cd5e28105e3c)
* Library of [research papers and presentations for counter-detection and web privacy](https://github.com/prescience-data/dark-knowledge)
* CPU fingerprinting gives a model of the CPU with [60% accuracy](https://github.com/CISPA/browser-cpu-fingerprinting)
* [How to bypass PerimeterX](https://www.reddit.com/r/webscraping/comments/1ac34ob/how_to_bypass_perimeterx/kjrxv8n/)
* Article [BotOrNot](https://incolumitas.com/pages/BotOrNot/)
* Your [request fingerprint](https://tls.peet.ws/api/all)

# Antidetection tips

Browser - use [separately downloaded](https://incolumitas.com/2021/05/20/avoid-puppeteer-and-playwright-for-scraping/) version of Chrome instead of Chromium, and pass it in `executablePath` in Puppeteer.  
* Screen width/height + Window height/width  - can be emulated by attaching a debugger via Chrome extension, but `screen.availHeight` and width will be wrong. So, it is better to change screen size on a virtual machine or use an anti-detect browser.  
* Disable WebRTC when using proxies/mask public IP: https://github.com/puppeteer/puppeteer/issues/6377  
* Match all proper browser headers in the same order
* Autocontext api https://habr.com/ru/companies/globalsign/articles/475586/ https://fb-killa.pro/threads/povyshaem-svoju-anonimnost-putem-kontrolja-nad-audiocontext-fingerprint.2759/#post-19349
* Make sure nothing of your scripts if visible in global score, some websites collect all data (like window.*) and analyze it
* Did you know if you go directly on the website without googling it it will be visible by using window.history.length? 

# What is available in a JS worker:
Worker is another sneaky way to detect real browser data, as you can't modify object properties in it with some extension.
`window`, `screen`, and access to DOM are not available (and therefor canvas)

* Timezone ( `Intl.DateTimeFormat().resolvedOptions().timeZone` )
* Language ( `navigator.language || navigator.userLanguage` )
* User agent ( `navigator.userAgent` )
* Hardware Concurrency ( `navigator.hardwareConcurrency` )
* [GPU data](https://developer.mozilla.org/en-US/docs/Web/API/WorkerNavigator/gpu) (except Linux & Firefox upd 30.01.2024)


