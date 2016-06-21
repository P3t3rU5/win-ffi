# WinFFI

[![Gitter](https://badges.gitter.im/P3t3rU5/win-ffi.svg)](https://gitter.im/P3t3rU5/win-ffi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

WinFFI is a gem to use the windows API using the ffi gem inspired by windows-pr gem.
This gem is work in progress

The main component of WinFFI is [win-ffi-core](https://github.com/P3t3rU5/win-ffi-core) which initializes and populates things like Windows Version and Architecture. Install it with:

```
gem install win-ffi-core
```

The gem is divided in components, each representing a different windows library:
- [user32](https://github.com/P3t3rU5/win-ffi-user32)
- [gdi32](https://github.com/P3t3rU5/win-ffi-gdi32)
- [kernel32](https://github.com/P3t3rU5/win-ffi-kernel32)
- other future components

# License

(The MIT License)

Copyright &copy; 2016 Pedro Miranda

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
