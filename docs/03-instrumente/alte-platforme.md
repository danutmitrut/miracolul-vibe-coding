# Alte platforme și unelte

Pe lângă platformele full-stack și editoarele de cod, există instrumente specializate care completează ecosistemul vibe coding.

## Claude (Anthropic)

### Ce e

Claude e un model AI conversațional creat de Anthropic. Nu e o platformă de dezvoltare în sine, dar e "creierul" din spatele multor unelte de vibe coding.

### De ce contează

- **Cursor îl folosește** - E modelul preferat de mulți pentru generare de cod
- **Conversație naturală** - Înțelege context complex și nuanțe
- **Cod de calitate** - Generează cod curat, bine structurat

### Cum să-l folosești direct

1. Mergi pe claude.ai
2. Descrii ce vrei să construiești
3. Claude generează codul
4. Copiezi în proiectul tău

### Exemplu

Tu: "Am nevoie de un script Python care să-mi descarce toate pozele dintr-un folder Google Drive și să le organizeze după data creării în subfoldere de tip An/Luna."

Claude: Generează scriptul complet, cu explicații și instrucțiuni de folosire.

### Când să-l folosești

- **Brainstorming tehnic** - Discuți arhitectura înainte de a construi
- **Cod izolat** - Funcții, scripturi, bucăți de logică
- **Învățare** - Întrebi "cum funcționează X?" și primești explicații
- **Debugging** - Copiezi eroarea și ceri ajutor

### Cost

- Gratuit pentru utilizare de bază
- ~$20/lună pentru Claude Pro (limite mai mari, acces la modelele cele mai noi)

---

## v0 by Vercel

### Ce e

v0 e un generator de interfețe de utilizator. Descrii ce vrei să vezi, primești componente React gata de folosit.

### Pentru ce e bun

- **Landing pages** - Secțiuni hero, pricing, features
- **Dashboard-uri** - Tabele, grafice, carduri statistici
- **Formulare** - Login, register, contact
- **Componente UI** - Butoane, modale, navigații

### Cum funcționează

1. Descrii componenta: "Un card de produs cu imagine, titlu, preț și buton de adăugare în coș"
2. v0 generează codul React + Tailwind CSS
3. Copiezi în proiectul tău

### Exemplu output

```jsx
<Card>
  <CardHeader>
    <Image src="/product.jpg" alt="Produs" />
  </CardHeader>
  <CardContent>
    <h3 className="text-lg font-bold">Nume Produs</h3>
    <p className="text-2xl text-green-600">149 RON</p>
  </CardContent>
  <CardFooter>
    <Button className="w-full">Adaugă în coș</Button>
  </CardFooter>
</Card>
```

### Puncte forte

- **Design modern** - Componente care arată profesional din start
- **Cod curat** - Folosește best practices (Tailwind, shadcn/ui)
- **Variante** - Primești multiple opțiuni din care să alegi

### Limitări

- **Doar UI** - Nu include logică sau backend
- **Trebuie integrat** - Codul trebuie pus undeva

### Ideal pentru

Developeri frontend sau antreprenori care lucrează cu un developer și vor să accelereze partea vizuală.

---

## Framer AI

### Ce e

Framer e un tool de design și dezvoltare de site-uri. Framer AI adaugă generare din text.

### Pentru ce e bun

- **Site-uri de prezentare** - Portofolii, landing pages
- **Site-uri pentru afaceri mici** - Restaurant, salon, cabinet
- **One-pagers** - Pagini simple, elegante

### Cum funcționează

1. Descrii site-ul: "Site pentru o cafenea artizanală, cu meniu, locație pe hartă și formular de contact"
2. Framer generează design-ul complet
3. Ajustezi vizual
4. Publici direct

### Puncte forte

- **Design de calitate** - Arată ca făcut de profesionist
- **Responsive** - Funcționează pe mobil din start
- **Hosting inclus** - Nu trebuie să configurezi nimic

### Limitări

- **Site-uri statice** - Nu pentru aplicații complexe
- **Personalizare limitată** - Ești în cadrul sistemului Framer

### Ideal pentru

Freelanceri, afaceri mici, oricine are nevoie de site frumos rapid.

---

## Softr

### Ce e

Softr transformă o bază de date (Airtable, Google Sheets) într-o aplicație web.

### Pentru ce e bun

- **Portaluri pentru clienți** - Clienții își văd comenzile, facturile
- **Directoare** - Liste de membri, produse, locații
- **Aplicații interne** - Instrumente pentru echipă

### Cum funcționează

1. Ai date în Airtable sau Google Sheets
2. Conectezi Softr la ele
3. Softr generează interfața automat
4. Personalizezi cu AI sau drag-and-drop
5. Publici

### Exemplu

Ai un spreadsheet cu angajați (nume, departament, email, foto). Softr îl transformă într-un director intern cu căutare, filtrare și profiluri individuale.

### Puncte forte

- **Rapid** - De la spreadsheet la aplicație în ore
- **Sincronizare live** - Datele se actualizează automat
- **Autentificare** - Poți avea utilizatori cu conturi

### Limitări

- **Limitat de structura datelor** - Ce e în spreadsheet, aia poate afișa
- **Complexitate redusă** - Nu pentru logică avansată

### Ideal pentru

Echipe care deja folosesc Airtable/Sheets și vor o interfață mai frumoasă pentru date.

---

## Tabel sumar

| Unealtă | Tip | Pentru ce | Cost start |
|---------|-----|-----------|------------|
| **Claude** | AI conversațional | Cod, brainstorming, debugging | Gratuit |
| **v0** | Generator UI | Componente React | Gratuit |
| **Framer AI** | Site builder | Site-uri prezentare | Gratuit |
| **Softr** | Spreadsheet → App | Aplicații din date | Gratuit |

## Combinația câștigătoare

Pentru un antreprenor care vrea să construiască un MVP:

1. **Claude** - Discuți ideea, planifici arhitectura
2. **v0** - Generezi interfețele rapid
3. **Cursor** sau **Replit** - Asamblezi totul
4. **Framer** - Faci landing page-ul de prezentare

Fiecare unealtă face ce știe mai bine. Tu le orchestrezi.

---

**Următorul capitol:** [Viteză și eficiență](../04-filozofie-si-valori/viteza-eficienta.md) - De ce contează să mergi rapid
