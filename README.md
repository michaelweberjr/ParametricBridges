# Parametric Bridges
This is a dynamo/python script for Autodesk Revit 2020 and dynamo version 2.X (I have tested with 2.2 & 2.3).

The script requires BimorphNodes, LunchBox and Springs installed in your dynamo.

# How to use

The script has all of it's inputs on the left side of the visual interface. It requires an excel file with the roadway alignment that you want the bridge to span.
Spans define where the peirs are placed. You specify this in an array where each value is the length of the span and the last span is given the value '-1' to span to end of the alignment.
