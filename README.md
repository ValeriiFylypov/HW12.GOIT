# HW12.GOIT

Task 1.
Write a program that displays on the screen every second the time that has passed since the program was started.

The second thread of the same program displays the message 5 seconds have passed every 5 seconds.

Task 2
Write a program that prints to the console a string consisting of numbers from 1 to n, but with some values replaced:

if the number is divisible by 3 - print fizz
if the number is divisible by 5 - print buzz
if the number is divisible by 3 and 5 simultaneously - print fizzbuzz
For example, for n = 15, the expected result is as follows: 1, 2, fizz, 4, buzz, fizz, 7, 8, fizz, buzz, 11, fizz, 13, 14, fizzbuzz.

The program must be multithreaded and work with 4 threads:

Thread A calls fizz() to check if the number is divisible by 3, and if so, add the string fizz to the output queue for thread D.
Thread B calls buzz() to check if the number is divisible by 5, and if so, add the string buzz to the output queue for thread D.
Thread C calls fizzbuzz() to check if the number is divisible by 3 and 5 at the same time, and if so, add the string fizzbuzz to the output queue for thread D.
Thread D calls the number() method to print the next number in the queue, if there is one to print.


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Aufgabe 1.
Schreiben Sie ein Programm, das auf dem Bildschirm jede Sekunde die Zeit anzeigt, die seit dem Start des Programms vergangen ist.

Der zweite Thread desselben Programms zeigt alle 5 Sekunden die Meldung an, dass 5 Sekunden vergangen sind.

Aufgabe 2
Schreiben Sie ein Programm, das auf der Konsole eine Zeichenkette ausgibt, die aus Zahlen von 1 bis n besteht, wobei einige Werte ersetzt werden:

wenn die Zahl durch 3 teilbar ist - drucke fizz
wenn die Zahl durch 5 teilbar ist - drucke buzz
wenn die Zahl gleichzeitig durch 3 und 5 teilbar ist - fizzbuzz ausgeben
Für n = 15 zum Beispiel ist das erwartete Ergebnis wie folgt: 1, 2, fizz, 4, buzz, fizz, 7, 8, fizz, buzz, 11, fizz, 13, 14, fizzbuzz.

Das Programm muss multithreadingfähig sein und mit 4 Threads arbeiten:

Thread A ruft fizz() auf, um zu prüfen, ob die Zahl durch 3 teilbar ist, und wenn ja, die Zeichenkette fizz in die Ausgabewarteschlange für Thread D zu stellen.
Thread B ruft buzz() auf, um zu prüfen, ob die Zahl durch 5 teilbar ist, und wenn ja, fügt er die Zeichenkette buzz der Ausgabewarteschlange für Thread D hinzu.
Thread C ruft fizzbuzz() auf, um zu prüfen, ob die Zahl gleichzeitig durch 3 und 5 teilbar ist, und wenn ja, fügt er die Zeichenkette fizzbuzz der Ausgabewarteschlange für Thread D hinzu.
Thread D ruft die Methode number() auf, um die nächste Zahl in der Warteschlange zu drucken, falls es eine zu drucken gibt.
