
0.5.0.0
=======

* Switch to using the builder provided by the `ByteString` package
* Change the encoding of Float and Double with the Serialize class to use the
  `Data.Serialize.IEEE754` module
* Add support for encoding and decoding `ShortByteString`
* New and improved test suite thanks to Kei Hibino
* Fix two bugs involving the `lookAhead` combinator and partial chunks.
