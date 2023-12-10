### @explicitHints true

# Omarillo Logo - Lesson #1

## Omarillo Logo - Lesson #1 @unplugged
**Welcome to coding with Omarillo Logo.**

In questa lezione creerai il tuo primo programma per Omarillo. Vedrai apparire un **Omarillo** nella tua console di gioco e dire "Ciao, benvenuti all'I.T.I Omar" proprio come la tartaruga dice Hello, World!.
![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson1/raw/main/assets/hello_world_screenshot.png)

## Step 1
Tutti i nostri programmi iniziano con un blocco ⇢``on start``⇠ block. Questo blocco esegue tutti i comandi che si trovano al suo interno non appena inizia il programma. Ti è stato fornito di seguito. Se elimini accidentalmente il blocco, puoi trovarlo nel menu *"Loops"* menu.
```blocks
/**
 * This is the "on start" block
 */
```

## Step 2
** Follow Along**

Successivamente dovrai creare il tu **Omarillo**. Per fare ciò utilizza il blocco  ⇢``show omarillo``⇠ block e posizionalo all'interno del blocco ⇢``on start``⇠. Questo crea  l'**Omarillo** o la **Tartaruga** e la posiziona al centro dello schermo.
```blocks
/**
 * questo è il blocco "show omarillo" block
 */
 omarillo.showOmarillo()
```

## Step 3
** Follow Along**

Ora che abbiamo un **Omarillo**, puoi chiedergli di dire qualcosa. Trascina fuori l'Omarillo ⇢`` che dice "Ciao, mondo!" ⊕``⇠ e posizionalo all'interno del blocco ⇢``on start``⇠ ma dopo il blocco ⇢``mostra omarillo``⇠.
```blocks
omarillo.showOmarillo()
omarillo.say("Ciao, benvenuti all'I.T.I Omar!")
```
## Step 4
**Success!**

Nota nella console di gioco a sinistra, il tuo **Omarillo** ha detto "Ciao, benvenuti all'I.T.I Omar!" per 5 secondi e poi le parole svaniscono. Se desideri eseguire nuovamente il programma, fai clic sul pulsante "🔁" sulla console di gioco. Puoi anche fare clic su "⊕" e modificare i millisecondi con un numero più grande, per farli rimanere più a lungo.

```blocks
omarillo.showOmarillo()
omarillo.say("Ciao, benvenuti all'I.T.I Omar!", 60000)
```

## Step 4
**Your Turn**

Fai in modo che  **Omarillo** dica il tuo nome!

## Step 5
**Done**

Complimenti hai completato con successo la tua prima lezione e stai addestrando Omarillo.