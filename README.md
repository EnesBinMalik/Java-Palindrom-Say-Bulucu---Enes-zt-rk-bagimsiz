# Java Palindrom Say? Analizi

Girilen say?n?n palindrom olup olmad???n? inceleyen ve kontrol algoritmas?n? g?rselle?tiren interaktif Java e?itim uygulamas?.

## ?zellikler

- Palindrom testi
- algoritman?n ad?m ad?m g?rselle?tirilmesi
- Java kod alan?
- al??t?rma ve analiz ara?lar?.

## Teknolojiler

- React
- TypeScript
- Vite

Bu depo, Java algoritmalar?n? taray?c? tabanl? bir aray?zde a??klamak ve sim?le etmek i?in haz?rlanm??t?r. Java ?rnek kodlar? uygulama i?inde incelenebilir; web aray?z?n? ?al??t?rmak i?in Node.js gerekir.

## Kurulum ve ?al??t?rma

**Gereksinimler:** G?ncel bir Node.js LTS s?r?m? ve npm.

```bash
npm install
npm run dev
```

Geli?tirme sunucusunu ba?latt?ktan sonra terminalde g?sterilen yerel adresi taray?c?da a??n.

## Kontroller ve ?retim derlemesi

```bash
npm run lint
npm run build
```

`npm run lint` TypeScript denetimini, `npm run build` ise da??t?m dosyalar?n?n olu?turulmas?n? ?al??t?r?r. Derlemeyi yerel olarak g?r?nt?lemek i?in ?nce `npm run build`, ard?ndan `npm run preview` komutlar?n? kullan?n.

## Proje yap?s?

- `src/components/` ? aray?z, sim?lat?r ve g?rselle?tirme bile?enleri
- `src/components/PalindromeTester.tsx, src/components/AlgorithmVisualizer.tsx` ? algoritman?n temel uygulama bile?enleri
- `src/main.tsx` ? uygulama ba?lang?? noktas?
- `package.json` ? ba??ml?l?klar ve npm komutlar?

## Katk?

De?i?iklik ?nermeden ?nce ilgili algoritma ad?mlar?n?n do?ru ?al??t???n? do?rulay?n. Kod bi?imini ve mevcut TypeScript tiplerini koruyun.
