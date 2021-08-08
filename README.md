# encoding:utf-8
# Nasıl Barındırılır
Bu Bot'u dağıtmanın en kolay yolu
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/erdemliserkan58/musicpro/pull/1"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

Get STRING_NAME from here:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@QueenArzoo/VCPlayBot)

### Mandatory Vars.

- Zorunlu Değişkenlerden Bazıları:
   - `API_ID` :  Alternatif Telegram Hesabınızın API_ID'sini verin. ayrıca buradan [@APIInfoBot](https://t.me/APIinfoBot) alın
   - `API_HASH` :  Alternatif Telegram Hesabınızın API_HASH'ını verin. ayrıca buradan [@APIInfoBot](https://t.me/APIinfoBot) alın
   - `STRING_NAME` :  (https://replit.com/@QueenArzoo/VCPlayBot) bir dize oturumu yapın
   - `BOT_TOKEN` :  (https://t.me/botfather)'dan bir Bot yapın ve bot jetonunu doldurun.
   - `SUDO_USERS` :  Botu kontrol edebilmek istediğiniz kullanıcıların Kullanıcı Kimliğini doldurun. Her kimliğe s/b olarak bir boşluk bırakarak birden fazla kimlik ekleyebilirsiniz.







## Komutlar › 

- `/play <şarkı adı>` - Şarkıyı oynat
- `/dplay <şarkı adı>` - Şarkıyı deezer aracılığı ile oynat
- `/splay <şarkı adı>` - Şarkıyı jio saavn aracılığı ile oynat
- `/playlist` - Şimdi oynatma listesini göster
- `/current` - Şimdi oynatılanı göster
- `/song <şarkı adı>` - istediğiniz şarkıları hızlıca indirin
- `/search <query>` - youtube'da ayrıntılarla videoları arayın
- `/deezer <şarkı adı>` - deezer ile istediğiniz şarkıları hızlıca indirin
- `/saavn <şarkı adı>` - saavn üzerinden istediğiniz şarkıları hızlıca indirin
- `/video <şarkı adı>` - istediğiniz videoları hızlıca indirin

#### Yalnızca yöneticiler.
- `/player` - müzik çalar ayarları panelini aç
- `/pause` - şarkı çalmayı duraklat
- `/resume` - şarkı çalmaya devam
- `/skip` - sonraki şarkıyı çal
- `/end` - müzik çalmayı durdur
- `/userbotjoin` - asistanı sohbetinize davet edin
- `/userbotleave` - asistanı sohbetinizden kaldırın
- `/admincache` - Yönetici listesini yenile

### Kanal Müzik Oynatma Komutları›
Yalnızca bağlı grup yöneticileri için:
- `/cplay <şarkı adı>` - Şarkıyı oynat
- `/cplay <reply to link>` - cevaplanan youtube bağlantısını oynat
- `/cplay <reply to audio>` - cevaplanan dosyayı oynat
- `/cdplay <şarkı adı>` - şarkıyı deezer üzerinden oynat
- `/csplay <şarkı adı>` - jio saavn üzerinden şarkıyı oynat
- `/cplaylist` - Şimdi oynatma listesini göster
- `/cccurrent` - Şimdi oynatılıyor göster
- `/cplayer` - müzik çalar ayarları panelini aç
- `/cpause` - şarkı çalmayı duraklat
- `/cresume` - şarkı çalmaya devam et
- `/cskip` - sonraki şarkıyı çal
- `/cend` - müzik çalmayı durdur
- `/userbotjoinchannel` - asistanı sohbetinize davet edin
* kanal c yerine de kullanılabilir

Bağlantılı kanalda oynamayı sevmiyorsanız:
 1. Kanal kimliğinizi alın.
 2. Grubunuzu şu şekilde yeniden adlandırın: Kanal Müziği: your_channel_id
 3. @VCPlayBot'u tam izinlerle Kanal yöneticisi olarak ekleyin
 4. kanala yardımcı ekleyin
 5. Grubunuza komutları göndermeniz yeterlidir.

### Sudo Kullanıcıları için Komutlar âš”ï¸
- `/userbotleaveall` - asistanı tüm sohbetlerden kaldır
- `/gcast <mesajı yanıtla>' - küresel olarak tüm sohbetlere gönderilen mesajı yanıtladı
- `/pmpermit [on/off]` - pmpermit mesajını etkinleştir/devre dışı bırak

#### İzin ver
- `.a` - birinin size pm atmasını onaylayın
- `.da` - birinin size mesaj atmasını onaylamayın
+ Sudo Kullanıcıları herhangi bir grupta herhangi bir komutu çalıştırabilir

#### Müzik Botu Geliştiricisi
- [Rojserbest](http://github.com/rojserbes): Callsmusic Developer
# -*- coding:utf-8 -*-
