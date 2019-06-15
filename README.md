# LAMP-security-CTF5
CTF VULNHUB AND ROOT-ME 
Video CTF : فيديو لحل CTF
https://www.youtube.com/watch?v=jUxAbkDHy3s

file exploitation written in lang [>>>>>C<<<<<<]
هتلاقي فوق ملف الاستغلال بلغة [>>>>>C<<<<<<]

المطلوب :

بص هنتكلم بالمصري انت تروح تاخد الايبي بتاع التحدي او السيرفر اي ان يكون يعني

وتعمل عليه سكان باداة زي nmap 

او الي انت عايزه بقا

بعد كدا هتلاقي بورت 22
الي هو مين 
SSH
طيب هخش ازي ؟
اقولك انا انت تروح تعمل تخمين او بروت فورس
طيب انا مش معايا المستخدمين اصلا للسيرفر هعمل ازاي اقولك انت تخش ع الرابط بتاع التحدي او الايبي وهتلاقي صفحة
عادية بس للتسهيل الصفحة دي فيها ثغرة
Command Injection
الشرح دا عربي للفهم بسيط جدا هيديك فكرتها بس
طيب انا عايز استغل الثغرة كامله في التحدي او السيرفر اعمل اي
بس انت هتخش ع اي مسار في التحدي هتبص علي الرابط هتلاقي مثال :-
1.1.1.1/about=sffsf
انت هتحط بقا استغلالك ازاي ؟
1.1.1.1/about=../../../../../../../../../../../../etc/passwd%00
هو دا التغيير خد بالك منه ههه
ماشي بعد كدا هيظهرلك ملف 
passwd
الملف الخاص بالمستخدمين بتوع السيرفر
انت هتاخدهم وتاخد منهم الاسامي الي تشك منها مثلا
amy
jenifer
كلام من دا 
وتروح علي الاداة الجميلة الي اسمها
hydra
وتشتغل تخمين 
SSH
زي ماقولنا
وبعد كدا تتصل وتاخد الملف
الي مكتوب بلغة
C
وتروح ترسله للسيرفر عن طريق الامر
scp file.c test@1.1.1.1:file.c

وبعد كدا تديله امر للاكسكيوت او تنفيذ الملف
gcc file.c -o file
وبعد كدا 
./file
الملف هيشتغل تمام كدا انت تخطيت الحماية 
تروح تكتب
cd /
وبعد كدا هتلاقي الملف =
passwd
هتلاقيه مقبلك
الباص بتاع التحدي مثال :-
ههههههه انت مفكرني هسيبك ع الجهاز ولا اي 
متخفش الباص بيتغير من تحدي لتحدي بسبب السيرفرات الي عليها وكلام من دا يعني
سلام 
English :


Required:

With the voice of the Egyptian you?

They are native inhabitants of ZIM nmap

Or you want to stay

After you get to meet Port 22
He is Maine
SSH
Ok Hakhsh Azi?
I tell you that you are going to work guessing or proto force
Ok I'm not a mama originally for the server Hzl Azai I tell you
Normal to facilitate the page where there is a loophole
Injection Command
Explanation Da Arabi for understanding is very simple
Ok I want to take advantage of the gaps
But you are going to pick up any path in the challenge.
1.1.1.1/about=sffsf
You are wasting your time exploiting how?
.
Is Da change
Walk after Kada and show you a file
Bassud
The user profile of the server
Thou shalt exhort them,
Amy
Jennifer
The words of da
The beautiful tool goes to her name
hydra
A guesswork is employed
SSH
Our costume
After you connect and take the file
It is written in a language
C
And you send it to the server
scp file.c test@1.1.1.1: file.c

After it has been modified, order the execscript or execute the file
GCC file
And after Kada
./a file
The file is fully functional so you are out of protection
Toreh writes
CD /
And after the file has come
Bassud
Come to your place
The challenge of the bus is:
Hahahahaha you Mkkrni Hsebk p device and no
The bus is low
Good meet
