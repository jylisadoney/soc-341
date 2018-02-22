---
title: Syntax
nav: true
---
# Search Syntax

<style>
table, th, td { 
border: 1px solid black;
border-collapse: collapse;
width: 100%;
}
th, td {
padding: 5px;
}
tr:nth-child(even) {background-color: #f2f2f2;}
</style>

Operator | Description | Example 
---------| ----------- | -------
AND | Each result contains all search terms | public AND vaccines
OR | Each result contains at least one search term | vaccines OR immunizations
(Parentheses) | Groups and combines terms | (vaccines OR immunizations) AND media
NOT | Results do not contain the specified terms | vaccines NOT autism
"Quotation marks" | Results contain exact phrases | "public perception"
Asterisk (*) | Enter the root of a search term and replace the ending with an (*) | vaccin* -- Finds: vaccine, vaccines, vaccination, etc.


Combine search syntax operators:
`(vaccin* OR immuniz*) AND (opinion* OR perception*) AND media`
