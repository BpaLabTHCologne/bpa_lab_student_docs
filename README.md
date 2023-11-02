# Einführung in das BPA-Lab 
Diese Dokumentation soll dazu dienen, dass Studierende des Studiengangs „Wirtschaftsinformatik“, die das Modul „Business Engineering“ absolvieren möchten, alle notwendigen Informationen haben, damit sie den Fischertechnik-Lagerroboter des BPA-Labs in ihrem Prozessautomatisierungsprojekt mit der Camunda 8 Cloud Plattform einsetzen können.

## Motivation und Idee des BPA-Labs
Das Business Process Automation Labor (BPA-Lab) soll mehrere Anwendungsgebiete unterstützen und fördern. 
Einerseits soll es der Forschung dienen und zum anderen als Lehr- und Lernumgebung für Studierende und
Lehrende verwendet werden.
Im Bereich der Forschung konzentriert sich das BPA-Lab auf die Untersuchung von Methoden, Techniken und Werkzeugen 
zur Automatisierung sowie auf die Analyse von Geschäftsprozessen, wobei der Fokus insbesondere auf den Anwendungsfeldern
Produktion und Logistik liegt. Im Bereich der Lehre soll das BPA-Lab als Lernfabrik fungieren, 
um Studierenden praxisnahe Anwendungsszenarien zu bieten, in denen sie
ihr theoretisches Wissen in der Geschäftsprozessautomatisierung einsetzen und
erweitern können. Neben der Automatisierung und Analyse spielt auch die Prozessmodellierung eine wichtige Rolle, 
um ein ganzheitliches Verständnis der zugrunde liegenden Prozesse zu erlangen.


## Integrierbare Hardware- und Softwarekomponenten

### Hochregal-Lagerroboter
Der Lagerroboter ist ein Produkt von [Fischertechnik](https://www.fischertechnik.de/de-de), das aus einem Baukasten konstruiert wurde. Der Roboter hat einen Greifarm, der sich mithilfe eines Motors horizontal und vertikal bewegen kann. Neben dem Greifarm gibt es ein Hochregal mit sechs Lagerplätzen, die der Greifarm ansteuern und einen Gegenstand in diese einlagern oder auslagern kann. In diesem Modell werden abgerundete Bausteine von Fischertechnik als Gegenstände genutzt.

![image](https://github.com/BpaLabTHCologne/bpa_lab_student_docs/assets/134142150/7e61d157-bf0b-4016-b8e8-1d36cd364fae)

Im Repository [bpa_lab_warehouse_operations](https://github.com/BpaLabTHCologne/bpa_lab_warehouse_operations) findet man die Implementierung und Dokumentation einer Prozessapplikation, die die Funktionalitäten des Lagerroboters veranschaulicht.

***

### Openroute Service API
Der Openroute Service bietet verschieden Dienste auf Basis von OpenStreetMap-Daten (OSM-Daten) an. Diese OSM-Daten sind frei verfügbare Geodaten, auf die über eine öffentlich zugängliche Datenbank zugegriffen werden kann.

![image](https://github.com/BpaLabTHCologne/bpa_lab_student_docs/assets/134142150/bad57994-b9c7-4343-aad0-69c6ea2d077f)

In einer beispielhaften Prozessapplikation ([bpa_lab_openroute_service_api](https://github.com/BpaLabTHCologne/bpa_lab_openroute_service_API)) wurden die Funktionen zur Routenplanung der Schnittstelle von Openroute Service implementiert. Zudem wird anhand des Beispielprozesses und der Openroute Serivce REST API erläutert, wie eine [REST Connector Task](https://docs.camunda.io/docs/components/connectors/protocol/rest/) in Camunda 8 implementiert werden kann.


## Weiterführende Informationen
Sollte tiefers Interesse in das BPA-Lab bestehen, finden Sie genauere Informationen in dem Repository [bpa_lab_docs](https://github.com/BpaLabTHCologne/bpa_lab_docs). Dort finden Sie Inhalte zu dem Aufbau der GitHub Organisation, den enthaltenen Repositories, einen Überblick über die gesamte Architektur des BPA-Labs und einen Vorstellung der Lernfabrik 4.0, die zu Demonstrationszwecken genutzt wird.
