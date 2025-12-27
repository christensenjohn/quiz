# Gæt og Grimasser 🎭

Et interaktivt spil til hele familien, hvor man kan vælge mellem kategorier tilpasset både børn og voksne. Spillet præsenterer unikke mime-opgaver i en enkel og brugervenlig grænseflade.

## 🚀 Funktioner
- **To kategorier:** Skræddersyede spørgsmål til henholdsvis "Børn" og "Voksne".
- **Stor database:** Over 250 unikke mime-opgaver.
- **Responsivt design:** Virker på både mobil, tablet og computer.
- **Ingen dubletter:** Alle spørgsmål er trimmet og unikke.

## 🛠 Teknologier
- **HTML5**
- **CSS3**
- **JavaScript** (med JSON-baseret datastruktur)

## 📖 Sådan spiller man
1. Gå til siden: https://christensenjohn.github.io/quiz/
2. Vælg om du er **Barn** eller **Voksen**.
3. Tryk på knappen for at få et nyt spørgsmål.
4. Mim opgaven for de andre deltagere uden at sige en lyd!

## 📂 Datastruktur
Spørgsmålene gemmes i et JSON-format, hvilket gør det nemt at udvide med flere kategorier eller sprog i fremtiden:

```javascript
{
  "Type": "Børn",
  "Spørgsmål": "Mim en dinosaur, der brøler"
}
