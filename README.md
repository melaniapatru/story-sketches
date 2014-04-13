story-sketches
==============

Native animation support http://ocw.cs.pub.ro/courses/ndk

Documentatie:

// android working with canvas
http://faculty.ycp.edu/~dhovemey/spring2012/cs496/lecture/lecture16.html
http://stackoverflow.com/questions/16650419/draw-in-canvas-by-finger-android

// android detecting edges
http://stackoverflow.com/questions/10240106/cannyedgedetector-giving-a-stack-overflow-with-bitmaps

// interpollation/ animation
http://faculty.ycp.edu/~dhovemey/spring2012/cs496/lecture/lecture16.html
http://www.csse.uwa.edu.au/~wongt/projective-interp.html
http://www.cemyuksel.com/research/catmullrom_param/

Descrierea ideii de algoritm:

1. Detectarea edgeurilor
2. Trasarea conturului vectorial
3. Impartirea in segmente vectoriale de dimensiune mica
4. Matchingul intre segementul intial si segmentul final
5. Interpolarea intre fiecare segemente
6. Smoothing de contur de imagine