# Curated anti-detect tools list  
Just making a tools list for my project, feel free to send pull requests :) 
While you are looking around, it may be a good idea to sign up on all the Discord channels each product has can find some interesting insides from users.
   
Important: if you work on something related to undetection, like humanizing puppeteer actions, we may consider collaboration as I'm working currently on it too. My [TG](https://t.me/eugenebos).

# Anti-detect browsers
* [Undetectable](https://undetectable.io/?r=AXCFe) - 5 cloud profiles free, $49 for unlimited local with 25 "configs", 1 additional config $1 (API + driver automation)
* [Multilogin](https://multilogin.com/#a_aid=secretbonus3) - starts from €74 for 100 profiles  
* [Incogniton](https://incogniton.com/aff/620515/) - 10 free, $29.99/Month for 50
* [NSTBrowser](https://app.nstbrowser.io/r/NZ0daY) - 5 profiles opened / day free, 100 - $19, 500 - $59, 3000 - $199 (I guess currently you need to contact them to purchase it)
* [Octo Browser](https://octobrowser.net) - starts from €21 for 10  
* [Gologin](https://go.gologin.com/secretbonus-IFOGFRB) - $24 for 100 profiles, no unlimited plan, free proxies  
* [AdsPower](https://share.adspower.net/YyHH9v) - 2 profiles free, $5.4 for 10 profiles, no unlimited plan  
* [Morelogin](https://www.morelogin.com/?from=AAA2qquLhqBd) - 2 free, $9 for 10 profiles and 2 users  
* [Dolphin-anty](https://dolphin-anty.com/a/3047556) - 10 free, $89 for 100  
* [Kameleo](https://kameleo.io/) - starts €59/user with unlimited profiles  
* [Vmlogin](https://www.vmlogin.us/) - $99 for 200 profiles  
* [Indigo](https://www.goindigo.in/) - €99 for 100 profiles  
* [GhostBrowser](https://ghostbrowser.com/) - 4 profiles free, $21 unlimited  
* [Bablosoft](https://bablosoft.com/shop/BrowserAutomationStudio) - free browser automation studio  
* [OctoBrowser](https://octobrowser.net/) - €21 for 10 profiles
* [ixBrowser](https://ixbrowser.com/en) - free, but doesn't mask everything, for example, no GPU masking, API by request
* [Gpmlogin](https://gpmloginapp.com/en) - didn't check it yet, pricing is for unlimited use, for 1pc it is $125


Useless:
* [AntBrowser](https://antbrowser.pro) - too many lies detected by CreepJS
* [Switch Antidetect](https://switch.mybot.su) - using Chrome 103 while 120 is out. Too slow updates.
* [GhostBrowser](https://ghostbrowser.com/) - only user-agent switch, easily fingerprinted
* [MarketerBrowser](https://www.marketerbrowser.com/) - can't even switch user-agent without detection
  
A bit old [article on how anti-detect browsers can be detected](https://cpa.rip/stati/antidetect-palivo/). Example from the article: `if( Object.getOwnPropertyNames(navigator)[0] ) alert('fake parameters detected');`
  
# Detection tests

* [Creep JS](https://abrahamjuliot.github.io/creepjs/) - the most advanced detector  
* [Pixelscan](https://pixelscan.net/) - simple fingerprint checker  
* [Cloudflare captcha](https://nowsecure.nl) - check if you are passing the captcha  
* [Coveryourtracks](https://coveryourtracks.eff.org/) - test to see if you are protected from fingerprinting  
* [ReCaptha score](https://antcpt.com/score_detector/) - see you reCaptcha score  
* [AmIUnique Fingerprint](https://amiunique.org/fingerprint) - see your fingerprint  
* [Sannysoft Fingerprint](https://bot.sannysoft.com/) - check your fingerprint  
* [BrowserLeaks](https://browserleaks.com/)  
* [F.vision](http://f.vision/)  
* [Extension-detector](https://z0ccc.github.io/extension-detector/)
* [Audio fingerprint](https://audiofingerprint.openwpm.com/)
* [Behavioral Bot Classification](https://bot.incolumitas.com/)
* [My own tool](https://reviewer.eugenebos.com/test) - the only benefit the code is plain, so you can find very easily how everything is tested.

Others:
* [BrowserScan](https://www.browserscan.net/en)
* [Iphey](https://iphey.com/)
* [Canvas inspector](https://data.bablosoft.com/canvas-inspector-3/distr/CanvasInspectorInstall.exe)
  
More tools can be found: at https://github.com/kkoooqq/fakebrowser  

# Anti-detect libs

[Privacy Manager](https://www.ivanovation.ro/modules/) - 12 modules to change fingerprint of your computer.

For Puppeteer:  
* [Imposter](https://github.com/TheGP/Imposter) - my package that emulates human actions on the page, currently in development, join me :)
* [Secure-puppeteer](https://github.com/prescience-data/secure-puppeteer)
* [Extra stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth) - trash, as easily detected by CreepJS  
* [Fingerprints from Bablosoft](http://fingerprints.bablosoft.com/) - free and paid fingerprints to use  
* [Perfect Canvas from Bablosft](https://wiki.bablosoft.com/doku.php?id=perfectcanvas) - emulating real canvas data  
  
For Selenium/Python:  
* [Undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver)  

Chrome [launch arguments](https://developer.chrome.com/docs/extensions/reference/api/i18n#concepts_and_usage):
* `--profile-directory=${dir_name}` // should be together with `userDataDir`
* `--accept-lang=en,en-US,` // th,en,en-GB,en-US works only on new profile dirs
* `--user-agent=${user_agent}` // properly changes user-agent in headers and JS runtime
* `--disable-extensions-except=${EXTENSION_PATH}`
* `--load-extension=${EXTENSION_PATH}`
* `--aggressive-cache-discard` // useful in case u want more time for a debugger to attach or an extension to modify something
* `--disable-gpu` // less detectable canvas fingerprint, but GPU vendor/renderer still will be present

# Humanizing

* [Fake-browser](https://github.com/kkoooqq/fakebrowser) Based on Puppeteer, with human-like interactions  
* [Bezier mouse movements](https://github.com/Pomax/bezierjs)  
* [Definitely-not-a-robot](https://github.com/dougwithseismic/npm-definitely-not-a-robot)  
* [Puppeteer-Humanize](https://github.com/nicoandmee/puppeteer-humanize)  
* [Ghost-Cursor](https://github.com/Xetera/ghost-cursor) - generate realistic, human-like mouse movement data between coordinates

# Captha solvers
As each service differs with different captchas support, I took the most popular one: reCaptcha v2 1000 captchas to compare the price:
* [Capsolver](https://dashboard.capsolver.com/passport/register?inviteCode=U2gREjbK6qnY) - AI. $0.8. Supports Outlook & Arksose captchas.
* [2captcha](https://2captcha.com/?from=21664443) - human. Libs: JS, GO, PHP, Python, Ruby, C#, Java. $1-2.99 (doesn't work for Outlook)
* [CaptchaAI](https://captchaai.com/?from=175374) - AI, fixed price from $13.5/month for 5 captcha treads.
* [CapMonster](https://capmonster.cloud/) - AI. $0.6
* [SolveCaptcha](https://solvecaptcha.com?from=434017) - human. Many ready-to-use libs. $1
* [CapGuru](https://cap.guru/en/regen/?ref=144789) - unsure. Same API as Rucaptcha. $0.55
* [NopeCha](https://nopecha.com/) - AI. Starts from $5/month for 2k captchas/day.
* [MetaBypass](https://metabypass.tech/) - AI. Libs: Go, PHP, Python. $3
* [EzCaptcha](https://dashboard.ez-captcha.com/#/register?inviteCode=oewYJRREtMU) - AI.	$0.6
* [AntiCaptcha](http://getcaptchasolution.com/gy01xuqodw) - $0.95, AI
* [HardCaptcha](https://hardcaptcha.com/signup?rc=WOHWELMAWC) - start from $79/month, AI.

# SMS confirmations
* [SmsActivate](https://sms-activate.org/?ref=8536388)
* [OnlineSim](https://onlinesim.io/?bref=880810)
* [VakSms](https://vak-sms.com/3b4308f6-b7ff-4085-a095-5e63f650fa7f)
* [SmsHub](https://smshub.org/) - looks like the cheapest but has a lot of low-quality numbers(at least in Thailand), sometimes specifying an operator helps
* [GrizzlySms](https://1grizzlysms.com/registration?r=539140)
* [5Sim](https://5sim.net/)

# Residential proxies
* [DataImpulse](https://dataimpulse.com/?aff=10601) - from $1/GB (has $5/5Gb welcome package, but normally from $50). IMAP/SMTP blocked.
* [WebShare](https://www.webshare.io/?referral_code=r5ah58acc1n1) - $6/Gb (from 4.5), cheap status: from $6/month per 20. IMAP/SMTP works.
* [GeoNode](https://geonode.com/) - $4/Gb (from $1.7)
* [LunaProxy](https://www.lunaproxy.com/register?Invitation_code=59NQELMK) - $3/Gb (from $0.8), has static too ($3/week, $5/month), IMAP/SMTP blocked.
* [Piaproxy](https://account.piaproxy.com/register?invitation_code=9SOOQJZT)
* [Soax](https://soax.com?afmc=9e) - starts at $6.6/GB and less
* [IPRoyal](https://iproyal.com/?r=381340) - starts at around 5.25/GB for 10GB, less too expensive (IMAP only if spending 5k)
* [922proxy](https://www.922proxy.com/index.html?inviter_code=eac554c7) - $3/GB (up to 60 min), $0.22/IP, $5/30 days
* [BrightData](https://get.brightdata.com/jdpda3d3pu8n) - around $8/GB

# Other

* [Script to collect visitors' fingerprints](https://github.com/kkoooqq/fakebrowser/blob/main/script/dumpDD.js) on your website.
* Article [How to bypass “slider CAPTCHA” with JS and Puppeteer](https://filipvitas.medium.com/how-to-bypass-slider-captcha-with-js-and-puppeteer-cd5e28105e3c)
* Library of [research papers and presentations for counter-detection and web privacy](https://github.com/prescience-data/dark-knowledge)
* CPU fingerprinting gives a model of the CPU with [60% accuracy](https://github.com/CISPA/browser-cpu-fingerprinting)
* [How to bypass PerimeterX](https://www.reddit.com/r/webscraping/comments/1ac34ob/how_to_bypass_perimeterx/kjrxv8n/)
* Article [BotOrNot](https://incolumitas.com/pages/BotOrNot/)

# Antidetection ideas

Browser - use [separately downloaded](https://incolumitas.com/2021/05/20/avoid-puppeteer-and-playwright-for-scraping/) version of Chrome instead of Chromium, and pass it in `executablePath` in Puppeteer.  
* Screen width/height + Window height/width  - can be emulated by attaching a debugger via Chrome extension, but `screen.availHeight` and width will be wrong. So, it is better to change screen size on a virtual machine or use an anti-detect browser.  
* Disable WebRTC when using proxies/mask public IP: https://github.com/puppeteer/puppeteer/issues/6377  
* Match all proper browser headers in the same order
* Autocontext api https://habr.com/ru/companies/globalsign/articles/475586/ https://fb-killa.pro/threads/povyshaem-svoju-anonimnost-putem-kontrolja-nad-audiocontext-fingerprint.2759/#post-19349

# What is available in a JS worker:
Worker is another sneaky way to detect real browser data, as you can't modify object properties in it with some extension.
`window`, `screen`, and access to DOM are not available (and therefor canvas)

* Timezone ( `Intl.DateTimeFormat().resolvedOptions().timeZone` )
* Language ( `navigator.language || navigator.userLanguage` )
* User agent ( `navigator.userAgent` )
* Hardware Concurrency ( `navigator.hardwareConcurrency` )
* [GPU data](https://developer.mozilla.org/en-US/docs/Web/API/WorkerNavigator/gpu) (except Linux & Firefox upd 30.01.2024)


