# Schaltplan

![](Schaltplan.png)

# Passende Schaltplansymbole

- **R** - Widerstände (R1 und R2)
- **Battery_Cell** - Batteriehalter (BT1)
- **LED** - Leuchtdiode (D1 und D2)
- **SW_DPDT_x2 Unit A und B** - Schiebeschalter (SW1A und SW1B)
- **+3V0** - Spannungsversorgung
- **GND** - Spannungsversorgung
- **PWR_FLAG**
- ggf. **MountingHole_Pad** - Befestigungsloch

# Passende Footprints

- Battery:BatteryHolder_Keystone_1060_1x2032
- LED_SMD:LED_1210_3225Metric_Pad1.42x2.65mm_HandSolder
- LED_THT:LED_D5.0mm
- Resistor_SMD:R_1210_3225Metric_Pad1.30x2.65mm_HandSolder
- MSS22D18G2:MSS22D18G2 (MSS22D18G2.pretty in Projektordner kopieren)

# Workflow

- Kicad-library und kicad-library-3d installieren (Linux)
- Anlegen eines neuen Projekts, öfnnen des Schaltplaneditors
- Hinzufügen von Schaltplansymbolen _a_ und Spannungsversorgungssymbole _p_
- Verbinden der Bauteile _w_
- Zuordung der Bauteilwerte _v_
- Annotieren der Bauteildesignator
- Zuordnung der Footprints **(Speichern nicht vergessen)**
- ERC ausführen und Fehler beheben
- Grid einstellen auf 0,1 mm
- Layout aus Gingerbread einfügen (Gesamtes Dokument - nicht Auswahl)
- Schaltplan auf Board übertragen _F8_
- Bauteile bewegen mit _m_, auf die andere Seite wechseln mit _f_ und Drehen mit _r_
- Leiterbahnen anlegen _x_, Löschen _Entf_ und Vias setzen mit _v_
- Kupferflächen erstellen und aktualisieren _d_ für SMD Bauteile muss Freiraum und Mindestbreite verkleinert werden
- Bestückungsdruck aufräumen
- DRC ausführen und Fehler beheben
- Gerber-Dateien exportieren

# Tipps
- Werkzeuge beenden _ESC_
- _e_ um Objekte zu editieren
- Einige Linux Distributionen haben extra Pakete für Schaltplansymbole, Footprints und 3D-Modelle
