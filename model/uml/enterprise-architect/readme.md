# OGC Soil Data Interoperability Experiment

## Configuring Enterprise Architect for the OGC Soil Data IE

The template Sparx Enterprise Architect project file soil-data-ie-template.eap has been created to get users started with the information modelling.

!! IMPORTANT !!

Please do not check-out and modify soil-data-ie-template.eap - instead create a local copy yourself and manage it as below.

At times this template will be updated - for example if new reference models become available, or existing ones are updated.

Participants who don't want to use Enterprise Architect (otherwise known as 'sane people') can browse the HTML version of the model at https://github.com/opengeospatial/model/html/

## OVERVIEW OF soil-data-ie-template.eap

It contains an un-versioned package for the existing models that are evaluated, used, and /or extended by this interoperability experiment:

Common Models:

    Hollow World - release 4            baseline ISO TC/211  and OGC packages

    GeoSciML - v3.2                     the GeoScience Mark-up Language (used by ANZSoilML).

    Timeseries Profile of O&M - rc1.0   the new profile of Observations and Measurements for timeseries/monitoring data.

!! NOTE THAT these files represent the work of other communities and are to be treated with the appropriate considerations for 

!! IP and copryright and so on. Please don't edit these models or redistribute without appropriate permission.
	
It contains one SVN version package that references version controlled XMI files held in this SVN repository.

   Soil Data IE

## USING soil-data-ie-template.eap
	
The following assumes you have checked out this SVN repo as a SVN 'working copy'.

0. Open soil-data-ie-template.eap and save as a local project name (e.g. soil-data-ie-BS.eap)

1. Set up Enterprise Architect Version Control Configurations in the new Project file:

   In Enterprise Architect, set up or confirm the following Version Control Settings:

      Unique ID         Type        Repository

      SoilDataIE-trunk  Subversion  working copy of https://svn.opengeospatial.org/ogc-projects/ip/SoilDataIE/trunk/uml

2. Load the ANZSoilML UML model

   In Enterprise Architect:

      Right click on the root model icon... Package Control -> Get Package

      Select the Version Control Configuration for SoilDataIE-trunk

      Select the shared file for 'soil-data-ie.xml'

         !! don't load any of the other packages manually - you'll get them in the next step. 

         (EA didn't allow me to follow the previous 3 steps - instead I went straight to next step - BS)

      Right click on the root model icon and select Package Control -> Get All latest