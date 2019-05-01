---
layout: post
title: Lending Club Analysis
subtitle: Exploring Peer to Peer lending
bigimg: /img/borrowing.jpg
---

![GWU Data Science logo](/img/gwdsp.png)

## Lending Club

Since 2007, Lending Club has been helping millions of people take control of their debt, grow their small businesses, and invest for the future. Lending Club is a peer to peer lending company in which investors provide funds for potential borrowers and investors earn a profit depending on the risk they take. It is the world's largest marketplace in this space.  [a link to LendingClub website](https://www.lendingclub.com/)

## How Lending Club work?
1. Customers interested in a loan complete a simple application at LendingClub.com
2. Lending Club leverage online data and technology to quickly assess risk, determine a credit rating and assign appropriate interest        rates.
3. Approved applicants receive offers and can evaluate loan options
4. Investors can choice which type of loan and the return they wish to invest in

The entire process is online, using technology to lower the cost of credit and pass the savings back in the form of lower rates for borrowers and solid returns for investors. Here is the link to more details about LC.

![LendingClub](/img/lendingclub.png)

# Breakdown of loan Grades and Sub loan grades
This is important because Lending Club assigns grades to all the loans as an indicator of risk.  The grade determine the borrower interest rate and the investor potential return rate assuming the loan has been replay.  Grade A is prime (highly loan will be pay back) and Grade G is subprime ( most likely to default)

As the chart show, interest rates increase as the grade and sub-grades increases.

Tableau

{% include rshiny-iframe.html %}

## Where are the loan?
This is a map of the US with the total loan amount.  According to this map, most of the loan are concentrated in California, Texas, New York 
