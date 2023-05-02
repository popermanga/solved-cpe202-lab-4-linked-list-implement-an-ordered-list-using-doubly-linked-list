Download Link: https://assignmentchef.com/product/solved-cpe202-lab-4-linked-list-implement-an-ordered-list-using-doubly-linked-list
<br>
Before doing this lab make sure to read over section 3.22, 3.23 carefully. You will be extending the implementation as described in the text.

The structure of an ordered list is a collection of items where each item holds a relative position that is based upon some underlying characteristic of the item. The ordering is typically either ascending or descending and we assume that list items have a meaningful comparison operation that is already defined. Many of the ordered list operations are the same as those of the unordered list.

Implement the following operations for an <strong>ordered list of integers</strong> <strong>ordered in ascending order</strong> using a <strong>doubly linked list</strong>.  The “<strong>head</strong>” of the list be where the “smallest item is and let “<strong>tail</strong>” be where the largest item is.

OrderedList () creates a new ordered list that is empty. It needs no parameters and returns an empty list. Write separate test for each function.

<ul>

 <li>add (item) adds a new item to the list making sure that the order is preserved. It needs the item and returns nothing. Assume the item is not already in the list.</li>

 <li>remove (item) removes the item from the list. It needs the item and modifies the list. Return the position of removed item if it is in the list, otherwise return -1 (as not found).</li>

 <li>search_forward (item) searches for the item in the list. It needs the item and returns the boolean value True if the item is in the list and False if the item is not in the list.</li>

 <li><strong>search_backward </strong>(item) searches for the item in the list starting from the tail of the list. It needs the item and returns the boolean value True if the item is in the list and False if the item is not in the list.</li>

 <li>is_empty () tests to see whether the list is empty. It needs no parameters and returns a boolean value. True if the list is empty and False if any items are in the list.</li>

 <li>size () returns the number of items in the list. It needs no parameters and returns an integer.</li>

 <li>index (item) returns the position of item in the list. It needs the item and returns the index. If it is not in the item it returns -1(as not found).</li>

 <li>pop () removes and returns the last item in the list. It needs nothing and returns an item.</li>

 <li>pop (pos) removes and returns the item at position pos. It needs the position and returns the item. If there</li>

</ul>

is no item in that, position it returns -1 (as not found). <strong>pop(pos) should compare pos to the size of the list and search from the head if pos &lt;= size/2 and from the rear if pos &gt; size/2.</strong>

<h1>Submit two files to PolyLearn</h1>

<ol>

 <li>py</li>

 <li>py</li>

</ol>




<strong>For documentation</strong> use signature and purpose statemet of the design recipe for each function (input-output and purpose statement) .For your classes use data definition of design recipe. Just write repr for your classes as boilerplate. No need for templet.


