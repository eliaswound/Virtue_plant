# Virtue_plant
This is a class defined for a virtue_plant. I am writing this class and making it follow the basic mendallian rule. For the Punnet square generator, credit to # https://github.com/catherinemoresco/PunnetSquareMaker/blob/master/punnetsquaremaker_python3.py

This class have 3 different properties: 
self.genotype provides the genotype of the plant 
self.phenotype provides the phenotype of the plant 
self.virtue provides a virtue storage of the plant, with the form dict{0:[0/1, 0/1],[0/1]}. Where dict[i] is the ith trait, dict[i][0] contains the two alleles, and dict[i][1] is the cross linking stat. 
There are two methods: cross cross the plant with another plant, and return a new plant. after cross. The cross is generated randomly wiht 0.5 prob passing allele to the next gen. 
Punnett square gives a nice square wiht probabilities. 
