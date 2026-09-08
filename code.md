=IF($B$3="","",FILTER($A$61:$E$110,(UPPER(TRIM($F$61:$F$110))=UPPER(TRIM($B$3)))+(UPPER(TRIM($C$61:$C$110))=UPPER(TRIM($B$3))),"No matches found"))
