# wireshark2

### Spørgsmål 1
Hvad er IP-adressen og TCP-porten brugt af kilde-klienten for at overføre filen til gaia.cs.umass.edu?
Hvilken IP-adresse og port er brugt af gaia.cs.umass.edu til at modtage filen?

### Spørgsmål 2
Hvad er sequence-nummeret på det TCP SYN-segment brugt til at starte TCP-forbindelsen mellem klienten og gaia.cs.umass.edu?
Hvad er det i segmentet, der identificerer segmentet som et SYN-segment? 

### Spørgsmål 3
Hvad er sequence-nummeret af det SYNACK-segment sendt af gaia.cs.umass.edu til klienten som svar på SYN?
Hvad er værdien af ACK-feltet i SYNACK-segmentet?
Hvordan bestemte gaia.cs.umass.edu den værdi?
Hvad er det i segmentet, der identificerer det som et SYNACK-segment?

### Spørgsmål 4
Hvad er sequence-nummeret af TCP-segmentet der indeholder HTTP-POST kommandoen? (For at finde segmentet, kan det være nødvendigt at filterere for HTTP)

### Spørgsmål 5
Betragt TCP-segmentet med HTTP-POST som det første segment i TCP-forbindelsen. Hvad er sequence-numrene på de første 6 segmenter i TCP-forbindelsen (inkluderende segmentet med HTTP-POST)?.
På hvilket tidspunkt var hver segment sendt?
Hvornår var ACK for hver segment modtaget?
Givet forskellen mellem hvornår hver TCP-segment var sendt, og hvornår deres ACK er modtaget, hvad er så RTT for hver af de 6 segmenter?

### Spørgsmål 6
Hvad er minimum mængden af buffer-space (win) dedikeret fra serveren?
Har det nogen effekt på forbindelsen?

### Spørgsmål 7
Er der nogen gentransmiterede segmenter? Hvad skal man kigge efter for at finde ud af det?

### Spørgsmål 8
Hvor meget data er der typisk modtaget i ACK? Er det muligt at identificerer de tilfælde hvor receiver kun ACK'er hver andet segment?
