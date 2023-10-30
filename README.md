# string-interpolation

This repo is being used to track the [open issues](https://github.com/hadrielk/string-interpolation/issues) for supporting f-strings in C/C++, or string-interpolation in general.

The current draft proposal targeted at ISO C++ WG21 is [f-string Draft rev-2](http://api.csswg.org/bikeshed/?url=https://raw.githubusercontent.com/hadrielk/cpp-proposals/main/f-string/f-string-r2.bs). Note that it is only a draft, and has not been submitted as a Proposal to WG21, although it has been discussed on the [std-proposals mailing list](https://lists.isocpp.org/mailman/listinfo.cgi/std-proposals).

But we're also investigating the possibility of using this in C, and potentially proposing parts of it to WG14.

The current mechanism is done entirely within the preprocessor, and the working-groups have been trying to keep the C and C++ preprocessors nearly identical.

Any proposal to diverge their implementations further will be extremely difficult to gain approval.

Therefore, we've been keeping usage in C in mind, not only C++.
