NeTEx-XML
=========

Netex XML Schema 

NeTEX XMl schema
(C) 2009-2017  NeTEX , CEN, Crown Copyright
        
NeTwork EXchange XML Schemas for : Core, Part 1 (Network), Part 2 (Timetables), Part 3 (Fares)
================================================

This is version 1.04 of the CEN NeTEx schema
See the NeTEx UML Physical and Conceptual models for an UML view

The schema is modularised into subschemas, grouped into directories corresponding to the  Part 1,  Part 2  and  Part 3  schema. 

There is an XMLSpy project file in the root directory that provides an organised view of the schemas and examples
    
  - netex-v01.04.spp
  
There is also an Oxygen project file

  - netex-v01.04.xpr

====================

Getting Started:
  
There are two main root schemas

  - netex_publication : Embeds NeTEx XML model elements in a bulk output file format for use in asynchronous publication. The intended content scope can be indicated by a filter object. 

  - netex_siriSG.xsd : Embeds NeTEx XML model elements in the SIRI protocol  for dynamic exchange of elements between servers. Both Request/response and publish/subscribe is supported

In addition

  - nx.xsd : Embeds NeTeX XML model elements within a simple thematic organisation to facilitate browsing and inspection of NeTEx. 
    The NX schema is not intended for actual use. 

There are XML examples of the use of both protocols, see examples subdirectory.

   
=====================================================================================================================
    See ReadMe.txt file for list of changes

