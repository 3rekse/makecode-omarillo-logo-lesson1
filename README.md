### @explicitHints true

# Omarillo Logo - Lesson #1

## Omarillo Logo - Lesson #1 @unplugged
**Welcome to coding with Omarillo Logo.**

In questa lezione creerai il tuo primo programma Omarillo Logo. Vedrai apparire una **Omarillo** nella tua console di gioco e dirle "Ciao, mondo! Benvenuti all' Omar" proprio come la tartaruga .
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

Successivamente dovrai creare il tu **Omarillo**. Per fare ciò utilizza il blocco  ⇢``show turtle``⇠ e posizionalo all'interno del blocco ⇢``on start``⇠. Questo crea  l'**Omarillo** o la **Tartaruga** e la posiziona al centro dello schermo.
```blocks
omarillo.showOmarillo()
```

## Step 3
** Follow Along**

Now that we have a **Turtle**, you can ask it to say something. Drag out the ⇢``turtle says "Hello, World!" ⊕``⇠ block and place it inside the ⇢``on start``⇠ block but after the ⇢``show turtle``⇠ block.
```blocks
turtle.showTurtle()
turtle.say("Hello, World!")
```
## Step 4
**Success!**

Notice in the game console to the left, your **Turtle** said "Hello, World!" for 5 second and then the words vanish. If you want to run your program again, click the "🔁" button on the game console. You can also click the "⊕" and change the milliseconds to a larger number, to make it stay longer.
```blocks
turtle.showTurtle()
turtle.say("Hello, World!", 60000)
```

## Step 4
**Your Turn**

Get the **Turtle** to say your name!

## Step 5
**Done**

You have successfully completed your first lesson in Turtle Logo.
