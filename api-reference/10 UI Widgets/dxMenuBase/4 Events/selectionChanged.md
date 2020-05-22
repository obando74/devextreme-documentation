---
type: event
---
---
##### shortDescription
Fires after a collection item is selected or unselected.

##### param(e): object
Provides function parameters.

##### field(e.component): object
Provides access to the widget instance.

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

##### field(e.addedItems): array
An array of items added to selection.

##### field(e.removedItems): array
An array of items removed from selection.

---
Instead, you can use the [onSelectionChanged](/api-reference/10%20UI%20Widgets/dxMenuBase/1%20Configuration/onSelectionChanged.md '{basewidgetpath}/Configuration/#onSelectionChanged') option to handle the event.

This event fires only if the [selectionMode](/api-reference/10%20UI%20Widgets/dxMenuBase/1%20Configuration/selectionMode.md '{basewidgetpath}/Configuration/#selectionMode') option is set to *'single'* and the [selectByClick](/api-reference/10%20UI%20Widgets/dxMenuBase/1%20Configuration/selectByClick.md '{basewidgetpath}/Configuration/#selectByClick') option is set to *true*.

#####See Also#####
- [Handle Events - jQuery](/concepts/10%20UI%20Widgets/0%20Basics/10%20Widget%20Basics%20-%20jQuery/15%20Handle%20Events.md '/Documentation/Guide/UI_Widgets/Basics/Widget_Basics_-_jQuery/#Handle_Events')
- [Handle Events - AngularJS](/concepts/10%20UI%20Widgets/0%20Basics/20%20Widget%20Basics%20-%20AngularJS/15%20Handle%20Events.md '/Documentation/Guide/UI_Widgets/Basics/Widget_Basics_-_AngularJS/#Handle_Events')
- [Handle Events - Knockout](/concepts/10%20UI%20Widgets/0%20Basics/25%20Widget%20Basics%20-%20Knockout/15%20Handle%20Events.md '/Documentation/Guide/UI_Widgets/Basics/Widget_Basics_-_Knockout/#Handle_Events')