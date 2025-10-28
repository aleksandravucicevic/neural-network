# Analiza RCV1 skupa podataka pomoću neuronske mreže i LightGBM klasifikatora
Ovaj projekat prikazuje proces obrade i klasifikacije RCV1 skupa podataka korištenjem dva različita pristupa mašinskog učenja (ML):
* **neuronsku mrežu** sa 3 skrivena sloja, implementiranu pomoću _Keras_ biblioteke
* **LightGBM klasifikator** poznat po efikasnosti i brzini u radu sa velikim skupovima podataka.

Cilj projekta je uporediti performanse ova dva modela kroz metrike tačnosti, preciznosti, odziva i F1 vrijednosti.

## Rezultati i zaključak
Eksperimentalni rezultati pokazuju da **LightGBM** postiže bolje performanse u tačnosti u odnosu na neuronsku mrežu, uz znatno manju potrošnju resursa i brže treniranje.
S druge strane, **neuronska mreža** omogućava bolju skalabilnost i prilagodljivost većim i složenijim skupovima podataka, ali zahtijeva duže vrijeme izvršavanja.

## Ključne tehnologije
* Python 3.11+
* Keras/TensorFlow
* LightGBM
* scikit-learn

# Autorska prava
© 2025 Aleksandra Vučićević
