# Bazele TypeScript

Exerciții de TypeScript scrise în facultate (aprilie 2022): de la tipurile de bază la clase.

**Ce conține `app.ts`:**
- **Tipurile:** `number`, `string`, `object`, tablouri, tupluri, `enum`, `any`, tipuri reunite (`string | number`)
- **Instrucțiuni de control și funcții:** `if / else`, `switch`, `for`, `do…while`, funcții cu parametri tipizați și opționali
- **Clase și interfețe:** o clasă simplă, o interfață `Shape` implementată de `Rectangle`, cu constructor și modificatori de acces (`public`, `protected`, `readonly`)

`app.ts` se compilează în `app.js`, pe care îl încarcă `index.html`; rezultatele apar în pagină și în consola browserului.

**Cum se rulează:**

```
npm install -g typescript
tsc app.ts
```

Apoi se deschide `index.html` în browser și se deschide consola (F12).
