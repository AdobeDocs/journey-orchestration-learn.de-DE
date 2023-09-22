---
title: Informationen zu Journey Orchestration
description: Machen Sie sich mit dem Konzept, den unterstützten Anwendungsfällen und der Funktionsweise von Journey Orchestration vertraut.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 99%

---

# Informationen zu [!UICONTROL Journey Orchestration]

Mit [!UICONTROL Journey Orchestration] können Sie Anwendungsfälle für die Echtzeit-Orchestrierung erstellen, indem Sie kontextuelle, in Ereignissen oder Datenquellen gespeicherte Daten nutzen.

## Einführung in [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] ist ein in Adobe Experience Platform integrierter Anwendungsdienst. Er bietet ein intelligentes und offenes Ökosystem, um alle relevanten Live-Daten über skalierbare, auf Ereignissen basierende Interaktionen kanalübergreifend zu aktivieren – vom Marketing über den Betrieb bis hin zum Service. [!UICONTROL Journey Orchestration] kann sämtliche Daten aus Adobe Experience Platform und beliebigen externen Versandsystemen nutzen, um ansprechende Erlebnisse zu erzeugen und bereitzustellen.

Das folgende Video bietet eine Einführung in diese Themen:

* Das Konzept von [!UICONTROL Journey Orchestration]
* Arten von Anwendungsfällen, die damit möglich werden
* Die Kernelemente der Funktionsweise von [!UICONTROL Journey Orchestration]

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## Das Konfigurieren einer Journey

Die wichtigsten Schritte bei der Vorbereitung auf das Erstellen von Journeys sind:

1. [Konfigurieren von Streaming-Ereignissen](/help/configuring-journey-orchestration/configure-streaming-events.md) – Diese Konfiguration ist obligatorisch, da [!UICONTROL Journey Orchestration] auf Ereignisse lauscht.
1. [Konfigurieren von Datenquellen](/help/configuring-journey-orchestration/configure-data-sources.md) – Diese Konfiguration ist nicht erforderlich, wenn Ihre Journeys nur lokale Daten aus einer Ereignis-Payload nutzen.
1. [Konfigurieren von benutzerdefinierten Aktionen](/help/configuring-journey-orchestration/configure-actions.md) – Erforderlich, wenn Sie den Service eines Drittanbieters verwenden möchten, der über eine [!DNL REST API] mit JSON-formatierter Payload aufgerufen werden kann.

>[!NOTE]
>
>Diese Konfigurationsschritte erfordern technische Kenntnisse. Sie müssen mit dem [Experience Data Model (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=de) und dem [Erstellen von XDM-Erlebnisereignis-Schemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=de) vertraut sein.

## So erstellen, veröffentlichen und analysieren Sie eine Journey

1. [Erstellen einer Journey](/help/building-a-journey/creating-a-journey.md)
1. [Validieren und Veröffentlichen einer Journey](/help/validate-and-publish-a-journey.md)
1. [Analysieren einer Journey mit Reporting-Tools](/help/analyze-a-journey-via-reporting-tools.md)

## Weitere Ressourcen

* [Journey Orchestration Help Center](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=de)
* [Adobe Experience Platform-Tutorials](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=de)
* [Hilfe zu Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK – Launch](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=de)
* [Adobe Experience Platform Location Service](https://experienceleague.adobe.com/docs/places/using/home.html?lang=de)
