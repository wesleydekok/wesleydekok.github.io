# IRIS Website — Decap CMS Setup

## Wat upload je naar GitHub?

Upload deze volledige mapstructuur naar je repository `wesleydekok.github.io`:

```
/
├── index.html
├── activiteiten.html
├── bestuur.html
├── admin/
│   ├── index.html
│   └── config.yml
├── content/
│   ├── activiteiten/      ← JSON per activiteit
│   ├── bestuur/           ← JSON per bestuurslid
│   ├── sponsors/          ← JSON per sponsor
│   └── nieuws/            ← JSON per nieuwsbericht
└── uploads/               ← afbeeldingen (aangemaakt door CMS)
```

---

## Eenmalige setup (15 minuten)

### Stap 1 — Netlify account aanmaken
1. Ga naar **netlify.com** en maak een gratis account
2. Klik **"Add new site" → "Import an existing project"**
3. Koppel je GitHub account en selecteer `wesleydekok.github.io`
4. Deploy settings laat je standaard → klik **"Deploy site"**

> Je site is nu ook bereikbaar via een netlify.app URL, maar GitHub Pages blijft gewoon werken.

### Stap 2 — Netlify Identity aanzetten
1. Ga in Netlify naar **Site configuration → Identity**
2. Klik **"Enable Identity"**
3. Scroll naar **Registration** → zet op **"Invite only"**
4. Scroll naar **Git Gateway** → klik **"Enable Git Gateway"**

### Stap 3 — Jezelf uitnodigen als admin
1. Ga naar **Identity → Invite users**
2. Vul jouw e-mailadres in
3. Je krijgt een e-mail → klik de link → stel een wachtwoord in

### Stap 4 — CMS openen
Ga naar `https://wesleydekok.github.io/admin/`
Log in met je Netlify Identity e-mail + wachtwoord.

---

## Gebruik

### Activiteit toevoegen
1. Ga naar `/admin/`
2. Klik **Activiteiten → Nieuwe activiteit**
3. Vul alles in → klik **Publiceren**
4. Binnen 1 minuut staat het live op de site

### Bestuurslid toevoegen
1. Klik **Bestuursleden → Nieuw bestuurslid**
2. Upload een foto, vul naam en functie in
3. Klik **Publiceren**

### Nieuwsbericht plaatsen
1. Klik **Nieuwsberichten → Nieuw nieuwsbericht**
2. Schrijf je bericht in de editor
3. Klik **Publiceren**

---

## Vragen?
Neem contact op via je eigen kanalen of vraag het opnieuw aan Claude!
