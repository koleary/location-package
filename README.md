# Location Package
A Drupal Content Package for creating rich location content.

The Location Content Package is a Drupal feature created using Features module (fetures is not a dependency). Location contains everything you need to immediately begin creating location content. Locations can be anything from brick-and-mortar stores to branch offices to music venues.
##To use
Clone this repo into your modules directory, download the dependencies from Drupal.org. Address and it's libraries must be installed using composer (see the address project page at https://www.drupal.org/project/address for instructions). Voting API and widgets can be installed via the modules UI. Once the modules are visible on the 'extend' select 'Location','Map','Review' and 'Featured location' (if needed). and click 'install'. Drupal will detect the dependencies and ask if you want to install them. Click yes and the packages will be installed. 

To begin creating location content go to the content page, click 'add content' and choose 'Location'.

##SEO ready
Content packages are designed to be immediately usable and fully marked up for SEO with schema.org RDF mappings. 
##Fully internationalized
Location depends on the address module developed for Drupal Commerce. Address uses the most robust and up-to-date libraries to provide the proper address formats and postal codes for hundreds of countries.
##Fully configured
Location includes base field overrides, sane default human-readable field names and descriptions for every field as well as field formatters that provide the simplest most common experience. 

##Fully customizable
Once loaded into your database all of the default configuration can be changed if needed using standard Drupal configuration interfaces.

##Location includes 
####Content types
Location, Map
####Comment types
Review
####Custom block types
Featured Location
####Views
Locations (page and block)
####Dependencies
Drupal core, address, voting API, voting API widgets, (voting API and widgets required for review only)






