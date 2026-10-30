# Solothurn: law history in git

The law of the canton of Solothurn (Kanton Solothurn, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-so/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

291 acts with 933 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 218 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-1-kv/` | Verfassung des Kantons Solothurn (BGS 111.1) | 11 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `111-31-publikationsgesetz-pug/` | Gesetz über die amtlichen Publikationsorgane (BGS 111.31) | 2 | as enacted, then each consolidated version: 1 October 2018 to 1 July 2023 |
| `112-11-burgerrechtsgesetz/` | Gesetz über das Kantons- und Gemeindebürgerrecht (BGS 112.11) | 5 | oldest version available, then each consolidated version: 1 March 2010 to 1 January 2024 |
| `113-111-gpr/` | Gesetz über die politischen Rechte (BGS 113.111) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2025 |
| `114-1-infodg/` | Informations- und Datenschutzgesetz (BGS 114.1) | 2 | oldest version available, then each consolidated version: 1 November 2008 to 1 January 2015 |
| `114-3-gesp/` | Gesetz über die Einwohnerregister- und die Stimmregisterplattform (BGS 114.3) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 November 2020 |
| `114-5-auslagerungsgesetz-ausg/` | Gesetz über die Auslagerung von Informatikdienstleistungen (BGS 114.5) | 1 | as enacted, 1 May 2025 |
| `115-1-wov-g/` | Gesetz über die wirkungsorientierte Verwaltungsführung (BGS 115.1) | 11 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2025 |
| `116-1-behopg/` | Gesetz über das Behördenportal (BGS 116.1) | 1 | as enacted, 1 November 2020 |
| `121-1/` | Kantonsratsgesetz (BGS 121.1) | 12 | oldest version available, then each consolidated version: 3 September 2010 to 1 January 2027 |
| `122-51/` | Archivgesetz (BGS 122.51) | 1 | as enacted, 1 January 2007 |
| `122-111-regierungs-und-verwaltungsorganisationsgesetz-rvog/` | Gesetz über die Organisation des Regierungsrates und der Verwaltung (BGS 122.111) | 4 | oldest version available, then each consolidated version: 1 August 2005 to 1 August 2025 |
| `122-131-delegationsgesetz/` | Gesetz über die Delegation von Verwaltungsbefugnissen (BGS 122.131) | 1 | one version (the oldest available), 1 August 1999 |
| `122-151-katastrophengesetz/` | Gesetz über Massnahmen für den Fall von Katastrophen und kriegerischen Ereignissen (BGS 122.151) | 1 | one version (the oldest available), 1 January 1984 |
| `124-11-verwaltungsrechtspflegegesetz/` | Gesetz über den Rechtsschutz in Verwaltungssachen (BGS 124.11) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2025 |
| `124-21-verantwortlichkeitsgesetz/` | Gesetz über die Haftung des Staates, der Gemeinden, der öffentlich-rechtlichen Körperschaften und Anstalten und die Verantwortlichkeit der Behörden, Beamten und öffentlichen Angestellten und Arbeiter (BGS 124.21) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2025 |
| `125-12-go/` | Gesetz über die Gerichtsorganisation (BGS 125.12) | 18 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `126-1/` | Gesetz über das Staatspersonal (BGS 126.1) | 12 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2025 |
| `126-581-pkg/` | Gesetz über die Pensionskasse Kanton Solothurn (BGS 126.581) | 3 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2022 |
| `126-583-rrg/` | Gesetz über das Ruhegehalt des Regierungsrates (BGS 126.583) | 1 | as enacted, 1 January 2016 |
| `127-10-anwaltsgesetz-anwg/` | Gesetz über die Rechtsanwälte und Rechtsanwältinnen (BGS 127.10) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2021 |
| `131-1-gg/` | Gemeindegesetz (BGS 131.1) | 11 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `131-73-finanz-und-lastenausgleichsgesetz-filag-eg/` | Gesetz über den Finanz- und Lastenausgleich der Einwohnergemeinden (BGS 131.73) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2020 |
| `131-74-fiag-kg/` | Gesetz über den Finanzausgleich der Kirchgemeinden (BGS 131.74) | 1 | as enacted, 1 January 2020 |
| `211-1/` | Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches (BGS 211.1) | 13 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `212-431-eg-bewg/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (BGS 212.431) | 1 | one version (the oldest available), 1 August 2000 |
| `311-1/` | Gesetz über das kantonale Strafrecht und die Einführung des Schweizerischen Strafgesetzbuches (BGS 311.1) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 November 2021 |
| `323-1-eg-zeugsg/` | Einführungsgesetz zum Bundesgesetz über den ausserprozessualen Zeugenschutz (BGS 323.1) | 1 | as enacted, 1 July 2016 |
| `331-11-juvg/` | Gesetz über den Justizvollzug (BGS 331.11) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2024 |
| `413-111-vsg/` | Volksschulgesetz (BGS 413.111) | 12 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2023 |
| `414-11/` | Mittelschulgesetz (BGS 414.11) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2023 |
| `414-131/` | Gesetz über die Fachmittelschule (BGS 414.131) | 1 | one version (the oldest available), 1 August 2004 |
| `415-211-fhg/` | Fachhochschulgesetz (BGS 415.211) | 3 | as enacted, then each consolidated version: 1 March 2008 to 1 August 2023 |
| `416-111-gbb/` | Gesetz über die Berufsbildung (BGS 416.111) | 4 | as enacted, then each consolidated version: 1 January 2009 to 1 August 2023 |
| `416-961/` | Gesetz über die Beteiligung an der interkantonalen Trägerschaft des Heilpädagogischen Seminars Zürich (BGS 416.961) | 1 | as enacted, 26 September 1985 |
| `419-11-stipendiengesetz/` | Gesetz über Ausbildungsbeiträge (BGS 419.11) | 3 | oldest version available, then each consolidated version: 1 August 2008 to 1 August 2022 |
| `423-581-1/` | Gesetz über die staatliche Besoldungsreform (BGS 423.581.1) | 2 | as enacted, then each consolidated version: 23 November 1941 to 1 January 2024 |
| `423-581-2/` | Gesetz über die Änderung des Gesetzes vom 29. März 1925 über die Beteiligung des Staates an der Roth-Stiftung des Kantons Solothurn und des Gesetzes vom 29. August 1909 über die Kantonsschule, die landwirtschaftliche Winterschule und die Fortbildungsschulen (BGS 423.581.2) | 2 | as enacted, then each consolidated version: 6 May 1957 to 1 January 2024 |
| `431-11/` | Gesetz über Kulturförderung (BGS 431.11) | 2 | as enacted, then each consolidated version: 2 June 1967 to 1 January 2017 |
| `511-11/` | Gesetz über die Kantonspolizei (BGS 511.11) | 8 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2024 |
| `512-41-ruhetagsgesetz-rtg/` | Gesetz über die öffentlichen Ruhetage (BGS 512.41) | 2 | oldest version available, then each consolidated version: 1 October 2010 to 1 September 2014 |
| `521-1-eg-mw/` | Einführungsgesetz über die Militärgesetzgebung und die Wehrpflichtersatzabgabe (BGS 521.1) | 1 | as enacted, 1 September 2020 |
| `531-1-eg-bzg/` | Einführungsgesetz zur eidgenössischen Bevölkerungsschutz- und Zivilschutzgesetzgebung (BGS 531.1) | 2 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2015 |
| `614-11-steuergesetz/` | Gesetz über die Staats- und Gemeindesteuern (BGS 614.11) | 17 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `614-51/` | Gesetz über die Billettsteuer (BGS 614.51) | 1 | as enacted, 26 September 1982 |
| `614-61/` | Gesetz über die Steuern und Gebühren für Motorfahrzeuge und Fahrräder (BGS 614.61) | 3 | oldest version available, then each consolidated version: 1 January 1993 to 1 January 2023 |
| `614-71-hundegesetz/` | Gesetz über das Halten von Hunden (BGS 614.71) | 2 | as enacted, then each consolidated version: 1 August 2007 to 1 January 2026 |
| `614-81/` | Gesetz über die Schiffssteuer (BGS 614.81) | 1 | as enacted, 1 January 1981 |
| `617-11/` | Gesetz über die Privatisierung der Solothurner Kantonalbank (BGS 617.11) | 1 | as enacted, 16 December 1994 |
| `618-111-gebaudeversicherungsgesetz-gvg/` | Gesetz über die Gebäudeversicherung, den Brandschutz und die Elementarschadenprävention, die Feuerwehr und den Elementarschadenfonds (BGS 618.111) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `625-11-fig/` | Fischereigesetz (BGS 625.11) | 3 | as enacted, then each consolidated version: 1 January 2009 to 1 March 2026 |
| `626-11-jag/` | Jagdgesetz (BGS 626.11) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2018 |
| `711-1-pbg/` | Planungs- und Baugesetz (BGS 711.1) | 6 | oldest version available, then each consolidated version: 1 January 2010 to 1 October 2024 |
| `711-18-planungsausgleichsgesetz-pag/` | Gesetz über den Ausgleich raumplanungsbedingter Vor- und Nachteile (BGS 711.18) | 1 | as enacted, 1 July 2018 |
| `711-27-geoig/` | Geoinformationsgesetz (BGS 711.27) | 1 | as enacted, 1 April 2014 |
| `712-15-gwba/` | Gesetz über Wasser, Boden und Abfall (BGS 712.15) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2018 |
| `712-921/` | Gesetz über die Schaffung einer Ölwehr im Kanton Solothurn (BGS 712.921) | 1 | as enacted, 1 January 1969 |
| `721-54-subg/` | Submissionsgesetz (BGS 721.54) | 4 | oldest version available, then each consolidated version: 1 May 2004 to 1 July 2022 |
| `725-11/` | Strassengesetz (BGS 725.11) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2021 |
| `725-21/` | Einführungsgesetz zum Bundesgesetz über die Nationalstrassen (BGS 725.21) | 1 | one version (the oldest available), 1 August 2000 |
| `732-1-ovg/` | Gesetz über den öffentlichen Verkehr (BGS 732.1) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2023 |
| `811-11-gesg/` | Gesundheitsgesetz (BGS 811.11) | 10 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `811-17-eg-ausbildungsfordergesetz-pflege/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (BGS 811.17) | 2 | as enacted, then each consolidated version: 1 July 2024 to 1 September 2026 |
| `812-1-eg-usg/` | Einführungsgesetz zum Vollzug der eidgenössischen Umweltschutzgesetzgebung und weiterer Erlasse (BGS 812.1) | 1 | as enacted, 1 January 2018 |
| `817-11-spig/` | Spitalgesetz (BGS 817.11) | 8 | oldest version available, then each consolidated version: 1 March 2009 to 1 September 2026 |
| `831-1-sg/` | Sozialgesetz (BGS 831.1) | 19 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `836-11/` | Einführungsgesetz zum Bundesgesetz über Massnahmen zur Förderung des Wohnungsbaues (BGS 836.11) | 1 | one version (the oldest available), 1 January 2004 |
| `837-536-1-slfg/` | Gesetz über die Swisslos-Fonds (BGS 837.536.1) | 1 | as enacted, 1 January 2021 |
| `921-11/` | Landwirtschaftsgesetz (BGS 921.11) | 1 | one version (the oldest available), 1 January 2009 |
| `931-11/` | Waldgesetz (BGS 931.11) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2014 |
| `940-11-wag/` | Wirtschafts- und Arbeitsgesetz (BGS 940.11) | 5 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2027 |
| `940-20-covid-19-hartefallgesetz/` | Gesetz über Härtefallmassnahmen für Unternehmen im Zusammenhang mit Covid-19 (BGS 940.20) | 2 | as enacted, then each consolidated version: 1 January 2022 to 23 February 2023 |
| `941-21/` | Energiegesetz (BGS 941.21) | 2 | oldest version available, then each consolidated version: 1 July 2005 to 1 January 2015 |
| `111-32-publikationsverordnung-puv/` | Verordnung über die amtlichen Publikationsorgane (BGS 111.32) | 2 | as enacted, then each consolidated version: 1 October 2018 to 1 July 2023 |
| `112-12-burgerrechtsverordnung/` | Vollzugsverordnung zum Gesetz über das Kantons- und Gemeindebürgerrecht (BGS 112.12) | 6 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2026 |
| `113-112-vpr/` | Verordnung über die politischen Rechte (BGS 113.112) | 4 | oldest version available, then each consolidated version: 1 July 2010 to 1 January 2024 |
| `113-114/` | Verordnung über Abstimmungs- und Wahlplakate (BGS 113.114) | 2 | as enacted, then each consolidated version: 1 September 2015 to 1 September 2023 |
| `114-4-vesp/` | Verordnung zum Gesetz über die Einwohnerregister- und die Stimmregisterplattform (BGS 114.4) | 1 | as enacted, 1 March 2016 |
| `115-11-wov-vo/` | Verordnung zum Gesetz über die wirkungsorientierte Verwaltungsführung (BGS 115.11) | 5 | oldest version available, then each consolidated version: 1 May 2009 to 1 July 2022 |
| `116-2-behopv/` | Verordnung über das Behördenportal (BGS 116.2) | 1 | as enacted, 1 November 2020 |
| `121-2/` | Geschäftsreglement des Kantonsrates von Solothurn (BGS 121.2) | 11 | oldest version available, then each consolidated version: 3 September 2010 to 1 January 2027 |
| `121-251/` | Verordnung über die Fraktionsbeiträge (BGS 121.251) | 2 | oldest version available, then each consolidated version: 3 May 2005 to 1 January 2022 |
| `122-112-rvov/` | Verordnung über die Organisation des Regierungsrates und der Verwaltung (BGS 122.112) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2026 |
| `122-132/` | Verordnung über die Delegation von Verwaltungsbefugnissen (BGS 122.132) | 1 | as enacted, 1 August 2000 |
| `122-152/` | Verordnung zum Katastrophengesetz (BGS 122.152) | 1 | one version (the oldest available), 1 September 1993 |
| `122-218/` | Verordnung über die Delegation der Unterschriftsberechtigung in den Departementen (BGS 122.218) | 29 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2026 |
| `122-511-archivvo/` | Archivverordnung (BGS 122.511) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 March 2020 |
| `123-21-amtschreibereiverordnung-asv/` | Verordnung über die Geschäftsführung der Amtschreibereien (BGS 123.21) | 6 | oldest version available, then each consolidated version: 1 May 2009 to 1 January 2016 |
| `123-321-ev-schkg/` | Verordnung zur Einführung des Bundesgesetzes über Schuldbetreibung und Konkurs sowie des Bundesgesetzes über die Schuldbetreibung gegen Gemeinden und andere Körperschaften des kantonalen öffentlichen Rechts (BGS 123.321) | 1 | one version (the oldest available), 1 January 2011 |
| `124-12-v-elub/` | Verordnung über die elektronische Übermittlung im Verwaltungsverfahren (BGS 124.12) | 2 | as enacted, then each consolidated version: 1 July 2018 to 1 November 2020 |
| `124-13/` | Verordnung über die Form der Zustellung in Verwaltungssachen (BGS 124.13) | 1 | as enacted, 1 July 2022 |
| `125-71/` | Geschäftsreglement des Obergerichts des Kantons Solothurn und der ihm angegliederten Spezialgerichte (BGS 125.71) | 5 | oldest version available, then each consolidated version: 1 August 2005 to 1 January 2026 |
| `125-81/` | Haftrichterverordnung (BGS 125.81) | 2 | as enacted, then each consolidated version: 1 August 2005 to 1 August 2011 |
| `125-121-vaga/` | Verordnung über die Aufbewahrung und Archivierung der Gerichtsakten (BGS 125.121) | 1 | as enacted, 1 January 2026 |
| `125-411/` | Reglement über die Geschäftsführung und Organisation des Richteramtes Solothurn-Lebern (BGS 125.411) | 3 | as enacted, then each consolidated version: 1 October 2006 to 1 June 2016 |
| `125-412/` | Reglement über die Geschäftsführung und Organisation des Richteramtes Bucheggberg-Wasseramt (BGS 125.412) | 2 | as enacted, then each consolidated version: 1 October 2006 to 1 July 2011 |
| `125-413/` | Reglement über die Geschäftsführung und Organisation des Richteramtes Thal-Gäu (BGS 125.413) | 2 | as enacted, then each consolidated version: 1 October 2006 to 1 July 2011 |
| `125-414/` | Reglement über die Geschäftsführung und Organisation des Richteramtes Olten-Gösgen (BGS 125.414) | 3 | as enacted, then each consolidated version: 1 October 2006 to 1 December 2013 |
| `125-415/` | Reglement über die Geschäftsführung und Organisation des Richteramtes Dorneck-Thierstein (BGS 125.415) | 2 | as enacted, then each consolidated version: 1 October 2006 to 1 July 2011 |
| `125-922/` | Verordnung des Kantonsrates über das Verfahren vor dem Versicherungsgericht und über die Organisation und das Verfahren der Schiedsgerichte in den Sozialversicherungen (BGS 125.922) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 March 2015 |
| `125-932/` | Geschäftsreglement des kantonalen Steuergerichts (BGS 125.932) | 2 | as enacted, then each consolidated version: 1 August 2005 to 1 August 2017 |
| `125-942/` | Reglement über die Geschäftsführung und Organisation der Kantonalen Schätzungskommission (BGS 125.942) | 2 | as enacted, then each consolidated version: 1 October 2006 to 1 July 2011 |
| `126-31-personalrechtsverordnung-prv/` | Verordnung über das Personalrecht (BGS 126.31) | 8 | as enacted, then each consolidated version: 1 September 2007 to 1 April 2025 |
| `126-51-1/` | Verordnung über die Besoldungen und die Arbeitszeit des Staatspersonals und der Lehrkräfte an kantonalen Schulen (BGS 126.51.1) | 1 | one version (the oldest available), 1 July 2010 |
| `126-161/` | Verordnung über die Bearbeitung von Personendaten des Staatspersonals (BGS 126.161) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 August 2023 |
| `126-371-2-lernendenverordnung/` | Verordnung für Lernende der beruflichen Grundbildung (BGS 126.371.2) | 5 | oldest version available, then each consolidated version: 1 August 2007 to 1 February 2019 |
| `126-511-31/` | Verordnung über die Sitzungsgelder und die Sitzungspauschalen (BGS 126.511.31) | 1 | one version (the oldest available), 1 April 2011 |
| `126-511-329-4/` | Verordnung über die Entschädigung der für die Sportfachstelle tätigen Personen, insbesondere im Bereich Jugend+Sport (J+S) (BGS 126.511.329.4) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2021 |
| `126-515-123-53/` | Verordnung über die Entschädigung der Experten bei den Schüler-Radfahrerprüfungen (BGS 126.515.123.53) | 2 | oldest version available, then each consolidated version: 1 September 2007 to 1 April 2016 |
| `126-515-856-1/` | Verordnung über die Entschädigung von Kursleitern und Referenten an Jungbürger- und Neubürgerkursen (BGS 126.515.856.1) | 1 | as enacted, 1 August 1991 |
| `126-541/` | Verordnung über die Unfallfürsorge des Staatspersonals des Kantons Solothurn (BGS 126.541) | 1 | one version (the oldest available), 1 January 1982 |
| `127-11/` | Verordnung über das Anwaltsregister (BGS 127.11) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `128-111/` | Verordnung über die juristische Grundausbildung (BGS 128.111) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `128-121/` | Verordnung über Seminarkurse für Angestellte der Amtschreibereien zur Vorbereitung auf die solothurnische Notariatsprüfung (BGS 128.121) | 1 | as enacted, 1 January 2006 |
| `128-213-jpv/` | Juristische Prüfungsverordnung (BGS 128.213) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 March 2026 |
| `128-221/` | Verordnung über die Ausbildung von Fachpersonen der Amtschreiberei (BGS 128.221) | 2 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2016 |
| `129-11/` | Notariatsverordnung (BGS 129.11) | 8 | oldest version available, then each consolidated version: 1 February 2011 to 1 January 2020 |
| `131-45/` | Verordnung über das Leumundszeugnis (BGS 131.45) | 1 | as enacted, 1 January 1988 |
| `131-51-regv/` | Verordnung über die Harmonisierung amtlicher Register (BGS 131.51) | 3 | as enacted, then each consolidated version: 1 September 2008 to 1 January 2024 |
| `131-731-finanz-und-lastenausgleichsverordnung-filav-eg/` | Verordnung über den Finanz- und Lastenausgleich der Einwohnergemeinden (BGS 131.731) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2020 |
| `131-741-fiav-kg/` | Verordnung über den Finanzausgleich der Kirchgemeinden (BGS 131.741) | 1 | as enacted, 1 January 2020 |
| `212-11-vzd/` | Verordnung über den Zivilstandsdienst (BGS 212.11) | 3 | as enacted, then each consolidated version: 1 January 2007 to 1 July 2017 |
| `212-152-vas/` | Verordnung über die Aufsicht über Stiftungen (BGS 212.152) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `212-331-inventarisations-verordnung/` | Verordnung über die Inventaraufnahme und Schätzung im Erbgang (BGS 212.331) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2013 |
| `212-331-2/` | Verordnung über die Entschädigung der Inventurbeamten (BGS 212.331.2) | 2 | as enacted, then each consolidated version: 1 May 1992 to 1 July 2023 |
| `212-432/` | Verordnung über die Veröffentlichung des Erwerbs von Grundeigentum (BGS 212.432) | 2 | oldest version available, then each consolidated version: 1 January 2005 to 1 July 2023 |
| `212-435-3/` | Verordnung über das Enteignungsverfahren (BGS 212.435.3) | 1 | one version (the oldest available), 1 May 1977 |
| `212-436/` | Verordnung über die Enteignung von Kulturland (BGS 212.436) | 1 | as enacted, 1 January 2024 |
| `212-451/` | Verordnung über das Register der vom Kanton ermächtigten Geldinstitute und Genossenschaften für die Viehverpfändungen (BGS 212.451) | 1 | as enacted, 14 October 1986 |
| `212-471-1/` | Verordnung über die Anlage des eidgenössischen Grundbuches (BGS 212.471.1) | 2 | oldest version available, then each consolidated version: 1 January 1996 to 1 February 2015 |
| `212-472/` | Verordnung über die Führung des Grundbuches (BGS 212.472) | 7 | oldest version available, then each consolidated version: 1 May 2009 to 1 January 2026 |
| `212-473-82/` | Verordnung über die Schätzung des landwirtschaftlichen Ertragswertes (BGS 212.473.82) | 1 | one version (the oldest available), 1 January 1996 |
| `212-477-1-vav-so/` | Verordnung über die amtliche Vermessung (BGS 212.477.1) | 3 | oldest version available, then each consolidated version: 1 May 2004 to 1 January 2026 |
| `212-478-41/` | Verordnung über die Überprüfung der allgemeinen Revision der Katasterschätzung (BGS 212.478.41) | 3 | oldest version available, then each consolidated version: 17 January 1980 to 1 April 2025 |
| `212-478-42/` | Verordnung über die Katasterschätzung (BGS 212.478.42) | 3 | oldest version available, then each consolidated version: 1 January 1993 to 1 April 2025 |
| `212-478-43/` | Verordnung über die allgemeine Revision der Katasterschätzung; Übergangsregelung (BGS 212.478.43) | 1 | as enacted, 1 January 1992 |
| `212-555/` | Verordnung über die Verwertung von Fundgegenständen und die Verwendung des Erlöses (BGS 212.555) | 2 | oldest version available, then each consolidated version: 1 July 1994 to 1 March 2012 |
| `311-3/` | Vollzugsverordnung zu Artikel 120 StGB über die straflose Unterbrechung der Schwangerschaft (BGS 311.3) | 1 | as enacted, 1 January 1995 |
| `311-4-kov/` | Verordnung über die kantonalen Ordnungsbussen und den Vollzug der Ordnungsbussengesetzgebung durch die Transportpolizei (BGS 311.4) | 3 | as enacted, then each consolidated version: 1 January 2017 to 1 June 2026 |
| `321-51-konfiskationsverordnung/` | Verordnung über die Aufbewahrung, Vernichtung und Verwertung eingezogener Gegenstände (BGS 321.51) | 1 | as enacted, 7 September 1978 |
| `322-12/` | Verordnung über die Jugendstrafrechtspflege (BGS 322.12) | 2 | oldest version available, then each consolidated version: 1 February 2011 to 1 January 2026 |
| `328-13/` | Verordnung über die Begnadigung (BGS 328.13) | 1 | one version (the oldest available), 1 February 2011 |
| `331-12-juvv/` | Verordnung über den Justizvollzug (BGS 331.12) | 6 | oldest version available, then each consolidated version: 1 February 2011 to 1 November 2021 |
| `411-254-nareg-vo/` | Verordnung zum Register über die Gesundheitsfachpersonen NAREG (BGS 411.254) | 3 | as enacted, then each consolidated version: 1 January 2017 to 1 February 2022 |
| `413-121-1-vsv/` | Volksschulverordnung (BGS 413.121.1) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2023 |
| `413-412-laufbahnreglement/` | Laufbahnreglement für die Volksschule (BGS 413.412) | 9 | as enacted, then each consolidated version: 1 August 2011 to 1 August 2023 |
| `413-614/` | Verordnung über die Gemeindebeiträge an die Kosten der gymnasialen Ausbildung während der obligatorischen Schulzeit (BGS 413.614) | 4 | as enacted, then each consolidated version: 1 January 2007 to 1 August 2023 |
| `414-71/` | Verordnung über die Benützung von Schulräumen und Schulanlagen der Kantons- und Berufsschulen (BGS 414.71) | 1 | one version (the oldest available), 1 December 2010 |
| `414-113/` | Mittelschulverordnung (BGS 414.113) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 1 May 2017 |
| `414-114-gymnasiumsverordnung-gymv/` | Verordnung über die gymnasialen Maturitätsschulen (BGS 414.114) | 6 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2027 |
| `414-116-3/` | Reglement über die Übertrittsbedingungen von Schülerinnen und Schülern der Sekundarstufe I aus den Bezirken Dorneck und Thierstein in die allgemeinbildenden Schulen der Sekundarstufe II des Kantons Basel-Landschaft (BGS 414.116.3) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 August 2026 |
| `414-116-4/` | Reglement über die Übertrittsbedingungen von Schülerinnen und Schülern der Sekundarstufe I aus den Bezirken Dorneck und Thierstein in die allgemeinbildenden Schulen der Sekundarstufe II des Kantons Basel-Stadt (BGS 414.116.4) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 August 2026 |
| `414-116-22/` | Verordnung über die Aufnahme ins Regionale Gymnasium Laufental-Thierstein (BGS 414.116.22) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2015 |
| `414-116-221/` | Reglement zur Aufnahme ins Regionale Gymnasium Laufental-Thierstein (BGS 414.116.221) | 5 | as enacted, then each consolidated version: 5 June 2002 to 1 August 2026 |
| `414-118-passerelleverordnung/` | Verordnung über die Passerelle Berufsmaturität oder Fachmaturität - universitäre Hochschulen (BGS 414.118) | 5 | as enacted, then each consolidated version: 1 January 2015 to 1 November 2022 |
| `414-132-fachmittelschulverordnung/` | Verordnung über die Fachmittelschule des Kantons Solothurn (BGS 414.132) | 2 | oldest version available, then each consolidated version: 1 August 2009 to 1 August 2018 |
| `414-133/` | Promotionsreglement für die Fachmittelschule (BGS 414.133) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2021 |
| `414-134-prufungsverordnung-fur-die-abschlussprufungen-der-fachmittelschule-fms/` | Verordnung über die Erteilung des Fachmittelschulausweises an kantonalen Fachmittelschulen (BGS 414.134) | 4 | oldest version available, then each consolidated version: 1 August 2009 to 1 August 2026 |
| `414-135/` | Aufnahmereglement für die Fachmittelschule (BGS 414.135) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2026 |
| `414-151-2/` | Verordnung über Schulgelder, Gebühren und Kostenbeiträge an den Mittelschulen (BGS 414.151.2) | 4 | oldest version available, then each consolidated version: 1 August 2006 to 1 August 2018 |
| `414-441-5-promotionsreglement-maturitatsschulen/` | Reglement über Aufnahme, Zeugnisse, Promotion und Entlassung für die Maturitätsschulen des Kantons Solothurn (BGS 414.441.5) | 8 | oldest version available, then each consolidated version: 1 August 2007 to 1 August 2026 |
| `414-471-12/` | Reglement über die Fachmaturitäten (BGS 414.471.12) | 6 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `414-472/` | Reglement über die gymnasialen Maturitätsprüfungen (BGS 414.472) | 6 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `415-215-1/` | Verordnung über Schulgelder und Schulgebühren an den Höheren Fachschulen (BGS 415.215.1) | 1 | as enacted, 1 March 2011 |
| `416-112-vbb/` | Verordnung über die Berufsbildung (BGS 416.112) | 8 | as enacted, then each consolidated version: 1 January 2009 to 1 March 2023 |
| `416-112-1/` | Geschäftsreglement der Beschwerdekommission der Berufsbildung (BGS 416.112.1) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 May 2012 |
| `416-113-1/` | Reglement über die Berufsmaturität (BGS 416.113.1) | 7 | as enacted, then each consolidated version: 1 January 2014 to 1 August 2026 |
| `416-114-1-bvj-reglement/` | Reglement für das Berufsvorbereitungsjahr (BGS 416.114.1) | 2 | as enacted, then each consolidated version: 1 April 2014 to 1 August 2021 |
| `416-114-2-invol-reglement/` | Reglement für die Integrationsvorlehre (BGS 416.114.2) | 2 | as enacted, then each consolidated version: 1 December 2017 to 15 March 2025 |
| `416-142/` | Reglement über die Notengebung an den Berufsfachschulen (BGS 416.142) | 3 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2026 |
| `416-144-abu-prufungsreglement/` | Reglement über das Qualifikationsverfahren im Fach Allgemeinbildung in der beruflichen Grundbildung (BGS 416.144) | 3 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `416-145-hf-pflege/` | Studienreglement der Höheren Fachschule Pflege (BGS 416.145) | 2 | as enacted, then each consolidated version: 1 February 2015 to 1 September 2023 |
| `416-353-652/` | Verordnung über den Einsatz und die Entschädigung von Expertinnen und Experten an den Berufsmaturitätsprüfungen (BGS 416.353.652) | 1 | one version (the oldest available), 1 January 2003 |
| `419-12-stipendienverordnung/` | Vollzugsverordnung zum Gesetz über Ausbildungsbeiträge (BGS 419.12) | 4 | oldest version available, then each consolidated version: 1 August 2008 to 1 August 2022 |
| `431-115/` | Verordnung über das Kuratorium für Kulturförderung (BGS 431.115) | 2 | as enacted, then each consolidated version: 1 July 2004 to 1 April 2021 |
| `431-117/` | Verordnung über die künstlerische Ausschmückung staatlicher Bauten (BGS 431.117) | 1 | one version (the oldest available), 1 July 2004 |
| `435-141/` | Verordnung über den Natur- und Heimatschutz (BGS 435.141) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2026 |
| `435-146/` | Verordnung über den Pflanzenschutz (BGS 435.146) | 1 | one version (the oldest available), 23 February 1972 |
| `435-148-5/` | Verordnung über den Schutz der Weinbergschnecke (BGS 435.148.5) | 1 | as enacted, 12 September 1968 |
| `436-11-kulturdenkmaler-verordnung/` | Verordnung über den Schutz der historischen Kulturdenkmäler (BGS 436.11) | 1 | as enacted, 1 August 2005 |
| `511-12/` | Dienstreglement für die Kantonspolizei (BGS 511.12) | 2 | oldest version available, then each consolidated version: 1 September 2007 to 1 June 2023 |
| `511-13-poldavo/` | Verordnung über die polizeiliche Datenerhebung, -bearbeitung und –speicherung (BGS 511.13) | 2 | as enacted, then each consolidated version: 1 August 2003 to 1 January 2016 |
| `511-121-dienstaufsichtsverordnung/` | Verordnung über die Dienstaufsicht und Kontrolle der Tätigkeiten der Polizei Kanton Solothurn zur Wahrung der inneren Sicherheit (BGS 511.121) | 1 | as enacted, 1 January 2013 |
| `511-131/` | Verordnung über Privatdetektive und Sicherheitsunternehmen (BGS 511.131) | 1 | as enacted, 1 September 1991 |
| `512-11-ausweisverordnung/` | Verordnung über die Einführung des Bundesgesetzes über die Ausweise für Schweizer Staatsangehörige (BGS 512.11) | 2 | oldest version available, then each consolidated version: 1 March 2010 to 1 January 2017 |
| `512-42-ruhetagsverordnung-rtv/` | Verordnung zum Gesetz über die öffentlichen Ruhetage (BGS 512.42) | 2 | oldest version available, then each consolidated version: 1 September 2007 to 1 September 2014 |
| `512-153-ev-aig-und-asylg/` | Einführungsverordnung zum Bundesgesetz über die Ausländerinnen und Ausländer und über die Integration und zum Asylgesetz (BGS 512.153) | 3 | as enacted, then each consolidated version: 1 January 2012 to 1 September 2023 |
| `512-211/` | Verordnung über den Vollzug des eidgenössischen Waffenrechts (BGS 512.211) | 1 | one version (the oldest available), 1 November 2008 |
| `512-251-kantonale-sprengstoffverordnung/` | Vollzugsverordnung zur Bundesgesetzgebung über explosionsgefährliche Stoffe (BGS 512.251) | 1 | one version (the oldest available), 1 April 2004 |
| `521-11-vbsa/` | Verordnung über die Bewilligung von Sportschiessanlagen (BGS 521.11) | 1 | as enacted, 1 September 2020 |
| `521-931/` | Verwaltungsreglement "Winkelried-Fonds" (BGS 521.931) | 4 | as enacted, then each consolidated version: 1 January 2000 to 1 January 2016 |
| `523-11-sportverordnung/` | Verordnung über die Kantonale Sportfachstelle und die Kantonale Sportkommission (BGS 523.11) | 1 | one version (the oldest available), 1 January 2003 |
| `531-2-bzvso/` | Verordnung über den Bevölkerungsschutz und den Zivilschutz (BGS 531.2) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2018 |
| `613-31/` | Vollzugsverordnung zum Bundesgesetz über die direkte Bundessteuer (BGS 613.31) | 3 | oldest version available, then each consolidated version: 1 February 2011 to 1 April 2026 |
| `613-41/` | Vollzugsverordnung zum Bundesgesetz über die Verrechnungssteuer (BGS 613.41) | 2 | oldest version available, then each consolidated version: 1 January 2006 to 1 April 2026 |
| `614-12/` | Vollzugsverordnung zum Gesetz über die Staats- und Gemeindesteuern (BGS 614.12) | 11 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2026 |
| `614-14/` | Verordnung über das Abrechnungsverfahren beim Einheitsbezug von Staats- und Gemeindesteuern (BGS 614.14) | 2 | oldest version available, then each consolidated version: 1 January 2001 to 1 January 2020 |
| `614-72-hundeverordnung/` | Verordnung zum Gesetz über das Halten von Hunden (BGS 614.72) | 3 | as enacted, then each consolidated version: 1 August 2007 to 1 June 2026 |
| `614-136/` | Verordnung über die Entschädigung der Staatssteuerregisterführer und Staatssteuerregisterführerinnen (BGS 614.136) | 1 | one version (the oldest available), 1 January 2008 |
| `614-159-01/` | Steuerverordnung Nr. 1: Organisation des kantonalen Steuerwesens für die Veranlagung der Haupt- und Nebensteuern des Staates und der direkten Bundessteuer (BGS 614.159.01) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 April 2026 |
| `614-159-02/` | Steuerverordnung Nr. 2: Organisation des kantonalen Steuerwesens für die Veranlagung der Grundstückgewinnsteuer (BGS 614.159.02) | 3 | oldest version available, then each consolidated version: 1 January 2004 to 1 April 2026 |
| `614-159-03/` | Steuerverordnung Nr. 3: Erhebung der Quellensteuer (BGS 614.159.03) | 6 | oldest version available, then each consolidated version: 1 January 2004 to 1 January 2025 |
| `614-159-04/` | Steuerverordnung Nr. 4: Organisation des kantonalen Steuerwesens für die Veranlagung der Nebensteuern (Handänderungssteuer, Nachlasstaxe, Erbschafts- und Schenkungssteuer) (BGS 614.159.04) | 3 | oldest version available, then each consolidated version: 1 January 1998 to 1 April 2026 |
| `614-159-05/` | Steuerverordnung Nr. 5: Organisation des Steuerbezuges für die Haupt- und Nebensteuern des Staates (BGS 614.159.05) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `614-159-06/` | Steuerverordnung Nr. 6: Meldewesen und Amtshilfe im Steuerverfahren (BGS 614.159.06) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `614-159-07/` | Steuerverordnung Nr. 7: Auskünfte aus Steuerakten und Herausgabe von Steuerakten an Verwaltungsbehörden und Gerichte (BGS 614.159.07) | 6 | oldest version available, then each consolidated version: 1 February 2011 to 1 April 2026 |
| `614-159-08/` | Steuerverordnung Nr. 8: Auskünfte aus dem Steuerregister (BGS 614.159.08) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 April 2026 |
| `614-159-10/` | Steuerverordnung Nr. 10 über Bezug, Fälligkeit und Verzinsung der Haupt- und Nebensteuern (BGS 614.159.10) | 4 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2024 |
| `614-159-11/` | Steuerverordnung Nr. 11: Zahlungserleichterungen, Erlass und Abschreibungen (BGS 614.159.11) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 April 2026 |
| `614-159-12/` | Steuerverordnung Nr. 12: Berufliche Vorsorge (BGS 614.159.12) | 1 | one version (the oldest available), 1 January 2001 |
| `614-159-13/` | Steuerverordnung Nr. 13: Abzüge für Berufskosten (BGS 614.159.13) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `614-159-15/` | Steuerverordnung Nr. 15: Bemessung des Mietwertes der eigenen Wohnung (BGS 614.159.15) | 6 | oldest version available, then each consolidated version: 1 January 2007 to 1 April 2026 |
| `614-159-16/` | Steuerverordnung Nr. 16: Unterhalts-, Betriebs- und Verwaltungskosten von Liegenschaften im Privatvermögen (BGS 614.159.16) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `614-159-18/` | Steuerverordnung Nr. 18: Besteuerung nach dem Aufwand (BGS 614.159.18) | 2 | oldest version available, then each consolidated version: 1 January 2001 to 1 January 2016 |
| `614-159-20/` | Steuerverordnung Nr. 20: Anpassung von Tarifstufen, allgemeinen Abzügen und Sozialabzügen an die Teuerung (BGS 614.159.20) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `614-159-21/` | Steuerverordnung Nr. 21: Elektronisches Einreichen der Steuererklärung (BGS 614.159.21) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 April 2025 |
| `614-159-22/` | Steuerverordnung Nr. 22: Elektronische Zustellung von Verfügungen und Rechnungen (BGS 614.159.22) | 2 | as enacted, then each consolidated version: 1 August 2021 to 1 January 2025 |
| `614-159-23/` | Steuerverordnung Nr. 23: Einheitsbezug (BGS 614.159.23) | 3 | as enacted, then each consolidated version: 1 September 2022 to 1 January 2028 |
| `614-159-24/` | Steuerverordnung Nr. 24: Algorithmische Systeme (BGS 614.159.24) | 2 | as enacted, then each consolidated version: 1 January 2025 to 1 April 2026 |
| `614-175-1/` | Verordnung über die pauschale Steueranrechnung für den Kanton Solothurn (BGS 614.175.1) | 1 | as enacted, 1 September 1967 |
| `614-175-51/` | Vollzugsverordnung zum Bundesratsbeschluss über den zusätzlichen Steuerrückbehalt USA (BGS 614.175.51) | 1 | as enacted, 1 August 1952 |
| `614-175-611/` | Verordnung zur Vereinbarung zwischen der Schweiz und Frankreich über die Besteuerung der Erwerbseinkünfte von Grenzgängern (BGS 614.175.611) | 2 | as enacted, then each consolidated version: 1 December 2011 to 1 April 2026 |
| `618-56-beitragsreglement-pravention/` | Reglement über die Beiträge an den Brandschutz und die Elementarschadenprävention (BGS 618.56) | 1 | as enacted, 1 October 2025 |
| `618-112-gebaudeversicherungsverordnung-gvv/` | Vollzugsverordnung zum Gesetz über die Gebäudeversicherung, den Brandschutz und die Elementarschadenprävention, die Feuerwehr und den Elementarschadenfonds (BGS 618.112) | 4 | oldest version available, then each consolidated version: 1 January 2008 to 1 April 2025 |
| `618-112-24-schatzungsreglement/` | Reglement über die Schätzung von Versicherungswert und Schäden (BGS 618.112.24) | 1 | as enacted, 1 October 2025 |
| `618-114/` | Verordnung über die Entschädigung des Verwaltungsrates der Solothurnischen Gebäudeversicherung (BGS 618.114) | 1 | as enacted, 1 April 2025 |
| `618-517-feuerwehrwesen-reglement/` | Reglement betreffend Feuerwehren und Löschwasserversorgung (BGS 618.517) | 1 | as enacted, 1 October 2025 |
| `625-12-fivo/` | Fischereiverordnung (BGS 625.12) | 4 | oldest version available, then each consolidated version: 1 February 2010 to 1 March 2026 |
| `626-12-jav/` | Jagdverordnung (BGS 626.12) | 3 | oldest version available, then each consolidated version: 1 August 2006 to 1 January 2018 |
| `626-15-japv/` | Jagdprüfungsverordnung (BGS 626.15) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2022 |
| `711-15-vvk/` | Verordnung über Verfahrenskoordination und Umweltverträglichkeitsprüfung (BGS 711.15) | 3 | oldest version available, then each consolidated version: 1 July 2002 to 1 March 2020 |
| `711-25/` | Verordnung über Staatsbeiträge an die Kosten der Orts- und Regionalplanung (BGS 711.25) | 1 | one version (the oldest available), 1 January 1997 |
| `711-31/` | Verordnung über Baulandumlegung und Grenzbereinigung (BGS 711.31) | 1 | as enacted, 1 July 1979 |
| `711-41-gbv/` | Kantonale Verordnung über Grundeigentümerbeiträge und -gebühren (BGS 711.41) | 3 | oldest version available, then each consolidated version: 1 September 2010 to 1 March 2013 |
| `711-61-kbv/` | Kantonale Bauverordnung (BGS 711.61) | 6 | oldest version available, then each consolidated version: 1 January 2008 to 1 October 2024 |
| `711-65-v-elbau/` | Verordnung über das elektronische Baugesuchsverfahren (BGS 711.65) | 1 | as enacted, 1 October 2024 |
| `711-271-geoiv/` | Geoinformationsverordnung (BGS 711.271) | 2 | as enacted, then each consolidated version: 1 March 2016 to 1 March 2020 |
| `711-515/` | Verordnung über den Schutz von Fossilien und Mineralien (BGS 711.515) | 1 | as enacted, 23 November 1989 |
| `712-16-vwba/` | Verordnung über Wasser, Boden und Abfall (BGS 712.16) | 3 | as enacted, then each consolidated version: 1 October 2010 to 1 November 2018 |
| `712-922/` | Verordnung über den kantonalen Schadendienst (BGS 712.922) | 2 | as enacted, then each consolidated version: 1 November 2000 to 1 January 2014 |
| `721-55-subv/` | Submissionsverordnung (BGS 721.55) | 3 | oldest version available, then each consolidated version: 1 January 2005 to 1 July 2022 |
| `725-112-kantonsstrassen-beitragsverordnung/` | Verordnung über die Festsetzung der Beiträge der Einwohnergemeinden an den Bau von Kantonsstrassen (BGS 725.112) | 1 | as enacted, 1 January 2003 |
| `725-126/` | Verordnung über den Unterhalt und den Ausbau von Strassen im Berggebiet sowie von einfachen Parkplätzen im Erholungsgebiet aus den zweckgebundenen Mitteln der Motorfahrzeugsteuer (BGS 725.126) | 1 | one version (the oldest available), 24 May 1984 |
| `732-11-ovv/` | Verordnung über den öffentlichen Verkehr (BGS 732.11) | 1 | as enacted, 1 January 2023 |
| `733-11/` | Verordnung über den Strassenverkehr (BGS 733.11) | 4 | oldest version available, then each consolidated version: 1 January 1997 to 1 April 2014 |
| `736-12/` | Verordnung über die Schifffahrt (BGS 736.12) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 March 2018 |
| `737-1/` | Verordnung über die Einführung des Bundesgesetzes über die Luftfahrt (Luftfahrtsgesetz) (BGS 737.1) | 1 | one version (the oldest available), 13 December 1979 |
| `739-1/` | Verordnung über Rohrleitungsanlagen (BGS 739.1) | 1 | one version (the oldest available), 1 January 1982 |
| `811-12-gesv/` | Vollzugsverordnung zum Gesundheitsgesetz (BGS 811.12) | 9 | oldest version available, then each consolidated version: 1 July 2007 to 1 April 2026 |
| `811-13/` | Verordnung über die Amteiärzte und Amteiärztinnen sowie die Infektionsärzte und Infektionsärztinnen (BGS 811.13) | 5 | as enacted, then each consolidated version: 1 October 2004 to 1 October 2023 |
| `811-14/` | Verordnung zum Schutz vor Passivrauchen (BGS 811.14) | 2 | oldest version available, then each consolidated version: 1 May 2010 to 1 September 2019 |
| `811-16-kantonale-epidemienverordnung-v-epg/` | Verordnung über den Vollzug der eidgenössischen Epidemiengesetzgebung (BGS 811.16) | 5 | as enacted, then each consolidated version: 1 September 2019 to 1 January 2024 |
| `811-18-v-eg-ausbildungsfordergesetz-pflege/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (BGS 811.18) | 2 | as enacted, then each consolidated version: 1 July 2024 to 1 April 2026 |
| `811-19-aus-und-weiterbildungsverpflichtungsverordnung-gesundheitsberufe/` | Verordnung über die Aus- und Weiterbildung in nicht-universitären Gesundheitsberufen (BGS 811.19) | 1 | as enacted, 1 April 2026 |
| `811-121-zulassungsverordnung-zulav/` | Verordnung über die Zulassung von Leistungserbringern im ambulanten Bereich zur Tätigkeit zulasten der obligatorischen Krankenpflegeversicherung (BGS 811.121) | 1 | as enacted, 1 December 2024 |
| `811-422-4/` | Verordnung über den Lohn und die Entschädigung der Studierenden der höheren Berufsbildung (Diplompflege HF) bei der Solothurner Spitäler AG (BGS 811.422.4) | 2 | as enacted, then each consolidated version: 1 September 2011 to 1 July 2024 |
| `812-2-biosv/` | Biosicherheitsverordnung (BGS 812.2) | 1 | as enacted, 1 March 2020 |
| `812-41-lrv-so/` | Luftreinhalte-Verordnung (BGS 812.41) | 2 | oldest version available, then each consolidated version: 1 September 2008 to 1 July 2018 |
| `812-53/` | Verordnung über die Lagerung und Beseitigung von ausgedienten Fahrzeugen (BGS 812.53) | 1 | as enacted, 1 January 1994 |
| `812-55/` | Verordnung über den Vollzug der eidgenössischen Störfallverordnung (BGS 812.55) | 1 | as enacted, 1 November 1999 |
| `812-56-chemikalienverordnung-chemv-so/` | Verordnung über den Vollzug der Eidgenössischen Chemikaliengesetzgebung, der Dünger-Verordnung und der Pflanzenschutzmittelverordnung (BGS 812.56) | 1 | as enacted, 1 January 2010 |
| `812-61-lsv-so/` | Lärmschutz-Verordnung des Kantons Solothurn (BGS 812.61) | 1 | as enacted, 1 September 2002 |
| `812-72/` | Vollzugsverordnung zur Verordnung des Schweizerischen Bundesrates über den Strahlenschutz (BGS 812.72) | 1 | as enacted, 2 November 1978 |
| `813-14-heilmittel-und-betaubungsmittelverordnung-hbv/` | Verordnung über die Heilmittel und die Betäubungsmittel (BGS 813.14) | 2 | as enacted, then each consolidated version: 1 September 2019 to 1 October 2023 |
| `817-116-spivo/` | Verordnung über die Spitalliste (BGS 817.116) | 8 | as enacted, then each consolidated version: 1 January 2012 to 1 April 2026 |
| `821-51/` | Verordnung zur Einführung des Gleichstellungsgesetzes (BGS 821.51) | 1 | one version (the oldest available), 1 January 2011 |
| `831-2-sv/` | Sozialverordnung (BGS 831.2) | 19 | oldest version available, then each consolidated version: 1 April 2010 to 1 April 2026 |
| `831-3-rkel/` | Reglement über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (BGS 831.3) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 21 August 2020 |
| `832-15-aup/` | Verordnung über die Akut- und Übergangspflege (BGS 832.15) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 October 2012 |
| `832-214/` | Reglement über die Prämienverbilligung in Härtefällen (BGS 832.214) | 1 | as enacted, 1 January 2001 |
| `832-215/` | Reglement über die Prämienverbilligung für Personen, die an der Quelle besteuert werden (BGS 832.215) | 1 | as enacted, 1 June 2002 |
| `837-531/` | Verwaltungsreglement Adolf-Schläfli-Fonds (BGS 837.531) | 3 | oldest version available, then each consolidated version: 1 July 2001 to 1 January 2016 |
| `837-532/` | Verwaltungsreglement Olga Ziegler-Fonds (BGS 837.532) | 3 | as enacted, then each consolidated version: 1 January 2004 to 1 January 2016 |
| `837-533/` | Verwaltungsreglement Verwendung Alkoholzehntel (BGS 837.533) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 October 2023 |
| `837-534/` | Verwaltungsreglement über den kantonalen Fonds für die Prävention und Bekämpfung der Spielsucht (BGS 837.534) | 1 | as enacted, 1 September 2009 |
| `837-535/` | Verwaltungsreglement Max-Müller-Fonds (BGS 837.535) | 3 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2016 |
| `837-536-2-slfv/` | Verordnung über die Swisslos-Fonds (BGS 837.536.2) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2025 |
| `921-12-alv/` | Allgemeine Landwirtschaftsverordnung (BGS 921.12) | 2 | oldest version available, then each consolidated version: 1 January 2006 to 1 January 2022 |
| `922-15/` | Verordnung über die Entschädigung der Kantonalen Schätzungsstelle für die Schätzung des landwirtschaftlichen Ertragswertes (BGS 922.15) | 2 | oldest version available, then each consolidated version: 1 September 2007 to 1 September 2015 |
| `923-12-bodenverbesserungsverordnung-bovo/` | Verordnung über die Bodenverbesserungen in der Landwirtschaft (BGS 923.12) | 1 | one version (the oldest available), 1 January 2006 |
| `924-12/` | Verordnung über Investitionshilfen in der Landwirtschaft (IHV) (BGS 924.12) | 2 | oldest version available, then each consolidated version: 1 January 2006 to 1 January 2021 |
| `925-12-vlb/` | Verordnung über die land- und hauswirtschaftliche Aus- und Weiterbildung (BGS 925.12) | 2 | oldest version available, then each consolidated version: 1 September 2007 to 1 November 2013 |
| `926-712-vhtss/` | Verordnung über die Honorare und Entschädigungen im Bereich Tierseuchen und Tierschutz (BGS 926.712) | 1 | one version (the oldest available), 1 November 2005 |
| `926-712-1/` | Verordnung über die Festsetzung der Tierhalterbeiträge für die kantonale Tierseuchenkasse (BGS 926.712.1) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 April 2026 |
| `931-12-wavso/` | Waldverordnung (BGS 931.12) | 3 | oldest version available, then each consolidated version: 1 August 2008 to 1 January 2025 |
| `931-72/` | Verordnung über Waldfeststellung und Waldabstand (BGS 931.72) | 1 | one version (the oldest available), 1 January 1997 |
| `940-12-vwag/` | Verordnung zum Wirtschafts- und Arbeitsgesetz (BGS 940.12) | 3 | as enacted, then each consolidated version: 1 January 2016 to 1 September 2026 |
| `941-22-envso/` | Verordnung zum Energiegesetz (BGS 941.22) | 1 | as enacted, 1 January 2011 |
| `941-24-engvb/` | Verordnung zum Energiegesetz über Staatsbeiträge (BGS 941.24) | 5 | as enacted, then each consolidated version: 1 July 1993 to 1 January 2025 |
| `941-25-stromvg/` | Einführungsverordnung zum Bundesgesetz über die Stromversorgung (BGS 941.25) | 1 | as enacted, 1 July 2010 |
| `941-26/` | Einführungsverordnung zum Bundesgesetz über dringliche Massnahmen zur kurzfristigen Bereitstellung einer sicheren Stromversorgung im Winter (BGS 941.26) | 1 | as enacted, 1 January 2023 |

## Source

The BGS (systematic collection) of the canton, published by the canton at <https://bgs.so.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (GS). Annexes the collection publishes only as separate PDF files are not included.

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

The author of a commit is the amending act, named by its entry in the chronological collection (GS), with an e-mail address that cannot exist (`<act key>@bgs.so.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
