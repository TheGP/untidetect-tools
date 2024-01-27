# Curated anti-detect tools list  
Just making a tools list for my project, feel free to send pull requests :) 
While you are looking around, it may be a good idea to sign up on all the Discord channels each product has can find some interesting insides from users.

# Anti-detect browsers
* [Multilogin](https://multilogin.com/) - starts from €74 for 100 profiles  
* [Incogniton](https://incogniton.com/aff/620515/) - 10 free, $29.99/Month for 50  
* [Octo Browser](https://octobrowser.net) - starts from €21 for 10  
* [Kameleo](https://kameleo.io/) - starts €59/user with unlimited profiles  
* [Gologin](https://go.gologin.com/secretbonus-IFOGFRB) - $24 for 100 profiles, no unlimited plan, free proxies  
* [AdsPower](https://share.adspower.net/YyHH9v) - 2 profiles free, $5.4 for 10 profiles, no unlimited plan  
* [Vmlogin](https://www.vmlogin.us/) - $99 for 200 profiles  
* [Indigo](https://www.goindigo.in/) - €99 for 100 profiles  
* [GhostBrowser](https://ghostbrowser.com/) - 4 profiles free, $21 unlimited  
* [Undetectable](https://undetectable.io/?r=AXCFe) - 5 cloud profiles free, $49 for unlimited local with 25 "configs"  (API + driver automation)
* [Bablosoft](https://bablosoft.com/shop/BrowserAutomationStudio) - free browser automation studio  
* [Morelogin](https://www.morelogin.com/?from=AAA2qquLhqBd) - 2 free, $9 for 10 profiles and 2 users  
* [Dolphin-anty](https://dolphin-anty.com/a/3047556) - 10 free, $89 for 100  
* [OctoBrowser](https://octobrowser.net/)  
* [ixBrowser](https://ixbrowser.com/en) - free, core is a bit old but they say because of too few changes they didn't update yet (and it is not detected as old)

* [antbrowser](https://antbrowser.pro) - too many lies detected by CreepJS
* [Switch Antidetect](https://switch.mybot.su) - using Chrome 103 while 120 is out. Too slow updates.
* [GhostBrowser](https://ghostbrowser.com/) - only user-agent switch, easily fingerprinted
  
https://cpa.rip/stati/antidetect-palivo/ - a bit old article on how anti-detect browsers can be detected
  
# Detection tests

* [Creep JS](https://abrahamjuliot.github.io/creepjs/) - the most advanced detector  
* [Pixelscan](https://pixelscan.net/) - simple fingerprint checker  
* [Cloudflare captcha](https://nowsecure.nl) - check if you are passing the captcha  
* [Coveryourtracks](https://coveryourtracks.eff.org/) - test to see if you are protected from fingerprinting  
* [ReCaptha score](https://antcpt.com/score_detector/) - see you reCaptcha score  
* [AmIUnique Fingerprint](https://amiunique.org/fingerprint) - see your fingerprint  
* [Sannysoft Fingerprint](https://bot..com/) - check your fingerprint  
* [BrowserLeaks](https://browserleaks.com/)  
* [F.vision](http://f.vision/)  
* [Extension-detector](https://z0ccc.github.io/extension-detector/)
* [Audio fingerprint](https://audiofingerprint.openwpm.com/)
  
More tools can be found: at https://github.com/kkoooqq/fakebrowser  

# Anti-detect libs

For Puppeteer:  
* [Secure-puppeteer](https://github.com/prescience-data/secure-puppeteer) - hides exposed API of Puppeteer, so it becomes undetected by CreepJS  
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
* [Puppeteer-Humanize](https://www.npmjs.com/package/@forad/puppeteer-humanize)  
* [Ghost-Cursor](https://github.com/Xetera/ghost-cursor) - generate realistic, human-like mouse movement data between coordinates

# Captha solvers
* [2captcha](https://2captcha.com/?from=21664443) - human, ready to use libs
* [Capsolver](https://dashboard.capsolver.com/passport/register?inviteCode=U2gREjbK6qnY) - AI
* [NopeCha](https://nopecha.com/) - AI
* [CaptchaAI](https://captchaai.com/) - AI, fixed price
* [CapMonster](https://capmonster.cloud/) - AI

# SMS confirmations
* [SmsActivate](https://sms-activate.org/?ref=8536388)
* [OnlineSim](https://onlinesim.io/?bref=880810)
* [VakSms](vak-sms.com/3b4308f6-b7ff-4085-a095-5e63f650fa7f)
* [SmsHub](https://smshub.org/) - looks like the cheapest but has a lot of low-quality numbers(at least in Thailand), sometimes specifying an operator helps
* [GrizzlySms](https://1grizzlysms.com/registration?r=539140)

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
