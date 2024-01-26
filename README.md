# UT-Austin-Capstone-Project
Property Normalization in air shopping by developing LLMs to enhance accuracy by standardizing 3.5 million addresses formats into a unified structure to streamline data processing.

Dataset description -
1. 'GLBL_PRPTY_ID' - Global Property ID - No Null Values
2. 'PRPTY_ID' - Property ID - No Null Values
3. 'SRC_PRPTY_CD' - Source Property Code - No Null Values
4. 'CHN_CD' - Channel Code ?? Why does it have different formats for values? - Has Null Values
5. 'SRC_CD' - Source Code? Where the entry originates from? - No Null Values
6. 'SRC_GRP_CD' - Source Group Code ?
7. 'SRC_PRPTY_NM' -Source Property Name - No Null Values
8. 'ADR_LINE_1' - Address Line 1 - Has Null Values
9. 'PRIME_ARPT_CD' - Primary Airport Code?? - Has Null Values
10. 'POSTL_CD' - Postal Code - Has Null Values
11. 'CTY_NM' - City Name - Has Null Values
12. 'CNTRY_CD' - Country Code - Has Null Values - Has Codes and Decimals - How to normalize? Are they lattitude/Longitude information?
13. 'LAT' - Lattitude - Has Null Values
14. 'LONGTD' - Longitude - Has Null Value
