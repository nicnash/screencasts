Placeholder

The complete D3 pipeline

 * Uses [Enter](http://d3js.org/#enter-exit)
 * Typical D3 pattern
 * This is the crux of D3.  Get this and you get the majority of it
 * .selectAll("rect") is selecting all rect (there are non initially)
 * .data is binding data to your selection
 * .enter no dom element but there is a data element. virtual selection.  Triggering on all data elements because there are no rects 
 * D3 allows you to cleanly use functions to manipulate data
 * .set x to return value from function
 * 

## lets practice with this