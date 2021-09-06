Bygging 
===============

.. image:: img/bygging.svg 
   :width: 100

Skilgreining
------------

.. admonition:: Skilgreining
    :class: skilgreining
    
    „Bygging er mannvirki með nýtanlegt rými í samræmi við tilgang byggingarinnar“
   
Hlutverk
--------

 .. todo::
  Vantar að skilgreina hlutverk Byggingar

Eigindi
-------

Byggingarnúmer
~~~~~~~~~~~~~~
  
:Skilgreining:
 Byggingarnúmer er upplýsingalaust einkvæmt auðkenni mannvirkishluta

:Skýring:

:Tækniheiti:
 ByggingNr
 
:Stuttheiti:
 Byg

:Gagnatýpa:
 pósitív heiltala í hækkandi röð

:Uppruni:
 Framkallað gildi

:Birtingarform:  
 [B-*ByggingNr*] B-000000

Byggingarform
~~~~~~~~~~~~~
  
:Skilgreining:
 Byggingarform er flokkun

:Skýring:

:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 strengur (enum listi)

:Uppruni:
 Innlesið gildi

:Birtingarform:  
 "Íbúðarbygging"
 
Ummál botnplötu
~~~~~~~~~~~~~~~
  
:Skilgreining:
 Ummál botnplötu sem liggur að jörð

:Skýring:
   Hlutfall á milli flatarmáls og ummáls byggingar segir til um hversu mikið flækjustig er í byggingunni

:Tilgangur:
  

:Tækniheiti:
 BotnM
 
:Stuttheiti:
 BotnM

:Gagnatýpa:
 rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*BotnM* m] 0,0 m
 
Flatarmál botnplötu
~~~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Sá botnflötur byggingar sem liggur að jörðu auk þeirra botnflata sem skaga út fyrir hæðina fyrir neðan

:Skýring:
   Þegar hæð er stærri en hæðin sem er fyrir neðan hana verður flöturinn sem stendur út fyrir botnplata.
   *Ath ekki sama og núverandi botnflatarmál sem er núna heildar brúttóflatarmál byggingar.*
   Hlutfall á milli flatarmáls og ummáls byggingar segir til um hversu mikið flækjustig er í byggingunni.

:Tilgangur:
  Heildar rúmmál byggingar skiptist í rúmmál botnplötu annarsvegar og rúmmál hæða hinsvegar. 
  
  .. todo::
     Hversvegna þarf að halda sérstaklega utan um rúmmál botnplötu.

:Tækniheiti:
 BotnM2
 
:Stuttheiti:
 BotnM2

:Gagnatýpa:
 rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*Botnm2* m²] 0,0 m²
 
Flatarmál útveggja
~~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Nettóflatarmál yfirborðs útveggja

:Skýring:
   Flatarmál útveggja er mælt frá efri brún botnplötu

:Tilgangur:
  Tilgangur með skráningu er að reikna byggingarkostnað og viðhaldskostnað
  
:Tækniheiti:
 Utveggirm2
 
:Stuttheiti:
 Utvm2

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*Utveggirm2* m²] 0,0 m²
 
  
Flatarmál veggopa
~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Nettóflatarmál opa í útveggjum byggingar

:Skýring:
   Flatarmál glugga, hurða og annarra opa í útveggjum byggingar

:Tilgangur:
  Tilgangur með skráningu er að reikna byggingarkostnað og hitatap
  
:Tækniheiti:
 VeggOpm2
 
:Stuttheiti:
 VeggOpm2

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*VeggOpm2* m²] 0,0 m²
 
Flatarmál þaks
~~~~~~~~~~~~~~
  
:Skilgreining:
 Raunflötur þaks

:Skýring:
   Raunflötur er flatarmál þaks ásamt þakkanti og kvistum. 

:Tilgangur:
  Tilgangur með skráningu er að reikna byggingarkostnað og hitatap
  
:Tækniheiti:
 ThakM2
 
:Stuttheiti:
 ThakM2

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*ThakM2* m²] 0,0 m²
 
Flatarmál þakopa
~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Flatarmál opa í þaki

:Skýring:
   

:Tilgangur:
  Tilgangur með skráningu er að reikna byggingarkostnað og hitatap
  
:Tækniheiti:
 ThakOpM2
 
:Stuttheiti:
 ThakOpM2

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*ThakOpM2* m²] 0,0 m²
 
Flatarmál berandi platna
~~~~~~~~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Flatarmál berandi platna í byggingu

:Skýring:
  Berandi plötur eru láréttir millifletir
  
.. note:: Skýra greinarmun á berandi plötu og láréttum millifleti

:Tilgangur:
  Tilgangur með skráningu er að reikna byggingarkostnað og hitatap
  
:Tækniheiti:
 BerandiPlataM2
 
:Stuttheiti:
 BplM2

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 Innlesið gildi  (ekki null)
 
:Birtingarform:  
 [*BerandiPlataM2* m²] 0,0 m²
 
Flatarmál fylling platna
~~~~~~~~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 Flatarmál fylling platna í byggingu

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 
 
:Birtingarform:  
 
 
Flatarmál kaldar platna
~~~~~~~~~~~~~~~~~~~~~~~
  
:Skilgreining:
 

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 
 
:Birtingarform:  
 
 
Ummál
~~~~~
  
:Skilgreining:
 

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 
 
:Birtingarform:  
 
 
 
Brúttó ummál
~~~~~~~~~~~~
  
:Skilgreining:
 

:Skýring:
  

:Tilgangur:
  
  
:Tækniheiti:
 
 
:Stuttheiti:
 

:Gagnatýpa:
 pósitív rauntala 
 
:Uppruni:
 
 
:Birtingarform:  
 
 

Vensl
-----

Byggingaráfangi
~~~~~~~~~~~~~~~
  
.. figure:: img/bygging_byggingarafangi.svg 
  :width: 100

  Vensl byggingar og byggingaráfanga

Bygging samanstendur af byggingaráföngum.
