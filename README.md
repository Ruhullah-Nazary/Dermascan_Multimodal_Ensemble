Projektets arbetsprocess och gruppens ansvar

Vi började med att identifiera ett intressant projekt inom djupa neurala nätverk, med hänsyn till tillgängliga resurser som data och GPU. Varje gruppmedlem undersökte olika möjliga tillämpningar och vi valde slutligen “Dermascan Multimodal Ensemble” för hudcancerklassificering, eftersom det kombinerade bilddata och klinisk metadata med en tydlig medicinsk problemformulering.

Projektets steg:

Datasamling och förberedelse: Vi började med HAM10000-dataset, men fick låg prestanda på grund av få bilder och obalans mellan klasser. Vi kombinerade därför med ISIC 2019-dataset för att skapa bättre balans med tanken på att undvika dubbletter.

Modellutveckling: Vi utvecklade en ensemblemodell med tre arkitekturer och använde transfer learning för högre prestanda.

Multimodal integration: För att göra modellen kliniskt relevant inkluderade vi patientmetadata, eftersom hudläkare tar hänsyn till patientprofilen utöver bilddata.

Tolkbarhet: Vi implementerade Explainable AI (XAI) för att modellen inte bara skulle ge ett ja/nej svar utan även kunna förklara sina beslut.

Utvärdering och optimering: Alla större beslut som hantering av överanpassning och obalanserad recall för minoritetsklasser, togs gemensamt baserat på valideringsresultat.

Individuella bidrag:

Granit: Dataförberedelse och behandling, inklusive analys av datasetets klassfördelning och implementering av balanseringsstrategi.

Jag: Modellarkitektur och träning, med fokus på utveckling av trippelensemblen, integration av metadata och optimering av träningsprocessen.

Pär: Resultat och utvärdering, inklusive test och validering av modellprestanda.

Mustafa: Visualisering och tolkbarhet via XAI-analyser, för att göra modellens beslut förståeliga.

Samarbetsprocess och dokumentation:
Vi arbetade kontinuerligt i gruppen med regelbundna diskussioner och gemensamma beslut för alla större förändringar. Vi tränade modellen på Kaggle först och lade up på GitHub-repot när projektet var klart och därför saknar commit-historik. Istället har vi dokumenterat hela arbetsprocessen och varje medlems insats i denna fil.
