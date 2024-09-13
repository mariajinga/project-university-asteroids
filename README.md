# Asteroids Game | Joc Asteroids
*******************************************************
### *IMPORTANT*
*This project was developed by me during my time at university and was created using online resources and domain-specific books as sources of inspiration. The goal of this project was to explore and learn through practical examples, combining various information and techniques found in these resources to bring it to completion. I would like to mention that the source code of this project is posted on GitHub, but it is set to private to avoid any form of plagiarism, as it is the result of my own personal work.*

*Acest proiect a fost realizat de mine în timpul facultății și a fost creat folosind resurse de pe internet și cărți de specialitate drept surse de inspirație. Scopul acestui proiect a fost să explorez și să învăț prin intermediul unor exemple practice, combinând diverse informații și tehnici găsite în aceste resurse pentru a-l aduce la bun sfârșit. Menționez că codul sursă al acestui proiect este postat pe GitHub, dar este setat pe privat pentru a evita orice formă de plagiat, deoarece este rezultatul muncii mele personale.*

*******************************************************

## Overview | Prezentare Generală
Developing a Game Similar to Asteroids (https://en.wikipedia.org/wiki/Asteroids_(video_game))
Using either the <canvas> or <svg> control. In cases where the standard rules differ from the rules specified below, the version provided in the requirements must be implemented.

Example: https://m1el.github.io/wasm-asteroids/demo/demo.html

Realizarea unui joc similar cu Asteroids (https://en.wikipedia.org/wiki/Asteroids_(video_game)) utilizând controlul de tip <canvas> sau controlul de tip <svg>. În cazurile în care regulile standard diferă de
regulile din cerințele de mai jos trebuie implementată varianta din cerințe.

Exemplu: https://m1el.github.io/wasm-asteroids/demo/demo.html

## Project Structure | Structura Proiectului
- Implementation of Asteroids (represented as circles): Each asteroid will have an associated value randomly generated between 1-4, indicating the number of rockets required to destroy it. The number of required rockets will be constantly displayed within the drawing used for the asteroid. The color and size of the asteroid will change based on this number. Asteroids will move along linear trajectories with a randomly determined speed.
- Implementation of the Spaceship: The spaceship will be drawn as a triangle and can be controlled using the following keyboard commands: arrow keys (move the spaceship up/down/left/right with a constant speed), z – rotate left, c – rotate right, x – launch a rocket in the direction the spaceship is currently facing. The spaceship can move in all four directions regardless of its current orientation.
- Implementation of Rockets: Rockets will be represented as they travel from the spaceship to the asteroid. Collision detection with the asteroid will be ensured, and the number of rockets required to destroy it will be updated. A maximum of 3 rockets can be launched simultaneously.
- Collision between Asteroids: A collision between two asteroids will result in a change in their trajectories.
- Collision between the Spaceship and Asteroids: A collision will reduce the number of "lives" and restart the game until the number of lives reaches 0.
- Regeneration of Lives: Upon destroying each asteroid, the player will gain a certain number of points. When a predefined number of points is reached, the number of "lives" will be updated.
- Touchscreen Game Control: The game should support control using a touchscreen.
- Storing the Top 5 Scores and Player Names: The top 5 scores achieved and the names of the players will be stored using the Web Storage API (or a similar API).
*******************************************************
- implementare asteroizi (reprezentați sub formă de cerc): fiecare asteroid va avea asociată o valoare generată
aleator în intervalul 1-4, indicând numărul de rachete necesar pentru distrugerea acestuia. Numărul de rachete
necesare va fi afișat în permanență în cadrul desenului utilizat pentru asteroid. Culoarea și dimensiunea
asteroidului se vor modifica în funcție de acest număr. Asteroizii se vor deplasa pe traiectorii liniare cu o viteză
determinată aleator.
- implementare navă spațială desenată sub formă de triunghi; nava va putea fi controlată cu ajutorul
următoarelor comenzi din tastatură: săgeți (deplasare navă sus / jos / stânga / dreapta cu o viteză constantă), z – rotire spre stânga,
c – rotire spre dreapta, x – lansare rachetă în direcția în care este orientată nava; nava se poate deplasa în toate cele patru direcții
indiferent de orientarea curentă.
- implementare rachete: se va reprezenta racheta pe parcursul deplasării de la nava spațială la asteroid. Se va
asigura detecția coliziunii cu asteroidul și modificarea numărului de rachete necesar pentru distrugerea acestuia.
Sunt permise maxim 3 rachete lansate simultan.
- coliziune între asteroizi: coliziunea dintre doi asteroizi va determina modificarea traiectoriei acestora
- coliziune între nava spațială și asteroizi: va determina reducerea numărului de “vieți” și repornirea jocului,
pînă când numărul de vieți devine 0.
- regenerare număr vieți: la distrugerea fiecărui asteroid jucătorul va obține un număr de puncte. La atingerea
unui număr predefinit de puncte, se va actualiza numărul de ”vieți”.
- posibilitate control joc utilizând touchscreen
- stocarea celor mai bune 5 scoruri obținute și a numelui jucătorilor cu ajutorul Web Storage API (sau a unui
alt API similar)

*******************************************************

https://github.com/user-attachments/assets/17048d6c-7c55-47a4-890f-7ec7c8ba679e

*******************************************************

---
