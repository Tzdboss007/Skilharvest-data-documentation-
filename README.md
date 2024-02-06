# **SkilHarvest-data-documentation**
- My First documentation of SkilHarvest Data Analysis project work 

---
## Project Overview
This Data analysis project seeks to generate insight into Sales inventory records over a number of years. By analysing each parameter in these data it gives a clearer view of how well each item is doing and how to maximize output and increase sales. Further more it gives insight to customers behavior and prefrence when buying stationaries and how to better strategise sales.  
- SkilHarvest-data-documentation [SkilHarvest-data-documentation](#skilharvest_data_documentation)
- Project Overview [Project Overview](#project_overview)
- Data Souce []
---
- Sales of binder item and pencil in 2015 

```
=QUERY(A:H, "SELECT C,F WHERE (C = 'Binder' OR C ='Pencil') AND F = 2015",1)
```
- Sales in Central and East region in 2014
```
=QUERY(A:H, "SELECT A,H,F WHERE (A ='Central' OR A ='East') AND F= 2014",1) 
```
- Sale  in August and september 2014
```
=QUERY(A:H,"SELECT E,F,H WHERE (E = 'Aug' OR  E = 'Sep') AND F = 2014",1)
```
- Show sales of item that start with pen, include their region, sales rep, and year
```
=QUERY(A:H,"SELECT A,B,C,F WHERE C LIKE 'Pen%'",1)
```
- Show sales of item that ends with Sk, include their region, sales rep, and year
```
=QUERY(A:H,"SELECT A,B,C,F WHERE C LIKE '%sk'",1)
```
---

## Data Souce 
The source of data used in this Analysis if from skilhavest practical class  [ClICK HERE TO DOWNLOAD](http://tinyurl.com/2hdwhpvm) 

- Sales of binder item and pencil in 2015 
           
|Item|Year|                                     
|----|----|                     
|Pencil|2015|
|Binder|2015|
|Binder|2015|
|Binder|2015|
|Pencil|2015|
|Binder|2015|
|Binder|2015|
|Pencil|2015|
|Binder|2015|
|Pencil|2015|
|Pencil|2015|
|Pencil|2015|
|Pencil|2015|
|Pencil|2015|
|Binder|2015|
|Binder|2015|
|Pencil|2015|

- Sales in Central and East region in 2014

|Region |	Sales	| Year|
|-------|-------|-----|
|East	|309.38	|2014|
|East	|57.71	|2014|
|Central	|686.95	|2014|
|East	|1619.19	|2014|
|Central	|1005.9	|2014|
|East	|174.65	|2014|
|Central	|250	|2014|
|Central	|9.03	|2014|
|East	|255.84	|2014|
|Central	|251.72	|2014|
|East	|575.36	|2014|
|Central	|18.06	|2014|
|East	|299.85	|2014|
|Central	|54.89 |2014|
|Central	|479.04	|2014|
|Central	|1879.06	|2014|
|Central	|86.43	|2014|
|Central	|139.72	|2014|
|East	|1183.26	|2014|

- Sale  in August and september 2014
   
|Month	|Year	|Sales|
|-------|-----|-----|
|Aug	|2014	|1005.9|
|Aug	|2014	|174.65|
|Aug	|2014	|825|
|Sep	|2014	|250|
|Sep	|2014	|9.03|
|Sep	|2014	|255.84|
|Sep	|2014 |	151.24|

- Show sales of item that start with pen, include their region, sales rep, and year

|Region	|Sales_rep	|Item	Year|	
|-------|-----------|---------|
|East	|Richard	|Pen Set	|2014|	
|Central	|Morgan	Pen Set	|2014|	
|Central	|Matthew	Pen Set	|2014	
|East	|Richard Pencil	|2014|	
|Central	|Bill	Pencil	|2014|	
|East	|Richard	Pen Set	|2014|	
|West	|James	Pen	|2014|	
|East	|Richard	Pen	|2014|	
|Central	|Rachel	Pencil	|2014|	
|East	|Susan	Pen	|2014|	
|Central	|Matthew	Pen Set	|2014|	
|Central	|Smith	Pencil	|2014|	
|East	|Susan	Pen Set	|2014|	
|East	|Richard	Pencil	|2015|	
|Central	|Alex	Pencil	|2015|	
|Central	|Bill	Pen	|2015|	
|West	|James	Pencil	|2015|	
|Central	|Alex	Pen Set	|2015|	
|Central	|Rachel	Pencil	|2015|	
|Central	|Rachel	Pencil	|2015|	
|East	Nick	|Pen	|2015|	
|Central	|Alex	Pencil	|2015|	
|Central	|Bill	Pencil	|2015|	
|West	|Thomas	Pencil	|2015|	
|Central	|Morgan	Pencil	|2015|	

- Show sales of item that ends with Sk, include their region, sales rep, and year
     
|Region	|Sales_rep	|Item	Year|
|-------|-----------|---------|	
|West	|James	Desk	|2014|	
|Central |Smith	Desk	|2014|	
|Central	|Matthew	Desk	|2015|

---
## Tools Used 
Just one tool was used for both the Analysis and Visulaisation of the above data
- Google sheet [click Here](http://tinyurl.com/suswph5a)


