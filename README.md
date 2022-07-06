# Crypto Hub

Welcome to **crypto hub!** 

A place where people who are not very familiar with cryptocurrency can learn more about the terminology and some of the top coins that dominate the market.

## Site sections:
This site consists of 6 sections/pages:
1. Home
2. Guide
3. Currencies
4. Exchanges
5. Glossary
6. Contact Us
## Business goals
The business goal for this site is to:
1. The site provides a beginners guide to crypto for those who have not much if anything about cryptocurrency.  
2. Generate an interest in cryptocurrency and a desire to further get involved through trading and exploring other services available in the crypto space

## User Goals
The site is primarily focused on first time users as it offers updated content by way of a newsletter and discord server. However, there are some recurring user benefits outlined below:
### First time visitors:
1. I want to easily find useful information regarding cryptocurrency, what it is and how it affects me.
2. I want to learn how I can buy cryptocurrency and what I can do with it after I buy.
3. I want to easily sign up to a newsletter and/or discord server to learn more and stay up to date with new info in the crypto space.

### Recurring Visitors
1. I want to review the glossary of terms to better understand how to assess the performance of currencies in the market.
2. I want to review any updated content to stay up to date with market trends.
3. I want to easily find affiliate links to different social media platforms related to the presented material.

## UX Strategy
---
Crypto Hub aims to bring users on a journey, in line with core UX principles: 
### Target Audience
The site is aimed at users of all ages, as cryptocurrency is still a mysterious topic for many. However, there is a slight leaning towards users aged 18-30, as these users are typically further willing to invest in newer opportunites, rather than more established stock holdings and investment opportunites.

### User Journey
The typical first time user on this site is someone with little to no experience in the cryptospace. As such, the journey should take a user from a novice position, to one who feels they understand the crypto-space enough to begin to invest and explore other associated products.

### Welcome page - A gentle introduction
* This page welcomes the user to the site,  defines what a cryptocurrency is, how it affects the economy and what its purpose is in the global economy. 
* The goal of this page is to introduce crypto in a way that is unambiguous.
* The imagery and text should highlight the colaborative aspect of cryptocurrency and the individuals and groups (countries and companies) that are starting to embrace cryptocurrency as a new legal tender and means of trade.

### Guides - How does it work?
* This page defines what a blockchain is, the different ways to buy crypto, how to store it and a few video links to some helpful explanatory videos.
* A visitor should have a basic grasp of what cryptocurrency is now and will be looking to learn about how they can get involved and what to do once they have purchased their own crypto.

### Currencies - Popular currency review 
* This page goes through some of the most popular currencies and the fundamental differences between them. 
* The first section defines what a whitepaper is to the user and why it is important when it comes to researching different cryptocurrencies to invest in.
* Each section gives an overview of the currency, an exlanation of its technology, its place in the market as well as a link to its whitepaper.
* There is a series of video links covering exactly what a whitepaper is as well as each mentioned cryptocurrency at the bottom of the page.
* At this point, a visitor should have a fair grasp on what a blockchain is, how it is fundamental to cryptocurrency, what sort of currencies they can invest in and how to research any new crypto projects that they might be interested in.

### Popular exchanges - The best places to trade
* This page lists some of the most popular exchanges where you can invest and some key details particular to each exchange. 
* It features a pros and cons list for the chosen exchanges and brief overview of each.
* There are a series of video links covering each exchange and how an exchange works at the bottom of the page.
* Now, a visitor should be informed of how a crytpo exchange works and will have directions to four different popular crypto exchange sites where they can begin trading.
 ### Glossary - Terminology explained
This page goes through some of the more complicated terms when it comes to investing in crypto. It's purpose is to make it easier for a novice investor to make informed decisions about their investments.

### Contact us - Meet like minded individuals
This page gives site visitors the opportunity to sign up to a mailing list and connect with other like minded individuals. It also gives a link to a discord channel where people who subscribe can talk investments and ask questions.


### Assumed content requirement:
There are a few key elements for the requirements of a typical user:

*Information is clear and concise 

## Bug Fixes and Issues
There were multiple bugs encountered during the development of this project. These were listed along with the methods employed as solutions to each.

## Working with percentages
### Issue

* An issue I found when working with percentages was scaling. 
* When adjusting the zoom/resolution for the site, I found that some of the divs were scaling improperly. They were shrinking too a point where they could not hold their content.
* The title div was changing size and proportion to where it was not consistent with the design theme for the rest of the home page. (See fig. 1 & 2 below)

|![percentages bug 1\label{percentages fig. 1}](docs/images/percentages/percentages%20bug%20%231.jpg)|
|:--:|
| <strong>Fig.1 Improper scaling when zooming out</strong>  |



|![percentages bug 2](docs/images/percentages/percentages%20bug%20%232.jpg)|
|:--:|
| <strong>Fig.1 Improper scaling when zooming in</strong>  |


### Fix 
* In order to fix the issue, I started using fixed sizing in pixels for select element widths and heights. 
* I had previously believed that using percentages and vh would be more responsive, but now I can see that using these measurements in the wrong place on a site can create unpredictable site behaviour.

## Link paths
* An issue I found when launching my site to github pages were that one of my pictures was not loading in correctly.
* I investigated the issue and found that I had referenced the image using relative pathing instead of absolute.

### Issue
|![percentages bug 1\label{percentages fig. 1}](docs/images/link-paths/broken-link-1.png)|
|:--:|
| <strong>Fig.3 Image not loading in correctly</strong>  |

### Fix

I updated the link from:
    
        <img id="image-1" class="image"
                        src="/assets/images/women-by-window.jpg"
                        alt="Two women sitting in a chair discussing investment opportunites beside a bright open window.">

And changed it to:

        <img id="image-1" class="image" 
        src="assets/images/women-by-window.jpg" 
        alt="Two women sitting in a chair discussing investment opportunites beside a bright open window.">
                        

Here is the resulting image, loading in correctly
|![percentages bug 1\label{percentages fig. 1}](docs/images/link-paths/broken-link-fix.png)|
|:--:|
| <strong>Fig.4 Image loading in correctly</strong>  |