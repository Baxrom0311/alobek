# Bobojonov A'lobek — saylov oldi prezentatsiyasi

Animatsiyali veb-prezentatsiya (statik sayt, build shart emas).

## Tuzilma
- `site/index.html` — prezentatsiya (Netlify shu papkani chop etadi)
- `site/assets/` — logotiplar, rasm, favicon, ijtimoiy tarmoq preview rasmi
- `netlify.toml` — Netlify sozlamalari (`publish = "site"`)
- `saylov_prezentatsiya.html` — hammasi bitta faylda (offline ochish uchun)
- `saylov_oq_fon.pptx` — PowerPoint varianti

## Netlify'ga ulash
1. app.netlify.com → **Add new site → Import an existing project → GitHub**
2. `Baxrom0311/alobek` repozitoriyasini tanlang
3. Branch: `claude/presentation-editing-logos-v00uf5` (yoki `main`ga merge qilingan bo'lsa `main`)
4. Build command — bo'sh qoldiring, Publish directory — `site` (netlify.toml avtomatik to'ldiradi)
5. **Deploy** — tayyor. Sayt nomini *Site configuration → Change site name* orqali o'zgartirish mumkin.

## Boshqarish
`→` / `Space` — keyingi, `←` — oldingi, `F` — to'liq ekran, `#5` kabi havola — to'g'ridan-to'g'ri 5-slayd.
