# table:
1.  First we created the table element.
2. Next, we created the tbody element, which is a child of the table element.
3. Next, we used a loop to create the tr elements, which are children of the tbody element.
4. For each trelement, we used a loop to create the td elements, which are children of tr elements.
5. For each td element, we then created the text node with the table cell's text.

![image](https://user-images.githubusercontent.com/79115759/110588133-472da180-817d-11eb-9610-1c1ba7533b59.png)

getElementsByTagName(tagNameValue) is a method available in any DOM Element or the root Document element. When called, 
it returns an array with all of the element's descendants matching the tag name. 
The first element of the list is located at position [0] in the array.
