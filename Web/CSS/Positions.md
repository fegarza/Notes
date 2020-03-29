# CSS Positions

## Static

Is the default position of the boxes.

An element with `position: static;` is not positioned in any special way; it is  always positioned according to the normal flow of the page.

Static positioned elements are not affected by the top, bottom, left, and right properties.

## 

## Relative

An element with `position: relative;` is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the  element.

## Absolute

It means that the position has relation with the parent content.

An element with `position: absolute;` is positioned relative to the nearest positioned ancestor  (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors,  it uses the document body, and moves along with page scrolling.

## 

## Fixed

It means that the position has relation with the window.

An element with `position: fixed;` is positioned relative to the viewport, which means it always  stays in the same place even if the page is scrolled. The top,  right, bottom, and left properties are used to position the element.

## Sticky

An element with `position: sticky;` is positioned based on the user's scroll position.

A sticky element toggles between `relative` and `fixed`, depending on the scroll position. It is positioned relative until a  given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

Create a HTML document  with all the positions.
