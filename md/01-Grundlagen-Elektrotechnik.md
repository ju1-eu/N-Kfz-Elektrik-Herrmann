---
title: 'Keywords-ET'
author: ''
date: \today
subject: "Markdown"
keywords: [Markdown]
lang: "de"
bibliography: literatur-kfz.bib 
csl: zitierstil-number.csl
---
<!-----------------------------+
ju 13-5-22
Keywords - Grundlagen - Elektrotechnik
+------------------------------>

# Spannung 

Spannung ist das Ausgleichsbestreben der Elektronen von negativem Pol zum positiven Pol.

# Widerstand 

Widerstand ist das Hemmen der Fortbewegung durch die Atome des Leiterwerkstoffes, auf die die Elektronen treffen, um sich durch den Leiter zu bewegen.

# Strom 

Strom ist die gerichtete Bewegung der Elektronen. Ursache für den Stromfluss ist die Spannung.

# Multimeter (Messen, Besonderheiten)

Multimeter ist ein Multifunktionsgerät, das Spannungsmesser, Strommesser, Widerstandsmesser vereint.

**Widerstandsmessung** Bauteil/Leitung vollständig aus dem Stromkreis trennen. Messgerät legt Prüfstrom an, um den Widerstand zu messen.

**Spannungsmessung** Potenzialdifferenz bestimmen, hochohmig

**Strommesser** niederohmig

# Magnetfeld eines stromdurchflossenen Leiters

Ist die technische Stromflussrichtung in beiden Seiten gleich, dann bildet sich ein Magnetfeld um die beiden Leiter herum. 

Im Gegensatz dazu ist die technische Stromflussrichtung nicht gleich, bildet sich das Magnetfeld zwischen den beiden Leitern.

# Rechte Handregel (Generator Regel) 

Wir haben einen Dauermagneten, der Nordpol trifft in die Innenhandfläche.

Wenn ich bewege, d. h. die offene Handfläche dreht sich nach rechts, fließt der Strom Richtung Fingerspitzen.

# Linke Handregel (Motor Regel) 

Lasse ich Strom fließen, ist die Bewegung nach links.

# Das Ohmsche Gesetz

Das ohmsche Gesetz zeigt die Beziehung zwischen Spannung, Strom und Widerstand im Stromkreis. Die Stromstärke steigt mit zunehmender Spannung und nimmt ab mit zunehmendem Widerstand.

$\boxed{I = \frac{U}{R}} \quad \bigl[\frac{V}{\Omega}\bigl] = A \quad
 \boxed{R = \frac{U}{I}} \quad \bigl[\frac{V}{A}\bigl] = \Omega \quad
 \boxed{U = R \cdot I} \quad [\Omega \cdot A] = V$

# Festlegen des Nordpols einer stromdurchflossenen Spule 

Wird eine stromdurchflossene Spule mit der rechten Hand so umfasst, dass die Finger in die technische Stromflussrichtung zeigen, so zeigt der abgespreizte Daumen in Richtung des Nordpols.

**Anschluss dahinter** gewickelt, dann zeigt der Daumen nach oben in Richtung Nordpol.

**Anschluss davor** gewickelt, dann zeigt der Daumen nach unten in Richtung Nordpol.

# Einsatz von Widerständen

Spannung und Stromfluss zu begrenzen und dadurch Bauteile zu schützen. 

Abhängig von Reihen-, Parallel- oder gemischte Schaltung.

**Anwendung Reihenschaltung**

(1) Strombegrenzung
(2) Spannungsteilung

**Anwendung Parallelschaltung**

(1) Stromflusserhöhung
(2) Leistungsteilung $\boxed{R_{ges} = \frac{R_{Teil}}{n}}$

# Zusammenhang zwischen Stromdichte und Leitungsquerschnitt

Je größer die Fläche, desto kleiner die Stromdichte.

Kleine Fläche, große Stromdichte.



$\boxed{J = \frac{I}{A}} \quad \bigl[\frac{A}{mm^2}\bigl]$

$\boxed{A = \frac{\rho \cdot l \cdot I}{U_v}} \quad  \bigl[\frac{\Omega \cdot mm^2 \cdot m}{m \cdot \Omega}\bigl] = mm^2$ (Mindestquerschnitt, Nennquerschnitt) 

$\quad \rho_{Cu} = 0,0178~\frac{\Omega \cdot mm^2}{m}$


# Leiterwiderstand

Leiterwiderstand ist abhängig von der Leiterlänge, Leiterwerkstoff und von der Leiterfläche. 

Guter Leiter -- ist das Material leitend vs. nicht leitend.

$\boxed{R_l = \frac{\rho \cdot l}{A}} \quad  \bigl[\frac{\Omega \cdot mm^2 \cdot m}{m \cdot mm^2}\bigl] = \Omega \quad \rho_{Cu} = 0,0178~\frac{\Omega \cdot mm^2}{m}$

$\boxed{\text{max. Leiterwiderstand} = 1~\Omega}$

# Reihenschaltung von Widerständen

Spannungsteilerschaltung, an den einzelnen Widerständen fällt individuell eine Spannung ab. 
Alle Einzelspannungen zusammen addiert ergibt die Gesamtspannung. 
 
Der Strom bleibt konstant.

# Innenwiderstand von Spannungsquellen 

Ist der Gesamtwiderstand aller Zellen, ist auch Temperaturabhängig.

Die Klemmenspannung unter Last ist um Spannungsfall niedriger als die Leerlaufspannung.

$\boxed{U_k = U_q - I \cdot R_i} \quad [V - A \cdot \Omega \to V - V] = V$

$\boxed{R_i = \frac{U_i}{I}} \quad \boxed{U_k = U_q - U_i - U_v} \quad \boxed{R_{ges} = R_i + R_l + R_\text{ü} + R_{La}}$

# Relais 

Mit einem kleinen Steuerstrom kann ich einen hohen Laststrom schalten. 
 
Wird unterschieden zwischen Schließer-, Öffner- und Wechselrelais.

Relaisspulenwiderstand: $50 - 100~\Omega$ 

# Parallelschaltung  von Widerständen

Stromteilerschaltung, der abfallende Einzelstrom ergibt, addiert den Gesamtstrom. 

Der Gesamtwiderstand der Schaltung ist immer kleiner als der kleinste Einzelwiderstand. 

Spannung ist überall gleich.

Ersatzwiderstand 

$\boxed{R_{ges} = \frac{R_{Teil}}{n}}$ 

n = Anzahl der Widerstände (gleich große Widerstände)

$\boxed{R_{ges} = \frac{R_1 \cdot R_2}{R_1 + R_2}} \quad R_{ges} = \frac{1}{\frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}}$

$\to R_{1} = \frac{1}{\frac{1}{R_{ges}} - \frac{1}{R_2} - \frac{1}{R_3}} \quad \to R_{2} = \frac{1}{\frac{1}{R_{ges}} - \frac{1}{R_1} - \frac{1}{R_3}}  \quad \to R_{3} = \frac{1}{\frac{1}{R_{ges}} - \frac{1}{R_1} - \frac{1}{R_2}}$

# Leistung 

Leistung ist das Produkt aus Spannung und Strom.

Mit 1 Volt Spannung und 1 Ampere Strom haben wir 1 Watt Leistung.

$\boxed{P = U \cdot I} \quad [V \cdot A] = W \quad \boxed{P = \frac{U^2}{R}} \quad \boxed{P = R \cdot I^2}$

**Lampe** $12~V/55~W$ 

$R_{La} = \frac{U^2}{P} \quad I_{tat} = \frac{U_k}{R_{La}} = \frac{U_{ges} - U_v}{R_{La}} \quad P_{tat} = U_k \cdot I_{tat}$

# Spannungsverlust, Spannungsfall 

Spannungsverlust in einem stromdurchflossenen Leiter entsteht in Folge des Leiterwiderstandes, der sich am Verbraucher als Verlust auswirkt.

$U_{ges} = U_v + U_k \quad U_v = R_l \cdot I \quad U_k = U_{ges} - R_l \cdot I$

$\boxed{U_v = \frac{\rho \cdot l \cdot I}{A}} \quad \bigl[\frac{\Omega \cdot mm^2 \cdot m \cdot A}{m \cdot mm^2}\bigl] = V \quad \rho_{Cu} = 0,0178~\frac{\Omega \cdot mm^2}{m} \quad \boxed{U_{v_{max}} = 0,5~V}$



# Potenzialbestimmung 

Um das Potenzial in einem Punkt im Stromkreis zu bestimmen, bezieht man sich auf das Bezugspotenzial. Masse- und Pluspotenzial.


