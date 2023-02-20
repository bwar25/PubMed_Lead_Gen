# PubMed Lead Generation

**Lead Gen from PubMed**
</br>
## General
```
`PubMed_Classes` houses the classes, and are imported into `PubMed_Download` for use. 

Aside from a couple of inputs for each class, the script automatically results in a csv & dataframe which stores the information we use to upload into the CRM.

The 1 required change is in `PubMed_Classes` where the variable `self.filename` within the function `download_articles` within the class `ScrapePubMed` is set to an example file.

Export `Clean.final_df` to a csv in order to use.
```
