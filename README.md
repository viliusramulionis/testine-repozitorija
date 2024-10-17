# Naudojimasis terminalu:

C:\Users\viliu\Desktop\testine-repozitorija - Absoliutus kelias
. - Terminalo direktorijų struktūroje reiškia esamą direktoriją
.. - Nurodo vieną direktoriją aukščiau nuo esamos
cd - (Change Directory) Komanda kuri norodo esamos direktorijos pakeitimą 


echo "# testine-repozitorija" >> README.md          - Sukuria failą pavadinimu README.md ir jame patalpina tekstą "# testine-repozitorija"

# Naujos repozitorijos sukūrimas naudojat komandas:
git init                                            - Inicijuoja repozitoriją
git add .                                           - Nurodo kokius failus pridedame į commit'ą
git commit -m "first commit"                        - Commit žinutės priskyrimas
git branch -M main                                  - Atšakos (branch) nurodymas
git remote add origin REPOZITORIJOS_ADRESAS         - Github repozitorijos susiejimas
git push -u origin main                             - Commito įkėlimo iniciavimas

# Repozitorijos atnaujinimas:

git add .
git commit -m "update message"
git push
