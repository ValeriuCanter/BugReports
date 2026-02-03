# BugReports
## 🐞 1. Linkurile din meniu duc la pagini greșite
- **Titlu:** Linkurile din meniu duc la pagini greșite  
- **Descriere:** În meniul principal, linkul "Contact" redirecționează către pagina "Despre noi" în loc de formularul de contact.  
- **Pași de reproducere:**  
  1. Accesează website-ul.  
  2. Click pe meniul principal → "Contact".  
  3. Observă pagina deschisă.  
- **Rezultat actual:** Se deschide pagina "Despre noi".  
- **Rezultat așteptat:** Se deschide formularul de contact.  
- **Severitate:** Major  
- **Prioritate:** High  

---

## 🐞 2. Imaginile nu se încarcă pe pagina de produs
- **Titlu:** Imaginile nu se încarcă pe pagina de produs  
- **Descriere:** Pe pagina de detalii produs, imaginile apar ca "broken image" (404). Problema apare doar în browserul Chrome.  
- **Pași de reproducere:**  
  1. Accesează pagina unui produs.  
  2. Observă secțiunea de imagini.  
- **Rezultat actual:** Imaginile apar ca "broken image" (404).  
- **Rezultat așteptat:** Imaginile produsului se încarcă normal.  
- **Severitate:** Critical  
- **Prioritate:** High  

---

## 🐞 3. Formularul de înregistrare nu validează emailul
- **Titlu:** Formularul de înregistrare nu validează emailul  
- **Descriere:** Utilizatorii pot introduce adrese de email fără simbolul "@" și formularul acceptă înregistrarea.  
- **Pași de reproducere:**  
  1. Accesează pagina de înregistrare.  
  2. Introdu un email invalid (ex. "testmail.com").  
  3. Click pe "Înregistrează-te".  
- **Rezultat actual:** Formularul acceptă emailul invalid.  
- **Rezultat așteptat:** Sistemul ar trebui să afișeze mesaj de eroare.  
- **Severitate:** Medium  
- **Prioritate:** Medium  

---

## 🐞 4. Pagina de checkout se blochează la pasul de plată
- **Titlu:** Pagina de checkout se blochează la pasul de plată  
- **Descriere:** După selectarea metodei de plată, butonul "Finalizează comanda" nu răspunde și utilizatorul rămâne blocat.  
- **Pași de reproducere:**  
  1. Adaugă un produs în coș.  
  2. Mergi la checkout.  
  3. Selectează metoda de plată.  
  4. Click pe "Finalizează comanda".  
- **Rezultat actual:** Butonul nu răspunde, utilizatorul rămâne blocat.  
- **Rezultat așteptat:** Comanda ar trebui finalizată și confirmată.  
- **Severitate:** Critical  
- **Prioritate:** Highest  

---

## 🐞 5. Footer-ul nu se afișează corect pe mobil
- **Titlu:** Footer-ul nu se afișează corect pe mobil  
- **Descriere:** În versiunea mobilă, footer-ul se suprapune peste conținutul principal și butoanele nu pot fi accesate.  
- **Pași de reproducere:**  
  1. Accesează website-ul pe un telefon mobil.  
  2. Derulează până la footer.  
- **Rezultat actual:** Footer-ul se suprapune peste conținut și butoanele nu pot fi accesate.  
- **Rezultat așteptat:** Footer-ul ar trebui să fie vizibil și funcțional.  
- **Severitate:** Minor  
- **Prioritate:** Low


-------------------------------------------


## 🐞 1. Menu links lead to wrong pages
- **Title:** Menu links lead to wrong pages  
- **Description:** In the main menu, the "Contact" link redirects to the "About Us" page instead of the contact form.  
- **Steps to Reproduce:**  
  1. Open the website.  
  2. Click on the main menu → "Contact".  
  3. Observe the opened page.  
- **Actual Result:** The "About Us" page opens.  
- **Expected Result:** The contact form should open.  
- **Severity:** Major  
- **Priority:** High  

---

## 🐞 2. Product images do not load
- **Title:** Product images do not load  
- **Description:** On the product detail page, images appear as "broken image" (404). The issue occurs only in Chrome.  
- **Steps to Reproduce:**  
  1. Open a product page.  
  2. Check the image section.  
- **Actual Result:** Images appear as "broken image" (404).  
- **Expected Result:** Product images should load normally.  
- **Severity:** Critical  
- **Priority:** High  

---

## 🐞 3. Registration form does not validate email
- **Title:** Registration form does not validate email  
- **Description:** Users can enter email addresses without the "@" symbol and the form still accepts registration.  
- **Steps to Reproduce:**  
  1. Open the registration page.  
  2. Enter an invalid email (e.g., "testmail.com").  
  3. Click "Register".  
- **Actual Result:** The form accepts the invalid email.  
- **Expected Result:** The system should display an error message.  
- **Severity:** Medium  
- **Priority:** Medium  

---

## 🐞 4. Checkout page freezes at payment step
- **Title:** Checkout page freezes at payment step  
- **Description:** After selecting the payment method, the "Place Order" button does not respond and the user is stuck.  
- **Steps to Reproduce:**  
  1. Add a product to the cart.  
  2. Go to checkout.  
  3. Select a payment method.  
  4. Click "Place Order".  
- **Actual Result:** The button does not respond, user is stuck.  
- **Expected Result:** The order should be completed and confirmed.  
- **Severity:** Critical  
- **Priority:** Highest  

---

## 🐞 5. Footer does not display correctly on mobile
- **Title:** Footer does not display correctly on mobile  
- **Description:** On mobile devices, the footer overlaps the main content and buttons cannot be accessed.  
- **Steps to Reproduce:**  
  1. Open the website on a mobile phone.  
  2. Scroll down to the footer.  
- **Actual Result:** The footer overlaps the content and buttons are inaccessible.  
- **Expected Result:** The footer should be visible and functional.  
- **Severity:** Minor  
- **Priority:** Low  
