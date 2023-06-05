<link type="text/css">
the type attribuute specifies the media type of the linked document/resource. 

css box-sizing property:
without the property:
width/height + padding + border = actual width/height of an element 
with the property:
allows us to include the padding and border in an element's total height and width.
If you set box-sizing: border-box; on an element, padding and border are included in the width and height

vh: represents a percentage of the height of the viewport's initial containing block. 

min-height: CSS property sets the min height of an element. it prevents the used value of the height property from becoming smaller than the value specified for min-height. 

display: flex - property of flexbox, flex or inline-flex; 

CSS justify-content property: justify-content property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally);

weight: is the overall thickness of a typeface's stroke in any given font.
font-weight: specifies the weight of a font;

difference: 
<section>  means that the content inside is grouped(i.e relates to a single theme), and should appear as an entry in an outline of the page.
<div> does not convey any meaning, aside from any found in its class, lang and title attributes. 

CSS overflow: 
The overflow property specifies whether to clip the content or to add scrollbars when the content of an element is too big to fit in the specified area.

The overflow property has the following values:

visible - Default. The overflow is not clipped. The content renders outside the element's box
hidden - The overflow is clipped, and the rest of the content will be invisible
scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content
auto - Similar to scroll, but it adds scrollbars only when necessary
Note: The overflow property only works for block elements with a specified height.

CSS object fit property:is used to specify how an <img> or <video> should be resized to fit its container.
This property tells the content to fill the container in a variety of ways; such as "preserve that aspect ratio" or "stretch up and take up as much space as possible".
fill - This is default. The image is resized to fill the given dimension. If necessary, the image will be stretched or squished to fit
contain - The image keeps its aspect ratio, but is resized to fit within the given dimension
cover - The image keeps its aspect ratio and fills the given dimension. The image will be clipped to fit
none - The image is not resized
scale-down - the image is scaled down to the smallest version of none or contain

z-index:
property specifies the stack order of an element.
n element with greater stack order is always in front of an element with a lower stack order.
Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display:flex elements).
Note: If two positioned elements overlap without a z-index specified, the element positioned last in the HTML code will be shown on top. 

mix-blend mode:
The mix-blend-mode property specifies how an element's content should blend with its direct parent background.
normal	This is default. Sets the blending mode to normal	
multiply	Sets the blending mode to multiply	
screen	Sets the blending mode to screen	
overlay	Sets the blending mode to overlay	
darken	Sets the blending mode to darken	
lighten	Sets the blending mode to lighten	
color-dodge	Sets the blending mode to color-dodge	
color-burn	Sets the blending mode to color-burn	
difference	Sets the blending mode to difference	
exclusion	Sets the blending mode to exclusion	
hue	Sets the blending mode to hue	
saturation	Sets the blending mode to saturation	
color	Sets the blending mode to color	
luminosity	Sets the blending mode to luminosity

