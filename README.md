<div align="center">
  <p>
 <a href="https://discord.com/api/oauth2/authorize?client_id=692060368780001300&permissions=138042273056&scope=bot%20applications.commands"><img  src="https://cdn.discordapp.com/icons/694418750807736330/d6cce554798fdcd441d6b3e487ba116e.webp?size=4096" width="300" alt="qmy" /></a>
  </p>
  <p align="center">
  <a href="https://discord.com/api/oauth2/authorize?client_id=692060368780001300&permissions=138042273056&scope=bot%20applications.commands"><img src="https://img.shields.io/static/v1?label=Invite%20Me&message=Quran-قرآن&plastic&color=5865F2&logo=discord&style=for-the-badge"></a>
   <a href="https://discord.gg/3rZjSyS"><img src="https://img.shields.io/discord/694418750807736330?https://img.shields.io/static/v1?text=f&style=for-the-badge&logo=discord&logoColor=fff" alt="Discord server" /></a>
    <a href="LICENSE">
        <img src="https://img.shields.io/github/license/4i8/quranbot?label=License&style=for-the-badge">
    </a>
    <a href="https://github.com/4i8/quranbot/stargazers">
        <img src="https://img.shields.io/github/stars/4i8/quranbot?label=Stars&style=for-the-badge">
    </a>
    <a href="https://github.com/4i8/quranbot/releases/latest">
        <img src="https://img.shields.io/github/v/release/4i8/quranbot?label=Latest%20Version&style=for-the-badge">
    </a>
    <a href="https://github.com/4i8/quranbot/commit/master">
        <img src="https://img.shields.io/github/last-commit/4i8/quranbot?label=Last%20Update&style=for-the-badge">
    </a>
    <img src="https://img.shields.io/github/languages/code-size/4i8/quranbot?label=Size&style=for-the-badge">
    <a href="https://github.com/4i8/quranbot/issues">
        <img src="https://img.shields.io/github/issues/4i8/quranbot?label=Issues&style=for-the-badge">
    </a>
</p>
</div>

- [Installation And Setup](#english)
- [طريقة الاعداد](#عربي)

# الآن يمكن للمجتمع تنفيذ الإصلاحات والميزات الجديدة
# now it possible for the community to implement fixes and new features
# Just Pull Request

## **المشروع غير هادف للربح على الإطلاق**
## **The project is not for profit**
### It is never allowed to sell bots and you will be legally prosecuted
### لا يُسمح أبدًا ببيع  البوت وستتم مقاضاتك قانونًيا في حالة مخالفة هذا الشرط

# English
### First, download the project
```sh-session
git clone https://github.com/4i8/quranbot.git
```
### Second, install packages
```sh-session
cd quranbot
npm i
```
### Third, edit the config file
#### The most important thing is <required>, and the rest is optional if you want to modify it
```json
{
	"settings": {
		"nodes": [
			{
				"identifier": "MindServer",
				"host": "lava1.horizxon.studio",
				"port": 80,
				"password": "horizxon.studio",
				"secure": false
			}
		],
		"BOT_TOKEN": "<REQUIRD>",
		"TEST_BOT_TOKEN": "<REQUIRD>",
		"Mongo_DB": "<REQUIRD>",
		"Prefix": "/",
		"Basic_Lang": "AR",
		"Status": "DND",
		"Type": "PLAYING",
		"Activity": "/help",
		"Owner_ID": [],
		"Basis_permissions": [
			"MANAGE_GUILD",
			"MANAGE_MESSAGES",
			"MANAGE_WEBHOOKS",
			"SEND_MESSAGES",
			"VIEW_CHANNEL",
			"PRIORITY_SPEAKER",
			"CONNECT",
			"SPEAK",
			"MUTE_MEMBERS",
			"DEAFEN_MEMBERS",
			"MOVE_MEMBERS",
			"EMBED_LINKS",
			"ATTACH_FILES",
			"READ_MESSAGE_HISTORY"
		]
	},
	"colors": {
		"Primary": "9bda4d",
		"Warn": "ecad2d",
		"Error": "f91c37",
		"Dev": "0389fb"
	},
	"Links": {
		"server": "https://discord.gg/3rZjSyS",
		"invite": "https://discord.com/api/oauth2/authorize?client_id=692060368780001300&permissions=138042273056&scope=bot%20applications.commands",
		"website": ""
	},
	"emojis": {
		"error": "<:error:818207506530697236>",
		"True": "<:cool:818211436424855572>",
		"warn": "<:warn:818211442867306546>",
		"info": "<:info:818211440069574716>",
		"menu": "<:menu:818211363113402408>",
		"tips": "<:tips:818216712243118130>",
		"chevron": "<:chevron:818255260802875486>",
		"data": "<:data:818267628812238858>",
		"hashtag": "<:Hachtag:818418955471028254>",
		"dev": "<:dev:818420335065038858>",
		"off": "<:off:818221212261679174>",
		"on": "<:on:818221224655847475>",
		"wave": "<:wave:820012984935383090>",
		"points": "<:points:827703709563748362>",
		"settings_id": {
			"error": "818207506530697236",
			"True": "818211436424855572",
			"warn": "818211442867306546",
			"info": "818211440069574716",
			"menu": "818211363113402408",
			"tips": "818216712243118130",
			"chevron": "818255260802875486",
			"data": "818267628812238858",
			"hashtag": "818418955471028254",
			"dev": "818420335065038858",
			"wave": "820012984935383090"
		},
		"audio": {
			"backward": "<:backward:818215091584368650>",
			"forward": "<:forward:818215094089023498>",
			"pause": "<:pauseresume:818215095787061360>",
			"play": "<:play:818216718346223636>",
			"stop": "<:stop:818219872391397396>",
			"skip": "<:skip:818215099247362098> ",
			"loop": "<:loop:818216721788698674>",
			"off": "<:off:818221212261679174>",
			"on": "<:on:818221224655847475>",
			"vol_up": "<:vol_up:818283453433774090>",
			"vol_down": "<:vol_down:818283447780114442>",
			"clear": "<:Delete:818285019944583218>",
			"Shufel": "<:Shufel:826014148127096852>"
		},
		"audio_id": {
			"backward": "818215091584368650",
			"forward": "818215094089023498",
			"pause": "818215095787061360",
			"play": "818216718346223636",
			"stop": "818219872391397396",
			"skip": "818215099247362098",
			"loop": "818216721788698674",
			"off": "818221212261679174",
			"on": "818221224655847475",
			"vol_up": "818283453433774090",
			"vol_down": "818283447780114442",
			"clear": "818285019944583218",
			"Shufel": "826014148127096852"
		},
		"num": {
			"zero": "<:0_:827693326924382208>",
			"one": "<:1_:818211466862788608>",
			"tow": "<:2_:818211478275358750>",
			"three": "<:3_:818211496672493578>",
			"four": "<:4_:818211508788920380>",
			"five": "<:5_:818211555258269706>",
			"six": "<:6_:818211557640503346>",
			"seven": "<:7_:818211600661217280>",
			"eight": "<:8_:818211602889179227>",
			"nine": "<:9_:818211589375262771>",
			"ten": "<:10:818211598845476864>"
		},
		"num_id": {
			"zero": "827693326924382208",
			"one": "818211466862788608",
			"tow": "818211478275358750",
			"three": "818211496672493578",
			"four": "818211508788920380",
			"five": "818211555258269706",
			"six": "818211557640503346",
			"seven": "818211600661217280",
			"eight": "818211602889179227",
			"nine": "818211589375262771",
			"ten": "818211598845476864"
		}
	},
	"Webhooks": {
		"catch": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"console_log": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"use_commands": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"server_join": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"server_leave": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardDisconnect": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardError": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardReady": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardReconnecting": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardResume": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV"
	}
}
```
## Finally 
```
npm start
```
### `/prayer`
Multiple prayer time reminders with selecting countries The bot supports 23 countries, all Arab countries and some African countries. In the next updates, cities will be added in the Arab countries. Mention, cancel it, or change the country in the chat at any time
By writing and putting the chat you want to change the time and it will change automatically
### `/play`
More than 133 readers of all rewayas for each reader
### `/play`
It supports the search feature so that you write the name of the surah, the reciter, the surah number, or the reciter’s number, and it will give you options
### `/qasas`
To play the stories of the prophets with the voice of Nabil Al-Awadi and Tariq Al-Suwaidan in high quality
### `/quran`
The Mushaf command supports the search feature, so that you write the name of the surah, the order, or the page number, and it will show you the results with the feature of the Save Page button, so that if you return and write the command without any option, it will show you the last page you saved.
### The recovery system is stopped because there is no support for a powerful server that can handle the pressure
<br>
The recovery mode system automatically, if the boot has been reset, it will go back to the ROM and start the playlist, and at the last time it stopped, so don't worry about it

### `/azkar`
The order of dhikr is multiple, with specifying a time from five minutes to two days, you have the freedom to choose the time, and you can specify unlimited chats, and also change the chat time at any time for
By writing and putting the chat you want to change the time and it will change automatically
### `/khutma`
The order of khutma is multiple, with specifying a time from five minutes to two days, you have the freedom to choose the time, and you can specify unlimited chats, and also change the chat time at any time by writing and putting the chat you want to change the time for, and it will change automatically
### `/reset`
And if you want to interrupt the remembrance, the conclusion, or the reminder of the prayer times from the chat, write this command
### `/language`
The bot supports three languages, Arabic, English and French
### `/loop`
Repeat playlist
### `/nowplaying`
Knowing the surah that is working at the present time
### `/pause`
Pause the sound temporarily
### `/queue`
Know your playlist
### `/resume`
Audio resume
### `/seek`
Advance the sound to a specific time, for example: 1:03:50
### `/skip`
Skip the currently playing section
### `/volume`
Volume up limit 15010
### `/stop`
Destroy the playlist

# عربي

### اولا نزل البروجكت
```sh-session
git clone https://github.com/4i8/quranbot.git
```
### ثانياً نزل البكجات
```sh-session
cd quranbot
npm i
```
### ثالثاً عدل الكونفق
#### اهم شي <مطلوب> الباقي اختياري لو عايز تعدله عدله
```json
{
	"settings": {
		"nodes": [
			{
				"identifier": "MindServer",
				"host": "lava1.horizxon.studio",
				"port": 80,
				"password": "horizxon.studio",
				"secure": false
			}
		],
		"BOT_TOKEN": "<مطلوب>",
		"TEST_BOT_TOKEN": "<مطلوب>",
		"Mongo_DB": "<مطلوب>",
		"Prefix": "/",
		"Basic_Lang": "AR",
		"Status": "DND",
		"Type": "PLAYING",
		"Activity": "/help",
		"Owner_ID": [],
		"Basis_permissions": [
			"MANAGE_GUILD",
			"MANAGE_MESSAGES",
			"MANAGE_WEBHOOKS",
			"SEND_MESSAGES",
			"VIEW_CHANNEL",
			"PRIORITY_SPEAKER",
			"CONNECT",
			"SPEAK",
			"MUTE_MEMBERS",
			"DEAFEN_MEMBERS",
			"MOVE_MEMBERS",
			"EMBED_LINKS",
			"ATTACH_FILES",
			"READ_MESSAGE_HISTORY"
		]
	},
	"colors": {
		"Primary": "9bda4d",
		"Warn": "ecad2d",
		"Error": "f91c37",
		"Dev": "0389fb"
	},
	"Links": {
		"server": "https://discord.gg/3rZjSyS",
		"invite": "https://discord.com/api/oauth2/authorize?client_id=692060368780001300&permissions=138042273056&scope=bot%20applications.commands",
		"website": ""
	},
	"emojis": {
		"error": "<:error:818207506530697236>",
		"True": "<:cool:818211436424855572>",
		"warn": "<:warn:818211442867306546>",
		"info": "<:info:818211440069574716>",
		"menu": "<:menu:818211363113402408>",
		"tips": "<:tips:818216712243118130>",
		"chevron": "<:chevron:818255260802875486>",
		"data": "<:data:818267628812238858>",
		"hashtag": "<:Hachtag:818418955471028254>",
		"dev": "<:dev:818420335065038858>",
		"off": "<:off:818221212261679174>",
		"on": "<:on:818221224655847475>",
		"wave": "<:wave:820012984935383090>",
		"points": "<:points:827703709563748362>",
		"settings_id": {
			"error": "818207506530697236",
			"True": "818211436424855572",
			"warn": "818211442867306546",
			"info": "818211440069574716",
			"menu": "818211363113402408",
			"tips": "818216712243118130",
			"chevron": "818255260802875486",
			"data": "818267628812238858",
			"hashtag": "818418955471028254",
			"dev": "818420335065038858",
			"wave": "820012984935383090"
		},
		"audio": {
			"backward": "<:backward:818215091584368650>",
			"forward": "<:forward:818215094089023498>",
			"pause": "<:pauseresume:818215095787061360>",
			"play": "<:play:818216718346223636>",
			"stop": "<:stop:818219872391397396>",
			"skip": "<:skip:818215099247362098> ",
			"loop": "<:loop:818216721788698674>",
			"off": "<:off:818221212261679174>",
			"on": "<:on:818221224655847475>",
			"vol_up": "<:vol_up:818283453433774090>",
			"vol_down": "<:vol_down:818283447780114442>",
			"clear": "<:Delete:818285019944583218>",
			"Shufel": "<:Shufel:826014148127096852>"
		},
		"audio_id": {
			"backward": "818215091584368650",
			"forward": "818215094089023498",
			"pause": "818215095787061360",
			"play": "818216718346223636",
			"stop": "818219872391397396",
			"skip": "818215099247362098",
			"loop": "818216721788698674",
			"off": "818221212261679174",
			"on": "818221224655847475",
			"vol_up": "818283453433774090",
			"vol_down": "818283447780114442",
			"clear": "818285019944583218",
			"Shufel": "826014148127096852"
		},
		"num": {
			"zero": "<:0_:827693326924382208>",
			"one": "<:1_:818211466862788608>",
			"tow": "<:2_:818211478275358750>",
			"three": "<:3_:818211496672493578>",
			"four": "<:4_:818211508788920380>",
			"five": "<:5_:818211555258269706>",
			"six": "<:6_:818211557640503346>",
			"seven": "<:7_:818211600661217280>",
			"eight": "<:8_:818211602889179227>",
			"nine": "<:9_:818211589375262771>",
			"ten": "<:10:818211598845476864>"
		},
		"num_id": {
			"zero": "827693326924382208",
			"one": "818211466862788608",
			"tow": "818211478275358750",
			"three": "818211496672493578",
			"four": "818211508788920380",
			"five": "818211555258269706",
			"six": "818211557640503346",
			"seven": "818211600661217280",
			"eight": "818211602889179227",
			"nine": "818211589375262771",
			"ten": "818211598845476864"
		}
	},
	"Webhooks": {
		"catch": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"console_log": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"use_commands": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"server_join": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"server_leave": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardDisconnect": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardError": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardReady": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardReconnecting": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV",
		"shardResume": "https://discord.com/api/webhooks/1075847093056438332/PTxJUCOxrqd7pIr6iEl6pmWyNxxGyLnkaE0gVhzC8yzgYaLhjkFHhJfpbjmOoY82laqV"
	}
}
```
## واخيراً 
```
npm start
```
### `/prayer`
امر تذكير بوقت الصلاة متعدد مع تحديد الدول البوت يدعم 23 دولة جميع الدول العربية و بعض الدول الأفريقية في التحديثات القادمة سيتم اضافة المدن في الدول العربية وايضاً يمكنك تحديد المنشن المراد تحديده للتذكير بأوقات الصلاة بحيث يمنشه بس يجي موعد الصلاة ويمكنك تحديد شاتات بشكل لامحدود وايضا تغير المنشن او الغاءه او تغير الدولة اللي في الشات في اي وقت عن 
طريق كتابة ووضع الشات المراد تغير له الوقت وسيتغير تلقائياً
### `/play`
اكثر من 133 قارىء بجميع الروايات لكل قارىء
### `/play`
يدعم ميزة البحث بحيث تكتب اسم السورة او القارىء او رقم السورة او رقم القارىء وراح يطلع لك خيارات
### `/qasas` 
لتشغيل قصص الانبياء بصوت نبيل العوضي وطارق السويدان بجودة عالية
### `/quran`
امر المصحف  يدعم ميزة البحث بحيث تكتب اسم السورة او ترتيب او رقم الصفحة راح يطلعلك النتائج مع ميزة زر حفظ الصفحة بحيث لو رجعت كتبت الامر بدون اي اوبشن راح يطلعلك اخر صفحة انت حفظتها وايضاً تقدر تكتب الامر في خاص البوت مب شرط في السيرفر
### نظام الريكوفري متوقف بسبب انه لايوجد دعم لسيرفر قوي يتحمل الضغط
<br>
نظام ريكوفري مود تلقائيا لو صار رسترة للبوت راح يرجع للروم ويشغل قائمة التشغيل وعند اخر مدة وقف عنده ف لاتشيل هم

### `/azkar`
امر الاذكار متعدد مع تحديد وقت من خمس دقايق  الى يومين لك حرية الاختيار في الوقت ويمكنك تحديد شاتات بشكل لامحدود وايضا تغير وقت الشات في اي وقت عن 
طريق كتابة ووضع الشات المراد تغير له الوقت وسيتغير تلقائياً
### `/khutma`
امر الختمة متعدد مع تحديد وقت من خمس دقايق الى يومين لك حرية الاختيار في الوقت ويمكنك تحديد شاتات بشكل لامحدود وايضا تغير وقت الشات في اي وقت عن طريق كتابة ووضع الشات المراد تغير له الوقت وسيتغير تلقائياً 
### `/reset`
واذا تبغا تعطل الاذكار او الختمة او التذكير بأوقات الصلاة من الشات اكتب هذا الامر
### `/language`
البوت يدعم ثلاث لغات اللغة العربية والانجليزية والفرنسية
### `/loop`
عمل تكرار لقائمة التشغيل
### `/nowplaying`
معرفة السورة اللي شغالة في الوقت الحالي
### `/pause`
ايقاف الصوت بشكل مؤقت
### `/queue`
معرفة قائمة التشغيل
### `/resume`
استئناف الصوت
### `/seek`
تقديم الصوت الى وقت محدد مثال: 1:03:50
### `/skip`
تخطي المقطع اللي شغال حالياً
### `/volume`
رفع الصوت الحد 15010
### `/stop`
تدمير قائمة التشغيل