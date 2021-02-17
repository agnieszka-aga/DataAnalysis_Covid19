<b> DataAnalysis_Covid19 </b> <br>
Data Analysis of JHU CSSE COVID-19 Data with Python <br>
Raw data: https://github.com/CSSEGISandData/COVID-19

-> German version below

This is my very first more complex coding project. 
The topic is unfortunately not the most interesting but I really had motivation to analyze Covid-19 data: 
The goal was to calculate the incidence rates (7-days sum / 100000 inhabitants) for all countries and represent them graphically (on the map) to get better overview and to check which role the incidence rate really plays when countries are put on the RKI list of risk regions. Finally, it became more than that.

The project consists of four files:
1) Data Preparation Part 1 - Raw dataset cleansing and preparation for further steps - pandas & numpy
2) Data Preparation Part 2 - Preparation of additional datasets (population, coordinates) - pandas & numpy
3) Data Preparation Part 2A / Population Web Scrap - web scraping of population data from 2020 - request & beautifulsoup
4) Data Visualization - data visualization and analysis (choropleth maps, (interactive) scatter and box plots)- pandas, numpy, plotly, folium, ipywidgets & json -> Choropleth maps  are not displayed correctly here (in nbviewer) - I'm working on it...

Since the raw datasets are updated daily, it would make more sense to perform all / most of steps in a single function because now it is necessary to go through all files and update each cleaned/prepared dataset as well as plots / maps manually. That could be the next step.

-> Deutsche Version

Das ist mein allererstes Programmierprojekt.
Das Thema ist leider nicht das Interessanteste, aber es gab einen Grund, warum ich den Covid-19-Datensatz doch analysieren wollte:
Das Ziel war es, die Inzidenzwerte für alle Länder zu berechnen und diese dann graphisch auf einer Karte darzustellen, um einen besseren Überblick zu bekommen und um zu prüfen, welche Rolle die Inzidenzwerte bei der Einstufung der Länder als Risikogebiete (RKI Liste) spielen. Es ist aber etwas mehr als das geworden.

Das Projekt besteht aus vier Dateien:
1) Data Preparation Part 1 - Bereinigung und Aufbereitung der Rohdaten für die weiteren Bearbeitungsschritte - pandas & numpy
2) Data Preparation Part 2 - Aufbereitung zusätzlicher Datensätze (Bevölkerung, Koordinaten) - pandas & numpy
3) Data Preparation Part 2A / Population Web Scrap - Web Scraping von aktuellen (2020) Einwohnerzahlen - request & beautifulsoup
4) Data Visualization - Datenvisualisierung und -analyse (Choroplethenkarten, (interaktive) Punkt- und Säulendiagramme) -  pandas, numpy, plotly, folium, ipywidgets & json -> Die Choroplethenkarten werden hier (in nbviewer) nicht korrekt angezeigt. Ich arbeite dran...

Da die Rohdaten täglich aktualisiert werden, wäre es eigentlich sinnvoller, alle / die meisten Schritte in einer Funktion auszuführen. Jetzt muss man alle Dateien und Diagramme/Karten manuell aktualisieren, was relativ umständlich ist. Die Automatisierung aller Schritte könnte der nächste Schritt sein.
