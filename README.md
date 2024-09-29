## Spotify-Datenanalyse 2023

## Datenquelle

Die Daten stammen aus einem öffentlichen Datensatz über die am häufigsten gestreamten Songs auf Spotify im Jahr 2023. Sie enthalten Informationen über die Anzahl der Streams, die BPM, die Tanzbarkeit, die Positivität und viele weitere musikalische Eigenschaften.
## Projektübersicht

Dieses Projekt analysiert den **"Most Streamed Spotify Songs 2023"**-Datensatz, der Informationen über die am häufigsten gestreamten Songs auf Spotify enthält. Ziel ist es, Einblicke in die musikalischen Eigenschaften und die Popularität von Künstlern und Songs zu gewinnen. Dabei wurden verschiedene Fragestellungen bearbeitet, die mit statistischen Methoden und Datenvisualisierungen beantwortet wurden.

## Aufgabenstellung

Die Analyse konzentriert sich auf die Beantwortung folgender Fragen:

1. **Welche 10 Artists haben die höchste Anzahl an Songs im Datensatz?**
2. **Wie verteilen sich die Songs nach ihren BPM-Werten? Welche Anzahl an BPM ist im Datensatz am häufigsten vertreten?**
3. **Welche Songs haben die höchste Tanzbarkeit (Danceability) und welcher Tanzbarkeitsgrad tritt am häufigsten auf? Wie fällt die Tanzbarkeit unter den 10 meistgestreamten Artists aus?**
4. **Wie unterscheiden sich der Anteil an gesprochenen Worten (Speechiness) zwischen älteren und neueren Songs?**
5. **Was sind die 10 Songs mit der höchsten Positivität (Valence)?**
6. **Wie korrelieren die Anzahl der Streams mit musikalischen Eigenschaften wie Tanzbarkeit (Danceability), Positivität (Valence), und weiteren?**

## Zusammenfassung der Ergebnisse

### 1. **Top 10 Artists mit den meisten Songs:**
   - Durch Gruppierung nach Artists wurde festgestellt, welche 10 Artists die meisten Songs im Datensatz haben.

![image](https://github.com/user-attachments/assets/fee339e3-33dd-442c-b22e-782ac3942cef)

### 2. **Verteilung der Songs nach BPM:**
   - Die Songs wurden nach ihrer BPM (Beats per Minute) aufgeschlüsselt, um die am häufigsten vertretenen BPM-Werte im Datensatz zu ermitteln.
   - Der BPM-Wert, der am häufigsten im Datensatz vorkommt, liegt zwischen **120 und 130 BPM**, was typisch für viele Pop- und Dance-Songs ist.

![image](https://github.com/user-attachments/assets/280009af-7cf3-48c6-a337-3174e90414ac)

### 3. **Verteilung der Tanzbarkeit, Tanzbarkeit der meist gestreamten Artists und Titel mit der höchsten Tanzbarkeit**
   - Ein Großteil der Songs zeigen einen 70%igen Anteil der Tanzbarkeit.

![image](https://github.com/user-attachments/assets/f825298f-b2c9-44d9-9b84-261c0fd86b35)
     
   - Die Tanzbarkeit unter den top 10 gestreamten Artists ist erstaunlich divers. Während Eminem einen durchschnittlichen Anteil von ca. 80% aufweist liegt der durchschnittliche Anteil der Tanzbarkeit von Olivia Rodrigo's Songs bei rd. 51,5%.

![image](https://github.com/user-attachments/assets/83180dba-c5c8-43d8-8101-1f339e7c0ee7)

- Die höchste Tanzbarkeit weist der Song 'Peru' mit 96% auf.

![image](https://github.com/user-attachments/assets/fd335e50-67b7-4b75-a56a-d28e7e720a58)

### 4. **Unterschiede im Anteil gesprochener Worte zwischen älteren und neueren Songs:**
   - Durch die Analyse von "Speechiness" über die Jahre hinweg wurde gezeigt, dass der Anteil an gesprochenen Worten in Songs mit den Jahren leicht gestiegen ist.

![image](https://github.com/user-attachments/assets/47896c85-b4d6-449f-82ca-c5163f0bd979)

### 5. **Top 10 Songs mit der höchsten Positivität (Valence):**
   - Die 10 Songs mit der höchsten Positivität wurden identifiziert und in einem Balkendiagramm dargestellt. Diese Songs haben eine Valence von über **90%**, was auf eine sehr positive und fröhliche Stimmung hinweist.

![image](https://github.com/user-attachments/assets/078cf655-c486-4ccf-b3b3-da2d6a29baba)

### 6. **Korrelation zwischen Streams und musikalischen Eigenschaften:**
   - Es wurden Korrelationen zwischen der Anzahl der Streams und verschiedenen musikalischen Eigenschaften wie Tanzbarkeit (Danceability), Positivität (Valence) und Energie (Energy) berechnet. Eine Korrelationstabelle und eine Heatmap visualisieren die Ergebnisse. Die stärkste positive Korrelation wurde zwischen Tanzbarkeit und Positivität gefunden, während die Anzahl der Streams nur eine schwache Korrelation mit diesen Eigenschaften aufwies.

![image](https://github.com/user-attachments/assets/67deb6d8-4954-4cf0-8153-b05410247121)

## Visualisierungen

Das Projekt enthält mehrere Visualisierungen, darunter:
- Balkendiagramme für die Anzahl der Songs und Streams der Künstler.
- Histogramme für die Verteilung der BPM-Werte und der Tanzbarkeit.
- Scatterplots, die den Anteil gesprochener Worte und die Korrelationen zwischen den musikalischen Eigenschaften darstellen.

## Fazit

Diese Analyse liefert interessante Einblicke in die Musik, die im Jahr 2023 auf Spotify beliebt war, und zeigt, wie sich musikalische Eigenschaften auf die Anzahl der Streams auswirken. Dabei gibt es sowohl erwartete Zusammenhänge, wie eine positive Korrelation zwischen Tanzbarkeit und Positivität, als auch unerwartete, wie die geringe Korrelation zwischen Streams und anderen musikalischen Merkmalen. Diese Korrelationen könnten in einer weiteren Analyse weiter erforscht werden.

