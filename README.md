Voxer Nagios Plugins
====================

Plugins for nagios used by [Voxer][0], made specifically for [SmartOS][1]

Plugins
-------

### check_svcs

Check for services in SMF that are not functioning properly

### check_hard_errors

Check kstat for hard errors - useful for identifying failing hardware

### check_mem

Like `check_disk` for memory usage using kstat to calculate used memory

    Usage: check_mem -w 80 -c 90

If the amount of used memory is greater than 90 go critical, over 80 is
warning, anything else is OK

License
-------

LICENSE - "MIT License"
Copyright (c) 2012 Voxer LLC. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[0]: http://voxer.com
[1]: http://smartos.org