Cornucopia is a library for turning a freehand sketch into a fair curve.  It is intended to be used in graphics or CAD applications.  The resulting curve is a spline composed of Cornu Spirals (hence the name), also known as Euler Spirals or clothoids.  This is an implementation of the algorithm described in:

Ilya Baran, Jaakko Lehtinen, Jovan Popović "Sketching Clothoid Splines Using Shortest Paths", Eurographics 2010.  http://www.mit.edu/~ibaran/curves

Some documentation is still missing and the API is subject to change.  To build Cornucopia, be sure to have a development snapshot of Eigen 3 and Qt 4.6 installed.  Test/EndToEndTest.cpp shows a two simple usecases: the standard API and a simplified one with no dependencies.  See CornucopiaDescription for more details about building and running.