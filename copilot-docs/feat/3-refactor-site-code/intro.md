# Refactor Site Code Feature Introduction

The "Refactor Site Code" feature aims to Update the github pages site to use bootstrap to style the website. 

## Purpose

The primary purpose of this feature is to refactor the website code to be more readable and manageable.

## Context

GitHub Pages is a popular service that allows users to host websites directly from their GitHub repositories. This feature will update the website code to make it easier to read and to manage the site content. 

## Background Information

- **index.html** currently the site is 1 monilith index.html file. 
- We would like to break index.html into multiple files.
  - We would like to create a base.html file to be used as the site template
  - We would like individual html files for each page that will be an extension of the base.html to show the contents inside of the template without duplicating code. 
  - We want use use a file and directory structure for managing html files, images, css, and javascript files. 


This document serves as an introduction to the "Refactor Site Code" feature, providing the necessary context and background for successful implementation.