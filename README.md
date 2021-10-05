# Netflix-movies-and-tv-shows-clustering
The aim of the project is to cluster the content in the Netflix platform based on the description given about the content in the dataset using topic modelling. LDA has been used to do the clustering.
Here are the key take aways from the project.
1. International Movies , Drama and Comedy are the top three genres

2. There is more movie content than TV shows content on Netflix .

3. United States , India and United Kingdom are the top three countries which produced most number of Movies / TV shows.

4. Netflix added highest content in the year 2019 followed by 2020 and 2018.

5. December , October and January are the peak months where the content got added on Netflix.

6. Anupam Kher , Shah Rukh Khan , Om Puri and Nazeeruddin Shah were the top actors on Netflix content.

7. Raul Campos, Jan Suter , Marcus Raboy and Jay Karas were the top directors.

8. Netflix is increasingly focusing on Movies in recent years.

9. Life , Young , Famili , New , Friend are the most common words in our corpus.

10. 6 clusters were generated after clustering ( Topic Modelling ).After analysing the top words in the clusters we were able to name them as 

      Cluster  --  Name   --               	         Top relevant words
         1    --       Crime    --                                  (forc, power , save)
         2    --       International movie  -- 	          (world , seri , special)
         3    --       Romantic      --  	          (man , woman , young)
         4    --       Drama     --                                (famili , young , life)
         5    --       Children and family movies   -- (friend , new , school)
         6    --       Documentary  --                        (life , story , live)

 Best LDA model's params {'n_components': 6}
 Best log likelihood Score for the LDA model -253836.02.
 LDA model Perplexity on train data 2420.73.

