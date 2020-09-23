# [MAD] Chapitre 1: Généralités - Ensembles

## Relations

   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/Images/MAD/Ensembles/ENSEMBLES3.png" /></p>

    
## Formules / Propriétés
    
   * #### Schématisées
    
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLES.jpg" /></p>
    

   * #### Tableau
    
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/Images/MAD/Ensembles/ENSEMBLES4.png" /></p>
    
     
   * ### Définition de la différence
   
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/DIFFERENCE.png" /></p>
   
   
   * ### Différence Symétrique
   
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/DIFFERENCE_SYMETRIQUE.png" /></p>
   
   
## Cardinalité

   * ### Exemples

   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/CARDINAL_EX1.png" /></p>
    
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/CARDINAL_EX2.png" /></p>
   
   <p>  |*A ∪ B*| = |A| + |B| -  |A ∩ B|</p>
   <p>|*A /_\ B*| = |A| + |B| - 2|A ∩ B|</p>
   
   * #### Formule(s) Cardinalité De l'Union
    
   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/CADINAL_UNION.png" /></p>
    

## Ensemble Des Parties

   * ### Exemples
    
        - Généralités :
    
            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE1.png" /></p>
    
            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE3.png" /></p>

        
        - Ensembles :
    
            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE5.png" /></p>
        
            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE6.png" /></p>
    

     * ### Formule(s)

      - De manière générale :
        
        <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE2.png" /></p>
    
       - Nombre de sous ensemble **propres et non-vides** :
        
       <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/ENSEMBLE_PARTIE4.png" /></p>


## n-uples / Produit Cartésien

   * ### n-uple
        
        - Couple de **n** éléments
        
        - (a,b) => duplet
        
        - (a,b,c) => triplet

        - ...


   * ### Produit Cartésien

        - Définition :
            
            Le produit cartésien de **n** ensembles correspond à l'ensemble des couples de **n** éléments (**n-uples**) formés de chaque éléments de chaque ensembles


        - Formule(s)

            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/PRODUIT_CARTESIEN1.png" /></p>

            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/PRODUIT_CARTESIEN2.png" /></p>


        - Exemples

            <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/PRODUIT_CARTESIEN3.png" /></p>

             <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/PRODUIT_CARTESIEN4.png" /></p>

        - Appartenance ∈ et Inclusion ⊆

        *Méthodologie :*

        Pour savoir si A ∈ B on enlève les accolades des deux côtés, et les valeurs de gauches doivent être écrites identiques à droite (mais il peut y'en avoir plus à droite)

       {2} ∈ {1;2;3;4;5;6;7}
       
       2  ∉ {1;2;3;4;5;6;7}
       
       {{2}} ∈ {{1};{2};3;4;5;6;7}


        Pour savoir si A ⊆ B, on enlève les accolades seulement à *droite* et les valeurs de gauches doivent être écrites identiques à droite (mais il peut y'en avoir plus à droite)

        {2} ⊈     {1;2;3;4;5;6;7}
        
        2  ⊆     {1;2;3;4;5;6;7}
        
        {{2}} ⊈     {1;2;3;4;5;6;7} 
   
      ### Table d'appartenance 
         
      Soit 𝐴, 𝐵 et 𝐶 trois ensembles (dans un univers 𝛺). Vérifier l'identité suivante au moyen d'une table d'appartenance :
   
      <code> 𝐴 \ (𝐵 ∪ 𝐶) = (𝐴 \ 𝐵) ∩ (𝐴 \ 𝐶)<ecode>
   
      1. Placer les trois ensembles et en enumérer toutes les combinaisons (binaire)
      2. Effectuer les combinaisons:
         𝐴 ∪ 𝐵 : si 𝐴 _ou/et_ 𝐵 est à 1 -> 1 
         𝐴 ∩ 𝐵 : si 𝐴 _et_ 𝐵 sont à 1 -> 1
         𝐴 \ 𝐵 : on effectue 𝐴 - 𝐵. Si 𝐴=1 et 𝐵 = 0 -> 1 sinon -> 0
   
   
      <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/1.14-TablesD'appartenance.png" /></p>
   
   
         

## Puissance D'un Ensemble

   * ### Exemples

   <p align="center"><img src="https://raw.githubusercontent.com/gottburgm/Share/master/PGITF/Images/PUISSANCE_ENSEMBLE.png" /></p>
