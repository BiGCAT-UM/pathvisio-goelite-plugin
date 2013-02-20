GO-Elite plugin for PathVisio
========================

This plugins allows the user to perform GO analysis from within the PathVisio application.
It connects to the GO-Elite (http://www.genmapp.org/go_elite/) webservice and provides the
pruned results of the GO analysis in a table. The GO terms can be visualized as a hierarchical
pathway (features provided by GO plugin - http://www.pathvisio.org/wiki/GoPlugin - still under
development). 

Workflow:
- Load gene database (see www.bridgedb.org/data/gene-database/)
- Load expression data set
- Start plugin and specify parameters
   - Criteria to create input and denominator list
   - Species
   - Number of permuations
   - Z-Score threshold
   - P-Value threshold
   - Min. number of changed genes
- Specify GeneOntology obo file (see http://geneontology.org/GO.downloads.ontology.shtml)
- Run analysis (might take a while)
- Click on result term and GO pathway will be created (make sure visualization is set up, so 
  the data is visualized on the data nodes in the pathway)
