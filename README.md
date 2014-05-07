# Operation Drunken Noodle

Comparative maps, etc.  A complete rewrite of CMap 
(http://gmod.org/wiki/CMap).  See "doc" directory for PPT/PDF overview of
goals.

# Author

Ken Youens-Clark <kyclark@gmail.com>

# Map data formats

## Tab-delimited

A basic tab-delimite file with the following format (from CMap 1):

         map_name: T1
     feature_name: T1.1
    feature_start: 0
     feature_stop: 1000
 feature_type_acc: contig
  feature_aliases: T1.A,T1.AA

## GFF

Ben Faga proposed a variation on GFF format for CMap data imports:

  ##gff-version 3
  ##cmap-gff-version 1
  # This file was produced from a CMap database using Bio::GMOD::CMap::Admin::GFFProducer
  # Data was created by Apurva Narechania of the Gramene Project
    
  ##cmap_species  species_acc=oryza_sativa;species_common_name=O.%20sativa;species_full_name=Oryza%20sativa;display_order=1
    
  ###
  ##cmap_map_set  map_set_name=Chromosomes;map_set_short_name=Chromosomes;map_type_acc=Seq;map_set_acc=osc1;shape=box;color=blue;width=7;published_on=2008-06-25;unit_modifier=1
  ##cmap_map  map_name=1;map_start=1.00;map_stop=43596771.00;display_order=1
  ##sequence-region   1   1.00    43596771.00
  1   CMap    syntenic_block  272.00  770372.00   .   -   .   ID=syntenic_block5279691;Name=sb3_272-770372;corr_by_id=syntenic_block5279692 synteny
  1   CMap    syntenic_block  771644.00   865909.00   .   +   .   ID=syntenic_block5279693;Name=sb3_771644-865909;corr_by_id=syntenic_block5279694 synteny
