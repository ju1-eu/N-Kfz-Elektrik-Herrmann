---
title: 'Grundlagen - Elektrotechnik II'
author: ''
date: \today
subject: "Markdown"
keywords: [Markdown]
lang: "de"
bibliography: literatur-kfz.bib 
csl: zitierstil-number.csl
---
<!-----------------------------+
ju 12-6-22
Keywords - Grundlagen - Elektrotechnik II
+------------------------------>

# Pulsweitenmodulation

1. **PWM-Signal:** Rechtecksignal (vgl. Kennlinie)

1. **Messen:** Oszilloskop

1. **Ansteuerung:** $0 - 100~\%$, Impuls-Pause-Verhältnisänderung (nur Pulsweite ändert sich), aber Periodendauer / Frequenz bleibt konstant (keine Spannungsänderung!)

1. **Anwendung**
    - Elektromotor (Drehzahl)
    - Glühlampen (Helligkeit, dimmen)
    - Beleuchtung, Beispiel: Einfaden-Glühlampe (Standlicht + Bremslicht)

Die **Pulsweitenmodulation** (PWM) ist eine digitale Modulationsart, bei der eine technische Größe zwischen zwei Werten (Spannungspegel $0~V$ und VCC) wechselt. Dabei wird bei konstanter Frequenz ein Rechtecksignal moduliert, das in Pulsweite (*oder* Breite bzw. Länge) variiert. Das Verhältnis zwischen Impuls und Pause (Ein- und Ausschaltzeit) wird als **Tastgrad / Tastverhältnis** bezeichnet. **Anwendung** in der Steuer- und Regelungstechnik.


# Halbleiter

**Halbleiter** der Widerstand ist temperaturabhängig.

**Material** Beispiel: reines Silizium, wenn es erwärmt wird, wird es leitend.

**Dotieren** Leitfähigkeit verbessern.

## P-Leiter und N-Leiter

1. **P-Leiter** *Elektronenmangel* (Leitermaterial Silizium wird verunreinigt mit Bohr)

2. **N-Leiter** *Elektronenüberschuss* (Leitermaterial Silizium wird verunreinigt mit Phosphor)

$\to$ Spannung anlegen, dann kommt es zum Elektronenfluss, weil die Elektronen versuchen sich auszugleichen.

## Sensoren und Aktoren

**Sensoren** erfassen Messgrößen und wandeln diese in elektrische Signale um. (Sinne des Autos) 

**Aktoren** Ausführen 

**NTC und PTC**

1. **Heißleiter** $\to$ NTC-Widerstände 
    - *negativer Temperatur-Koeffizient* $\to$ fallender Widerstand bei steigender Temperatur $\uparrow \downarrow$ 
    - vgl. Kennlinie (x = Temperatur, y = Widerstand) 
    - **Anwendung:** Temperatursensoren (Kühlmittel-, Kraftstoff-, Luft-, Motortemperaturfühler)
    - Schaltsymbol
    - typische Werte: Kalt: $2 - 4~k\Omega$ und Warm: $200 - 400~\Omega$
    - *Leitfähigkeit* steigt mit zunehmender Temperatur 
    - Widerstand und Spannungsfall am NTC wierden kleiner 

1. **Kaltleiter** $\to$ PTC-Widerstände 
    - *positiver Temperatur-Koeffizient* $\to$ zunehmender Widerstand bei steigender Temperatur $\uparrow \uparrow$ 
    - vgl. Kennlinie (x = Temperatur, y = Widerstand) 
    - **Anwendung:** Hochtemperaturbereich (Diesel-Abgastemperatursensoren), Glühkerzen, Heizungen von Lambdasonden
    - Schaltsymbol
    - *Leitfähigkeit* verringert sich mit zunehmender Temperatur
    - Widerstand und Spannungsfall am PTC werden größer 
    - "Je höher der Widerstand, desto geringer der Stromfluss."
