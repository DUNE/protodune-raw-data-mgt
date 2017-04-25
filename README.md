# Data Management Documents for protoDUNE
## Overview
This repository contains documents for a proposed raw data managment system and a few online
components for the protoDUNE single-phase detector (CERN experiment NP04), which is scheduled
to take data with CERN SPS beams in late 2018. The dual-phase detector (NP02) employs a somewhat
different approach to data management however there are overlaps in the infrastructure which is
mentioned in some of the documents provided here.

## Data Handling
* Archive/protoDUNE-DMS-design.tex is a description of a specific design of the data management system based on deployment and reuse of F-FTS, which is a data management system supported by FNAL.

* Archive/*pdrdm.tex* is an initial note evaluating basic design requirements.

* Archive/*spbf.tex* is a stub for the document to describe testing of the Single-Phase protoDUNE Disk Buffer Farm. This probably won't be updated due to the decision to use commercial storage appliance for the buffer, to be procured at CERN.

* Archive/*uoob.tex* is a document which explores a few different options for passing the data from the DAQ pipeline to storage and looks at issues such as event interlacing etc.

* Archive/*TB_online_June2016* is a report to the DUNE Technical Board

* Archive/*neut-buffer.tex* describes a concrete implementation of a xrootd storage cluster at CERN which is a candidate for the single-phase protoDUNE online buffer. Obsolete due to design decisions as described above.

## Workflow

* Documents whose names starts with "prompt" are related to the prompt processing system for protoDUNE. These currently include requirements and a design proposal.
* "p3s plan 2017" contains (as the name suggests) description of work that needs to be completed in 2017 with system components, milestones etc as necessary to be on track for the protoDUNE commissioning.

## Presentations

The folder "CHEP16" contains the materials for the paper to be published in the proceedings of the CHEP 2016 conference which concerns data management in protoDUNE.


## Graphics

* the folder *"figures"* contains graphics to all of these documents, with the exception of the CHEP paper which has its own graphics folder

## Built PDFs

Go here:

https://dune.bnl.gov/docs/

