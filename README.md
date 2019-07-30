[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Payment Channel Analysis
===

[Paper](./channel-analysis.pdf)

## Abstract

Payment channels are one part of the scalability solution and user experience enhancement. Various schemes have been proposed in the past years with specific use cases. We propose new definitions to help classifying payment channels and analyze various Bitcoin channel schemes. We summarize the analyzed protocols and highlight their strong points.

## Introduction
Payment channels or micropayment channels are one part of the scalability solution. The idea of payment channels was suggested by Satoshi in an email to Mike Hearn. Since then, various schemes to construct such structures have been proposed. To have a better understanding of the differences between various channel schemes, and to be able to analyze a channel scheme objectively, we propose a list of characteristic definitions for payment channel construction. An analysis of different commonly exposed payment channel constructions is done following these definitions. The list does not contain all the payment channel schemes, some of them might be missing. However, the list contains a fairly good representation of the different existing constructions.

## Building LaTex

A `Makefile` is provided into folder to compile the project, use

```
make
```
