# si-biotrack-wearableSistem portabil wearable de monitorizare a activitatii fizice si parametrilor fiziologici

1. Scopul proiectului

Dezvoltarea unui dispozitiv portabil bazat pe Raspberry Pi Pico W, capabil să monitorizeze în timp real anumiți parametri fiziologici și activitatea fizică a utilizatorului. Datele colectate vor fi transmise wireless către o aplicație mobil, unde vor putea fi vizualizate și analizate.

2. Componente hardware și senzori utilizați

Raspberry Pi Pico W – microcontroller principal, responsabil de colectarea, procesarea și transmiterea datelor.

MPU6050 – accelerometru și giroscop utilizat pentru detectarea mișcării, numărarea pașilor și identificarea unor activități fizice.

MAX30102 – senzor optic pentru măsurarea pulsului (BPM) și estimarea saturației oxigenului din sânge.

MAX30205 – senzor pentru măsurarea temperaturii în contact cu pielea.

OLED SSD1306 – afișarea locală a valorilor măsurate [OPTIONAL, DACA REUSESC SA FAC DISPOZITIVUL SUFICIENT DE COMPACT].
Buzzer sau modul haptic - pentru alerte sonore/haptice

3. Comunicația cu aplicația Android

Raspberry Pi Pico W va comunica wireless cu o aplicație Android. Se propune utilizarea Bluetooth Low Energy (BLE), prin intermediul căruia microcontroller-ul va transmite periodic valorile măsurate.

Aplicația va permite vizualizarea parametrilor în timp real, afișarea graficelor și păstrarea unui istoric al măsurătorilor.

Aplicatia va putea permite configurarea monitorizarii (alegerea intervalului de monitorizare, activarea/dezactivarea monitorizarii temperaturii). Utilizatorii vor putea seta praguri personalizate

    - Alertă dacă pulsul depășește o anumită valoare.
    - Alertă dacă temperatura măsurată depășește un prag.
    - Alertă la detectarea unei posibile căderi.
    - Activarea/dezactivarea alertelor

4. Funcționalități propuse

Monitorizarea pulsului și a temperaturii.

Estimarea nivelului de oxigen din sânge.

Numărarea pașilor și monitorizarea activității fizice.

Detectarea unor posibile căderi.

Vizualizarea datelor și a istoricului în aplicația Android.
