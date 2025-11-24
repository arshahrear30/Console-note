Programmer || Developer || Coder

## 9.1

Build Signed Apk
Android Studio > Build > Generate Signed Bundle/Apk >

1. Android App Bundle (Play Store এ upload এর জন্য)

2. Apk (নিজেরা দেখবো / client-কে share করলে install করবে)

App Bundle থেকে Next এ click দেবো > একটা jks file create করতে হবে (jks fileটা console এ app upload দিতে লাগবে প্রতিবার। এটা upload security file। এটা লাগবে must।)

JKS File Creation (Keystore)
1. Create new তে click করবো যদি আগে না create করি। Keystore path PC থেকে কোথায় রাখবো folder select করবো।

একটা password note pad এ লিখবো ঐ note ও same folder এ রাখবো। এরপর Keystore path এর নিচে 4 জায়গায় same password paste করবো। Certificate টা skip করা যায়, পূরণ করা best practice। > Ok দিলে হয়ে গেছে।

2. Choose Existing এ click করবো যদি already jks file create থাকে।

Finalizing the Build
পরবর্তীতে auto password আসার জন্য Remember এ টিক দিয়ে রাখতে পারি > Next > Destination folder লেখার নিচে > debug (এটা testing করার জন্য ব্যবহার করা হয়) > release (যখন Play Store অর অন্য কোথাও upload করতে যাবো তখন) > Create > Enter

appটা যেই folder এ create করছি same C drive / E drive এ Release করা / apk create করা good practice না, নয় অনেক সময় bug হয়। release করা folder select করা যায় Destination folder থেকে। Play Store এ console এ এই fileটাই upload করবো।

Play Store এ app update দেওয়ার জন্য Android Studio এর build.gradle (Module :app) এটার versionCode আগেরটার চেয়ে বড় হবে। versionName ও change করতে হবে update দিতে গেলে।

Backup and Security
Always যেইটা করতে হবে। App এর source code এবং JKS file password note file এই 3টা file Google Drive or online যেকোনো মাধ্যমে save করে রাখতেই হবে, নয়তো কখন PC crash করে সব শেষ।

Source code ZIP file এ convert করবো । Android Studio >> File >> Export >> Export to Zip File (zip এ রাখলে file ভালো থাকে) > Online এ মূলত এই Zip file টা সংরক্ষণ করবো ।

## 9.2

GMAIL + 25USD (Duel Currency card / Debit card - এই card বানাতে passport লাগে, bank এ যোগাযোগ করতে হবে) লাগে Console খুলতে । আপনি পুরো জীবনে একটা developer account খুলতে পারবেন একজনের information দিয়ে একটা device এ যেমন: router, mobile, laptop, PC।

Search: how to create Console developer account https://support.google.com/googleplay/android-developer/answer/6112435?hl=bn-Latn এখানে সব বলা আছে ।

sign up for a Play Console developer account

## 9.3
Search: google developer policy https://play.google/developer-content-policy/

## 9.4
Console এ এমন একটা name দেবো যেটা অন্য কেউ Play Store এ দেয় নাই এবং unique এবং app relevant।

google developer policy থেকে name guideline:

Store Listing and Promotion

ASO keyword
ASO keyword দিয়ে Chat GPT এর help নিয়ে Short description লিখবো । কোনো প্রশংসা word লিখবো না । যেমন: Top, Best... একই word দুই-তিনবার না use করা।

Full description লেখার সময় অন্য কোনো app এর সাথে compare না করি । এক word বারবার use না করি । Apps এর functionality গুলো লিখতে পারেন ।

## 9.9
Logo তে shadow অর Number অর Best app এইজাতীয় hype text গুলো লেখা যাবে না।

Phone Screenshort (SS): SS দেওয়ার সময় অবশ্যই যাতে কোনো ad না দেখা যায় । কোনো famous person এর picture অর anything যেন না আসে ।

Search: make screenshots for google play online tag: tag এ গিয়ে দেখবো আমার app কার কার সাথে যায় । ঐ অনুযায়ী select করবো ।

Store listing contact details: email address for contract with developer এটা user-এর জন্য । এছাড়াও website। not mandatory ।

External Marketing: Advertise এ select click থাকা ভালো এতে apkpure অর অন্যান্য market তাদের site এ আমাদের app promote করবে এবং আমাদের user gain হবে । good practice।

## 9.12
Console এ grow থেকে Main Store Listing এর কাজ করেছি এবং Store setting থেকে এইখানের form গুলো পূরণ করেছি ।

Release > Production > Release name এ আমরা version দেবো । Release note > <en-US> এর মাঝখানে আপনি যা লিখবেন: app এর কী কী bug fix করেছেন অর কী কী update এনেছেন এইগুলো আরকি ।

এখনই app upload করা যাবে না, আরও কিছু জিনিস পূরণ করতে হবে ।
