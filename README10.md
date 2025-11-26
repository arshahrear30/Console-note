## 10.1
Privacy policy নিয়ে পড়াশোনা করবো । privacy policy ভুল হলে account termination হয়ে যায় কিন্তু । App এর কোথাও না কোথাও এই privacy policy link থাকতে হবে must । Signup এবং About page এ must privacy policy link দিবা ।

Console > Policy and programs > App content > Privacy Policy > Start > URL চাইবে ।

## 10.2
Search: google sites এটার মধ্যে free তে privacy policy লিখতে পারি । এবং publish দিয়ে link customize করতে পারি।

## 10.3
Privacy policy: User-কে বলে দেবো আমি তোমার এই এই data নিচ্ছি । আমি এই এই data দিয়ে এই এই করবো, এই এই করাতে পারি । Apps এর data কোন website এর মাধ্যমে কাজ করায় । যেমন API-এর কাজের website link টাও দিতে পারি। User-এর login data যেই domain hosting এর under এ থাকে তা clear করা।

Apps এ যদি signup না লাগে, তাহলে must কিন্তু device id সে সংগ্রহ করবে । এটা দিয়ে তো সে AdMob ও অন্যান্য মাধ্যমে ad চালাবে ।

This policy is effective as of ------- . এটাতে আমরা app কত তারিখে update করা হয়েছে last, ঐ date থেকে এই policy গুলো effective – এটা বোঝাবে।

## 10.4
Data Deletion Right: যদি আমরা signup-এর data collection করি, অর্থাৎ 1st party হয়ে যাই, আমার কাছে data আসে, তাহলে এই option টা রাখতে হবে । কারণ user যদি চায় তার data মুছে ফেলতে, তাহলে একটা email দেওয়া থাকবে, ওটাতে mail করলে আমরা data delete করে দেবো সেই জন্য ।

Company name যখন লিখবো এটাকে hyper link করে দেবো যেই domain এর জায়গায় User এর data গুলো store হয় ।
Information Collection and Use :: এইখানে company name এর সাথে same domain টা লিখে দেবো।

https://github.com/arshahrear30/Console-note/edit/main/privacy.md

## 10.5
Console > Policy and programs > App content > Data safety > Start >

Collect: মানে আমি data নিয়ে আমার কোনো server এ রাখি ।

Shared: আমার data কোনো 3rd party-এর কাছে share করি ।

Ephemerally: data কিছুক্ষণ-এর জন্য device এ থাকে পরে আবার মুছে যায় । এটা হতে পারে server এও আপনি কিছুক্ষণ-এর জন্য রাখেন পরে আবার মুছে দেন।

WEBVIEW করতে গিয়ে অনেক app reject খায়, কারণ যেই website এর webview করি আমাদের সেই website কী কী data collect করে, কী কী করে সেটাও user-কে clear করতে হয় । কিন্তু আমরা করি না অথবা ঐ website-এর API অথবা অন্যান্য কিছু তো আমরা জানি না । তাই নিজের website এর webview use করা better।

## 10.6
Data collection and security: এটা always Yes দেবো । কারণ আপনি আপনার app এ ad বসালে আপনার device id collect করে, one kind of data collection। Encryption in transit এটাও টিক দেবো, কারণ আমরা তো HTTPS use করি, তাই always HTTPS-এর মাধ্যমে এটা encrypted থাকে।

OAuth মানে আপনার app টা Continue with Google অর Facebook দিলে direct login হয়ে যায় ।

যদি দুইটাই option রাখি যেমন: user name এবং password দিয়ে এবং Continue with Google অর Facebook, তাহলে যেই option select করবো: Username, password and other authentication।

My app does not allow users to create an account: user data delete option না থাকলে No দেবো।

NEXT > Data types: Manifest এ গেলে তো জানবেন আপনি কী কী allow করেছেন, ঐগুলো এখানে select করবেন । Device or other id এটা must select করবেন, কারণ max app এ তো ad চালায় । > Device and other IDs কেন নেই > Start > Shared দেবো, কারণ 3rd party Ad Mob-এর কাছে তো data চলে যাচ্ছে এই device id। > Advertising or marketing

আমরা তো সবাই app এর analytics use করি, তাই (Shared):: Firebase > তাই আমরা App info and performance এর নিচে Crash logs select করবো । >> Start >> Analytics e select 

এতক্ষণ আমরা simple app এর জন্য দেখছি, এখন আমরা signup login page থেকে data collection করে এমন app এর জন্য দেখবো 10.8 থেকে।

## 10.8
Console > Policy and programs > App content > Data safety > Start >

App e signup option thakle .. that mean jei APP e account create korar option acey oitay app delete korar option raka must ..

Add a link that users can use to request that their account and associated data is deleted (Optional) 
ei khane Yes e click diya URL option e click dibo ..ei khane je kono ekta website e delete er policy and kivabe delete kortay hoibay ta likhe oi URL ta dibo .. Proyojon e screenshort diba oi website e .. data koy din por delete hoibay eta o thakte hoibo.. Support team er contact thakte hoibo ..Google site e ei kaz gula likte pari link share korte pari ..

## 10.9 
jodi baccader jonno app banai tailay amra must  Family self-certificate ads sdk program valo moto porbo


