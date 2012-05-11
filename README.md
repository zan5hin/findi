findi
-------

A port of a port of sosumi. Find your iPhone through Apple's API.

Source from:

[comfuture's recordmylatitude](https://github.com/comfuture/recordmylatitude/blob/master/findmyiphone/__init__.py)

That was inspired by:

[tyler hall's sosumi](https://github.com/tylerhall/sosumi)

I will attempt to keep up with Apple's changing API, as it breaks horribly when the modify version numbers. Fair warning.

Use
-------

# Initialize findmyiphone with your Apple ID

iphone = FindMyIPhone('email@example.com', 'password')

# Locate the iPhone

iphone_location = iphone.locate()

# iPhone.locate() returns a dictionary that contains a latitude and longitude

latitude = iphone_location.get('latitude')
longitude = iphone_location.get('longitude')


LICENSE
-------

The MIT License

Copyright (c) 2012 Jack Pearkes

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

