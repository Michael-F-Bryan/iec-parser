# IEC 61131-3 Parser

[![Build Status](https://travis-ci.org/Michael-F-Bryan/iec-parser.svg?branch=master)](https://travis-ci.org/Michael-F-Bryan/iec-parser)

(**[API Docs](https://michael-f-bryan.github.io/iec-parser/)**)

A Rust crate for reading IEC 61131-3 programs into memory.

A copy of the IEC 61131-10 XSD files is placed under the `spec/` directory. 
The originals can be found[on the PLCOpen Website][plcopen-61131-10] and are
used in accordance with the [IEC Code Components License][iec-license].

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.

[plcopen-61131-10]: https://plcopen.org/technical-activities/IEC61131-10/CodeComponents/PLCopenXML.htm
[iec-license]: https://www.iec.ch/webstore/custserv/pdf/CC-EULA.pdf