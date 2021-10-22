# Test Repo for CyberChef/CyberSaucier recipes

Many of the recipies are test recipies for testing [CyberSaucier](https://github.com/DBHeise/CyberSaucier), but the recipies under the folder named "real" are suitable for actual use.

----

## Repo Folder Structure

* real - acutal cyberChef recipes that I use
* Simplified - simple recipies, probably too simple for use
* Subset - a subset of recipies (taken from [MattNotMax](https://github.com/mattnotmax/cyberchef-recipes))


----

## Format of a CyberSaucier Recipe File

Recipe files are JSON files and are expected to be a single JSON object with a few required properties:

* name - the name of the recipe; used as an identifier
* recipe - the JSON CyberChef Recipe (use the "Save" option in the CyberChef UI to get the "Clean JSON" or "Compact JSON" form of the recipe to use here)
* meta - an extra object that will be included in the CyberChef output object
  * fieldname - a field to add on to the return object (takes the CyberChef output and adds it as a field [with this fieldname] to the output object)
