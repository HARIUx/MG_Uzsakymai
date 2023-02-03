# MG Užsakymų "dashboard"

Problemos kurios buvo išspręstos šios programos pagalba:
* Nebuvo lengvo ir greito būdo patikrinti kiek ir kokie rytiniai/vakariniai užsakymai nesurinkti
* Nebuvo lengvo ir greito būdo patikrinti kiek kurios krypties užsakymų jau surinkta ir kiek dar liko surinkti

Sprendimas:
* Python kalba parašyta programa kuri automatiškai nurodytu intervalu atnaujina informaciją ekrane

Veikimo principas:
1. Programa simuliuoja klaviatūros klavišų paspaudimus tam kad išgautų iš WMS programos .dbf failą su visais užsakymais
2. Programa išanalizuoja .dbf faile esančia informaciją ir išfiltruoja/išrūšiuoja tik MG užsakymus
3. Programa pateikia MG užsakymų informaciją ekrane
4. Programa laukia iki kito intervalo pradžios (po to grįžta į 1. etapą)

Programos išvaizda:
![MG_uzsakymai](https://user-images.githubusercontent.com/77055205/215567599-71db3cd3-1998-40ff-b418-be662abcc5d9.png)


https://user-images.githubusercontent.com/77055205/216558005-d1689015-d715-4009-b731-7a7a2f109c28.mp4

