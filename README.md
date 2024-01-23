# Curated anti detect tools list  
Just making a tools list for my project, feel free to send pull requests :)  

# Anti-detect browsers
[Multilogin](https://multilogin.com/) - starts from €74 for 100 profiles  
[Incogniton](https://incogniton.com/aff/620515/) - 10 free, $29.99/Month for 50  
[Octo Browser](https://octobrowser.net) - starts from €21 for 10  
[Kameleo](https://kameleo.io/) - starts €59/user with unlimited profiles  
[Gologin](https://go.gologin.com/secretbonus-IFOGFRB) - $24 for 100 profiles, no unlimited plan, free proxies  
[AdsPower](https://share.adspower.net/YyHH9v) - 2 profiles free, $5.4 for 10 profiles, no unlimited plan  
[Vmlogin](https://www.vmlogin.us/) - $99 for 200 profiles  
[Indigo](https://www.goindigo.in/) - €99 for 100 profiles  
[GhostBrowser](https://ghostbrowser.com/) - 4 profiles free, $21 unlimited  
[Undetectable](https://undetectable.io/?r=AXCFe) - 5 cloud profiles free, $49 for unlimited local with 25 "configs"  
[Bablosoft](https://bablosoft.com/shop/BrowserAutomationStudio) - free browser automation studio  
[Morelogin](https://www.morelogin.com/?from=AAA2qquLhqBd) - 2 free, $9 for 10 profiles and 2 users  
[Dolphin-anty](https://dolphin-anty.com/a/3047556) - 10 free, $89 for 100
[OctoBrowser](https://octobrowser.net/)

  
# Detection tests

[Creep JS](https://abrahamjuliot.github.io/creepjs/) - the most advanced detector  
[Pixelscan](https://pixelscan.net/) - simple fingerprint checker  
[Cloudflare captcha](https://nowsecure.nl) - check if you are passing the captcha  
[Coveryourtracks](https://coveryourtracks.eff.org/) - test to see if you protected from fingerprinting  
[ReCaptha score](https://antcpt.com/score_detector/) - see you reCaptcha score  
[AmIUnique Fingerprint](https://amiunique.org/fingerprint) - see your fingerprint  
[Sannysoft Fingerprint](https://bot..com/) - check your fingerprint  
[BrowserLeaks](https://browserleaks.com/)  
[F.vision](http://f.vision/)  
[Extension-detector](https://z0ccc.github.io/extension-detector/)
  
More tools can be found: https://github.com/kkoooqq/fakebrowser  

# Anti-detect libs

For Puppeteer:  
[Secure-puppeteer](https://github.com/prescience-data/secure-puppeteer) - hides exposed API of Puppeteer, so it becomes unditected by CreepJS  
[Extra stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth) - trash, as easily detected by CreepJS  
[Fingerprints from Bablosoft](http://fingerprints.bablosoft.com/) - free and paid fingerprints to use  
[Perfect Canvas from Bablosft](https://wiki.bablosoft.com/doku.php?id=perfectcanvas) - emulating real canvas data  
  
For Selenium/Python:  
[Undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver)  

# Humanizing

[Fake-browser](https://github.com/kkoooqq/fakebrowser) Based on Puppeteer, with human-like interactions  
[Bezier mouse movements](https://github.com/Pomax/bezierjs)  
[Definitely-not-a-robot](https://github.com/dougwithseismic/npm-definitely-not-a-robot)  
[Puppeteer-Humanize](https://www.npmjs.com/package/@forad/puppeteer-humanize)  
[Ghost-Cursor](https://github.com/Xetera/ghost-cursor) - generate realistic, human-like mouse movement data between coordinates

# Captha solvers
[Capsolver](https://dashboard.capsolver.com/passport/register?inviteCode=U2gREjbK6qnY)

# Other

Article [How to bypass “slider CAPTCHA” with JS and Puppeteer](https://filipvitas.medium.com/how-to-bypass-slider-captcha-with-js-and-puppeteer-cd5e28105e3c)

# Antidetection ideas

Browser - use [separately downloaded](https://incolumitas.com/2021/05/20/avoid-puppeteer-and-playwright-for-scraping/) version of Chrome instead of Chromium, and pass it in executablePath in Puppeteer.  
Screen width/height + Window height/width  - can be emulated by attaching a debugger via Chrome extension

