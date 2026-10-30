# Graubünden: law history in git

The law of the canton of Graubünden (Kanton Graubünden, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-gr/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's first official language in the collection, exactly as the canton publishes it.

## What this repository holds

311 acts with 899 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 209 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `110-100/` | Verfassung des Kantons Graubünden (BR 110.100) | 10 | oldest version available, then each consolidated version: 1 March 2014 to 1 January 2025 |
| `110-200/` | Gesetz über die Einteilung des Kantons Graubünden in Regionen (BR 110.200) | 1 | as enacted, 1 January 2016 |
| `130-100-kbug/` | Bürgerrechtsgesetz des Kantons Graubünden (BR 130.100) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `150-100-gpr/` | Gesetz über die politischen Rechte im Kanton Graubünden (BR 150.100) | 8 | oldest version available, then each consolidated version: 1 August 2012 to 1 January 2026 |
| `150-400-grossratswahlgesetz-grwg/` | Gesetz über die Wahl des Grossen Rates (BR 150.400) | 2 | as enacted, then each consolidated version: 1 October 2021 to 1 January 2026 |
| `170-050-shg/` | Gesetz über die Staatshaftung (BR 170.050) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `170-100-grossratsgesetz-grg/` | Gesetz über den Grossen Rat (BR 170.100) | 10 | oldest version available, then each consolidated version: 28 August 2013 to 1 January 2026 |
| `170-300-rvog/` | Regierungs- und Verwaltungsorganisationsgesetz (BR 170.300) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2017 |
| `170-380-ggvr/` | Gesetz über die Gehälter und die berufliche Vorsorge der Mitglieder der Regierung (BR 170.380) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2027 |
| `170-400-personalgesetz-pg/` | Gesetz über das Arbeitsverhältnis der Mitarbeitenden des Kantons Graubünden (BR 170.400) | 6 | oldest version available, then each consolidated version: 1 March 2012 to 1 January 2025 |
| `170-450-pkg/` | Gesetz über die Pensionskasse Graubünden (BR 170.450) | 5 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `171-000-offentlichkeitsgesetz/` | Gesetz über das Öffentlichkeitsprinzip (BR 171.000) | 2 | as enacted, then each consolidated version: 1 November 2016 to 1 January 2025 |
| `171-100-kdsg/` | Kantonales Datenschutzgesetz (BR 171.100) | 6 | oldest version available, then each consolidated version: 1 October 2008 to 1 January 2026 |
| `171-200-einwohnerregistergesetz-erg/` | Gesetz über die Einwohnerregister und weitere Personen- und Objektregister (BR 171.200) | 4 | as enacted, then each consolidated version: 1 December 2010 to 1 January 2026 |
| `173-000-gog/` | Gerichtsorganisationsgesetz (BR 173.000) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 May 2026 |
| `175-050-gg/` | Gemeindegesetz des Kantons Graubünden (BR 175.050) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2018 |
| `177-100-dvg/` | Gesetz über die digitale Verwaltung (BR 177.100) | 1 | as enacted, 1 April 2024 |
| `180-100-publikationsgesetz-pug/` | Gesetz über die Gesetzessammlungen und das Amtsblatt (BR 180.100) | 1 | as enacted, 1 January 2012 |
| `210-100-egzzgb/` | Einführungsgesetz zum Schweizerischen Zivilgesetzbuch (BR 210.100) | 9 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `210-200-egzor/` | Einführungsgesetz zum Schweizerischen Obligationenrecht (BR 210.200) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `210-300-notg/` | Notariatsgesetz (BR 210.300) | 5 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2025 |
| `217-300-kgeoig/` | Kantonales Geoinformationsgesetz (BR 217.300) | 1 | as enacted, 1 January 2012 |
| `217-600/` | Einführungsgesetz zum Bundesgesetz vom 16. Dezember 1983 über den Erwerb von Grundstücken durch Personen im Ausland (BewG) (BR 217.600) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `219-050/` | Pflegekindergesetz (BR 219.050) | 1 | one version (the oldest available), 1 January 2013 |
| `220-000-egzschkg/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (BR 220.000) | 3 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2025 |
| `310-100-anwg/` | Anwaltsgesetz (BR 310.100) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `350-500-justizvollzugsgesetz-jvg/` | Gesetz über den Justizvollzug im Kanton Graubünden (BR 350.500) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `370-100-vrg/` | Gesetz über die Verwaltungsrechtspflege (BR 370.100) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `370-300-egzssv/` | Einführungsgesetz zum Schlichtungs- und Schiedsgerichtsverfahren nach eidgenössischem Sozialversicherungsrecht (BR 370.300) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `421-000-volksschulgesetz-vsg/` | Gesetz für die Volksschulen des Kantons Graubünden (BR 421.000) | 5 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2025 |
| `425-000-mittelschulgesetz-msg/` | Gesetz über die Mittelschulen im Kanton Graubünden (BR 425.000) | 4 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2019 |
| `427-200-ghf/` | Gesetz über Hochschulen und Forschung (BR 427.200) | 3 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2025 |
| `430-000-bwbg/` | Gesetz über die Berufsbildung und weiterführende Bildungsangebote (BR 430.000) | 2 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2016 |
| `432-000-agsg/` | Gesetz über Ausbildungsstätten im Gesundheits- und Sozialwesen (BR 432.000) | 2 | oldest version available, then each consolidated version: 1 August 2014 to 1 July 2024 |
| `433-100-fortbildungsgesetz/` | Gesetz über die Unterstützung der Fortbildung Jugendlicher und Erwachsener im Kanton Graubünden (BR 433.100) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 31 December 2025 |
| `440-100-behindertenintegrationsgesetz-big/` | Gesetz zur sozialen und beruflichen Integration von Menschen mit Behinderung (BR 440.100) | 1 | as enacted, 1 January 2012 |
| `450-200-stipendiengesetz-stipg/` | Gesetz über Ausbildungsbeiträge (BR 450.200) | 3 | as enacted, then each consolidated version: 1 August 2007 to 1 January 2017 |
| `470-000-sportforderungsgesetz/` | Gesetz über die Förderung von Sport und Bewegung (BR 470.000) | 1 | as enacted, 1 August 2015 |
| `490-000-gaa/` | Gesetz über die Aktenführung und Archivierung (BR 490.000) | 3 | as enacted, then each consolidated version: 1 January 2016 to 1 April 2024 |
| `492-100-spg/` | Sprachengesetz des Kantons Graubünden (BR 492.100) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `494-300-kulturforderungsgesetz-kfg/` | Gesetz über die Förderung der Kultur (BR 494.300) | 2 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2018 |
| `496-000-kantonales-natur-und-heimatschutzgesetz-knhg/` | Gesetz über den Natur- und Heimatschutz im Kanton Graubünden (BR 496.000) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `500-000-gesundheitsgesetz/` | Gesetz zum Schutz der Gesundheit im Kanton Graubünden (BR 500.000) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `500-500-einfuhrungsgesetz-zum-heilmittelgesetz-egzhmg/` | Einführungsgesetz zum Bundesgesetz über Arzneimittel und Medizinprodukte (BR 500.500) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `500-800-suchthilfegesetz/` | Gesetz über die Suchthilfe im Kanton Graubünden (BR 500.800) | 2 | oldest version available, then each consolidated version: 1 August 2013 to 1 January 2016 |
| `500-900/` | Gesetz über die Psychiatrischen Dienste Graubünden (BR 500.900) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `506-000-krankenpflegegesetz-kpg/` | Gesetz über die Förderung der Krankenpflege und der Betreuung von betagten und pflegebedürftigen Personen (BR 506.000) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 July 2024 |
| `520-100-ruhetagsgesetz/` | Gesetz über die öffentlichen Ruhetage (BR 520.100) | 2 | as enacted, then each consolidated version: 1 January 1986 to 1 January 2016 |
| `530-100/` | Einführungsgesetz zum Arbeitsgesetz und zur Unfallverhütung nach Unfallversicherungsgesetz (BR 530.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `538-100/` | Gesetz über die Beilegung von kollektiven Arbeitsstreitigkeiten (BR 538.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `542-100-kpvg/` | Gesetz über die Krankenversicherung und die Prämienverbilligung (BR 542.100) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `544-000-egzahvg-ivg/` | Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und die Invalidenversicherung (BR 544.000) | 2 | oldest version available, then each consolidated version: 1 December 2010 to 1 January 2015 |
| `544-300-kantonales-gesetz-uber-erganzungsleistungen/` | Gesetz über kantonale Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (BR 544.300) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `545-100-egzavg-avig/` | Einführungsgesetz zur Arbeitsvermittlung und Arbeitslosenversicherung (BR 545.100) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 July 2021 |
| `546-100-sozialhilfegesetz/` | Gesetz über die öffentliche Sozialhilfe im Kanton Graubünden (BR 546.100) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2016 |
| `546-250-kantonales-unterstutzungsgesetz-ug/` | Gesetz über die Unterstützung Bedürftiger (BR 546.250) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `548-100-kfzg/` | Gesetz über die Familienzulagen (BR 548.100) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `548-200/` | Gesetz über Mutterschaftsbeiträge (BR 548.200) | 2 | oldest version available, then each consolidated version: 1 August 2009 to 1 January 2025 |
| `548-300-kibeg/` | Gesetz über die Förderung der familienergänzenden Kinderbetreuung im Kanton Graubünden (BR 548.300) | 2 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2025 |
| `613-000-polg/` | Polizeigesetz des Kantons Graubünden (BR 613.000) | 9 | oldest version available, then each consolidated version: 1 January 2013 to 1 May 2026 |
| `618-100-egzaag/` | Einführungsgesetz zur Ausländer- und Asylgesetzgebung des Bundes (BR 618.100) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `620-100-egzwpeg/` | Einführungsgesetz zum Bundesgesetz über die Wehrpflichtersatzabgabe (BR 620.100) | 2 | as enacted, then each consolidated version: 1 May 2017 to 1 January 2025 |
| `630-000-bevolkerungsschutzgesetz-bsg/` | Gesetz über den Bevölkerungsschutz des Kantons Graubünden (BR 630.000) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `630-200/` | Kantonales Einführungsgesetz zur wirtschaftlichen Landesversorgung (BR 630.200) | 1 | as enacted, 1 February 2006 |
| `640-100-zivilschutzgesetz-zsg/` | Gesetz über den Zivilschutz des Kantons Graubünden (BR 640.100) | 3 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `710-100-finanzhaushaltsgesetz-fhg/` | Gesetz über den Finanzhaushalt des Kantons Graubünden (BR 710.100) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 July 2026 |
| `710-300-gfa/` | Gesetz über die Finanzaufsicht (BR 710.300) | 5 | as enacted, then each consolidated version: 1 March 2012 to 1 January 2026 |
| `720-000/` | Steuergesetz für den Kanton Graubünden (BR 720.000) | 12 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `720-200-gkstg/` | Gesetz über die Gemeinde- und Kirchensteuern (BR 720.200) | 8 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `730-200-finanzausgleichsgesetz-fag/` | Gesetz über den Finanzausgleich im Kanton Graubünden (BR 730.200) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2027 |
| `740-000-kjg/` | Kantonales Jagdgesetz (BR 740.000) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `760-100-kfg/` | Kantonales Fischereigesetz (BR 760.100) | 1 | one version (the oldest available), 1 January 2014 |
| `780-100/` | Gesetz über das Salzregal des Kantons Graubünden (BR 780.100) | 1 | one version (the oldest available), 1 January 2011 |
| `801-100-krg/` | Raumplanungsgesetz für den Kanton Graubünden (BR 801.100) | 5 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `803-100/` | Enteignungsgesetz des Kantons Graubünden (BR 803.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `803-200/` | Perimetergesetz des Kantons Graubünden (BR 803.200) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `807-100-strg/` | Strassengesetz des Kantons Graubünden (BR 807.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 31 December 2025 |
| `807-700-wasserbaugesetz-kwbg/` | Gesetz über den Wasserbau im Kanton Graubünden (BR 807.700) | 1 | one version (the oldest available), 1 January 2011 |
| `810-100-bwrg/` | Wasserrechtsgesetz des Kantons Graubünden (BR 810.100) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `812-100-stromvg-gr/` | Stromversorgungsgesetz des Kantons Graubünden (BR 812.100) | 1 | one version (the oldest available), 1 January 2011 |
| `815-100-kantonales-gewasserschutzgesetz-kgschg/` | Einführungsgesetz zum Bundesgesetz über den Schutz der Gewässer (BR 815.100) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2025 |
| `820-100-kantonales-umweltschutzgesetz-kusg/` | Einführungsgesetz zum Bundesgesetz über den Umweltschutz (BR 820.100) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `820-200-beg/` | Energiegesetz des Kantons Graubünden (BR 820.200) | 4 | as enacted, then each consolidated version: 1 January 2011 to 31 December 2025 |
| `820-400-bundner-klima-und-innovationsgesetz-bkig/` | Gesetz über die Förderung und Finanzierung von Massnahmen zu Klimaschutz und Innovation in Graubünden (BR 820.400) | 1 | as enacted, 31 December 2025 |
| `835-100-gve/` | Gesetz über die Vergütung nicht versicherbarer Elementarschäden (BR 835.100) | 1 | one version (the oldest available), 1 January 2011 |
| `840-100-brandschutzgesetz/` | Gesetz über den vorbeugenden Brandschutz und die Feuerwehr im Kanton Graubünden (BR 840.100) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 February 2017 |
| `850-100-ibg/` | Gesetz über die amtlichen Immobilienbewertungen (BR 850.100) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `870-100-egzsvg/` | Einführungsgesetz zum Bundesgesetz über den Strassenverkehr (BR 870.100) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2019 |
| `872-100-gov/` | Gesetz über den öffentlichen Verkehr im Kanton Graubünden (BR 872.100) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2023 |
| `877-100-egzumbsg/` | Einführungsgesetz zum Bundesgesetz über die Binnenschifffahrt (BR 877.100) | 1 | one version (the oldest available), 1 January 2011 |
| `910-000-landwirtschaftsgesetz/` | Gesetz über die Erhaltung und Förderung der Landwirtschaft (BR 910.000) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 31 December 2025 |
| `914-000-vetg/` | Veterinärgesetz (BR 914.000) | 2 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2016 |
| `915-100/` | Meliorationsgesetz des Kantons Graubünden (BR 915.100) | 4 | oldest version available, then each consolidated version: 1 January 2008 to 31 December 2025 |
| `920-100-kwag/` | Kantonales Waldgesetz (BR 920.100) | 3 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `932-100-gwe-wirtschaftsentwicklungsgesetz/` | Gesetz über die Förderung der wirtschaftlichen Entwicklung in Graubünden (BR 932.100) | 4 | oldest version available, then each consolidated version: 1 September 2007 to 1 July 2026 |
| `932-200-kantonales-covid-19-hartefallgesetz-2022-khfg-22/` | Kantonales Gesetz über Härtefallmassnahmen für Unternehmen im Zusammenhang mit der COVID-19-Epidemie im Jahr 2022 (BR 932.200) | 1 | as enacted, 1 January 2022 |
| `935-500-kgs/` | Geldspielgesetz des Kantons Graubünden (BR 935.500) | 1 | as enacted, 1 January 2021 |
| `938-200/` | Gesetz über die Graubündner Kantonalbank (BR 938.200) | 2 | oldest version available, then each consolidated version: 1 April 2009 to 1 January 2016 |
| `945-100-gwg/` | Gastwirtschaftsgesetz für den Kanton Graubünden (BR 945.100) | 1 | one version (the oldest available), 1 January 2011 |
| `947-100/` | Gesetz über das Berg- und Schneesportwesen (BR 947.100) | 1 | one version (the oldest available), 1 January 2011 |
| `950-250-gfw/` | Gesetz über die Förderung von Wohnraum (BR 950.250) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2026 |
| `960-100-gdt/` | Gesetz zur Förderung der digitalen Transformation in Graubünden (BR 960.100) | 1 | as enacted, 1 January 2021 |
| `110-300-kantonale-wappenschutzverordnung-kwschv/` | Verordnung zum Vollzug des Bundesgesetzes über den Schutz des Schweizerwappens und anderer öffentlicher Zeichen (BR 110.300) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2025 |
| `130-110-kbuv/` | Verordnung zum Bürgerrechtsgesetz des Kantons Graubünden (BR 130.110) | 2 | oldest version available, then each consolidated version: 1 June 2014 to 1 January 2018 |
| `150-200-vpr/` | Verordnung über die politischen Rechte im Kanton Graubünden (BR 150.200) | 5 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `150-300/` | Verordnung über die Nationalratswahlen (BR 150.300) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2015 |
| `150-410-grossratswahlverordnung-grwv/` | Verordnung über die Wahl des Grossen Rates (BR 150.410) | 1 | as enacted, 1 October 2021 |
| `170-340/` | Verordnung betreffend die Übertragung von Befugnissen der Regierung auf die Departemente und Dienststellen (BR 170.340) | 4 | oldest version available, then each consolidated version: 1 November 2012 to 1 January 2025 |
| `170-360/` | Gebührenverordnung für die Standeskanzlei (BR 170.360) | 1 | one version (the oldest available), 1 July 1998 |
| `170-375/` | Verordnung betreffend Auslagenersatz und Geschenkannahme (BR 170.375) | 1 | one version (the oldest available), 1 April 2013 |
| `170-410-pv/` | Personalverordnung (BR 170.410) | 8 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `170-415-azv/` | Arbeitszeitverordnung (BR 170.415) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2023 |
| `170-420/` | Verordnung für die nebenamtlichen Mitarbeitenden des Kantons Graubünden (BR 170.420) | 1 | one version (the oldest available), 1 January 2014 |
| `170-430-vp-reglement/` | Reglement über die vorzeitige Pensionierung (BR 170.430) | 2 | as enacted, then each consolidated version: 1 April 2013 to 1 January 2022 |
| `170-440-ktv-verordnung-ktv-vo/` | Verordnung über die Krankentaggeld-Versicherung (BR 170.440) | 1 | as enacted, 1 January 2026 |
| `170-480/` | Reglement über den Fonds für nichtversicherte Risiken der kantonalen Verwaltungs- und Schulbetriebe sowie der Psychiatrischen Dienste Graubünden (BR 170.480) | 1 | one version (the oldest available), 1 January 2009 |
| `170-500-infv/` | Verordnung über die Informatik in der kantonalen Verwaltung (BR 170.500) | 3 | as enacted, then each consolidated version: 1 June 2011 to 1 December 2024 |
| `170-700/` | Verordnung über die Deckung des Bürobedarfs in der kantonalen Verwaltung (BR 170.700) | 1 | as enacted, 1 October 2012 |
| `170-800-pmv/` | Verordnung über das Parkplatzmanagement der kantonalen Verwaltung (BR 170.800) | 2 | as enacted, then each consolidated version: 1 July 2003 to 1 January 2023 |
| `171-110-kantonale-datenschutzverordnung-vkdsg/` | Verordnung zum Kantonalen Datenschutzgesetz (BR 171.110) | 1 | as enacted, 1 January 2026 |
| `171-120-bilduberwachungsverordnung-vbu/` | Verordnung über die Bildüberwachung des öffentlichen und öffentlich zugänglichen Raums (BR 171.120) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `171-210-einwohnerregisterverordnung-erv/` | Verordnung zum Gesetz über die Einwohnerregister und weitere Personen- und Objektregister (BR 171.210) | 2 | as enacted, then each consolidated version: 1 December 2010 to 1 March 2015 |
| `173-010-ogv/` | Verordnung über die Organisation und Geschäftsführung des Obergerichts (BR 173.010) | 4 | as enacted, then each consolidated version: 15 February 2024 to 1 January 2025 |
| `173-180-rostr/` | Reglement über die Organisation der Stabsstelle der Regionalgerichte (BR 173.180) | 1 | as enacted, 1 January 2025 |
| `173-190-schlichtungsbehordenverordnung-sbv/` | Verordnung über die Organisation und Geschäftsführung der Schlichtungsbehörden (BR 173.190) | 1 | as enacted, 1 January 2025 |
| `173-200-jav/` | Verordnung über die Justizaufsicht (BR 173.200) | 1 | as enacted, 1 January 2025 |
| `173-210-frjv/` | Verordnung über das Finanz- und Rechnungswesen im Justizbereich (BR 173.210) | 1 | as enacted, 1 January 2025 |
| `173-400-eswv/` | Verordnung über die elektronische Stimmabgabe und Wahl in den Leitungsorganen der Gerichte (BR 173.400) | 1 | as enacted, 1 January 2025 |
| `173-510-besoldungsverordnung-bsv/` | Verordnung über die Besoldung der nebenamtlichen Mitglieder richterlicher Behörden (BR 173.510) | 1 | as enacted, 1 January 2025 |
| `173-520-vio/` | Verordnung über die Information der Öffentlichkeit durch die richterlichen Behörden (BR 173.520) | 1 | as enacted, 1 January 2025 |
| `175-100-fiav/` | Verordnung zur Finanzaufsicht über die Gemeinden (BR 175.100) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 July 2018 |
| `177-110-vdvg/` | Verordnung zum Gesetz über die digitale Verwaltung (BR 177.110) | 3 | as enacted, then each consolidated version: 1 June 2023 to 1 January 2026 |
| `180-200/` | Verordnung betreffend die Verwendung von Rumantsch Grischun für die romanischen Abstimmungsunterlagen und das romanische Bündner Rechtsbuch (BR 180.200) | 1 | as enacted, 1 July 2001 |
| `180-500/` | Verordnung über das Amtsblatt des Kantons Graubünden (BR 180.500) | 3 | as enacted, then each consolidated version: 1 April 1998 to 1 January 2017 |
| `210-350-notv/` | Notariatsverordnung (BR 210.350) | 5 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2027 |
| `210-370-notgebv/` | Verordnung über die Notariatsgebühren (BR 210.370) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `213-500-kzstv/` | Zivilstandsverordnung des Kantons Graubünden (BR 213.500) | 7 | oldest version available, then each consolidated version: 1 January 2013 to 1 September 2022 |
| `215-010-kesv/` | Verordnung zum Kindes- und Erwachsenenschutz (BR 215.010) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `215-020-kadov/` | Kantonale Adoptionsverordnung (BR 215.020) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `215-050/` | Verordnung über die Bevorschussung von Unterhaltsbeiträgen für unterhaltsberechtigte Kinder (BR 215.050) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `217-100-kgbv/` | Verordnung über das Grundbuch im Kanton Graubünden (BR 217.100) | 3 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `217-200/` | Verordnung über die Gebühren der Grundbuchämter (BR 217.200) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `217-310-kgeoiv/` | Kantonale Geoinformationsverordnung (BR 217.310) | 2 | as enacted, then each consolidated version: 15 February 2012 to 1 June 2016 |
| `217-320-kvav/` | Verordnung über die amtliche Vermessung in Graubünden (BR 217.320) | 1 | as enacted, 15 February 2012 |
| `217-330-gkgeoig/` | Gebührenverordnung zum kantonalen Geoinformationsgesetz (BR 217.330) | 1 | as enacted, 1 January 2012 |
| `217-340-kvlk/` | Verordnung über den Leitungskataster (BR 217.340) | 1 | as enacted, 1 June 2016 |
| `219-100/` | Verordnung betreffend die Aufsicht über die Stiftungen (BR 219.100) | 2 | oldest version available, then each consolidated version: 1 June 2012 to 1 January 2019 |
| `219-210/` | Verordnung über die Zusammenarbeit und Koordination in der Jugendhilfe (BR 219.210) | 1 | as enacted, 1 January 2007 |
| `219-300/` | Verordnung über die Gebühren für Verrichtungen beim Erbgang (BR 219.300) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `220-010-rvzegzschkg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (BR 220.010) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2025 |
| `310-200-anwv/` | Anwaltsverordnung (BR 310.200) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `310-210-anwaltsprufungsverordnung-anwpv/` | Verordnung über die Anwaltsprüfung (BR 310.210) | 1 | as enacted, 1 April 2023 |
| `310-250-honorarverordnung-hv/` | Verordnung über die Bemessung des Honorars der Rechtsanwältinnen und Rechtsanwälte (BR 310.250) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `320-110-rvzegzzpo/` | Verordnung zum Einführungsgesetz zur Schweizerischen Zivilprozessordnung (BR 320.110) | 1 | as enacted, 1 January 2011 |
| `320-210-vgz/` | Verordnung über die Gerichtsgebühren in Zivilverfahren (BR 320.210) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `350-110-rvzegzstpo/` | Verordnung zum Einführungsgesetz zur Schweizerischen Strafprozessordnung (BR 350.110) | 9 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `350-150/` | Verordnung zur DNA-Profil-Gesetzgebung des Bundes (BR 350.150) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2024 |
| `350-210-vgs/` | Verordnung über die Gerichtsgebühren in Strafverfahren (BR 350.210) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `350-325-kantonale-sprengstoffverordnung-ksprstv/` | Vollziehungsverordnung zum eidgenössischen Sprengstoffrecht (BR 350.325) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `350-510-justizvollzugsverordnung-jvv/` | Verordnung über den Justizvollzug im Kanton Graubünden (BR 350.510) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `350-520-vev/` | Verordnung über die Vollzugseinrichtungen im Kanton Graubünden (BR 350.520) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2025 |
| `370-110-vgo/` | Verordnung über die Gebühren und Barauslagen in öffentlich-rechtlichen Verfahren vor dem Obergericht (BR 370.110) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `370-120-vkv/` | Verordnung über die Kosten in Verwaltungsverfahren (BR 370.120) | 1 | one version (the oldest available), 1 January 2010 |
| `370-130-verv/` | Verordnung über den elektronischen Rechtsverkehr (BR 370.130) | 3 | as enacted, then each consolidated version: 1 April 2024 to 1 May 2026 |
| `370-140/` | Verordnung über die Gebühren und Barauslagen in Verfahren vor dem Justizgericht (BR 370.140) | 1 | as enacted, 1 January 2025 |
| `370-310-vesv/` | Verordnung über die Entlöhnung von Schlichtungsbehörde und Schiedsgericht nach EGzSSV (BR 370.310) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `421-010-volksschulverordnung-vsv/` | Verordnung zum Volksschulgesetz (BR 421.010) | 8 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2025 |
| `421-030-tagesstrukturverordnung/` | Verordnung über weiter gehende Tagesstrukturen (BR 421.030) | 3 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2024 |
| `421-040-avot/` | Verordnung über das Aufnahmeverfahren betreffend Talentklassen (BR 421.040) | 3 | as enacted, then each consolidated version: 1 January 2015 to 1 September 2016 |
| `421-800/` | Verordnung über den schulärztlichen Dienst (BR 421.800) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2016 |
| `421-850/` | Verordnung über die Schulzahnpflege (BR 421.850) | 2 | oldest version available, then each consolidated version: 1 August 2012 to 1 August 2026 |
| `425-040/` | Verordnung über die Aufsichtskommission im Mittelschulwesen (BR 425.040) | 2 | as enacted, then each consolidated version: 1 March 2005 to 1 July 2026 |
| `425-050-gymv/` | Verordnung über das Gymnasium (BR 425.050) | 4 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2023 |
| `425-060-aufnahmev/` | Verordnung über das Aufnahmeverfahren an den Mittelschulen (BR 425.060) | 9 | oldest version available, then each consolidated version: 1 October 2014 to 1 August 2025 |
| `425-080-msbgv/` | Verordnung über Beitragszahlungen und Gebühren im Mittelschulwesen des Kantons Graubünden (BR 425.080) | 5 | as enacted, then each consolidated version: 1 August 2015 to 1 July 2026 |
| `425-100-mittelschulorganisationsverordnung-msov/` | Verordnung über die Organisation der Mittelschulen mit kantonaler Trägerschaft (BR 425.100) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2024 |
| `425-130-hmsv/` | Verordnung über die Handelsmittelschule (BR 425.130) | 5 | as enacted, then each consolidated version: 8 November 2011 to 1 July 2026 |
| `425-140-fmsv/` | Verordnung über die Fachmittelschule (BR 425.140) | 5 | oldest version available, then each consolidated version: 1 October 2012 to 1 September 2021 |
| `425-150-imsv/` | Verordnung über die Informatikmittelschule (BR 425.150) | 2 | as enacted, then each consolidated version: 1 August 2024 to 1 July 2026 |
| `425-170-vwm/` | Verordnung über die Wohnheime im Mittelschulwesen (BR 425.170) | 1 | as enacted, 1 August 2019 |
| `427-210-vh/` | Verordnung über Hochschulen mit kantonaler Trägerschaft (BR 427.210) | 3 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2025 |
| `427-220-vhf/` | Verordnung über Hochschulen ohne kantonale Trägerschaft und über Forschung (BR 427.220) | 2 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2025 |
| `430-100-bwbgv/` | Verordnung über die Berufsbildung und weiterführende Bildungsangebote (BR 430.100) | 2 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2025 |
| `430-150-bauverordnung-bwbg/` | Verordnung über die Subventionierung von Bauten in der Berufsbildung, in weiterführenden Bildungsangeboten und an Hochschulen (BR 430.150) | 2 | as enacted, then each consolidated version: 1 August 2012 to 1 January 2016 |
| `430-180-gebvafb/` | Gebührenverordnung für das Amt für Berufsbildung (BR 430.180) | 3 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2025 |
| `430-200/` | Verordnung über die Brückenangebote (BR 430.200) | 1 | as enacted, 1 January 2009 |
| `430-300-defizitverordnung/` | Verordnung über die Defizitfinanzierung der Institutionen der Berufsbildung und weiterführender Bildungsangebote (BR 430.300) | 3 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `430-350-beitragsverordnung/` | Verordnung über Beiträge an Leistungserbringende ohne Defizitfinanzierung in der Berufsbildung und weiterführenden Bildungsangeboten (BR 430.350) | 1 | as enacted, 1 January 2008 |
| `430-400-kbmv/` | Kantonale Berufsmaturitätsverordnung (BR 430.400) | 3 | as enacted, then each consolidated version: 1 March 2015 to 1 July 2026 |
| `432-010-vozagsg/` | Verordnung zum Gesetz über Ausbildungsstätten im Gesundheits- und Sozialwesen (BR 432.010) | 4 | oldest version available, then each consolidated version: 1 January 2014 to 1 July 2026 |
| `433-150/` | Vollziehungsverordnung zum Fortbildungsgesetz (BR 433.150) | 1 | as enacted, 1 December 1998 |
| `440-110-behindertenintegrationsverordnung-biv/` | Verordnung zur sozialen und beruflichen Integration von Menschen mit Behinderung (BR 440.110) | 2 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2021 |
| `450-250-stipendienverordnung-stipvo/` | Verordnung zum Gesetz über Ausbildungsbeiträge (BR 450.250) | 5 | oldest version available, then each consolidated version: 1 August 2013 to 1 July 2023 |
| `470-010-sportforderungsverordnung/` | Verordnung über die Förderung von Sport und Bewegung (BR 470.010) | 3 | as enacted, then each consolidated version: 1 August 2015 to 1 September 2024 |
| `490-010-vaa/` | Verordnung zum Gesetz über die Aktenführung und Archivierung (BR 490.010) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 April 2024 |
| `490-200/` | Verordnung über die Kantonsbibliothek Graubünden (BR 490.200) | 1 | one version (the oldest available), 1 January 2007 |
| `492-110-spv/` | Sprachenverordnung des Kantons Graubünden (BR 492.110) | 6 | oldest version available, then each consolidated version: 1 August 2014 to 1 January 2027 |
| `494-310-kulturforderungsverordnung-kfv/` | Verordnung zum Gesetz über die Förderung der Kultur (BR 494.310) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2020 |
| `496-150/` | Verordnung über den Schutz der Oberengadiner Seelandschaft (BR 496.150) | 1 | as enacted, 2 June 1972 |
| `498-200-nationalparkordnung/` | Verordnung über den Schutz des Schweizerischen Nationalparks (BR 498.200) | 1 | one version (the oldest available), 1 January 2011 |
| `498-210-obvn/` | Verordnung über die Erhebung von Ordnungsbussen bei Verstössen gegen die Nationalparkordnung (BR 498.210) | 1 | as enacted, 1 July 2012 |
| `500-010-vozgesg/` | Verordnung zum Gesundheitsgesetz (BR 500.010) | 10 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `500-100/` | Verordnung über die Gebühren im Gesundheitsbereich (BR 500.100) | 7 | oldest version available, then each consolidated version: 1 August 2014 to 1 November 2023 |
| `500-510-verordnung-zum-einfuhrungsgesetz-zum-heilmittelgesetz-vozegzhmg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Arzneimittel und Medizinprodukte (BR 500.510) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2018 |
| `500-920-vzpdgrg/` | Verordnung zum Gesetz über die Psychiatrischen Dienste Graubünden (BR 500.920) | 2 | as enacted, then each consolidated version: 1 July 2013 to 1 January 2019 |
| `502-100/` | Verordnung über die Amtsärzte und Amtsärztinnen (BR 502.100) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2018 |
| `504-300/` | Vollziehungsverordnung zum Bundesgesetz über die Betäubungsmittel (BR 504.300) | 1 | one version (the oldest available), 1 January 2013 |
| `506-060-verordnung-zum-krankenpflegegesetz-vozkpg/` | Verordnung zum Gesetz über die Förderung der Krankenpflege und der Betreuung von betagten und pflegebedürftigen Personen (BR 506.060) | 12 | oldest version available, then each consolidated version: 1 January 2015 to 1 May 2026 |
| `507-100-lebensmittelverordnung/` | Vollziehungsverordnung zum Bundesgesetz über Lebensmittel und Gebrauchsgegenstände (BR 507.100) | 1 | one version (the oldest available), 1 January 2011 |
| `507-310-gebvlc/` | Verordnung über die Gebühren in den Bereichen Lebensmittel, Chemikalien und ökologisches Gleichgewicht (BR 507.310) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 October 2019 |
| `507-400/` | Kantonale Fleischhygieneverordnung (BR 507.400) | 1 | one version (the oldest available), 1 January 2011 |
| `507-500-vvztabpg/` | Vollziehungsverordnung zum Bundesgesetz über Tabakprodukte und elektronische Zigaretten (BR 507.500) | 1 | as enacted, 1 April 2025 |
| `520-200/` | Verordnung über das Bettagsmandat und die Bettagskollekte (BR 520.200) | 1 | as enacted, 1 March 1971 |
| `530-150/` | Verordnung zum Einführungsgesetz zum Arbeitsgesetz und zur Unfallverhütung nach Unfallversicherungsgesetz (BR 530.150) | 2 | oldest version available, then each consolidated version: 1 September 2010 to 1 January 2018 |
| `530-300/` | Verordnung zum Vollzug des Personenverkehrsabkommens (BR 530.300) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `542-120-vozkpvg/` | Verordnung zum Gesetz über die Krankenversicherung und die Prämienverbilligung (BR 542.120) | 6 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `544-010-vvzegzahvg-ivg/` | Vollziehungsverordnung zum Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und die Invalidenversicherung (BR 544.010) | 2 | oldest version available, then each consolidated version: 1 December 2010 to 1 January 2015 |
| `544-050/` | Reglement über die Organisation der Sozialversicherungsanstalt des Kantons Graubünden (BR 544.050) | 1 | one version (the oldest available), 1 December 1997 |
| `545-200/` | Verordnung zum Bundesgesetz über Massnahmen zur Bekämpfung der Schwarzarbeit (BR 545.200) | 1 | as enacted, 1 January 2008 |
| `545-265/` | Geschäftsreglement der tripartiten Kommission (BR 545.265) | 1 | as enacted, 1 December 1998 |
| `545-270-vozegzavg-avig/` | Verordnung zum Einführungsgesetz zur Arbeitsvermittlung und Arbeitslosenversicherung (BR 545.270) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 July 2021 |
| `545-280/` | Reglement der Arbeitslosenkasse (BR 545.280) | 1 | as enacted, 1 January 2010 |
| `545-290/` | Verordnung über den "Bündner Arbeitslosenfonds" (BR 545.290) | 1 | one version (the oldest available), 14 March 2011 |
| `546-500/` | Vollziehungsverordnung zum Bundesgesetz über die Schwangerschaftsberatungsstellen (BR 546.500) | 1 | one version (the oldest available), 1 December 2012 |
| `548-310-kibev/` | Verordnung über die Förderung der familienergänzenden Kinderbetreuung im Kanton Graubünden (BR 548.310) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `549-100-vvzohg/` | Vollziehungsverordnung zum Bundesgesetz über die Hilfe an Opfer von Straftaten (BR 549.100) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2025 |
| `613-100-polv/` | Polizeiverordnung (BR 613.100) | 7 | oldest version available, then each consolidated version: 1 January 2014 to 1 May 2026 |
| `613-140-polizeikostenverordnung-polkostv/` | Verordnung über die Kosten für Amtshandlungen und Dienstleistungen der Kantonspolizei (BR 613.140) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2019 |
| `613-190-rvzbwis/` | Verordnung zum Bundesgesetz über Massnahmen zur Wahrung der inneren Sicherheit (BR 613.190) | 1 | as enacted, 1 June 2022 |
| `615-100/` | Verordnung über die Ausstellung von Ausweisen für Schweizer Staatsangehörige (BR 615.100) | 2 | oldest version available, then each consolidated version: 1 November 2012 to 1 January 2016 |
| `618-110-rvzegzaag/` | Verordnung zum Einführungsgesetz zur Ausländer- und Asylgesetzgebung (BR 618.110) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 September 2024 |
| `618-200/` | Reglement für die Integrationskommission (BR 618.200) | 1 | as enacted, 1 February 2011 |
| `630-010-vozbsg/` | Verordnung zum Bevölkerungsschutzgesetz (BR 630.010) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `640-110-vozzsg/` | Verordnung zum Zivilschutzgesetz (BR 640.110) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `710-110-fhv/` | Verordnung über den kantonalen Finanzhaushalt (BR 710.110) | 9 | as enacted, then each consolidated version: 1 December 2012 to 1 January 2025 |
| `710-150/` | Reglement über die Tresorerie des Kantons Graubünden (BR 710.150) | 3 | as enacted, then each consolidated version: 1 April 2013 to 1 September 2020 |
| `710-200/` | Finanzhaushaltsverordnung für die Gemeinden (BR 710.200) | 3 | as enacted, then each consolidated version: 1 December 2012 to 1 January 2024 |
| `710-400/` | Verordnung zur Umsetzung der Public Corporate Governance für den Kanton Graubünden (BR 710.400) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2023 |
| `710-600-landeslotterie-reglement-llr/` | Reglement für die Ausrichtung von Beiträgen aus der Spezialfinanzierung Landeslotterie (BR 710.600) | 3 | oldest version available, then each consolidated version: 1 December 2012 to 1 September 2024 |
| `730-220-fav/` | Verordnung über den Finanzausgleich (BR 730.220) | 4 | oldest version available, then each consolidated version: 1 December 2012 to 1 January 2027 |
| `740-010-kjv/` | Kantonale Jagdverordnung (BR 740.010) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 December 2016 |
| `740-020-rjv/` | Regierungsrätliche Jagdverordnung (BR 740.020) | 6 | oldest version available, then each consolidated version: 1 June 2014 to 1 July 2026 |
| `740-025-jagdbetriebsvorschriften-jbv/` | Verordnung über den Jagdbetrieb (BR 740.025) | 9 | as enacted, then each consolidated version: 1 August 2018 to 1 August 2026 |
| `740-030-obvj/` | Verordnung über die Erhebung von Ordnungsbussen bei Jagdrechtsübertretungen (BR 740.030) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 March 2020 |
| `740-040-vwl/` | Verordnung über die Wildschadenverhütung und Wildschadenvergütung in der Landwirtschaft (BR 740.040) | 2 | oldest version available, then each consolidated version: 1 April 2014 to 1 March 2018 |
| `740-050-vww/` | Verordnung über die Wildschadenverhütung und Wildschadenvergütung im Wald (BR 740.050) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 June 2017 |
| `740-060-jpgv/` | Verordnung über die Jagdpatentgebühren (BR 740.060) | 4 | oldest version available, then each consolidated version: 1 June 2011 to 1 August 2025 |
| `740-100-kjpv/` | Kantonale Jagdprüfungsverordnung (BR 740.100) | 4 | oldest version available, then each consolidated version: 1 December 2013 to 1 June 2019 |
| `740-110-vjsp/` | Verordnung über die jagdliche Schiesspflicht (BR 740.110) | 4 | as enacted, then each consolidated version: 1 March 2015 to 1 May 2020 |
| `740-200-vwsg/` | Verordnung über die Wildschutzgebiete (BR 740.200) | 2 | as enacted, then each consolidated version: 1 September 2018 to 1 September 2023 |
| `740-300-khv/` | Kantonale Hegeverordnung (BR 740.300) | 2 | oldest version available, then each consolidated version: 1 December 2010 to 15 June 2017 |
| `740-330-kstv/` | Kantonale Steinwildverordnung (BR 740.330) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 May 2025 |
| `740-350-jhv/` | Kantonale Jagdhundeverordnung (BR 740.350) | 4 | oldest version available, then each consolidated version: 1 April 2010 to 1 May 2025 |
| `740-400-dvo/` | Dienstverordnung für die kantonalen Jagd- und Fischereiaufsichtsorgane (BR 740.400) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 June 2017 |
| `740-500-rejk/` | Reglement für die Jagdkommission (BR 740.500) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 June 2017 |
| `760-150-kfv/` | Kantonale Fischereiverordnung (BR 760.150) | 1 | one version (the oldest available), 1 January 2014 |
| `760-155-fischereibetriebsvorschriften-fbv/` | Verordnung über den Fischereibetrieb (BR 760.155) | 4 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `760-160-obvf/` | Verordnung über die Erhebung von Ordnungsbussen bei Fischereirechtsübertretungen (BR 760.160) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2020 |
| `760-180-pgbv/` | Verordnung über die Fischereipatentgebühren (BR 760.180) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 November 2017 |
| `760-300-refk/` | Reglement für die Fischereikommission (BR 760.300) | 1 | as enacted, 1 May 2009 |
| `780-110/` | Vollziehungsverordnung zum Gesetz über das Salzregal des Kantons Graubünden (BR 780.110) | 1 | as enacted, 1 October 1975 |
| `800-110-imv/` | Verordnung über die Immobilien (BR 800.110) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 December 2022 |
| `801-110-krvo/` | Raumplanungsverordnung für den Kanton Graubünden (BR 801.110) | 7 | oldest version available, then each consolidated version: 1 October 2011 to 1 October 2025 |
| `801-150-umnutzungsverordnung-uvo/` | Verordnung über die Umnutzung landwirtschaftlicher Wohnbauten und schützenswerter Bauten und Anlagen ausserhalb der Bauzonen (BR 801.150) | 1 | as enacted, 30 November 2000 |
| `803-110-entv/` | Enteignungsverordnung des Kantons Graubünden (BR 803.110) | 1 | one version (the oldest available), 1 January 2013 |
| `803-610-rvzegzivob/` | Verordnung zum Einführungsgesetz zur Interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (BR 803.610) | 1 | one version (the oldest available), 1 October 2022 |
| `807-110-strv/` | Strassenverordnung des Kantons Graubünden (BR 807.110) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 June 2023 |
| `810-110-bwrv/` | Verordnung zum Wasserrechtsgesetz des Kantons Graubünden (BR 810.110) | 1 | one version (the oldest available), 1 September 2009 |
| `810-115-vwpst/` | Verordnung über die Wasser- und Pumpwerksteuer (BR 810.115) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `810-120-vreg/` | Versicherungsreglement (BR 810.120) | 1 | as enacted, 1 July 1995 |
| `810-130-kstav/` | Verordnung über die kantonale Stauanlagenaufsicht (BR 810.130) | 1 | as enacted, 1 July 2017 |
| `810-200/` | Vollziehungsverordnung zum Bundesgesetz vom 22. Dezember 1916 über die Nutzbarmachung der Wasserkräfte (BR 810.200) | 2 | oldest version available, then each consolidated version: 1 January 1969 to 1 January 2025 |
| `815-200-kantonale-gewasserschutzverordnung-kgschv/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über den Schutz der Gewässer (BR 815.200) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2016 |
| `815-350/` | Gebührenverordnung für den Umweltschutz (BR 815.350) | 2 | oldest version available, then each consolidated version: 1 January 2004 to 1 January 2015 |
| `815-500-schadendienstverordnung/` | Verordnung über den Schadendienst (BR 815.500) | 1 | one version (the oldest available), 1 January 2005 |
| `820-110-kusv/` | Kantonale Umweltschutzverordnung (BR 820.110) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2025 |
| `820-150-kvuvp/` | Kantonale Verordnung über die Umweltverträglichkeitsprüfung (BR 820.150) | 3 | as enacted, then each consolidated version: 12 November 2009 to 10 April 2017 |
| `820-210-bev/` | Energieverordnung des Kantons Graubünden (BR 820.210) | 5 | oldest version available, then each consolidated version: 1 January 2014 to 31 December 2025 |
| `820-410-bundner-klima-und-innovationsverordnung-bkiv/` | Verordnung über die Förderung und Finanzierung von Massnahmen zu Klimaschutz und Innovation in Graubünden (BR 820.410) | 1 | as enacted, 31 December 2025 |
| `830-110-verordnung-zum-gebaudeversicherungsgesetz-vozgebvg/` | Verordnung zum Gesetz über die Gebäudeversicherung im Kanton Graubünden (BR 830.110) | 9 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `835-120-vve/` | Verordnung zum Gesetz über die Vergütung nicht versicherbarer Elementarschäden (BR 835.120) | 5 | as enacted, then each consolidated version: 1 January 2011 to 1 July 2023 |
| `840-110/` | Verordnung zum Brandschutzgesetz (BR 840.110) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `850-110-vaib/` | Verordnung über die amtlichen Immobilienbewertungen (BR 850.110) | 8 | oldest version available, then each consolidated version: 1 January 2012 to 1 December 2023 |
| `870-110-rvzegzsvg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über den Strassenverkehr (BR 870.110) | 8 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2025 |
| `870-120/` | Verordnung über die Verkehrssteuern für Motorfahrzeuge und Anhänger (BR 870.120) | 1 | one version (the oldest available), 1 January 2009 |
| `870-130-strassenverkehrsgebuhrenverordnung-strgebv/` | Verordnung über die Gebühren im Strassenverkehr (BR 870.130) | 2 | oldest version available, then each consolidated version: 1 June 2012 to 1 January 2023 |
| `872-150-vov/` | Verordnung über den öffentlichen Verkehr im Kanton Graubünden (BR 872.150) | 2 | oldest version available, then each consolidated version: 1 June 2011 to 1 January 2023 |
| `873-450/` | Verordnung über die nicht eidgenössisch konzessionierten Luftseilbahnen, Skilifte und Schrägaufzüge (BR 873.450) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2026 |
| `875-100-klfv/` | Kantonale Luftfahrtverordnung (BR 875.100) | 1 | as enacted, 1 January 2011 |
| `877-120-binnenschifffahrtsgebuhrenverordnung-bsgebv/` | Verordnung über die Gebühren für die Binnenschifffahrt (BR 877.120) | 2 | oldest version available, then each consolidated version: 1 April 2003 to 1 January 2023 |
| `910-050/` | Landwirtschaftsverordnung (BR 910.050) | 1 | one version (the oldest available), 1 December 2012 |
| `910-150-kgschvl/` | Verordnung über den Gewässerschutz in der Landwirtschaft (BR 910.150) | 1 | as enacted, 1 January 2020 |
| `910-175/` | Reglement über die Erhebung von Gebühren für Beratungen des Plantahofs (BR 910.175) | 2 | as enacted, then each consolidated version: 1 September 2003 to 1 March 2018 |
| `912-010/` | Viehwirtschaftsverordnung (BR 912.010) | 1 | one version (the oldest available), 1 January 2008 |
| `914-100-vetv/` | Veterinärverordnung (BR 914.100) | 1 | one version (the oldest available), 1 December 2012 |
| `914-200-somv/` | Sömmerungsverordnung (BR 914.200) | 1 | one version (the oldest available), 1 April 2011 |
| `915-110/` | Vollziehungsverordnung zum Meliorationsgesetz des Kantons Graubünden (BR 915.110) | 1 | one version (the oldest available), 1 April 2007 |
| `917-200/` | Reglement über die kantonale Alpkäseprämierung (BR 917.200) | 2 | as enacted, then each consolidated version: 1 August 2003 to 1 March 2018 |
| `919-100/` | Reglement der Kommission für Bildung und Beratung des Plantahofs (BR 919.100) | 2 | as enacted, then each consolidated version: 1 January 2001 to 1 March 2018 |
| `919-300/` | Reglement über die Kosten für Unterkunft und Verpflegung sowie über die Kursgebühren am Plantahof (BR 919.300) | 3 | as enacted, then each consolidated version: 1 August 2010 to 1 August 2023 |
| `920-110-kwav/` | Kantonale Waldverordnung (BR 920.110) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `920-150-irmv/` | Verordnung zum Integralen Risikomanagement bei Naturgefahren (BR 920.150) | 1 | as enacted, 1 January 2021 |
| `920-600-vfp/` | Verordnung über die forstliche Planung (BR 920.600) | 1 | as enacted, 1 September 2014 |
| `932-160-vwe-wirtschaftsentwicklungsverordnung/` | Verordnung über die Förderung der wirtschaftlichen Entwicklung in Graubünden (BR 932.160) | 5 | oldest version available, then each consolidated version: 1 March 2009 to 1 July 2026 |
| `932-210-kantonale-covid-19-hartefallverordnung-2022-khfv-22/` | Verordnung zum kantonalen Gesetz über Härtefallmassnahmen für Unternehmen im Zusammenhang mit der COVID-19-Epidemie im Jahr 2022 (BR 932.210) | 1 | as enacted, 1 January 2022 |
| `933-100-vvzkkg/` | Vollziehungsverordnung zum Bundesgesetz über den Konsumkredit (BR 933.100) | 1 | as enacted, 1 April 2006 |
| `935-300/` | Vollziehungsverordnung zum Bundesgesetz über das Messwesen (BR 935.300) | 1 | one version (the oldest available), 1 January 2007 |
| `935-400/` | Filmverordnung (BR 935.400) | 1 | one version (the oldest available), 1 June 2000 |
| `935-510-geldspielverordnung-vkgs/` | Verordnung zum Geldspielgesetz des Kantons Graubünden (BR 935.510) | 1 | as enacted, 1 January 2021 |
| `950-270-vfw/` | Verordnung über die Förderung von Wohnraum (BR 950.270) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2026 |
| `960-110-vdt/` | Verordnung zur Förderung der digitalen Transformation in Graubünden (BR 960.110) | 1 | as enacted, 1 January 2021 |

## Source

The BR (systematic collection) of the canton, published by the canton at <https://www.gr-lex.gr.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (AGS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (AGS), with an e-mail address that cannot exist (`<act key>@www.gr-lex.gr.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
