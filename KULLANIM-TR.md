# Agency Agents — Türkçe kullanım

Bu depo, `msitarzewski/agency-agents` projesinin `ceyhunyildizcy-oss` hesabındaki fork'udur. Uzman dosyaları, yapay zekâya görev sırasında yol gösteren talimatlardan oluşur.

## Bu sohbette kullanma

GitHub bağlantısıyla bu depoya erişilebildiğinde, istediğin işi ve uzmanı belirt:

- “Agency Agents kullan: Instagram hesabım için 7 günlük Reels planı hazırla.”
- “Agency Agents Frontend Developer kullan: mobil uyumlu bir ana sayfa geliştir.”
- “Agency Agents Code Reviewer kullan: şu kodu incele.”
- “Agency Agents kullan: bu proje için uygun uzmanı seç ve işe başla.”

Yeni bir sohbette kaynağı da belirtmek için şu mesajı kullan:

> @GitHub `ceyhunyildizcy-oss/agency-agents` deposundaki `.agents/skills/agency-agents/SKILL.md` dosyasını oku. Görevime uygun uzman dosyasını da okuyup uygula. Görevim: [yapılacak işi yaz].

Asistan önce uygun uzman dosyasını okur, sonra onun yöntemini işine uygular. Marka, hedef kitle, kod veya diğer gerekli girdileri mesajına ekle.

## Codex'te kullanma

Bu depoyu bir Codex çalışma ortamında aç. Depodaki `.agents/skills/agency-agents/` becerisi, depo kapsamındaki becerileri destekleyen Codex ortamları için hazırlanmıştır.

Örnek:

```text
$agency-agents Bu proje için uygun uzmanı seç; önce mevcut kodu incele ve istenen özelliği uygula.
```

Kök dizindeki `AGENTS.md` de aynı beceriye yönlendirir. Becerinin görünürlüğü kullandığın Codex ortamına bağlıdır; yalnızca GitHub bağlantısı kurmak depoyu yerel çalışma ortamı olarak açmakla aynı şey değildir.

## Kapsam

- Fork oluşturmak, bu dosyaları bütün sohbetlere otomatik olarak yüklemez.
- Bu düzenleme tek asistanın ilgili uzman talimatlarından yararlanmasını sağlar; tüm uzmanları ayrı süreçler olarak başlatmaz.
- Görev ve uzman dosyası, kullanılabilecek araçların veya erişim izinlerinin yerine geçmez.
- Diğer araçlara özel kurulum seçenekleri için mevcut `README.md` dosyasını kullan.

Kaynaklar: [Orijinal proje](https://github.com/msitarzewski/agency-agents) · [Resmî beceri belgesi](https://learn.chatgpt.com/docs/build-skills)
