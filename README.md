- **2024-01-25:** Skapat layout för index-html 
- **2024-01-25:** Lagt in bakåtkompabilitet genom "browserslist"
- **2024-01-25:** Installerat uglifyjr för minimering av jskod
- **2024-01-25:** Installerat html-minifier
- **2024-01-26:** Skapat undersidan för bilder och justerat storlek, samt optimerat bilder med moderna filformat genom picturetag enligt praxis med parcel
- **2024-01-27:**   Ordnat responsivitet för undersidor. Lagt rätt ordlängd samt lagt in installerade paket till scriptet "build" för minimering av js, css och html vid körning av "npm run build".
- **2024-01-27:** Justerat layout för HTML och CSS för undersida workprocess. Kört npm run build
- **2024-01-27:** Build fastnar för Netlify då sista commit inte hamnat på Github. .parcel-cache filen är för stor och ignoreras inte trots lagd i .gitignore. Försök med git rm .parcel-chace/data.mdb och commit för att ta bort stor fil och sedan ny push till main. Filen är fortfarande kvar och gör sync för commits omöjlig. Build fastnar. 
- **2024-01-27:** Tagit bort repositoriet från Github, startat nytt, commitat och pushat aktuella filer till nya repot. Fortfarande samma fel. .Parcel-cache/datamdb är för stor. 