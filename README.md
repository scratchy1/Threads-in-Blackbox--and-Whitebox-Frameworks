# Threads-in-Blackbox--and-Whitebox-Frameworks
Ein sicheres Zeichen für ein Whitebox-Framework ist die Verwendung von Vererbung bei der Erstel-lung Ihrer Anwendungsklassen.
Das gewünschte Verhalten wird durch Überschreiben existierender Me-thoden oder das Implementieren von abstrakten Methoden hinzugefügt.
Im Gegensatz dazu basieren Blackbox-Frameworks in JAVA auf Komposition und Forwarding statt Vererbung.
Hierbei werden den Frameworkklassen Objekte der von Ihnen erstellten Anwendungsklassen zur Verfügung gestellt (z.B. über den Konstruktor).
An diese Objekte können dann frameworkintern die zu erfüllenden Aufgaben durch Methodenaufrufe auf den Objekten weitergeleitet werden.
Daher im-plementieren die Anwendungsklassen meist bestimmte Schnittstellen.
