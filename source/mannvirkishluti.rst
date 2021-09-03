

Mannvirkishluti 
===============

.. image:: img/mannvirkishluti.svg 
   :width: 100

Skilgreining
------------

.. admonition:: Skilgreining
    :class: skilgreining
    
    „Mannvirkishluti er hluti mannvirkis af tiltekinni tegund sem gerður er í einum áfanga og tilheyrir aðeins einni landeign“
   
Hlutverk
--------

Hlutverk mannvirkishluta er að skipta mannvirki niður í hluta eftir framkvæmdaráföngum og mörkum landeigna. Mannvirkishlutinn myndar heild sem útreikningur hlutfallstalna fasteignaréttinda byggir á. Mannvirkishluti er "Abstract" hugtak sem hefur sértækar útfærslur sem ráðast eftir þörfum mismunandi mannvirkja.


.. _mannvirkishluti_eigindi:
Eigindi
-------

Mannvirkishlutanúmer
~~~~~~~~~~~~~~~~~~~~

:Skilgreining:
 Mannvirkishlutanúmer er upplýsingalaust einkvæmt auðkenni mannvirkishluta

:Skýring:

:Tækniheiti:
 MannvirkishlutiNr
:Stuttheiti:
 MVHLNR

:Gagnatýpa:
 raðnúmer innan mannvirkis
 pósitív heiltala í hækkandi röð sem byrjar á 1 

:Uppruni:
 Framkallað gildi

:Birtingarform:  
 [MVNR:MVHLNR] MV-000000:1

Tegund
~~~~~~~~~~~~~~~~~~~~ 

:Skilgreining:
   Tegund mannvirkishluta. 
:Skýring:
   Tegund tilgreinir erfðavensl. Tilgreinir hvers eðlis mannvirkishlutinn er og ákveður hvaða skráningaratriði eru skráð fyrir viðkomandi tegund mannvirkishluta.    Tegundir mannvirkishluta eru Byggingaráfangi, Flötur, Fasteignaréttindi. Möguleiki er á að bæta við fleiri tegundum mannvirkishluta þegar þörf kemur upp á að skrá nýja tegund mannvirkis.

:Tækniheiti:
   Tegund

:Stuttheiti:
   TEG

:Gagnatýpa:
   Enumeration 

   .. csv-table:: 
     :header: "Kóði", "Skilgreining"

     "BAF", "Byggingaráfangi"
     "FL", "Flötur"
     "FR", "Fasteignaréttindi"

:Uppruni:
   Skráð gildi

:Birtingarform:
   [Tegund] BAF

 
Ist 120 flokkur
~~~~~~~~~~~~~~~
  
 .. todo::
  Vantar að klára eigindi
  
:Skilgreining:
 

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 String (enum) 
 
:Uppruni:
 
 
:Birtingarform: 
 
 
Eignarhlutfall
~~~~~~~~~~~~~~
  
 .. todo::
  Vantar að klára eigindi
  
:Skilgreining:
 

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 Pósitív Rauntala 
 
:Uppruni:
 
 
:Birtingarform: 
 

Vensl
-----

Mannvirki
~~~~~~~~~
  
.. figure:: img/mannvirki_mannvirkishluti.svg 
   :width: 100
   :alt: Vensl mannvirkis og mannvirkishluta
   
   
   Vensl mannvirkishluta og mannvirkis

Mannvirkishluti tengist því mannvirki sem hann tilheyrir. Einn eða fleiri mannvirkishlutar mynda mannvirki.

Rekstrareining
~~~~~~~~~~~~~~
  
.. figure:: img/mannvirkishluti_rekstrareining.svg 
   :width: 100
   :alt: Sértækar útfærslur mannvirkishluta
   
   
   Vensl mannvirkishluta og rekstareiningar
   
   
Mannvirkishluti skiptist í eina eða fleiri rekstrareiningar.

Mannvirkishluti
~~~~~~~~~~~~~~~
   
.. figure:: img/mannvirkishluti_tegund.svg 
   :width: 380
   :figwidth: 500
   :alt: Sértækar útfærslur mannvirkishluta
   
   
   Erfðavensl mannvirkishluta 
  
Mannvirkishluti getur verið Byggingaráfangi, Flötur eða Fasteignaréttindi. Mannvirkishluti er "Abstract" hlutur en tegundir hans eru sértækar útfærslur hans.

