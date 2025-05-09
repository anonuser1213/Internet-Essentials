# Internet-Essentials
A list of essential privacy and security tools.

<summary><h2>General Considerations</h2></summary>
<details>

Make yourself less identifiable on the internet when possible. Being able to distinguish you from other users breaks anonymity.

Avoid giving out personal information, such as your email, phone number, adress or real name to most online services, as it is a strong unique tracker.

Hosting your own services is a good idea. Even though it often takes time and knowledge, you'll probably earn both time and knowledge in the long run. If you manage your own services you're in control of your data.

Simply using local services, such as a local program e.g. to convert files, send mail or write text will get you a long way. This guide covers both such more simple approaches and more technical methods.

Use FoSS, (Free and Open-Source Software) software when possible. This way it's less likely that someone is monetizing from your use of it, while it is often community built and has transparency.

https://www.techlore.tech/goincognito <-- offers a nice course on the topic with a bunch of videos to watch, highly reccomended! 

When it comes to digital privacy, security and anonymity, it's important to take your threat model into consideration. I.e. what you want to accomplish or what privacy/security you want. Everybody (no matter threat model) needs a good baseline, but could you have special interests?
</details>

## Tools
### __Browsers:__
A web browser is an essential part in connecting to the internet. Choosing the right browser can heavily influence your privacy and security.

<details>
<summary>Everyday Use</summary>

<details>

<summary>Gecko (Firefox) flavours</summary>
    
  * [Librewolf](https://librewolf.net/), a custom version of Firefox, focused on privacy, security and freedom.
  * [Fennec](https://f-droid.org/packages/org.mozilla.fennec_fdroid/) (for Android), Firefox without some telementary and proprietary code.
  * [Iceraven](https://github.com/fork-maintainers/iceraven-browser) (for Android), un-mozillafied Firefox with extended customization possibilities.
  * Hardened Firefox, a set of configurations making Firefox (and variants) more secure. This route is the best option since you get pretty much the same privacy stuff as librewolf but you can still get auto-updates (which is crucial for security) whilst you have to manuallt update librewolf (though that can probably be automated with some package manager and some). Doing this will take you some time to set up, but is well worth it.
</details>
<details>
<summary>Chromium flavours</summary>
    
  * [Brave](https://brave.com/), privacy focused browser. Really good for non tech-savvy people, a good reccomend for family and friends.
  * [DuckDuckGo Browser](https://duckduckgo.com/), privacy focused browser.
  * [Bromite](https://www.bromite.org/) (for Android), Chromium with some privacy improvements and built in ad blocker.
  * ([ungoogled-chromium](https://github.com/ungoogled-software/ungoogled-chromium)) FoSS variant of Chromium removing all connection to Google.
</details>
  
</details>
<details>
  <summary>Special Uses</summary>
 
  __Firefox flavours:__
  * [Tor Browser](https://www.torproject.org/), browser utilizing Tor, a free overlay network for anonymous communication.
</details>

<details>
  <summary>Browser Plugins</summary>
  
  * [Privacy Badger](https://privacybadger.org/) (both Firefox and Chromium), browser extension that automatically learns to block invisible trackers.
  * [NoScript](https://noscript.net/) (both Firefox and Chromium), blacklist or whitelist JavaScript for maximum security and protection.
  * [Canvas Blocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/) (Firefox), alters some JS APIs to prevent tracking.
  * [uBlock Origin](https://ublockorigin.com/) (both Firegox and Chromuium), FoSS ad and content blocker
  * [Ghostery](https://www.ghostery.com/) (both Firefox and Chromium), adblocker and cookie pop up blocker
  * 
</details>

### __Search Engines:__
Search engines access and utilize a lot of information about us, thus choosing a privacy friendly one is really important. Because of this, Google is not under any circumstances an option.

Nowdays most engines are very fast, though some show better results than others. It's important to still keep the purpose of the search engine in mind while choosing, though it is relatively easy to switch and try different ones.

<details>
  <summary>Search Engines</summary>
  
  * [DuckDuckGo](https://duckduckgo.com), privacy focused search engine with tons of features and great results.
  * [Ecosia](https://ecosia.org), cliamte focused, plants trees for their income, transparent B certified company.
  * [Startpage](https://www.startpage.com/), privacy focused search engine.
  * [SearXNG](https://searx.be/), privacy focused open source search engine.
  * [Qwant](https://www.qwant.com/), user focused search engine.
  * [Mojeek](https://www.mojeek.com/), growing independent search engine which does not track you.
</details>

### __Mail Services:__
In order to host an email there is need for an smtp server and a physical computer. It costs money for the mail provider to run this, thus all mail providers have to make money somehow, and if you dont pay for the product, you are the product. Be highly sceptical to completely free mail providers, as most of them earn money through scanning your email for data. Think; how does the host make their money? Are you okay with their model?

When choosing an email you can either have your own mail server hosted or use an already running mail server. Hosting your own mail server gives you more control and options, but is ofter a bit more complicated.

<details>
  <summary>Mail Services</summary>
  
  * [Tuta mail](https://tuta.com/), free with paid plan around €3-8 /month
  * [Proton mail](https://proton.me/mail), free with paid plan around €4-14 /month, free plan only gives you 500mb of storage 
</details>

<details>
  <summary>Mail Server Hosters</summary>
  
  * one.com, about €2 /month
</details>

<details>
  <summary>Self Hostable Mail Servers</summary>
  
  Hosting your own mail server can be a bit complicated and requires a computer running 24/7. See the [awesome selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted?tab=readme-ov-file#communication---email---complete-solutions) list for some options.
</details>

### __Messaging Services:__
A good messaging service should have good functionality while respecting the user, but should preferably not be too uncommon, as we still need a reliable service which people somewhat use.

Choosing an encrypted service is a good idea, since encryption makes your chats a lot harder to monitor, keeping you safe and secure.

SMS communication is not recommended since it's both expensive and potentially unsafe.

Using secure, private and encrypted communication is best practice for __everyone__ no matter your threat model. In yesteryear, you'd probably put your post in a closed conceled letter, not without the cover, not with a seethrough cover, so that no one in the process of sending the message would be able to see its contents. Not because you've got something to hide, but because of good prinicple. "You havn't got anything to hide, but you've also not got anything to show" 

<details>
  <summary>Encrypted Messengers</summary>
  
  * [Signal](https://signal.org/) (multi platform), free, easy to use, strong encryption, feature rich.
  * [Matrix protocol](https://matrix.org/) (multi platform), more advanced, open network secure, decentralised communication.
  * [Telegram](https://telegram.org)(multi platform), created by some russian, good private messages with encryption.
</details>

### __Social Media:__
It's very easy to get used to social media, while it at the same time is a big privacy issue.

Social media is also an uniquely clear example of how privacy issues can get serious consequences. "The feed" which is common in most social media today is heavily targeted towards the user, which can create a misleading perspective and a ["filter bubble"](https://en.wikipedia.org/wiki/Filter_bubble).

Apart from this it's bad for mental health and eats up all your time, studies have shown lower attention span (u get dumber) and just look at your screentime.

So just don't.

If possible, do not use social media at all. If you want to, the following are to prefer.

<details>
  <summary>Social Media Platforms</summary>
  
  * [Bluesky](https://bsky.social/), microblogging with controllable algorithms.
</details>
