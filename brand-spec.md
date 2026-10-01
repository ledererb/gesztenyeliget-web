# Gesztenyeliget — brand spec

**Rendszer egy mondatban:** meleg, szeriál vezérelt prémium editorial — törtfehér papír, mély antracit szöveg, terrakotta elsődleges akcent, ligetzöld másodlagos, Playfair Display címek + Inter szövegtörzs.

> Megjegyzés: a user-brief hex értékei felülírják a warm-editorial tokens.css alapértékeit (precedencia #1).

## Tokenek (OKLch-hex rögzítés)

- `--bg: #FAF7F2` — meleg törtfehér papír
- `--surface: #FFFFFF` — kártyák, lágy árnyékkal + 1px border
- `--fg: #1C1A17` — mély meleg antracit (sosem tiszta fekete)
- `--muted: #8A817A` — meta, időpont, alcímek
- `--accent: #C0512F` — terrakotta: elsődleges CTA, linkek, focus (1 kiemelt elem / képernyő)
- `--accent-2: #2F5B4F` — ligetzöld: szemöldök, tag-ek, elválasztók, árazat kiemelés
- `--border: color-mix(in oklab, var(--accent-2), transparent 92%)` — halvány zöld hajszálvonal

## Tipográfia

- Display: `'Playfair Display', Georgia, serif` (címek, árak, statisztika-számok)
- Body: `'Inter', -apple-system, system-ui, sans-serif`
- Mono: csak kódhoz (`ui-monospace`) — ezen az oldalon gyakorlatilag nem használt
- Skála: 13 · 15 · 17 · 20 · 28 · 42 · 64(+), line-height 1.62 body / 1.15 display, display tracking −0.02em

## Posture szabályok

1. Minimal chrome: whitespace hordozza a hierarchiát; árnyék csak lágy (card hover: y+2, blur 16, fg 6%).
2. Egy terrakotta elem képernyőnként; minden más előtérszín vagy ligetzöld.
3. Radius sáv: 8–24px (kártya 16, gomb 12, pill chip megengedett).
4. Gradiens, emoji, kórházi/steril vizuális klisé tiltva — fotó: meleg, természetes, emberi, ligetes.
5. Fejléc-tag-ek sentence case (magyar helyesírás), szemöldök (eyebrow) ligetzöld, letterspaced.

## Hangnem

Prémium, méltóságteljes, meleg, emberi. Nem intézményi nyelv: „lakó", „otthon", „gondoskodás" — sosem „ellátott", „osztály", „beteg".
