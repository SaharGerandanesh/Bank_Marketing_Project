# Bank_Marketing_Project
This is a Bank Marketing Machine Learning Classification Project.

Syfte: Förutsäga om en kund prenumererar på en bankprodukt (termininsättning).
1-EDA:

Datasetet utforskas genom att visa en översikt och distributioner för kategoriska variabler som job, education, och housing loan.

2-Datapreparation:

Kategoriska variabler omvandlas till dummy-variabler och datan delas upp i träning och testuppsättningar.
StandardScaler används för att normalisera numeriska data.
SMOTE används för att hantera klassobalans genom att syntetiskt öka minoritetsklassen.

3-Supervised Learning:

Modeller för Logistisk regression och KNN byggs och utvärderas på den ursprungliga datan.
Resultaten rapporteras i form av noggrannhet och klassificeringsrapporter.

4-PCA (Principal Component Analysis):

PCA används för att minska dimensionerna till 2 komponenter, vilket gör datan enklare att visualisera.
Modellerna för Logistisk regression och KNN tränas och utvärderas igen med den PCA-reducerade datan.

5-Visualisering:

PCA-resultaten visualiseras i en 2D-projektion för att ge en bättre bild av datafördelningen.

Presentation:

För en databerättelse, börja med att förklara datasetets syfte, t.ex. att förutsäga om en kund prenumererar på en banktjänst. Fortsätt med att visa EDA, diskutera de viktigaste variablerna och deras samband med målet (prenumeration). Presentera därefter maskininlärningsresultaten och jämförelser mellan de olika modellerna (med och utan PCA).
