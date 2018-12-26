Quick Excel Formulae

// To get the status from the salesforce report's Raw status field 
=MID(B2,SEARCH("alt=",B2)+5,(SEARCH("""",B2,SEARCH("alt=",B2)+5))-(SEARCH("alt=",B2)+5))