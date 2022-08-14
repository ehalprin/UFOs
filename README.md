# UFOs

## Overview of Project

### Background

This project was initiated by Dana, a data scientist from McMinnville Oregon. She has been interested in UFOs since an incident in her childhood, and wanted to develop an interactive display of a large data set of information on UFO sightings.

### Tools

The project was completed using JavaScript, HTML, and CSS.

## Results - "UFO Findings" web page

### Process

This web page was first set up using HTML to create the structure for the data table. Using HTML, I created several "inputs" for the user to filter the UFO sighting data. Then, using JavaScript, I created a script to react to any user inputs and filter the data accordingly.

### How-to Guide

This page is a easy way to filter through the UFO sighting data. All you need to do is enter a date, city, state, country, or shape into the "input" open text fields, and the table will adjust automatically. The placeholder text in the input text fields will give you a clue as to how to format your search terms:

![Using Search Term](https://github.com/ehalprin/UFOs/blob/main/static/images/Using_Search_Term.png)

You can also filter using multiple search terms by simply entering a filter into multiple text fields. The table again will adjust automatically:

![Using Multiple Search Terms](https://github.com/ehalprin/UFOs/blob/main/static/images/Using_Multiple_Search_Terms.png)

To clear your search, simply erase your search terms.

## Summary

### Drawbacks

Currently, the page cannot support search by duration or the comments, as these fields are not standardized. The user can also only enter one date to look at a single day, rather than a date range. Also, the user has to type in the "shape" category, and is not provided a list of what shapes have been observed.

### Recommendations

I would suggest next to: (1) standardize the way that the duration entries are formatted, so that duration could be added as an additional search term; and review the "comments" data field to identify interesting key words or tags, as a way to allow the user to search by additional themes not otherwise captured by the existing search elements; (2) allow the user to enter a date range, rather than just being able to look at a single day; and (3) change the "shape" to a drop-down menu, so that the user can see what types of shapes have been recorded, rather than having to guess.
