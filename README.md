# Loovenson AI Intelligence

Platfòm dijital Loovenson Dijital la fèt pou ede itilizatè yo aprann, kreye kontni, devlope prezans yo sou rezo sosyal, konprann sekirite dijital, epi eksplore opòtinite monetizasyon.

**Deviz:** Ede moun ateri nan Dijital.

## Fonksyon prensipal yo

- Asistan AI an kreyòl ayisyen ak franse
- Prompt Studio pou prepare enstriksyon AI ki pi efikas
- Sipò pou estrateji rezo sosyal
- Aprantisaj sou sekirite dijital
- Ide pou biznis ak monetizasyon dijital
- Entèfas ki adapte ak telefòn ak òdinatè

## Fichye pwojè a

- `index.html` — estrikti paj aplikasyon an
- `styles.css` — konsepsyon ak aparans aplikasyon an
- `app.js` — entèraksyon nan navigatè a
- `netlify.toml` — konfigirasyon Netlify ak wout API yo
- `netlify/functions/chat.mjs` — fonksyon sèvè ki voye demann bay Gemini
- `netlify/functions/status.mjs` — verifye si sèvis la konfigire san li pa revele kle a
- `.gitignore` — evite ajoute fichye anviwònman prive ak dosye devlopman
- `.env.example` — modèl konfigirasyon san okenn kle reyèl

## Mete pwojè a sou GitHub

1. Kreye yon depo GitHub pou pwojè a.
2. Voye tout fichye ak dosye pwojè a. Kenbe dosye `netlify/functions` la nan menm estrikti sa a.
3. Pa mete okenn kle API, modpas oswa token nan okenn fichye piblik.
4. Si GitHub montre yon avètisman sou enfòmasyon sansib, kanpe epi verifye fichye ak liy li montre a. Pa fòse piblikasyon an si gen yon sekrè reyèl ladan l.

## Deplwaye sou Netlify

1. Nan Netlify, chwazi pou enpòte yon pwojè ki soti nan GitHub epi konekte depo a.
2. `netlify.toml` deja defini dosye piblikasyon an ak fonksyon yo. Si Netlify mande paramèt, sèvi ak `.` pou Publish directory; Functions directory se `netlify/functions`.
3. Nan paramèt sit la, ouvri **Environment variables** epi ajoute `GEMINI_API_KEY` kòm non varyab la. Mete kle Gemini pa w la kòm valè a dirèkteman nan Netlify sèlman.
4. Ajoute `GEMINI_MODEL` ak yon non modèl Gemini ki disponib pou pwojè API ou a. Kòd la sèvi ak `gemini-2.5-flash` kòm valè pa defo si ou pa defini varyab sa a.
5. Redeplwaye sit la apre ou fin mete varyab yo.
6. Teste aplikasyon an sou sit ki deplwaye a.

## Sekirite enpòtan

- Pa janm mete kle API reyèl la nan GitHub, nan HTML, CSS, JavaScript ki kouri nan navigatè a, oswa nan README a.
- Pa voye kle API a nan mesaj oswa nan ekran ou pataje.
- Si yon kle reyèl te pibliye aksidantèlman, revoke li epi kreye yon nouvo nan sèvis ofisyèl la.
- Vèsyon sa a se yon baz pwojè. Anvan ou pataje l ak anpil moun, ajoute mezi kont abi, limit demann, ak pwoteksyon itilizasyon.
- Limit ak disponiblite sèvis AI ka chanje selon kont ak kondisyon founisè a.

## Lis verifikasyon

- [ ] Tout fichye yo nan depo GitHub la
- [ ] Dosye `netlify/functions` la prezève
- [ ] `GEMINI_API_KEY` antre nan Netlify Environment variables, pa nan GitHub
- [ ] Sit la deplwaye epi tès AI a reyisi
