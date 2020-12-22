Must be one or more (separated by '|') of the following constant values.

Constant	Value	Description
bottom	50	Push object to the bottom of its container, not changing its size.
center	11	Place the object in the center of its container in both the vertical and horizontal axis, not changing its size.
center_horizontal	1	Place object in the horizontal center of its container, not changing its size.
center_vertical	10	Place object in the vertical center of its container, not changing its size.
clip_horizontal	8	Additional option that can be set to have the left and/or right edges of the child clipped to its container's bounds. The clip will be based on the horizontal gravity: a left gravity will clip the right edge, a right gravity will clip the left edge, and neither will clip both edges.
clip_vertical	80	Additional option that can be set to have the top and/or bottom edges of the child clipped to its container's bounds. The clip will be based on the vertical gravity: a top gravity will clip the bottom edge, a bottom gravity will clip the top edge, and neither will clip both edges.
end	800005	Push object to the end of its container, not changing its size.
fill	77	Grow the horizontal and vertical size of the object if needed so it completely fills its container.
fill_horizontal	7	Grow the horizontal size of the object if needed so it completely fills its container.
fill_vertical	70	Grow the vertical size of the object if needed so it completely fills its container.
left	3	Push object to the left of its container, not changing its size.
right	5	Push object to the right of its container, not changing its size.
start	800003	Push object to the beginning of its container, not changing its size.
top	30	Push object to the top of its container, not changing its size.
android:layout_weight
Indicates how much of the extra space in the LinearLayout is allocated to the view associated with these LayoutParams. Specify 0 if the view should not be stretched. Otherwise the extra pixels will be pro-rated among all views whose weight is greater than 0.

May be a floating point value, such as "1.2".

Fields
gravity
Added in API level 1

public int gravity
Gravity for the view associated with these LayoutParams.

See also:

Gravity
weight
Added in API level 1

public float weight
Indicates how much of the extra space in the LinearLayout will be allocated to the view associated with these LayoutParams. Specify 0 if the view should not be stretched. Otherwise the extra pixels will be pro-rated among all views whose weight is greater than 0.

Public constructors
LayoutParams
Added in API level 1

public LayoutParams (Context c, 
                AttributeSet attrs)
Parameters
c	Context
attrs	AttributeSet
LayoutParams
Added in API level 1

public LayoutParams (int width, 
                int height)
Parameters
width	int
height	int
LayoutParams
Added in API level 1

public LayoutParams (int width, 
                int height, 
                float weight)
Creates a new set of layout parameters with the specified width, height and weight.

Parameters
width	int: the width, either ViewGroup.LayoutParams.MATCH_PARENT, ViewGroup.LayoutParams.WRAP_CONTENT or a fixed size in pixels
height	int: the height, either ViewGroup.LayoutParams.MATCH_PARENT, ViewGroup.LayoutParams.WRAP_CONTENT or a fixed size in pixels
weight	float: the weight
LayoutParams
Added in API level 1

public LayoutParams (ViewGroup.LayoutParams p)
Parameters
p	ViewGroup.LayoutParams
LayoutParams
Added in API level 1

public LayoutParams (ViewGroup.MarginLayoutParams source)
Parameters
source	ViewGroup.MarginLayoutParams
LayoutParams
Added in API level 19

public LayoutParams (LinearLayout.LayoutParams source)
Copy constructor. Clones the width, height, margin values, weight, and gravity of the source.

Parameters
source	LinearLayout.LayoutParams: The layout params to copy from.
Public methods
debug
Added in API level 1

public String debug (String output)
Parameters
output	String
Returns
String	
Was this page helpful?
Content and code samples on this page are subject to the licenses described in the Content License. Java is a registered trademark of Oracle and/or its affiliates.
