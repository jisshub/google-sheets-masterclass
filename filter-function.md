# Filter Function in Sheets

## Video

https://www.youtube.com/watch?v=HdWmipNreQo

## worksheet

https://docs.google.com/spreadsheets/d/1KE3E3r1LWaitEZKCS6-_pVnSyW0sfETBfISiwy13ND8/edit#gid=0

## Definition

> with this function we get multiple match results.

> results are updated automatically.

> can filter based on one or more columns.

> FITER function only returns true values.

> ie value where conditions are met.

> Filter functions takes 2 arguments.

    1. range
    2. condition

> make sure range is identical in height.

- Requirements
  1. Get app, sales and profit by region.
     **=FILTER(C2:E,B2:B=H4)**
  2. Update function to include sales values > 0.
     **=FILTER(C2:E,B2:B=H4,D2:D>0)**
  3. Sort the results by profit in asecnding order.
     - here v insert FILTER function inside the SORT.
     - later choose column number on which we want to sort.
     - set true means ascending order.
       **=SORT(FILTER(C2:E,B2:B=H4,D2:D>0),3,true)**

---
