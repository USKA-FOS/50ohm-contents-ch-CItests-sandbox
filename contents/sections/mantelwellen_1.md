Beim Anschluss von Antennen möchten wir erreichen, dass nur die Antenne Signale abstahlt bzw. aufnimmt, nicht jedoch die Speiseleitung selbst, die im Haus verlegt sein könnte. Hierzu eigenen sich geschirmte Leitungen, z. B. Koaxialkabel, da diese im Idealfall selbst keine elektromagnetischen Wellen abstrahlen oder aufnehmen, sondern das Signal abgeschirmt von der Aussenwelt (also z. B. der Hauselektrik) durch das Kabel leiten.

<indepth>
Damit die Schirmung eines Koaxialkabels auch die gewünschte Funktion erfüllt, muss eine *Bedingung* erfüllt sein: Der Strom im Innenleiter muss dem Strom im Aussenleiter genau entgegengesetzt sein und beide Ströme müssen den gleichen Betrag haben. In diesem Falle entsteht nur zwischen den beiden Leitern ein Feld, und die Umgebung des Kabels wird nicht beeinflusst. Der Aussenleiter weist genau dann keine hochfrequente Spannung gegenüber der Erde auf.

Umgekehrt bedeutet dies aber auch: Wenn der Aussenleiter eine hochfrequente Spannung gegenüber der Erde aufweist, dann sind die Ströme im Innenleiter nicht symmetrisch und das Koaxialkabel strahlt ab.

Die Ströme im Koaxialkabel sollten also symmetrisch sein (gleicher Betrag aber umgekehrtes Vorzeichen bzw. umgekehrte Richtung) und die Spannungen gegenüber der Erde sollten *unsymmetrisch* sein (nur der Innenleiter führt Spannung gegenüber der Erde).
</indepth>

---

Schliesst man jedoch eine symmetrische Antenne, z. B. einen Halbwellendipol, an ein Koaxialkabel an, so kann es dennoch dazu kommen, dass das Koaxkabel trotz Abschirmung strahlt! Dies liegt daran, dass auf der Oberfläche der Aussenseite des metallischen Aussenleiters hochfrequente Ströme fliessen können, die von einem elektromagnetischen Feld um die äussere Isolierung herum begleitet werden (vgl. Abbildung [ref:e_mantelwellen]). Diesen Effekt bezeichnen wir als *Mantelwellen*, welche sowohl beim Senden andere Geräte im Haus stören können, als auch zu Empfangsstörungen führen können, da das Koaxialkabel gewissermassen zum Teil der Antenne wird und damit störende Einflüsse im Haus leichter vom Funkgerät aufgenommen werden können. Die zusätzlichen Mantelströme "fehlen" dann auf einem der beiden Dipolschenkel, wodurch es ausserdem zu einer Verformung der Richtcharakteristik kommt.

[question:EG405]
[question:EG406]

Abbildung [ref:e_mantelwellen] verdeutlicht, wie ein Teil des Stroms, der eigentlich in den Dipolschenkel fliessen sollte, auf dem Koaxschirm zurückfliesst.

<margin>
[picture:633:e_mantelwellen:Mantelwellen]
</margin>

Mantelströme fliessen tatsächlich weitgehend auf der Oberfläche des Aussenleiters. Dies hängt mit dem sogenannten *Skineffekt* zusammen, der dafür sorgt, dass hochfrequente Ströme weitgehend auf der Oberfläche von metallischen Leitern fliessen. Insofern kann man sich ein Koaxialkabel auch als ein Dreileitersystem vorstellen:
  
1. Aussenseite des Innenleiters
2. Innenseite des Aussenleiters
3. Aussenseite des Aussenleiters
  
Der Strom auf der Aussenseite des Innenleiters und der Strom auf der Innenseite des Aussenleiters haben immer den gleichen Betrag und sind entgegengerichtet ($I_1$). Der Strom auf der Aussenseite des Aussenleiters ($I_3$) stellt den Mantelstrom dar.

[question:EG404]

---

Mantelwellen lassen sich beispielsweise dadurch verhindern, dass man ein sogenanntes *Symmetrierglied*, einen Balun, zur Verbindung von Koaxialkabel und Antenne verwendet.

<indepth>
Das Wort *Balun* ist zusammengesetzt aus den englischen Worten "balanced" und "unbalanced", da eine symmetrische Seite (z. B. eine symmetrische Antenne) mit einer unsymmetrischen Seite (dem Koaxialkabel, bei dem idealerweise nur der Innenleiter eine Spannung gegenüber Erde aufweist) verbunden werden soll.
</indepth>

[question:EG407]

---

Eine weitere Bauform für einen Balun ist es, ein Koaxialkabel um einen Ferritkern zu wickeln. Dies stellt eine sogenannte *stromkompensierte Drossel* dar und wird auch als *Mantelwellensperre* bezeichnet. Für Gegentaktsignale hat sie eine geringe Impedanz, da, wenn im Innenleiter der umgekehrte Strom wie im Aussenleiter fliesst, keine nennenswerte Wechselwirkung mit dem Ferritmaterial stattfindet. Für Mantelwellen jedoch wirkt der Aufbau wie eine (verlustbehaftete) Spule.

<margin>
[photo:325:e_mantelwellendrossel:Mantelwellensperre]
</margin>

[question:EG408]