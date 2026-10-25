# Asistentul meu de învățare

Aplicație pentru Windows: un profesor-tutore AI care ajută la consolidarea lecțiilor din manualele oficiale
(manuale.edu.ro). Asistentul află ce a rămas de la oră, explică ce lipsește (cu desene, scheme, hărți și grafice), exersează
împreună cu elevul, apoi îl lasă să rezolve singur. Nu face temele în locul lui: îl ghidează prin întrebări și indicii.
Are profiluri pentru copii, elevi și adulți, iar datele rămân pe calculator.

Acest depozit conține doar versiunile publicate (programul de instalare). Codul sursă nu este public.

## Descărcare

**[Ultima versiune](https://github.com/SiriusAA/AsistentulMeu/releases/latest)**: la „Assets”, fișierul
`Asistent-Invatare-Setup-<versiune>.exe` (cam 1,4 GB).

## Instalare

1. Rulați fișierul descărcat. Windows poate afișa „Windows a protejat computerul”, pentru că aplicația nu are semnătură
   comercială: apăsați „Mai multe informații” → „Rulează oricum”.
2. Alegeți folderul de instalare (sau lăsați-l cum este). Instalatorul are nevoie temporar de cam 4 GB liberi pe discul C:,
   chiar dacă alegeți alt disc.
3. La prima pornire se deschide configurarea: cine va învăța, cheia AI, clasa și manualele.

## Actualizare

- **Din aplicație** (de la versiunea 3.6.0): „⚙️ Setări → Despre” → „⬇️ Descarcă și instalează”, apoi „🔄 Repornește și
  instalează”. Aplicația nu se actualizează singură, fără să apăsați butoanele.
- **De mână:** descărcați programul de instalare nou de aici și rulați-l peste cel vechi.

În ambele cazuri lecțiile, setările și cheile se păstrează.

## Ce vă trebuie

- Un calculator cu Windows 10 sau 11, pe 64 de biți.
- Internet, pentru configurare și pentru lecții.
- O cheie AI cu credit: Claude (recomandat), OpenAI sau OpenRouter. Aplicația este gratuită; AI-ul îl plătiți direct
  furnizorului, după consum.
- Opțional: o cameră pentru pozele din caiet și un microfon; pentru modelul local (fără internet), o placă video cu cel
  puțin 8 GB de memorie.

## Fișierele unei versiuni

| Fișier | La ce folosește |
|---|---|
| `Asistent-Invatare-Setup-<versiune>.exe` | Programul de instalare (îl descărcați pe acesta) |
| `Asistent-Invatare-Setup-<versiune>.exe.blockmap`, `latest.yml` | Folosite de aplicație la actualizarea din „Setări → Despre”; nu trebuie descărcate de mână |
