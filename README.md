# Egunean behin figurak
Egunean behinerako figura geometrikoak sortzeko kodea.
Galdera hauek sortzeko pythoneko PIL (Python Image Library) libreria sortu dugu.
Hasiera  aldagai lokal bezala egingo dugun irudiaren (oihalaren) tamaina definituko dugu (600,400) eta figurek izango dute hiru kolore posibleak, gorria, berdea eta urdina.
Irudi mota bakoitzak bere funtzioa izango, marrazt_borobola, marraztu_karratua eta marraztu_triangelua.
Funtzioek 4 parametro jasoko dituzte, oihala(draw), posizioa(x,y) eta tamaina.
Funtzio honek tamaina jakin horretako poligonoa marraztuko du esandako tokian, eta ausazko kolore batekin.

marraztu_galdera funtzioak ausaz hiru funtzio hauen artean aukeratu eta n_x bider n_y figura marraztuko ditu.
Eta marraztu ahala, zein koloretako zein figura marraztu duen apuntatuko du, gero zenbat dauden jakiteko.
Horretarako bi zifratako identifikadore bat erabiliko dugu non lehengo zifra figura izango den eta bigarrena kolorea:

0 -Hirukia, 1 - Laukia, 2 - Borobila
0 - Gorria, 1 - Berdea, 2 - Urdina

Beraz :
00 - Hiruki gorria,
01 - Hiruki berdea,
...
22 - Borobil urdina

Fitxategia gordetzerakoan ordenean bakoitzeko zenbat sortu ditugun jarriko dugu fitxategiaren izenean gero datubasera kargatzerako orduan jakiteko irudi horretan zenbat figura/kolore ditugun.
