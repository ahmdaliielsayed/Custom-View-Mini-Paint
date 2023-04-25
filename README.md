Custom Views - Mini Paint
============================================================================

Solution code for Advanced Android with Kotlin Codelab 

Introduction
------------

Mini Paint is an app for making free drawing area to draw what you want.

## Summary
* [Canvas](https://developer.android.com/reference/android/graphics/Canvas): 2D drawing surface with methods for drawing.
* Canvas can be associated with a View for display.
* [Paint](https://developer.android.com/reference/android/graphics/Paint) for style and color.
* Create custom view and override [onDraw()](https://developer.android.com/reference/android/widget/ProgressBar.html#onDraw(android.graphics.Canvas)) and [onSizeChanged()](https://developer.android.com/reference/android/view/View.html#onSizeChanged(int,%20int,%20int,%20int)).
* Override [onTouchEvent()](https://developer.android.com/reference/android/view/View.html#onTouchEvent(android.view.MotionEvent)) to respond to user touch.
* Use extra bitmap to cache drawings that build over time.

### Screenshots

<table>
  <tr>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234308017-044ef8eb-f06c-41c0-99ec-da24056e78b5.png"/>
    </td>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234308054-b6b2a170-6dec-407c-81b5-956494d16380.png"/>
    </td>
  </tr>
</table>
