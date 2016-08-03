
<a id='SchumakerSpline.jl-1'></a>

# SchumakerSpline.jl


  * A simple shape preserving spline implementation in Julia. *
  * Curve - This is where the quadratic curve that is present in the first and last interval are used to predict points before the first interval and after the last interval respectively.
  * Linear - This is where a line is extended out before the first interval and after the last interval. The slope of the line is given by the derivative at the start of the first interval and end of the last interval.
  * Constant - This is where the first and last y values are used for prediction before the first point of the interval and after the last part of the interval respectively.
