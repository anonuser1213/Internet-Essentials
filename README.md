# Internet-Essentials
A list of essential privacy and safety tools.

## Habits
Never ever give out your real email to most online services, this is to prevent data brokers and to get hold of your email
Host your own services, so that you're in control of your data (for free with FoSS)
Use Mostly FoSS when possible to

## Tools
### __Browsers:__
A web browser is an essential part in connecting to the internet. Choosing the right browser can heavily influence your privacy and security.

<details>
<summary>Everyday Use</summary>

<details>

<summary>Firefox flavours</summary>
    
  * [Librewolf](https://librewolf.net/), a custom version of Firefox, focused on privacy, security and freedom.
  * [Fennec](https://f-droid.org/packages/org.mozilla.fennec_fdroid/) (for Android), Firefox without some telementary and proprietary code.
  * Hardened Firefox, a set of configurations making Firefox (and variants) more secure.
</details>
<details>
<summary>Chromium flavours</summary>
    
  * [Brave](https://brave.com/), privacy focused browser.
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
</details>

### __Search Engines:__
Search engines access and utilize a lot of information about us, thus choosing a privacy friendly one is really important. Because of this, Google is not under any circumstances an option.

Nowdays most engines are very fast, though some show better results than others. It's important to still keep the purpose of the search engine in mind while choosing, though it is relatively easy to switch and try different ones.

<details>
  <summary>Search Engines</summary>
  
  * [DuckDuckGo](https://duckduckgo.com), privacy focused search engine with tons of features and great results.
  * [Ecosia](https://ecosia.org), cliamte focused, plants trees for their income, transparent B certified company.
  * [Qwant](https://www.qwant.com/), user focused search engine.
</details>

### __Mail Services:__
In order to host an email there is need for an smtp server and a physical computer. It costs money for the mail provider to run this, thus all mail providers have to make money somehow, and if you dont pay for the product, you are the product. Be highly sceptical to completely free mail providers, as most of them earn money through scanning your email for data. Think; how does the host make their money? Are you okay with their model?

When choosing an email you can either have your own mail server hosted or use an already running mail server. Hosting your own mail server gives you more control and options, but is ofter a bit more complicated.

<details>
  <summary>Mail Services</summary>
  
  * [Tuta mail](https://tuta.com/), free with paid plan around €3-8 /month
  * [Proton mail](https://proton.me/mail), free with paid plan around €4-14 /month
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

<details>
  <summary>Encrypted Messengers</summary>
  
  * [Signal](https://signal.org/) (multi platform), free, easy to use, strong encryption, feature rich.
  * [Matrix protocol](https://matrix.org/) (multi platform), more advanced, open network secure, decentralised communication.
</details>