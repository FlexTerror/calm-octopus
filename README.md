1. Git bryr sig om saker som händer inuti ett repo. Repot motsvaras av en mapp på hårddisken (oftast roten i ett projekt).
2. För att hålla koll på ändringar i projektet över tiden skapas commits i repot. Varje commit utom den första har minst en förälder.
3. En branch är en länk till sista commiten i en kedja, branch-namn är bra sätt att hoppa runt mellan commits med.
4. Om man kodar tillsammans är det bra att ha ett remote-repo, de kan man skapa gratis på exempelvis Github.
5. Varje person har en egen kopia av repot, så om någon blir av med sin kod finns den redan uppbackad by design, antingen hos en kollega eller på Github.
6. Gör git pull för att hämta kod, git push för att skicka upp kod till remote repo
7. Om du skickar upp kod samtidigt som din kollega, och era ändringar krockar så får den som är sist lösa konflikten, skapa en merge-commit och skicka upp den.
