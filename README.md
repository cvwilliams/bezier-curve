# BezierCurve
Drawing of Bezier curve using HTML5 Canvas and WebGL

1.	Introduction:

The purpose of this program is to create an interactive way to apply the concepts of Bezier curves and viewport clipping. The user creates a rectangular viewport and then selects four points to generate the curve. All points not within the viewport that are on the curve will not be generated.

	
2.	Program Dependencies:
•	Browser with WebGL enabled
•	JQuery

3.	User Interface:
•	V key: Begins the viewport drawing mode
•	C key: Begins the point drawing mode
•	Esc key: Draws the curve once all four points have been drawn
•	Left Mouse Click: Draws points in the appropriate mode

4.	User Guide:
•	Begin by entering either Viewport mode (V key) or Curve mode (C)

In Viewport Mode:
•	Select two points on the screen (left mouse click) and the viewport will be drawn. Press V key again to redraw the viewport
In Curve Mode:
•	Select four points on the screen (left mouse click) and then press the Esc key to draw the curve. If a viewport is drawn, clipping will be demonstrated.
