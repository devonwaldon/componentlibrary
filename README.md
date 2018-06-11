# Atomic Development

>Adapted from the 'atomic design' methodology presented by [Brad Frost](http://bradfrost.com/blog/post/atomic-web-design/).

'What is it made up of'
ATOMS: nothing / doesn't make sense
MOLECULES: atoms
ORGANISMS: molecules/organisms

Building components, prefering inheritance over specificity
Idea being you can build for the typical cases, and overwrite / specify the more specific cases

## Atoms
Smallest unit; cannot be decomposed into parts
    Typography
    Base HTML elements
        h1-6
        p
        strong/em
        ol/ul
        button
        a tags
        etc

## Molecules
Combinations of atoms whose parts cannot (or rarely are) used separately
    .form-group (field / label / validation)
    .search-field (field w/ search icon)
    .menu list

## Organisms
Combinations of molecules / other organisms present across the system
    .card
    section
    hero
    footer
    navigation

## Templates
Specific styles for a template page (like blog index, or 'contact' template)

## Pages
'' '' for a page '' ...


