# &#128640; Ulas Can Sahin - eksiksiz Türkçe README

[🇬🇧](README.md) | [🇩🇪](README.de.md) | [🇪🇸](README.es.md) | [🇧🇷](README.pt-BR.md) | [🇹🇷](README.tr.md) | [🇫🇷](README.fr.md)

> Bu dosya kısa bir özet değil, tam Türkçe giriş sayfasıdır. Amaç, sınır, kullanım, doğrulama, güvenlik ve yayın akışını tek yerde anlatır.
>
> Kanonik İngilizce README: [README.md](README.md)

Public GitHub profile and repository gateway for Ulas Can Sahin.

En güncel İngilizce anlatım için kanonik README ile başlayın. Aynı operasyonel sözleşmeyi Türkçe okumak için bu sayfayı kullanın.

## Durum ve güven sinyalleri

|Alan | Detay|
|--- | ---|
|Durum | Public repository: ucsahinn/ucsahinn|
|Doğru kaynak | [Kanonik İngilizce README](README.md)|
|Kullanıcılar | Visitors who want to understand what Ulas ships.; Recruiters or collaborators looking for public project context.|
|Doğrulama | Language links point to existing files.; Profile assets render from tracked SVG files.|
|Güvenlik | Routes visitors to active public projects without hiding the project boundaries.; Keeps language navigation visible at the top of the profile README.|

## Bu repo nedir

- A profile-level entry point for shipped public repositories.
- A language-aware directory for Codex, security, product and documentation projects.
- A lightweight trust surface that points readers to the right repository instead of duplicating every project page.
- A place to show contribution signal, selected repository cards and current working areas.

## Ne değildir

- Not the source of truth for each product or package.
- Not a release channel for installers or archives.
- Not a place for private client, token, billing or infrastructure details.
- Not a replacement for each repository README, SECURITY file or release notes.

## Kimler için

- Visitors who want to understand what Ulas ships.
- Recruiters or collaborators looking for public project context.
- Users who need the right repo quickly.
- Maintainers checking that the profile stays public-safe.

## Hızlı başlangıç

1. Repoyu klonla veya güncelle.
2. README, güvenlik ve doküman haritasını oku.
3. Uygun doğrulamaları çalıştır.
4. Sadece bilinçli değişen dosyaları stage et.
5. Push veya release öncesi remote, secret ve link kontrollerini tekrar yap.

## Karar rehberi

- Need repo-specific install commands -> open that repository README.
- Need product release assets -> use the product repo release page, not this profile.
- Need security disclosure -> use the target repo SECURITY file if it exists.
- Need the high-level map -> stay on this profile README.

## Repo haritası

|Yol | Neden önemli|
|--- | ---|
|[README.md](README.md) | canonical profile README and language gateway|
|`README.de.md / README.es.md / README.pt-BR.md / README.tr.md / README.fr.md` | localized complete profile entry pages|
|[assets/profile/](assets/profile/) | public SVG cards used by the profile|
|[AGENTS.md](AGENTS.md) | repo-local working instructions|

## Çalışma akışı

1. Update profile copy from public repository facts only.
2. Keep links to active public repos clear and current.
3. Avoid stale claims about private work, user counts, rankings or unpublished releases.
4. Run link and secret checks before pushing profile changes.

## Komutlar ve doğrulama

Bu komutları sadece repoyu yerelde klonladıktan ve neyi kontrol ettiklerini anladıktan sonra çalıştırın.

```powershell
git diff --check
gitleaks dir . --no-banner --redact
git status --short --branch
```

## Doğrulama listesi

- Language links point to existing files.
- Profile assets render from tracked SVG files.
- No private paths, local-only release files or token-like values appear in README content.
- Remote main is checked after push.

## Güvenlik sınırı

- Routes visitors to active public projects without hiding the project boundaries.
- Keeps language navigation visible at the top of the profile README.
- Uses GitHub-native assets and workflow output only for public profile presentation.
- Excludes private operational details, credentials, dashboards and customer data.

Public-safe rule: do not add secrets, tokens, cookies, private keys, private prompts, customer data, local-only auth files, generated logs, archives or build outputs unless the canonical README explicitly says they belong in the public repo.

## Release ve yayın hijyeni

- Profile updates are documentation-only commits.
- Do not attach build artifacts or installers to this repository.
- Push only reviewed README and public asset changes.
- Verify GitHub rendered README after remote update when the change affects visible profile layout.

## Bakım

- Keep this localized README aligned with README.md when the repo contract changes.
- Prefer factual repo links over marketing claims.
- Do not invent install commands, metrics, users, releases or support promises.
- If a command is version-sensitive, re-check it before documenting it.
- When a localized file cannot be updated fully, leave a clear note instead of a partial translation.

## Katkı yolu

- Open a focused change against the smallest set of files.
- Read AGENTS.md or CONTRIBUTING.md when present before editing.
- Run the repo validation commands listed above.
- Review staged diffs explicitly before commit.
- Use security disclosure paths instead of public issues for sensitive reports.

## Bitti tanımı

Bitti demek: içerik tam, linkler doğru, güvenlik sınırı net, doğrulama çalışmış, Git temiz ve push sonrası remote HEAD kontrol edilmiş demektir.

|Öneri | Neden önemli|
|--- | ---|
|Content | Public GitHub profile and repository gateway for Ulas Can Sahin.|
|Links | All referenced local files must exist and resolve from the repository root.|
|Security | Profile assets render from tracked SVG files.|
|Verification | Public bir iddia vermeden önce yapıyı, linkleri, Markdown’u, secret taramasını, ilgili scriptleri ve remote HEAD’i doğrula.|
|Remote | After push, compare local HEAD with origin/main and GitHub remote HEAD.|

## Önemli bağlantılar

|Yol | Neden önemli|
|--- | ---|
|[Canonical README](README.md) | README.md|
|[Repo instructions](AGENTS.md) | AGENTS.md|
|[Profile assets](assets/profile/) | assets/profile/|
