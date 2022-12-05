---
layout: post
title: Perform a Simple Geospatial Workflow with Decentralized Data
sub_heading: ''
date: 
tags:
- geospatial
- web3
- Landsat
- NDVI
- Filecoin
- IPFS
banner_image: ''
related_posts: []

---
## Introduction

In the \[last post\] we talked about how the STAC specification can be enriched with CIDs in order to reference geospatial data from decentralized storage systems. In this post, we are going to put everything together by fetching a Landsat scene from FileCoin via A STAC server. We'll then pin our Python notebook to IPFS so anyone in the world can replicate our workflow.

## How to Calcuate NDVI for a Landsat Scene

NDVI is used to quantify vegetation greenness and is useful in understanding vegetation density and assessing changes in plant health. NDVI is calculated as a ratio between the red ( R ) and near infrared ( NIR ) values in traditional fashion. According to USGS, for landsat 9, the following band math can be used to calculate NDVI

> NDVI = (Band 5 – Band 4) / (Band 5 + Band 4)
>
> [Source](https://www.usgs.gov/landsat-missions/landsat-normalized-difference-vegetation-index "USGS NDVI Band Math")

## Fetch Bands 4 and 5 from a Landsat Scene

The EASIER Data Inititiae 

## Calcuate NDVI

WIP

## Pin Python Notebook to IPFS

WIP