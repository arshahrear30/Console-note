Programmer || Developer || Coder

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






