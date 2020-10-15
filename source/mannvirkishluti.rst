Mannvirkishluti
===============

.. image:: img/mannvirkishluti.svg 
  :width: 100
  :alt: Mannvirki
  :align: left
  
|
|
|
|
|

.. admonition:: Skilgreining
    :class: skilgreining
    
    „Mannvirkishluti er hluti mannvirkis af tiltekinni tegund sem gerður er í einum áfanga og tilheyrir aðeins einni landeign“
    
Hlutverk
--------

Hlutverk mannvirkishluta er að skipta mannvirki niður í hluta eftir framkvæmdaráföngum og mörkum landeigna. Mannvirkishlutinn myndar heild sem útreikningur hlutfallstalna fasteignaréttinda byggir á. Mannvirkishluti er "Abstract" hugtak sem hefur sértækar útfærslur sem ráðast eftir þörfum mismunandi mannvirkja.

Eigindi
-------

.. csv-table:: 
   :header: "Heiti", "Skilgreining", "Skýring", "Tækniheiti", "Stuttheiti",  "Gagnatýpa", "Uppruni", "Birtingarform"

   "**Mannvirkishlutanúmer**", "Mannvirkishlutanúmer er upplýsingalaust einkvæmt auðkenni mannvirkishluta", "", "MannvirkishlutiNr", "MVHLNR",  "raðnúmer innan mannvirkis, pósitív heiltala í hækkandi röð sem byrjar á 1 ", "Framkallað gildi", "[MVNR:MVHLNR] MV-000000:1"
   "**Tegund**", "Tegund mannvirkishluta tilgreinir hvers eðlis mannvirkishlutinn er og ákveður hvaða skráningaratriði eru skráð fyrir viðkomandi tegund mannvirkishluta. Tegundir mannvirkishluta eru Byggingaráfangi, Flötur, Fasteignaréttindi og möguleiki er á að bæta við fleiri tegundum þegar þörf kemur upp á að skrá nýja tegund mannvirkis.", "Tegund tilgreinir erfðavensl", "Tegund", "TEG", "Enumeration ['BAF' - Byggingaráfangi, 'FL' - Flötur, 'FR' - Fasteignaréttindi]", "Skráð gildi", "[Tegund] BAF"


Vensl
-----

Mannvirkishluti tengist því mannvirki sem hann tilheyrir. Einn eða fleiri mannvirkishlutar mynda mannvirki.

.. image:: img/mannvirki_mannvirkishluti.svg 
  :width: 100
  :alt: Vensl mannvirkis og mannvirkishluta

Mannvirkishluti getur verið Byggingaráfangi, Flötur eða Fasteignaréttindi. Mannvirkishluti er "Abstract" hlutur en tegundir hans eru sértækar útfærslur hans.

  .. image:: img/mannvirkishluti_tegund.svg 
  :width: 100
  :alt: Vensl mannvirkishluta og tegundar

