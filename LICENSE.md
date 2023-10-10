MIT License

Copyright (c) 2018 DAMIÀ FUENTES ESCOTÉ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

------------------------------------------------------------------------

Modifications Copyright (c) 2023 Jacob Pitsenberger

Jacob Pitsenberger is making these modifications under the terms of the MIT License:

Using the original djitellopy library which implements OpenCV for its video capture, I edited the BackgroundFrameRead class by following the suggestions in this issue thread: 
https://github.com/damiafuentes/DJITelloPy/issues/90#issuecomment-855458905 

The current djitellopy library is an implementation that uses  PyAV in this class whereas this version maintains the use of OpenCV.

As such, the differences between the tello.py modules in this version and the current one are extensive while the modifications I actually made were limited as they were done in the previous djitellopy version that uses OpenCV.
