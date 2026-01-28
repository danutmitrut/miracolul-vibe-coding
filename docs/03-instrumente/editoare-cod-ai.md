# Editoare de cod cu AI

Dacă platformele full-stack sunt "apartamente mobilate", editoarele de cod cu AI sunt "terenuri cu utilități". Mai multă muncă, dar și mai mult control.

## Cursor

### Ce e

Cursor e un editor de cod (IDE) construit de la zero cu AI în centru. E bazat pe VS Code (cel mai popular editor de cod din lume), dar cu superputeri AI.

### De ce e special

Cursor nu e doar un editor cu AI adăugat. E un editor în care AI-ul înțelege tot proiectul tău:
- Citește toate fișierele
- Înțelege arhitectura
- Știe ce ai construit deja
- Poate modifica cod existent, nu doar genera nou

### Cum funcționează

1. **Chat** - Vorbești cu AI-ul despre ce vrei
2. **Cmd+K** - Selectezi cod și ceri modificări
3. **Tab** - Accepti sugestii în timp real
4. **Composer** - Faci modificări în mai multe fișiere simultan

### Exemplu practic

Tu: "Adaugă un buton de export PDF la tabelul de comenzi"

Cursor:
- Găsește fișierul cu tabelul
- Identifică unde să adauge butonul
- Scrie codul pentru buton
- Creează funcția de export
- Adaugă biblioteca necesară

Tu verifici și accepți (sau ajustezi).

### Puncte forte

- **Context complet** - Înțelege tot proiectul, nu doar fișierul curent
- **Modificări multi-fișier** - Poate schimba 10 fișiere simultan
- **Calitate cod** - Generează cod curat, modern
- **Model choice** - Poți alege Claude, GPT-4, sau altele

### Limitări

- **Necesită setup** - Trebuie să configurezi proiectul
- **Cunoștințe de bază** - Ajută să înțelegi ce e un fișier, un folder, ce limbaj folosești
- **Cost** - ~$20/lună pentru versiunea pro

### Ideal pentru

Developeri sau cei care vor să devină developeri. Oferă cel mai bun echilibru între asistență AI și control.

---

## GitHub Copilot

### Ce e

GitHub Copilot e pionierul asistenților de cod. Creat de GitHub (deținut de Microsoft) împreună cu OpenAI.

### Cum funcționează

Se instalează ca extensie în editorul tău preferat (VS Code, JetBrains, etc.) și oferă sugestii în timp real pe măsură ce scrii.

### Exemplu practic

Scrii un comentariu:
```
// Funcție care validează un email
```

Copilot sugerează automat:
```javascript
function validateEmail(email) {
  const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
  return regex.test(email);
}
```

Apeși Tab, gata.

### Puncte forte

- **Integrat oriunde** - Funcționează în orice editor popular
- **Non-intruziv** - Sugerează, nu forțează
- **Rapid** - Sugestii în milisecunde
- **Adopție masivă** - 90% din Fortune 100 îl folosesc

### Limitări

- **Nu înțelege contextul larg** - Vede fișierul curent, nu tot proiectul
- **Nu conversezi** - E mai mult autocomplete, mai puțin partener
- **Sugestii scurte** - Nu generează aplicații întregi

### Ideal pentru

Developeri care știu să programeze și vor să accelereze, nu să înlocuiască munca.

---

## Windsurf (fost Codeium)

### Ce e

Windsurf e o alternativă la GitHub Copilot, cu un focus pe oferirea unei versiuni gratuite puternice.

### Cum funcționează

Similar cu Copilot - extensie în editor, sugestii în timp real, chat integrat.

### Puncte forte

- **Versiune gratuită generoasă** - Poți folosi fără să plătești
- **Rapid** - Considerat mai rapid decât Copilot de mulți utilizatori
- **Privacy** - Opțiuni pentru a nu trimite codul pe servere externe

### Limitări

- **Mai puțin cunoscut** - Comunitate mai mică
- **Integrări** - Nu la fel de omniprezent ca GitHub Copilot

### Ideal pentru

Cei care vor să încerce asistență AI în cod fără să plătească, sau care au preocupări de confidențialitate.

---

## Comparație

| Criteriu | Cursor | GitHub Copilot | Windsurf |
|----------|--------|----------------|----------|
| **Tip** | Editor complet | Extensie | Extensie |
| **Context** | Tot proiectul | Fișier curent | Fișier curent |
| **Conversație** | Da, avansată | Limitată | Da |
| **Preț** | ~$20/lună | ~$10/lună | Gratuit/~$10 |
| **Multi-fișier** | Da | Limitat | Limitat |
| **Curva învățare** | Medie | Mică | Mică |

## Ce să alegi

### Ești non-tehnic dar vrei control:
→ **Cursor** - E cel mai apropiat de "vorbesc cu AI și primesc cod"

### Ești developer și vrei accelerare:
→ **GitHub Copilot** - Standard în industrie, funcționează oriunde

### Vrei să încerci gratuit:
→ **Windsurf** - Zero cost, rezultate bune

### Vrei totul:
→ **Cursor** cu model Claude - Cea mai puternică combinație pentru vibe coding serios

## Pentru antreprenori

Dacă nu ai background tehnic, recomandarea e:

1. **Începe cu Bolt.new sau Replit** - Zero setup, rezultate rapide
2. **Când ai un proiect care crește**, treci la **Cursor** - Mai mult control, același stil conversațional
3. **Cursor + Claude** e combinația pe care o folosesc profesioniștii care fac vibe coding serios

Nu trebuie să începi cu Cursor. Dar când ești gata pentru nivelul următor, el te așteaptă.

---

**Următorul capitol:** [Alte platforme și unelte](alte-platforme.md) - Claude, Framer AI, v0 și Softr
