---
type: function(scaleValue)
---
---
##### notUsedInTheme

##### shortDescription
Specifies a callback function that returns the text to be displayed in scale labels.

##### param(scaleValue): object
Defines a scale value.

##### field(scaleValue.value): Date|Number
Specifies the scale value represented by a label.

##### field(scaleValue.valueText): string
Specifies the scale value with applied <a href="/Documentation/16_1/ApiReference/Data_Visualization_Widgets/dxRangeSelector/Configuration/scale/label/#format">formatting</a>.

##### return: string
The text to be displayed by a scale label.

---
When implementing a callback function for this property, use the scale value to be displayed in a label. This value can be accessed using the fields of the object that is passed as the function's parameter. Alternatively, you can use the **this** object within the function. This object has the same structure as the object passed as a parameter.

For general information on data formatting, refer to the [Data Formatting](/concepts/20%20Data%20Visualization/40%20Common/30%20Data%20Formatting '/Documentation/Guide/Data_Visualization/Common/Data_Formatting/') topic.