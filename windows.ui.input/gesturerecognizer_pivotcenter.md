---
-api-id: P:Windows.UI.Input.GestureRecognizer.PivotCenter
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Point PivotCenter { get;  set; }
-->

# Windows.UI.Input.GestureRecognizer.PivotCenter

## -description
Gets or sets the center point for a rotation interaction when single pointer input is detected.




<!--•	GestureRecognizer.PivotRadius/Center properties: “rotation manipulation”  single finger rotation manipulation (especially in “Setting the value of PivotRadius to 0 disables support for the rotation manipulation”)-->

<!--•	GestureRecognizer.PivotCenter – This is just to support single input rotation.  Should also set PivotRadius too and have ManipulationRotations enabled.  This value needs to be constantly updated during a manipulation to give the updated center of the manipulated UI.  Units are in PointerPoint values being sent to the GestureRecognizer.
•	GestureRecognizer.PivotRadius – Again this is just used to support single input rotation manipulations.  Units are in the PointerPoint DIP values.
-->

<!--•	GestureRecognizer.PivotCenter – This is for single-finger rotation support only.  It doesn’t affect 2+ finger manipulations.  Same with PivotRadius.-->

## -property-value
The screen location for the center of rotation, in device-independent pixel (DIP).

## -remarks

## -examples

## -see-also
[Input and interactions](/windows/uwp/design/input/), [User interaction mode sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/UserInteractionMode), [Focus visuals sample](https://go.microsoft.com/fwlink/p/?LinkID=619895), [Input: Device capabilities sample](https://go.microsoft.com/fwlink/p/?linkid=231530), [Input: Ink sample](https://go.microsoft.com/fwlink/p/?linkid=231622), [Input: Manipulations and gestures (JavaScript) sample](https://go.microsoft.com/fwlink/p/?linkid=231638), [Input: Simplified ink  sample](https://go.microsoft.com/fwlink/p/?linkid=246570), [Input: Windows 8 gestures sample](https://go.microsoft.com/fwlink/p/?LinkId=264995), [Input: XAML user input events sample](https://go.microsoft.com/fwlink/p/?linkid=226855), [XAML scrolling, panning, and zooming sample](https://go.microsoft.com/fwlink/p/?linkid=251717), [DirectX touch input sample](https://go.microsoft.com/fwlink/p/?LinkID=231627), [Input: Manipulations and gestures (C++) sample](https://go.microsoft.com/fwlink/p/?linkid=231605), [Input: Touch hit testing sample](https://go.microsoft.com/fwlink/p/?linkid=231590), [Input source identification sample](https://go.microsoft.com/fwlink/p/?LinkID=267908), [Touch injection sample](https://go.microsoft.com/fwlink/p/?LinkID=267906), [Win32 touch hit-testing sample](https://go.microsoft.com/fwlink/p/?LinkID=267915)
