# Repro

This repo is based on the template provided by `react-native-reusables`.


Just npm install, run web.

## Select in dialog issue

Link: http://localhost:8081/checkbox

Click the button to see the issue with the select inside of dialog.

The behaviour is broken in both chrome and firefox, but in firefox I also get errors:

> Uncaught InternalError: too much recursion

## Aria-label

Link: http://localhost:8081/checkbox

Click on the label. The checkbox does not get toggled.
