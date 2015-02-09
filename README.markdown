# Liquid-Thousands-Separated-Filter

by Matt Gemmell - [mattgemmell.com](http://mattgemmell.com) - [@mattgemmell](http://twitter.com/mattgemmell)

License: [CC0 Universal (public domain)](https://creativecommons.org/publicdomain/zero/1.0/deed.en)

* * *

##Description

A basic [Liquid](http://docs.shopify.com/themes/liquid-documentation/basics) / [Jekyll](http://jekyllrb.com) filter that adds thousands-separators to a number.


##Installation

To install, copy the `thousands-separated-filter.rb` file into your Jekyll `_plugins` folder.


##Usage

    {{ varname | thousands_separated }}

If `varname` contained "`123456789`", the result would be "`123,456,789`"

    {{ varname | thousands_separated:"." }}

As above, but using a custom thousands-separator.
