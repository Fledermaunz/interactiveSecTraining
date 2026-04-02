2) What is Burp Suite
Which edition of Burp Suite runs on a server and provides constant scanning for target web apps? -Burp Suite Enterprise
Burp Suite is frequently used when attacking web applications and ______ applications. -Mobile

3) Features of Burp Community
Proxy (enables interception and modification of requests and responses)
Repeater (caputring, modifying, resending same request multiple times)
Intruder (allows for spraying enpoints with requests, utilized for brute-force)
Decoder (decode captured information, encode payloads before sending them to the target)
Comparer (comparison of two pieces of data)
Sequencer (employewhen assessing the randomness of tokens)
  
Which Burp Suite feature allows us to intercept requests between ourselves and the target? -Proxy  
Which Burp tool would we use to brute-force a login form? -Intruder  

4) Installation
5) Dashboard
What menu provides information about the actions performed by Burp Suite, such as starting the proxy, and details about connections made through Burp? -Event log

6) Navigation
Shortcuts:
- Ctrl + Shift + D    Dashboard
- Ctrl + Shift + T    Target tab
- Ctrl + Shift + P    Proxy tab
- Ctrl + Shift + I    Intruder tab
- Ctrl + Shift + R    Repeater tab
Which tab Ctrl + Shift + P will switch us to? -Proxy tab

7) Options
In which category can you find a reference to a "Cookie jar"? -Sessions
In which base category can you find the "Updates" sub-category, which controls the Burp Suite update behaviour? -Suite
What is the name of the sub-category which allows you to change the keybindings for shortcuts in Burp Suite? -Hotkeys
If we have uploaded Client-Side TLS certificates, can we override these on a per-project basis (yea/nay)? -yea

8) Introduction to the Burp Proxy
9) Connecting through the Proxy (FoxyProxy)
redirect traffic through Burp Suite with Firefox extension

10) Site Map and Issue Definitions
Presumably after clicking on contact it appeared: What is the flag you receive after visiting the unusual endpoint? -THM{NmNlZTliNGE1MWU1ZTQzMzgzNmFiNWVk}

11) The Burp Suite Browser
12) Scoping and Targeting
13) Proxying HTTPS
14) Example Attack
1. Type an accepted mail format while Burp Proxy active and intercept on, then submit.
2. Replace in Burpsuite Proxy Intercept the mail with <script>alert("Succ3ssful XSS")</script>
3. Then press Crtl+U.
4. Press Forward and notice the Alert box in the browser.

