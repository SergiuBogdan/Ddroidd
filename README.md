Formularul are metoda de validare facuta in HTML.La implementarea reCAPTCHA , acesta a incetat sa mai functioneze din cauza metodei de validare.
Am ales sa implementez reCAPTCHA si sa pun o componenta in JavaScript pentru accesarea butonului de "Submit".
Daca in fisierul index.html se modifica metoda de validare din "POST" in "GET" si se va sterge componenta JavaScript, va functiona metoda de validare fara reCAPTCHA.

Edit: Am gasit problema careia nu mergea reCAPTCHA impreuna cu metoda de validare GET.Am facut un nou commit care reflecta acest fix.

Proiectul se porneste ruland pe rand comenzile , npm install si npm start dintr-o consola terminal in folderul radacina a proiectului.