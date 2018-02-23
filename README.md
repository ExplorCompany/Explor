# Explor
سورس مورگان ورژن 1

آموزش نصب:

اول سورس را گیت کلون میکنیم

vertical_traffic_light git clone https://github.com/morgan-team/morgan-V1

وارد مسیر زیر میشیم

vertical_traffic_light morgan/api/bot/bot.lua

در خط 3 توکن ربان ای پی را قرار می دهیم

در خط 5 ایدی عددی سودو اصلی

در خط 165 ایدی عددی سودو و ایدی عددی ربات سی ال ای

سیو میکنیم خارج میشیم

وارد مسیر زیر میشیم

vertical_traffic_light morgan/cli/plugins/Tools

در خط 2 ایدی عددی سودو را جا گذاری می کنیم

سیو می کنیم

وارد مسیر زیر میشیم

vertical_traffic_lightmorgan/cli/bot/bot.lua

در خط 17 ایدی عددی ربات ای پی را قرار می دهیم

در خط 95 ایدی عددی سودو و ایدی عددی ربات سی ال ای راقرار می دهیم

سیو میکنیم خارج میشیم

دستورات زیر را در ترمینال وارد کنید

vertical_traffic_light cd morgan/cli

vertical_traffic_light chmod +x morgan.sh

vertical_traffic_light chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

vertical_traffic_light ./morgan.sh install

vertical_traffic_light ./morgan.sh

صبر میکنیم تا کامل نصب بشه

شماره ربات وارد مکنید کد میزنید‌

از سرور خارج و دوباره وصل میشید...

کد های زیر را در سرور میزنیم

vertical_traffic_light cd morgan/api

vertical_traffic_light chmod +x morgan.sh

vertical_traffic_light chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

vertical_traffic_light ./morgan.sh install

vertical_traffic_light ./morgan.sh

صبر کنید تموم شه ، بعد ترمینال رو ببندید .

حالا ربات اماده لانچ کردنه :

vertical_traffic_lightcd morgan/api && chmod +x auto.sh && chmod 777 auto.sh && screen ./auto.sh

یه ترمینال دیگه باز کنید و این رو بزنید :

vertical_traffic_light cd morgan/cli && chmod +x auto.sh && chmod 777 auto.sh && screen ./auto.sh

تموم . میتونید از سرور خارج شید .

black_small_squareChannel : @ExplorCompany

black_small_squareEdited By :  @kiarashNASA
