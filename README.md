<header> 
 #1.Transfer Data
</header>   
   1.1 	Groovy to call the Data Map

Below code can be used to run the data map and can attached in the Forms

```bash
operation.application.getDataMap("Datamap_Name").execute(true)
```
Data map Name : Update the data map name to get executed
True/blank: Boolean parameter to clear the data before push pushing the data. 
	Selecting  “execute(true)” will clear the data before pushing the data
	Selecting  “execute()” will not clear the data before pushing the data
Note 1: Consider there is a threshold of 200MB.
Note 2: This groovy rule will be executed by admin users only.
