---
layout: default
---

Metin **kalın**, _italik_, ~~üstü çizili~~ veya `anahtar kelime` olabilir.

[Başka bir sayfaya bağlantı](./writeups.html).

Paragraflar arasında boşluk olmalıdır.

Paragraflar arasında boşluk olmalıdır. Projeniz hakkında bilgi içeren bir README veya dosya eklemenizi öneririz.

# Başlık 1

Bu, bir başlıktan sonra gelen normal bir paragraftır. GitHub, sürüm kontrolü ve işbirliği için bir kod barındırma platformudur. Sizin ve başkalarının projeler üzerinde her yerden birlikte çalışmasını sağlar.

## Başlık 2

> Bu, bir başlıktan sonra gelen bir alıntıdır.
>
> Bir şey yeterince önemliyse, olasılıklar aleyhinize olsa bile yaparsınız.

### Başlık 3

```js
// Sözdizimi vurgulu Javascript kodu.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Sözdizimi vurgulu Ruby kodu
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

<pre 
  class="command-line" 
  data-prompt="kali@kali $" 
  data-output="4"
><code class="language-bash"># Kabuk ile Bash betiği
echo "flag{i_4m_a_f14g}" > flag.txt
cat flag.txt
flag{i_4m_a_f14g}
rm flag.txt</code>
</pre> 

<pre class="line-numbers" 
  data-start="1" 
  data-line="6-7"
><code class="language-dart">// Satır numaralı Dart kodu
// 6. ve 7. satırlar vurgulanmıştır

import 'dart:ui';

import 'package:shared_preferences_web/shared_preferences_web.dart';
import 'package:url_launcher_web/url_launcher_web.dart';

import 'package:flutter_web_plugins/flutter_web_plugins.dart';

// ignore: public_member_api_docs
void registerPlugins(PluginRegistry registry) {
  SharedPreferencesPlugin.registerWith(registry.registrarFor(SharedPreferencesPlugin));
  UrlLauncherPlugin.registerWith(registry.registrarFor(UrlLauncherPlugin));
  registry.registerMessageHandler();
}</code></pre>


#### Başlık 4

*   Bu, bir başlıktan sonra gelen sırasız bir listedir.
*   Bu, bir başlıktan sonra gelen sırasız bir listedir.
*   Bu, bir başlıktan sonra gelen sırasız bir listedir.

##### Başlık 5

1.  Bu, bir başlıktan sonra gelen sıralı bir listedir.
2.  Bu, bir başlıktan sonra gelen sıralı bir listedir.
3.  Bu, bir başlıktan sonra gelen sıralı bir listedir.

###### Başlık 6

| başlık1      | başlık iki         | üç    |
|:-------------|:------------------|:------|
| tamam        | iyi isveç balığı   | güzel |
| stokta yok   | iyi ve bol         | güzel |
| tamam        | iyi `oreos`        | hmm   |
| tamam        | iyi `zoute` drop   | yumm  |

### Aşağıda bir yatay çizgi var.

* * *

### Sırasız liste örneği:

*   Öğe foo
*   Öğe bar
*   Öğe baz
*   Öğe zip

### Sıralı liste örneği:

1.  Birinci öğe
1.  İkinci öğe
1.  Üçüncü öğe
1.  Dördüncü öğe

### İç içe liste örneği:

- seviye 1 öğe
  - seviye 2 öğe
  - seviye 2 öğe
    - seviye 3 öğe
    - seviye 3 öğe
- seviye 1 öğe
  - seviye 2 öğe
  - seviye 2 öğe
  - seviye 2 öğe
- seviye 1 öğe
  - seviye 2 öğe
  - seviye 2 öğe
- seviye 1 öğe

### Küçük resim

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Büyük resim

![Dallanma](https://guides.github.com/activities/hello-world/branching.png)

### Tanım listeleri HTML sözdizimiyle kullanılabilir.

<dl>
<dt>Adı</dt>
<dd>Godzilla</dd>
<dt>Doğum</dt>
<dd>1952</dd>
<dt>Doğum Yeri</dt>
<dd>Japonya</dd>
<dt>Renk</dt>
<dd>Yeşil</dd>
</dl>

```
Uzun, tek satırlık kod blokları kaydırılmalıdır. Çok uzunsa yatay kaydırma olmalıdır. Bu satır bunu göstermek için yeterince uzun olmalı.
```

```
Son öğe.
```
