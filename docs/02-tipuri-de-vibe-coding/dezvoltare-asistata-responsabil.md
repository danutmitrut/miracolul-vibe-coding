# Dezvoltare asistată de AI responsabil

A doua abordare e pentru când miza crește. Când nu-ți mai permiți să pierzi proiectul. Când ai clienți, bani sau reputație în joc.

## Ce se schimbă

În dezvoltarea asistată responsabil, AI-ul rămâne partenerul tău, dar **tu rămâi responsabil**.

- Citești codul generat (sau măcar părțile critice)
- Înțelegi ce face înainte să-l accepți
- Testezi sistematic
- Documentezi deciziile importante
- Păstrezi controlul asupra arhitecturii

E ca diferența dintre a lăsa GPS-ul să te ducă oriunde zice el și a verifica din când în când că drumul are sens.

## Cum arată în practică

### Pasul 1: Definești clar cerința

Nu doar "vreau o aplicație de task-uri", ci:

> "Vreau o aplicație de management al task-urilor cu:
> - Autentificare prin email
> - Liste de task-uri pe proiecte
> - Deadline-uri cu notificări
> - Posibilitate de colaborare (invit colegi)
> - Export în CSV"

Cu cât cerința e mai clară, cu atât AI-ul generează cod mai relevant.

### Pasul 2: Generezi în bucăți mici

În loc să ceri toată aplicația odată, construiești modular:

1. "Creează sistemul de autentificare"
2. Verifici, testezi, ajustezi
3. "Acum adaugă structura pentru proiecte și task-uri"
4. Verifici, testezi, ajustezi
5. Și așa mai departe

Bucățile mici sunt mai ușor de înțeles și de corectat.

### Pasul 3: Review și testare

După fiecare bucată:

- **Citești codul** - Nu trebuie să înțelegi fiecare linie, dar trebuie să înțelegi logica generală
- **Testezi funcționalitatea** - Funcționează ce trebuie?
- **Testezi edge cases** - Ce se întâmplă dacă utilizatorul face ceva neașteptat?
- **Verifici securitatea** - Datele sensibile sunt protejate?

### Pasul 4: Documentezi

Notezi deciziile importante:
- De ce ai ales această structură
- Ce face fiecare componentă majoră
- Cum se leagă părțile între ele

Documentația te salvează peste 6 luni când ai uitat tot.

## Rol nou: Arhitect-Manager

În această abordare, nu mai ești doar "prompter". Devii un fel de **manager de proiect tehnic**:

- **Definești viziunea** - Ce trebuie să facă aplicația
- **Împarți munca** - Ce să construiască AI-ul în ce ordine
- **Evaluezi livrabilele** - E ok ce a generat?
- **Integrezi** - Cum se potrivesc piesele împreună
- **Asiguri calitatea** - Respectă standardele necesare?

Nu scrii cod, dar conduci procesul.

## Când e obligatorie această abordare

### Aplicații cu utilizatori reali

Orice altcineva în afară de tine folosește aplicația? Responsabilitate.

### Date sensibile

Nume, emailuri, parole, date financiare, informații de sănătate? Responsabilitate maximă.

### Tranzacții financiare

Bani care se mișcă? Nu există "aproape corect". Trebuie să fie corect.

### Integrări cu alte sisteme

Te conectezi la API-uri externe, baze de date existente, servicii third-party? Un bug poate afecta mai mult decât aplicația ta.

### Proiecte cu viață lungă

Dacă proiectul va exista peste 6 luni și va necesita modificări, trebuie să înțelegi ce ai construit.

## Beneficiile

### Încredere

Știi că ce ai construit e solid pentru că ai verificat.

### Mentenabilitate

Poți reveni peste timp și modifica, pentru că înțelegi structura.

### Scalabilitate

Poți crește echipa, pentru că există documentație și cod curat.

### Profesionalism

Poți livra clienților cu încredere.

## Costul

Durează mai mult decât pure vibe coding. Poate de 2-3 ori mai mult.

Dar e tot de 5-10 ori mai rapid decât dezvoltarea tradițională.

E un compromis: renunți la o parte din viteză pentru a câștiga siguranță și sustenabilitate.

## Mixul inteligent

În realitate, majoritatea proiectelor combină ambele abordări:

1. **Faza de explorare** (pure vibe coding)
   - Testezi ideea
   - Experimentezi cu variante
   - Validezi că are sens

2. **Faza de construcție** (dezvoltare responsabilă)
   - Reconstruiești cu atenție
   - Verifici și testezi
   - Documentezi

E ca diferența dintre schița rapidă și desenul final. Ambele au rolul lor.

---

**Următorul capitol:** [Categorii de unelte](categorii-unelte.md) - Ce instrumente ai la dispoziție
