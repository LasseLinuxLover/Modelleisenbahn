
# Modelleisenbahn Bremsmodul für H0
# Modeltrains break module for H0

Bild / Picture 1<img width="1120" height="570" alt="bremsabschnitt" src="https://github.com/user-attachments/assets/20a4d7ae-5927-45f0-b68c-c6ad91c81907" />
Bild / Picture 2<img width="4000" height="3000" alt="20260719_205229_neu" src="https://github.com/user-attachments/assets/73c28323-42c8-4e15-86a5-588f24b9bf1f" />

-- Deutsch (German) --

Mit dieser Schaltung kann man sehr günstig einen Bremsabschnitt für eine Modelleisenbahnanlage einrichten - man braucht nur ein Modul pro Anlage / Booster. Statt 30-80€ auszugeben zahlt man hier nur ein paar Euro für Dioden und ein Board zum Auflöten.

Wie es Funktioniert:

Der Decoder der Lok erkennt, wenn micht mehr das klassische Wechselstrom-Pulsweitenmodulationssignal anliegt, sondern nur noch positive Spannung (egal, ob eine Gleichspannung oder ein normales Pulsweitenmodulationssignal) anliegt. Daher ist in der Schaltung ein Gleichrichter verbaut (siehe Bild 1 mit der Schaltung), der dann die Spannung ins ausschließlich positive setzt. 

Es ist außerdem eine LED verbaut, die anzeigt, ob das Bremsmodul im Moment mit Strom versorgt ist.

Vor und nach dem Bremsabschnitt (der bei den Einstellungen meiner Loks ca. 60cm lang sein muss), ist ein Gleis zu verbauen, das nur den positiven Strom durchlässt, nicht aber den Negativen invertiert. Dieser Abschnitt muss mindestens so lang sein wie der längste Schleifer (bei Märklin) oder der längste Kontakt eines Wagens über die Räder (bei 2-Schienen-2-Leiter). Ansonsten kann es zu Kurzschlüssen kommen. 
Updates dazu kommen noch.

Damit es funktioniert, muss man einige Einstellungen am Decoder der Lok vornehmen. Eine Anleitung hierzu ist in Arbeit.

Genauere Anleitungen sind in Arbeit, da ich dies nacharbeite und das Experiment bereits Mitte 2024 abgeschlossen habe.



 
-- English --

This circuit allows you to set up a braking section for a model railway layout very inexpensively—you only need one module per layout or booster. Instead of spending €30–€80, you pay just a few euros for diodes and a board for soldering.

How it works:

The locomotive's decoder detects when the classic AC pulse-width modulation signal is no longer present and only positive voltage is applied (regardless of whether it is DC voltage or a standard pulse-width modulation signal). Therefore, a rectifier is incorporated into the circuit to convert the voltage to a strictly positive state (look at Picture 1).

An LED is also installed to indicate whether the brake module is currently powered.

Before and after the braking section (which needs to be approximately 60 cm long based on my locomotive settings), a track section must be installed that allows only the positive current to pass through without inverting the negative current. This section must be at least as long as the longest pickup shoe (for Märklin) or the longest wheel-based contact on a carriage (for 2-rail systems); otherwise, short circuits may occur.
Updates on this are still to come.

For this to work, you need to adjust a few settings on the locomotive's decoder. Instructions for this are currently being prepared.

More detailed instructions are in the works, as I am revisiting this work, having already completed the experiment in mid-2024.
