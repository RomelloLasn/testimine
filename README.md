# Süsteemi Testplaan

## 1. Sissejuhatus
### Testitava süsteemi või tarkvara kirjeldus

### Testplaani eesmärk

### Sihtgrupp (kes kasutab testplaani)

## 2. Testimise eesmärgid ja ulatus
### Milliseid funktsioone ja süsteemi osi testitakse

### Mis jääb testimise alt välja

### Testimise piirangud ja eeldused

## 3. Testimise metoodika ja lähenemine
### Kasutatavad testitüübid
- Funktsionaalne testimine
- Mitterahaline testimine
- Jõudlustestid jne

### Testimistasemed
- Üksuse testimine
- Integreerimise testimine
- Süsteemitestimine

### Kasutatavad tööriistad ja raamistikud

## 4. Testitavad stsenaariumid ja juhtumid
### Peamised teststsenaariumid ja nende kirjeldused

### Oodatavad tulemused

## 5. Testimise ressursid ja rollid
### Testimismeeskonna liikmed ja nende ülesanded

### Vajalikud tarkvara ja riistvara ressursid

## 6. Ajakava ja testimise etapid
### Testimisperioodid ja ajakava

### Testimise verstapostid

## 7. Vigade raporteerimine ja jälgimine
### Kasutatavad veahaldustööriistad (nt JIRA, TestRail)

### Vigade prioriseerimise ja lahendamise protsess

## 8. Edukriteeriumid ja lõpetamise tingimused
### Millal testimine loetakse edukaks

### Testimise lõpetamise tingimused

## 9. Riskid ja maandamismeetmed
### Võimalikud riskid ja nende mõjud

### Kuidas riske ennetada või leevendada


# UI Testimise Raamistikud

UI testimise raamistikud on tööriistad, mis aitavad automatiseerida kasutajaliidese testimist, tagades, et rakenduse visuaalsed ja funktsionaalsed osad töötavad ootuspäraselt. 

## Populaarsed UI testimise raamistikud

### 1. Selenium
- Avatud lähtekoodiga raamistik veebirakenduste UI testimiseks.
- Toetab mitut programmeerimiskeelt (Java, Python, C#, JavaScript).
- Võimaldab testide käivitamist erinevates brauserites.

### 2. Cypress
- Kaasaegne JavaScript-põhine testimisraamistik, mis keskendub eelkõige frontendi testimisele.
- Kiirem kui Selenium, kuna töötab otse brauseris.
- Hea arendajasõbralikkus ja detailne vealogimine.

### 3. Playwright
- Microsofti arendatud kaasaegne UI testimise raamistik.
- Toetab mitut brauserit (Chromium, Firefox, WebKit).
- Võimaldab testida ka mobiilibrauserites ja mitme brauseriakna vahel.

### 4. TestCafe
- JavaScript-põhine UI testimise raamistik.
- Ei vaja WebDriverit ega brauserilaiendusi.
- Toetab paralleeltestimist ja visuaalset regressioonitesti.

### 5. Appium
- Kasutatakse mobiilirakenduste UI testimiseks (iOS, Android).
- Toetab Selenium WebDriverit ja mitut programmeerimiskeelt.

### 6. Robot Framework
- Python-põhine avatud lähtekoodiga testimisraamistik.
- Kasutab märksõnapõhist testimist, mis teeb selle kasutajasõbralikuks.
- Toetab Seleniumi ja muid UI testimise tööriistu.
