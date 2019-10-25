- Plattformen
- Leitern (heil/kaputt)
- Aufzüge

- Fässer
- Feuer

- Hämmer

- Score items


- Der Spieler startet unten links. Ziel ist es, die oberste Plattform zu erreichen.
- Es gibt 4 unterschiedliche Level, die ein je festes Layout haben
	- 6 horizontale Plattformen
		- Der unterste spannt den ganzen Bildschirm
		- Die anderen haben je eine Lücke an abwechselnden Seiten, beginnend mit rechts
		- Plattformen sind zur Lücke geneigt
		- Zwischen den Plattformen sind Leitern, die heil oder kaputt sein können
			- TODO details
	- Donkey Kong ist oben links und wirft Fässer
		- Fässer können rollen oder fallen
		- Rollende Fässer:
			- Fässer rollen der Neigung der Plattform nach
			- Bei jeder Leiter kann ein Fass diese herunter fallen
			- Wenn das Ende der Plattform erreicht wird, fällt das Fass auf die nachste Plattform
		- Fallende Fässer:
			- Können gerade oder im Zickzack fallen
		- Am Ende der untersten Plattform stößt das Fass gegen ein brennendes Ölfass und kann ein Feuer spawnen
	- Feuer:
		- Bewegen sich zufällig nach links und rechts
		- Können an Leitern nach oben und unten bewegen
			- Auch an kaputten
	- Es gibt 2 Hämmer
		- Links auf der 3. Plattform
		- Links auf der 5. Plattform
		- Wenn ein Hammer angesprungen wird, wechselt Jumpman in den Hammer-Modus
		- Hammer-Modus:
			- Fässer, die der Hammer berührt werden zerstört und 500 Pkunke erhalten
			- Feuer, die der Hammer berührt werden zerstört und 800 Pkunke erhalten
			- Hält 10 Sekunden
			- Bei einem Treffer pausiert das Spiel 1 Sekunde
			