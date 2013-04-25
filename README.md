LinkCheck
=========

This application will scan web pages and find all the links that do not return status code 200 OK.  

It includes the following files in the package com.paypal.test.application.doc:
  DynamicCollectionIterator.java   
  WebPageBaseTest.java             
  WebPageLinkTest.java              
  a data file DocDeveloper.xls


More detailed information for files:
  WebPageBaseTest.java
    It is a base class, declared WebDriver, some common tests can be implemented in this class

  webPageLinkTest.java
    It has the following functionality
      a. Load the base URL and check all the links on the web pages that reside inside the base URL
      b. Load the URLs that user specified and check all the links for those pages

  DynamicCollectionIterator.java
    It ensures removing elements while iterating the list

  DocDeveloper.xls
    It has the following sheets
      a.landingPage: defindes all the base URLs. All the web pages resided inside the base URLs will be scanned. 
      b.Links: define all the individual pages that need to be scanned

Future work:
    Log parent page for all the URLs that scanned 


Contact:
    qiwilliams@paypal.com
