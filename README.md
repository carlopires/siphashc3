siphashc3
=========

python c-module for [siphash][1], based on [floodberry's version][2].

[![Build Status](https://travis-ci.org/carlopires/siphashc3.png?branch=master)](https://travis-ci.org/carlopires/siphashc3)

### Usage

#### Python2.7.x

~~~ python2.7.x
>>> from siphashc import siphash
>>> siphash('sixteencharstrng', 'i need a hash of this')
10796923698683394048L
~~~

#### Python3.4.x

~~~ python3.4.x
>>> from siphashc import siphash
>>> siphash('sixteencharstrng', 'i need a hash of this')
10796923698683394048
~~~

### License

Released under the [MIT license](http://www.opensource.org/licenses/mit-license.php). See `LICENSE.md` file for details.

[1]: https://131002.net/siphash/
[2]: https://github.com/floodyberry/siphash
