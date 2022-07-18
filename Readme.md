### Invoice Calculator

## What is it, why was it created?

Invoice calcuator is a tool to help engineers create invoice estimation in complex scenarios, when there is no invoice available to the customers yet. It was created in order to upgrade from excel spreadsheet and provide engineers with user friendly interface for improved efficiency.

## How does it work?

Tool is meant to be a one file application, so it can be easily downloaded, deployed, shared and used. End product is meant to be set purely in JS, in case of any company firewall policies preventing to load external frameworks. Tool does not store, nor shares any data input provided, everything happens in the local memory and can be wiped with simple refresh of the page, or window close(we consider storage of inserted data within external source file, in case such need appears). File takes name and prices of the subscription, then performs neccessary calculations based on user date input. Tool creates visual representation of an invoice estimation, that can be simply copied to clipboard, printed.saved to PDF with one click button.

## Changelog

# v. 0.1 - Intial planning and base development
     ✓ Front UI Boostrap 5
     ✓ Functions to add & calculate subcriptions
     ✓ Functions to add & remove subcription steaps
     ✓ Invoice Template
     ✓ Invoice Copy & Print function
# v. 0.2 - Initial design and calculation review
     ✓ Custom styles from @Katarzyna
     ✓ Slight UI corrections
     ✓ Confirm alert to prevent accidental deletion of subscriptions/changes
     ✓ Cross checked calculations with manual examples
     ✓ Readme.md

# To do:
     - Calculations need corrections due to not refreshing properly, depending on the data provided order
     - Authorization so that users cannot play without providing neccessary information step by step
     - Refactor to save some lines
     - Add more comments