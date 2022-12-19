# 74 Bootstrap Collapse

An example of using the Accordion functionality of Bootstrap 4
https://getbootstrap.com/docs/4.0/components/collapse/#accordion-example

This example uses 2 fragments.
## Accordion-Container 
Used as a wrapper to add the div with id accordion.
It includes a Drop Zone where we can place a Collection Display fragment, to select the collection of collapsible items we want to show

## Accordion-Element
Used for every element of the collection. It has some mappable fields (texts, image) to map the fields of your Object or Web Content.

## Instructions:
1. Add first the Accordion-Container to a page
2. Add a Collection Display fragment into the Accordion-Container drop-zone
3. Add the Accordion-Element fragment in the Collection Display
4. Map your object/web content to the editable fields of the Accordion-Element.

(You may need to edit the Accordion-Element fragment first to modify the editable fields and the styles to make it fit for your demo)

## Example
This was used to display a list of activites in a Fair. Each activity was a Liferay Object.
But you can use it for whatever you want (F.A.Q, etc..) -> Just add/remove fields in the Accordion-Element, and when you drop this fragment in the collection map the fields of your content accordingly.

### This is how it was used

![image](https://user-images.githubusercontent.com/19341713/208486835-96eb91a2-39f1-441f-a2e7-6c9bfbe5541f.png)

![image](https://user-images.githubusercontent.com/19341713/208486903-84f724e7-e1c1-42ef-9a66-57024617372a.png)
