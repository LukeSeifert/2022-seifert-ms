# Seifert Master Thesis



Molten salt reactors have had many depletion models generated since being announced as a generation IV reactor. Among these models, one important aspect which is considered is the online reprocessing capabilities of a liquid fueled molten salt reactor. This includes adding fresh fuel and removing fission products from the reactor during operation, allowing for a more efficient neutron economy.

In order to simulate reprocessing, there are two different mathematical approaches which are implemented, called batchwise and continuous reprocessing. For online reprocessing, the continuous reprocessing method is more physically reflective of the operation in reality. However, there are many works which have implemented batchwise reprocessing to simulate a continuous reprocessing process.

This work shows that continuous reprocessing and batchwise reprocessing methods are not interchangeable, and there is a fairly large difference in the results when using the two different approaches for the same system. This work also shows the computational cost and a depletion step mesh refinement for both continuous and batchwise reprocessing. From those results, it is determined that continuous reprocessing allows for significantly larger steps without large increases in error, which enables drastically reduced computational cost on the order of one magnitude. The effect of density increase when using the Serpent2 code due to continuous reprocessing is also investigated, and it is determined that for typical operations, the density change is roughly 0.12\%.
