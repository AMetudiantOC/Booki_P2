# Booki project

Booki_P2 is a simple HTML web page for static content. It was created as a base for my study project at Openclassrooms, but everyone is welcome to use it. The implementation strives to be simple and without unnecessary dependencies.

## Goals
----------
* The search field is an input field, so the text must be editable by the user
* Each accommodation or activity card is clickable in its entirety
* Filters should change appearance on hover
* The texts "Lodging" and "Activities", located in the header, are links. They lead respectively to the section "Accommodations in Marseille" and "Activities in Marseille".
* Easy customization of site layout and formatting

## Technical specifications
----------
* The site is responsive 
* It is adapted to the desktop, tablet and mobile formats without any element being cut off and the text being of sufficient size
* The format and size of the images are adapted to the resolution and loading time
* The icons come from the Font Awesome library
* The site font is [Raleway](https://fonts.google.com/specimen/Raleway) and is imported directly from Google Font 
* The code uses only pixels and percentages rather than REM and EM
* This page was created from Flexbox
* No CSS framework or CSS preprocessor is used
* The code is fully marked up with semantic tags (such as `main`, `header`, `nav`, etc.)
* The languages used are HTML and CSS and are valid with the [W3C](https://validator.w3.org/)
* The template is compatible with the latest versions of Google Chrome and Mozilla Firefox
* The code is not versioned

## Structure
----------
Each segment has been designed and thought independently from the rest in order to be reusable for other projects
* `/head/` Entry point for the application, configures the development environment
* `/HEADER/` Layout code for the navigation to the info point (which indicates the number of available accommodations in the city) 
* `/nav/` Concerns the logo of the site as well as the links "Accommodations" and "Activities"
* `/title/` Setting up the title
* `/btn/` Full search bar with clickable form, icon and "Search" button
* `/filters/` Set of filter buttons with icons and texts
* `/info point/` Information icon and text
* `/BODY/` Regroups the contents of the sections "Accommodations in Marseille" and "Activities in Marseille"
* `/section 1/` Contains the two large maps "Accommodations in Marseille" and "The most popular"
* `/section 2/` Concerns all the "Activities in Marseille" section
* `/FOOTER/` The three lists of clickable links in the footer are grouped here

## Instructions
----------
1. Install [VScode](https://code.visualstudio.com/)  
2. Fork and clone the repository  
3. Make changes or use only one of the segments  
4. Validate your changes with the W3C  
5. Deploy your own repository to a hosting service  

## Contributing
----------
* Fork and clone the repository
* Modify code and make proposals
* Review changes
* Send a download request

## License
----------
[OPENCLASSROOMS](https://openclassrooms.com/fr/)