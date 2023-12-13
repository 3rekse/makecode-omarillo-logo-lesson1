### @explicitHints true

# Omarillo Logo - Lesson #1

## Omarillo Logo - Lesson #1 @unplugged
**Welcome to coding with Omarillo Logo.**

In questa lezione creerai il tuo primo programma Omarillo Logo. Vedrai apparire un **Omarillo** nella tua console di gioco e dire "Ciao, benvenuti all' Omar" proprio come la tartaruga cice "Hello, world" .
![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson1/raw/main/assets/hello_world_screenshot.png)

## Step 1

Tutti i nostri programmi iniziano con un blocco ⇢``on start``⇠ block. Questo blocco esegue tutti i comandi che si trovano al suo interno non appena inizia il programma. Ti è stato fornito di seguito. Se elimini accidentalmente il blocco, puoi trovarlo nel menu *"Loops"* menu.
=======

```blocks
/**
 * This is the "on start" block
 */
```

## Step 2
** Follow Along**

Successivamente dovrai creare il tuo **Omarillo**. Per fare ciò utilizza il blocco  ⇢``show omarillo``⇠ e posizionalo all'interno del blocco ⇢``on start``⇠. Questo crea  l'**Omarillo** e lo posiziona al centro dello schermo.
=======

```blocks
omarillo.showOmarillo()
```

## Step 3
** Follow Along**

Ora che abbiamo l'**Omarillo**, puoi addestrarlo a di dire qualcosa. Trascina fuori il blocco ⇢`` omarillo says "Benvenuti, all'OMAR di Oleggio" ⊕``⇠ e posizionalo all'interno del blocco ⇢``on start``⇠ ma dopo il blocco ⇢``show omarillo``⇠.

```blocks
omarillo.showOmarillo()
omarillo.say("Benvenuti all'OMAR di Oleggio!")
```
## Step 4
**Success!**

Nella console di gioco a sinistra, il tuo **Omarillo** ha detto "Benvenuti all'OMAR di Oleggio!" per 5 secondi e poi le parole svaniscono. Se desideri eseguire nuovamente il programma, fai clic sul pulsante "🔁" sulla console di gioco. Puoi anche fare clic su "⊕" e modificare i millisecondi con un numero più grande, per farli rimanere più a lungo.
```blocks
turtle.showTurtle()
turtle.say("Hello, World!", 60000)
```

## Step 4
**Your Turn**

Ora fai dire il tuo nome al tuo **Omarillo**

## Step 5
**Done**

Hai completato con successo la tua prima lezione e hai addestrato Omarillo.
