---
title: Redesign Web Frontend der Veranstaltungsübersicht am Campus Gummersbach
    - Neva Kizilaslan
    - Cihan Eryetli
    - Bünyamin Ersoy
teaserimage: Nietzschmann-Ak-teaser.webp
gallery: 
    - Nietzschmann-Ak-desktop-startseite.webp
    - Nietzschmann-Ak-desktop-ButtonStartseite.webp
    - Nietzschmann-Ak-desktop-HellmodusStartseite.webp
    - Nietzschmann-Ak-desktop-LucasCranach.webp
    - Nietzschmann-Ak-desktop-Forschung.webp
    - Nietzschmann-Ak-desktop-Partner.webp
    - Nietzschmann-Ak-tablet-startseite.webp
    - Nietzschmann-Ak-mobileStartseite.webp
---
Kurzdokumentation: Redesign der Veranstaltungsübersicht an der Fakultät 10
Das Redesign der Veranstaltungsübersicht für die Fakultät 10 der TH Köln war für uns weit mehr als ein reines optisches Facelift. Das bisherige System glich eher einer starren, administrativen Datenbankabfrage: Wer fünf Minuten vor der Vorlesung seinen Raum auf dem Smartphone suchte, musste sich mühsam durch sechs verschachtelte Dropdown-Menüs kämpfen. Unser zentrales Ziel in diesem Projekt war es, diese tägliche Frustration aufzulösen. Wir wollten ein Interface schaffen, das den echten Campus-Alltag versteht und unterstützt – zugänglich, reaktionsschnell und absolut nutzerzentriert.
Was das Projekt ausmacht
Was diesen Entwurf im Kern besonders macht, ist die drastische Reduktion der kognitiven Last sowie die hohe persönliche Anpassbarkeit. Statt die Nutzer:innen zu zwingen, die interne Organisationsstruktur der Hochschule auswendig zu kennen, nutzen sie in unserer Lösung eine intelligente, zentrale Suche („Smart Search“) kombiniert mit interaktiven Filter-Pills.
Das absolute Herzstück unseres Konzepts ist dabei die neue Pin-Funktion: Mit einem einzigen Klick lässt sich der individuelle Studiengang dauerhaft speichern. Beim nächsten Öffnen der Seite entfällt jeder Suchaufwand – der persönliche Stundenplan ist sofort da.
Darüber hinaus zeichnet sich das Projekt durch seine technische Tiefe aus. Um das Nutzungserlebnis so realitätsnah wie möglich zu gestalten und die Forderung nach einem responsiven Browser-Erlebnis optimal zu erfüllen, haben wir das Konzept nicht als einfache Klickstrecke in einem Design-Tool belassen. Stattdessen haben wir einen voll funktionalen HTML/CSS-Prototypen programmiert. Dieser nutzt native Web-Standards und integriert Features wie den optionalen Dark Mode performant und nahtlos direkt im Browser.
Wie wir vorgegangen sind
Um zu diesem Ergebnis zu gelangen, sind wir konsequent den Phasen des nutzerzentrierten Designs gefolgt. Jeder gestalterischen Entscheidung ging eine klare Problemanalyse voraus.
1. Verstehen & Definieren
Zunächst haben wir die stark abweichenden Bedürfnisse der Zielgruppen analysiert. Studierende nutzen das System meist mobil, „on the go“ und unter Zeitdruck. Sie brauchen extrem schnelle Antworten („Wo muss ich jetzt hin?“). Lehrende und Mitarbeitende der Verwaltung sitzen hingegen meist am Desktop-Monitor und benötigen eine verlässliche Übersicht für die langfristige Semester- und Ressourcenplanung. Diese Erkenntnisse waren unser Kompass für die gesamte Gestaltung.
2. Ideenfindung & Konzept
Uns wurde schnell klar, dass ein einziges, starres Layout diesen diversen Anforderungen nicht gerecht wird. Daher haben wir die Ansichten kontextbasiert getrennt:
Für die mobile Tagesansicht der Studierenden haben wir ein scannbares Card-Design entwickelt. Die aktuell laufende Veranstaltung springt durch das primäre TH-Orange sofort ins Auge.
Um unübersichtliche Wahltermine – etwa bei parallelen Praktika – zu bändigen, wurde ein intuitiver Auswahlmechanismus konzipiert: Ein Klick fixiert den Wunschtermin, während Alternativen über eine reduzierte CSS-Deckkraft optisch in den Hintergrund treten. Der Stundenplan räumt sich sozusagen von selbst auf.
Für die Raumübersicht am Desktop setzen wir auf ein tabellarisches Grid. Durch großzügigen „White Space“ werden Leerzeiten als visuelle Heatmap erkennbar, was die Planung enorm erleichtert.
3. Ausarbeitung & Prototyping
Die finale Ausarbeitung erfolgte direkt im Code. Mit modularen HTML-Strukturen und modernem CSS (Flexbox, CSS Grid, Media Queries) reagiert das Design fließend auf Smartphone, Tablet und Desktop. Ein sehr großes Augenmerk lag auf der Barrierefreiheit: Alle Farben und Typografien wurden nach den Design-Vorgaben der TH Köln so abgestimmt, dass sie hohe WCAG-Kontrastwerte erfüllen und die digitale Teilhabe sichern. Die clevere Nutzung von CSS Custom Properties ermöglichte uns zudem die effiziente Umsetzung des Dark Modes.
Fazit
So ist am Ende ein Frontend entstanden, das lästige Klickwege abschafft, technische Komplexität verbirgt und den Fokus wieder auf das lenkt, was wirklich zählt: einen produktiven und stressfreien Studien- und Lehralltag am Campus Gummersbach.
