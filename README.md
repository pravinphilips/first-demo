A DLS enabled transfer list component for Vue.js.
Uses
•	Move single or multiple selected items from left array list to right array list and vice versa.
•	Filter and sorting enabled.
•	Customizable options are provided.
Installation
******* install command goes here **************
How to use?
In your component file embed the selector.
Eg: ***** Component tag name ***********
Options
Prop Name	Datatype	Optional/Mandatory
title	String	Optional
subtitle	String	Optional
listTitle	String	Optional
cancelButtonText	String	Optional
showSelectionCounter	boolean - false	Optional
showFilter	boolean - false	Optional
sourceData	{headers: [{key: '', value: '', type: ''}], dataSource: []}
Mandatory
targetData	{headers: [{key: '', value: '', , type: ''}], dataSource: []}
Mandatory
singleSelect	boolean - false	Optional
adjustColumnWidth	boolean - false	Optional
sortable	boolean - false	Optional
showCancel	boolean - false	Optional
submitButtonText
String - Submit	Mandatory
theme	Enum- light	Optional

Examples
<select-component
	title=”Your title”
	cancelButtonText=”Your text”
></select-component>

Events
________________________________________
EventName	Description
onSubmit(selectedValues)	Call back method in for Submit button in the implementing component
onLeftbuttonClicked(selectedValues)	Call back method in for move to left button in the implementing component
onRightButtonClicked(selectedValues)	Call back method in for move to right button in the implementing component
onCancel(event)	Call back method in for cancel button in the implementing component
 


