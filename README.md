# Neo4j Solutions Engineer Technical Assessment

* **Candidate:** Jooho Son
* **Date:** June 2, 2026
* **Target Role:** Senior Solutions Engineer

## Overview
This repository contains the deliverables for the Banking Transaction Analysis technical assessment. The proposed solution focuses on leveraging Neo4j's native graph topology to transition financial institutions from reactive fraud reporting to real-time Anti-Money Laundering (AML) intervention. 

## Directory of Deliverables

* **[`1. Dataset Overview.txt`](https://github.com/sonjooho/neo4j/blob/main/1.%20Dataset%20Overview.txt)**
  Summarizes the raw data, entity mappings, and the business justification for utilizing a graph-first architecture over a traditional RDBMS.
* **[`2. Graph Data Modeling and Data Ingestion.png`](https://github.com/sonjooho/neo4j/blob/main/2.%20Graph%20Data%20Modeling%20and%20Data%20Ingestion.png)**
* **[`2. Graph Data Modeling and Data Ingestion.json`](https://github.com/sonjooho/neo4j/blob/main/2.%20Graph%20Data%20Modeling%20and%20Data%20Ingestion.json)**
  The conceptual graph data model (visualized and exported via arrows.app). It highlights the normalization of identity, instrument, and network authority.
* **[`2. Graph Data Modeling and Data Ingestion.backup`](https://github.com/sonjooho/neo4j/blob/main/2.%20Graph%20Data%20Modeling%20and%20Data%20Ingestion.backup)**
  The complete database export containing the schema, constraints, indexes, and ingested CSV data. The database export from Aura instance, so this is snapshot export as `.backup` file
* **[`3. Cypher Query Development.txt`](https://github.com/sonjooho/neo4j/blob/main/3.%20Cypher%20Query%20Development.txt)**
  The analytical Cypher scripts developed for the assessment, focusing on multi-hop AML rings, merchant risk exposure, and VIP customer segmentation.
* **[`Neo4j AML Pitch Deck.pdf`](https://github.com/sonjooho/neo4j/blob/main/Neo4j%20AML%20Pitch%20Deck.pdf)**
  The presentation deck tailored for the panel session, aligning technical execution with commercial value.
