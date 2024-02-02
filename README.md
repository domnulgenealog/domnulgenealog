- 👋 Hi, I’m @domnulgenealog
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
domnulgenealog/domnulgenealog is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
În biblioteca şlcolii se păstrează o ediţie rară a uneia din primele cărţi ce conţine problemele
propuse la Olimpiada de Informatică din anul 1987. În general, fiecare din paginile acestei cărţi ar fi
trebuit să aibă tipărită în subsol următoarea informaţie:
<Numărul paginii curente>/<Numărul total de pajini în carte>.
Evident, numerele din subsol sunt scrise fără zerouri nesemnificative.
Întrucăt pe timpurile de atunci imprimantele mecanice nu erau aşa de perfecte ca cele de
astăzi, pe unele din pagini caracterul "/" nu a fost tipărit. În consecinţă, în unele subsoluri de pagină
apar şire de caractere S, formate, evident, doar din cifre zecimale, fără prefixe din zerouri.
De exemplu, în subsolul uneia din paginile cărţii în cauză apare şirul de cacactere 2348. De
fapt, în anul 1987, pe această pagina se intenţiona să fie tipărită informaţia 23/48.
Virginia, o elevă pasionată de informatică, a descoperit astfel de erori de tipar şi a decis să
elaboreze un algoritm de corectare a acestora. Pentru început, ea doreşte să afle numărul variantelor
posibile V de inserare a caracterului "/" în şirul S în aşa mod, încât perechile de numere astfel
formate să fie verosimile.
De exemplu, în cazul şirului de caractere 2348, perechile verosimile de numere sunt: 2/348
şi 23/48. Prin urmare, 𝑉 = 2.
Sarcină. Scrieţi un program, care, cunoscând şirul de caractere S, determină numărul de
variante V.
Date de intrare. Prima linie a intrării standard conţine şirul de caracter S.


Date de ieşire. Ieşirea standard va conţine pe o singură linie numărul întreg V.
Restricţii. Şirul de caractere S va fi format din cel mult 9 cifre zecimale, fără prefixe din
zerouri. Timpul de execuţie nu va depăşi 0,1 secundă. Programul va folosi cel mult 1 Megaoctet de
memorie operativă. Fişierul sursă va avea denumirea pagini.pas, pagini.c sau
pagini.cpp.
Exemplul 1.
Intrare Ieşire
2348 2
Exemplul 2.
Intrare Ieşire
23507645 3
