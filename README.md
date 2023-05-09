# Dice sum probability calculator

## Bakgrund

I många brädspel är det vanligt att det används olika sorters tärningar för att simulera slumpade händelser. Ett "d" eller "D" används för att indikera en tärning med ett specifikt antal sidor, där d4 menas med en fyrsidig tärning exempelvis.

Om flera tärningar av samma sort ska slås så anges det med en ledande siffra. Alltså betyder 2d6 att två sexsidiga tärningar ska slås och summan av resultatet visas.

## Uppgiften

Skriv ett program som beräknar den mest sannolika summan av de två tärningarna som slås.  
Anta att varje tärning har numrerade sidor, som börjar på 1 och att varje sida har lika stor sannolikhet att den landas på.

**Input**  
Inputen är en rad med två sal, N och M, som anger hur många sidor tärningen har.  
Tärningarna har mellan 4 och 20 sidor, dvs. 4 $\leq$ N,M $\leq$ 20.

**Output**  
En rad som skriver ut den mest sannolika summan.  
Om det finns flera fall med samma sannolikhet så skriv ut dessa rad för rad i fallande ordning.

## Exempel

Input #1

```cmd
6 4
```

Output

```cmd
7
```

Input #2

```cmd
6 4
```

Output

```cmd
5 
6
7
```

Input #3

```cmd

12 20
```

Output

```cmd
13
14
15
16
17
18
19
20
21
```
