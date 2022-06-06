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
ju 5-6-22
Keywords - Grundlagen - Elektrotechnik II
+------------------------------>

#  Pulsweitenmodulation

1. **PWM-Signal:** Rechtecksignal

1. **Messen:** Oszilloskop

1. **Ansteuerung:** $0 - 100~\%$, Impuls - Pause - Verhältnisänderung / Frequenzänderung (keine Spannungsänderung!)

1. **Anwendung**
    - Motorgeschwindigkeit 
    - Glühlampenhelligkeit 
    - Beleuchtung, Beispiel: Einfaden-Glühlampe (Standlicht + Bremslicht)

Die **Pulsweitenmodulation** (PWM) ist eine digitale Modulationsart, bei der eine technische Größe zwischen zwei Werten wechselt. Dabei wird bei konstanter Frequenz ein Rechtecksignal moduliert, das in Weite, Breite bzw. Länge variiert. Das Verhältnis zwischen Impuls und Pause wird als **Tastgrad** bezeichnet. **Anwendung** in der Steuer- und Regelungstechnik.

# Halbleiter

**Material:** reines Silizium, wenn es wärmer wird, wird es leidend.

**Dotieren**, um die Leitfähigkeit zu verbessern.

1. **P-Leiter** Silizium wird verunreinigt, mit Bohr, weniger Elektronen
2. **N-Leiter** Silizium wird verunreinigt, mit Phosphor, Elektronenüberschuss

$\to$ Spannung anlegen, dann kommt es zum Elektronenfluss, weil die Elektronen versuchen sich auszugleichen.

**Anwendung:** Diesel-Abgastemperatursensoren (PTC-Widerstände)

# Fragen zum Schaltplan Audi A3 2009


**1. Beschreiben Sie die Spannungsversorgung für die Pumpe für Kühler der Abgasrückführung.**

1. Stromverteiler (87) 
1. über Sicherung (24) 
1. Steckverbindung ($T_{40/11}$)
1. Plusverbindung $B_{321}$
1. Pumpe für Kühler der Abgasrückführung $V_{400}$ (Pin 2) 
1. Steckverbindung ($T_{14/9}$)
1. Masseverbindung (394)
1. Massepunkt (655) am Scheinwerfer links


**2. Welche Fehler können auftreten und welche Auswirkungen haben diese?**

**Welches Signal erwarten wir?** PWM-Signal

1. Bauteil defekt
1. Sicherung defekt 
1. Leitungsunterbrechung (Signalleitung, Plusleitung, Masseleitung)
1. Übergangswiderstand (Spannungsfall im Stecker oder Leitungen)
1. Masseschluss oder Plusschluss

**Mögliche Fehler**

1. MIL-Lampe an $\to$ Abgas relevanter Fehler (Steuerhinterziehung)
1. AGR klemmt fest, wenn offen $\to$ Leistungsverlust im warmen Zustand


**3. Fehler Abgastemperaturgeber 1, 3, 4 sind im Fehlerspeicher abgelegt. Nennen Sie mögliche Fehlerursachen.**

1. Bauteil defekt (Temperatursensoren) 
1. plusseitig

**4. Motordrehzahlgeber hat kein Signal. Welche möglichen Ursachen liegen vor?**

**Was erwarten wir?** Hallgeber, Versorgungsspannung (5 V)

1. Masseverbindung 
1. Bauteil defekt 
1. Plusverbindung (5 V)

**5. Ihnen liegt ein Fehler zur Kraftstoffvorratsanzeige vor. Nennen Sie mögliche Fehler.**

1. Geber defekt
1. Gebermasse 
1. Übergangswiderstand 
1. Leitungsunterbrechung von (Pin 3 + 4) zum Kombiinstrument 
1. Widerstand defekt