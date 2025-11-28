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

App এ signup option থাকলে, তার মানে যেই APP-এ account create করার option আছে ঐটায় app delete করার option রাখা must ।

Account Deletion Link
Add a link that users can use to request that their account and associated data is deleted (Optional)

এইখানে Yes এ click দিয়ে URL option এ click দেবো । এইখানে যেকোনো একটা website এ delete এর policy এবং কীভাবে delete করতে হবে তা লিখে ঐ URLটা দেবো । প্রয়োজনে screenshot দিবা ঐ website এ । data কয়দিন পর delete হবে এটাও থাকতে হবে । Support team এর contact থাকতে হবে । Google site এ এই কাজগুলো লিখতে পারি, link share করতে পারি ।

## 10.9
যদি বাচ্চাদের জন্য app বানাই তাহলে আমরা must Family self-certificate ads sdk program ভালো মতো পড়বো ।

## 10.12
Console > Policy and programs > App content > App Access > এইখানে দামী একটা account দিতে হবে Google-কে । যেন Google এর botটা দিয়ে account check করতে পারে । 2টা option থাকে:

All function in my app is available without any access restrictions: special access প্রয়োজন নাই ।

আর যদি sign up login option থাকে তাহলে: All or some functionality in my app is restricted.. এ click দেবো । Instruction name: login to TFS app Demo User name এবং password only for console নিচে গিয়ে instruction লিখে দিতে হবে । app access এর নিয়ম, guest mode কেমনে use করবে, 2 step bypass কেমনে করবে, WhatsApp এর মতো QR code scanner দিয়ে আরেক device এ login করা যায় কি না, কেমনে করে, এই সব থাকলে instruction দেবো ।

## 10.13
Console > Policy and programs > App content > Content ratings

এটাতে একটা mail দিতে হবে । এই mail এ আপনার সাথে console agreement করবে আর কি । category: Game, Social, All other... (3:35 second)

এটা ভালো মতো বুঝে answer দেবো । App update করলে আবার update করা যায় । এটা খুব sensitive। তাই প্রত্যেকটা option এর learn more এ গিয়ে ভালো মতো বুঝে Yes No দেবো ।

## 10.14
Could your store listing unintentionally appeal to child?? তার মানে আপনার app এর logoটা বাচ্চাদের এমনিতেই আকৃষ্ট করে কি না । No দেওয়াই ভালো ।

Does your app use advertising ID? Yes দিতে পারো যদি Manifest এ appটা ad id দেয় । SDK 33 up থাকে । Check mark: Advertising or marketing দিতে পারো । আরও অন্যগুলোও দিতে পারো ভালো মতো learn more পড়ে ।

Turn off release errors: এটাতে check mark select করবো না । করলে app এ error show করবে না । আমরা তো চাই error হলে show করুক যাতে আরও better experience আনতে পারি । তাই এটা uncheck-ই থাকুক ।

## Update 
Play Console খুললে 1 বছরে app না ছাড়লে এটা auto close হয়ে যাবে। আর app ছাড়লে 1 বছরের মধ্যে 1k download হতে হবে। Account সবই ঠিক আছে, 6 মাসের মধ্যে আপনি login করেন নাই console এ তাহলেও কিন্তু terminate হবেন। Console Account details এ গিয়ে email এবং contact verified হতে হবে। App upload দিয়ে পরে আবার idea change করলে app এবং account terminate হয়ে যাবে। App এ এমন কোনো link অথবা button বানানো যাবে না যেটা coming soon অর এখন কোনো কাজে লাগে না। এমন কোনো information দেওয়া যাবে না যেটা ভবিষ্যতে আসবে এমন। তাহলে কিন্তু misguide এর under এ পড়বে। :: এইগুলোকেই Broken Link বলে। app এ বেশি বেশি try catch use করবো, এতে crash কম হয়। Internal testing করবো অনেকবার অনেক phone এ। Internal testing এ app upload করে দেখলে Google 24 ঘণ্টা বা এর কম-বেশি সময়ের মধ্যে একটা report দেয়। সেই report Console এর pre launching এ পাবেন। ঐটাতেই Google অনেক bug identify করে দেয়।
