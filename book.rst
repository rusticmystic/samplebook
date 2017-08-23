.. ----------------------------------------------------------------------------
.. Title:   Sample Book
.. Author:  Shivdeep Singh
.. Date:    August 2017
.. License: Creative Commons Share-Alike Non-Commercial International 4.0
.. ----------------------------------------------------------------------------

.. meta::
   :description: An open-source sample book 
   :viewport: width=device-width, initial-scale=1, maximum-scale=1

.. |date| date::  %B %Y
   
===============================================================================
                             Sample Book                              
===============================================================================
-------------------------------------------------------------------------------
       Copyright (c) 2017 - Shivdeep Singh <manhasshivdeep@gmail.com> 
-------------------------------------------------------------------------------

.. default-role:: code

.. container:: title-logos

   .. image:: data/cc.large.png
      :width: 40px
   .. image:: data/by.large.png
      :width: 40px
   .. image:: data/sa.large.png
      :width: 40px
   .. image:: data/nc.large.png
      :width: 40px

   |
   | Latest version - |date|
   | 

.. ----------------------------------------------------------------------------
.. container:: title-logos

   .. image:: data/cubes.png
      :width: 100%

.. ----------------------------------------------------------------------------

This is a Sample Book. Designed in restructured text.

.. ----------------------------------------------------------------------------
.. contents:: **Table of Contents**
   :class: main-content
   :depth: 2

|
|

**Disclaimer:** All external pictures should have associated credits. If there
are missing credits, please tell me, I will correct it. Similarly, all excerpts
should be sourced (wikipedia mostly). If not, this is an error and I will
correct it as soon as you tell me.
           
.. ----------------------------------------------------------------------------
.. |WIP| image:: https://img.shields.io/badge/status-WIP-orange.svg?style=flat-square

.. ----------------------------------------------------------------------------
.. include:: 01-Preface.rst                  
.. include:: References.rst


.. --- Compilation ------------------------------------------------------------
.. rst2html.py --link-stylesheet --stylesheet=markdown.css book.rst book.html
