PROJECT DESCRIPTION for exam project in Fundamentals of Biological Databases 

1. Give a brief introduction about the disease phenotype, Melanoma,

2. Retrieve a table of short variations (SNPs and indels) from dbSNP for the phenotype assigned to your project and map those variations to human genes. Create a table in your
database to deposit the result. (Note: Check all the following steps beforehand to decide the required attributes for each table.)

3. Retrieve a table of genomic coordinates and related information of the RefSeq genes you have found in the previous part. Use UCSC table browser for this purpose. Create a table
in your database to deposit the result.

4. Do an advanced search for the phenotype that has been assigned to your project in GEO datasets. Consider human datasets released since Jan 1, 2010 to present and select one
of the sets from the resulting list. Describe the selected dataset in your report. Analyze it with GEO2R. Create a table in your database to deposit the result of GEO2R analysis.

5. Use the phenotype related genes you found in step 2 and map them to human proteins on UniProt. Retrieve their IDs, lengths, primary gene names and masses as another table for
your database. (Hint: Use the ‘ID mapping’ feature in the UniProt website)

6. Construct your database with the collected data in item (2), (3), (4) and (5). How would you enrich this database with some additional tables from other databases? Give two examples.
Explain the conceptual design of your database together with the ER diagram in your report. Also, define the primary and foreign keys in each relation in the database. (Hint: If you are
having trouble linking these tables, you can add an extra “cross-reference” table obtained from either BioMart or UCSC Table Browser)

7. Write down at least 3 queries and SQL commands that will require at least 2 tables and include their results to demonstrate that your database has been constructed properly.

8. Write an SQL command that will give an output of variation name, PDB IDs, Uniprot/SwissProt IDs, RefSeq IDs, exon counts, logFC value of a given gene symbol. 
Add a demo of your database with the query of different gene symbols to your final report. In the demo, select three case studies which can be a protein or a gene.

9. Write down an SQL query to retrieve a list of genes having PDB IDs and exon count is greater than or equal to 4.

10. Write down an SQL query to count a list of genes whose adjusted p-value in GEO2R is smaller than 0.05.
   a. How many genes are significant?
   b. Write down a query to retrieve a list of Uniprot IDs of genes whose adjusted pvalue in  GEO2R is smaller than 0.05 and those having a UniProt ID.
   c. Find the protein interactions among the resulting list by referring to STRING.
   d. Visualize these protein interactions in Cytoscape in force-directed layout. Color downregulated genes in blue and up-regulated ones in red. (Hint: Here, suppose that genes
   having negative logFC value are down-regulated, positive logFC value are upregulated.) Arrange the sizes of the proteins using the length attribute so that the longer
   the protein, the lower its size (e.g., inversely correlated). Add your network figure both to your presentation and to your final report. 
