# Ulas Can Sahin

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Security urunleri, self-hosted vault isleri, Codex workflow lari ve public-safe engineering dokumantasyonu icin public profil ve proje giris sayfasi.

## Bu repo neden var

Security urunleri, self-hosted vault isleri, Codex workflow lari ve public-safe engineering dokumantasyonu icin public profil ve proje giris sayfasi.

Bu lokalize giris sayfasi, okuyucunun repoyu kisa bir dil etiketine bakarak tahmin etmemesi icin tutulur. Derin kanonik referans README.md dosyasinda kalir; bu sayfa dogru baslangic noktasini, guvenlik sinirini ve dogrulama yolunu secmek icin yeterli baglam verir.

## Kimler icin

MyVuln, PassMan veya Codex starter repolarini hizlica anlamak isteyen guvenlik ekipleri, operator lar, reviewer lar ve gelistiriciler.

## Hizli baslangic

| Ihtiyacin varsa... | Ac |
| --- | --- |
| MyVuln live product | [https://myvuln.io/](https://myvuln.io/) |
| PassMan release hub | [https://github.com/ucsahinn/passman](https://github.com/ucsahinn/passman) |
| Codex Skill Forge | [https://github.com/ucsahinn/codex-skill-forge](https://github.com/ucsahinn/codex-skill-forge) |
| Codex CLI Handbook | [https://github.com/ucsahinn/codex-cli-best-practice](https://github.com/ucsahinn/codex-cli-best-practice) |
| Prompt Architect | [https://github.com/ucsahinn/codex-enterprise-prompt-architect](https://github.com/ucsahinn/codex-enterprise-prompt-architect) |

## Repo haritasi

- README.md - canonical profile page
- README.tr.md / README.de.md / README.es.md / README.pt-BR.md / README.fr.md - localized front doors
- GitHub profile repositories - project-specific source of truth

## Validasyon ve release hijyeni

Commit veya yayin oncesinde linkler, Markdown, mevcut repo validasyonu ve Gitleaks kontrol edilmelidir.

Onerilen release/readiness yolu:

1. Ilgili README ve bagli dokumanlari incele.
2. Repo validasyon komutu varsa calistir.
3. Markdown linklerini ve lokal assetleri kontrol et.
4. Gitleaks veya yapilandirilmis secret scan i calistir.
5. Push sonrasi yayinin bittigini soylemeden once origin/main dogrulamasi yap.

## Guvenlik ve public scope siniri

Profil sayfasi public repolara ve canli yuzeylere gider. Private kaynak kod, musteri verisi, secret ve local operator path bu repo yuzeyinde tutulmaz.

## Katki ve bakim

Scope, kurulum adimlari, release kurallari veya guvenlik sinirlari degistiginde lokalize sayfalari kanonik README ile ayni cizgide tut. Repo, canli urun dokumani veya public release kanitiyla desteklenmeyen iddia ekleme.

## Eksiksizlik standardi

Bu lokalize README kisa not degildir. Amac, baslangic, repo yuzeyleri, validasyon, guvenlik siniri ve kanonik referanslari aciklar.

Kanonik referans: [README.md](README.md).
