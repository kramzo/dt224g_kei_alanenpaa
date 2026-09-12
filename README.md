# Min första webbsida

- Webbplatsen är till för att lära mig, testa och förstå grunderna i webbutveckling
- Teknikerna som använts är HTML och CSS för att ge webbplatsen färg på bakgrunden, typsnittet och för att se till att bilderna håller en bättre storlek

## Publicerade versioner:
- [På GitHub](https://kramzo.github.io/dt224g_kei_alanenpaa/index.html)
- [På Netlify](https://dt224gkeialanenpaa.netlify.app)

## Frågor om git:
1. Vad är skillnaden mellan git add och git commit?
- `git add` förbereder och väljer vilka ändringar som ska sparas, medan `git commit` faktiskt sparar de valda ändringarna som en ögonblicksbild i Git-historiken.
2. Varför använder man branches istället för att jobba direkt i main?
- Man jobbar i branches så att koden i main kan lämnas orörd. På så sätt kan man testa och ändra kod utan att riskera att något förstörs i main. Branches fungerar också bra för att man kan dela upp arbetet mellan olika utvecklare vilket gör arbetet mindre kaotiskt.
3. Vad händer rent praktiskt när man gör en merge?
- Ändringarna eller historiken från två branches förs samman. Om man till exempel har gjort ändringar på en branch som man sedan vill föra in i main kan man göra en merge. Git försöker då kombinera ändringarna från de två branches.
4. Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
- När man pushar sin kod till GitHub hamnar den online i ett repository, men den blir inte automatiskt en publicerad webbplats som man kan besöka. När man publicerar på t.ex. Netlify så "aktiveras" webbplatsen och blir tillgänglig via en webbadress.
5. Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
- Man skapar en `.gitignore`-fil och anger vilka filer eller mappar som Git ska ignorera.