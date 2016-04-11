# bouncer design

The Code has to take an Image Stream (either from live footage or from a video)
It then finds the outline of the tennis court and finds the four points of the edges (Very Edge of White Lines)
It then finds Tennis Balls and their associated shadows.
It saves the locations of the tennis balls and associated shadows.
It finds Minimums in the distances between tennis balls and associated shadows. It then finds the location of the tennis ball through Perspective Transformation (either using the center of the shadow or the center of the tennis ball)
It saves a file containing the Bounce Data.

It displays Graphical Data showing the video feed on one side and a graphic of a Tennis Court on the other side. When bounces are registered, it shows the bounce on the Tennis Court graphic. The most recent bounce is highlighted red.

Cool!!!!!!!