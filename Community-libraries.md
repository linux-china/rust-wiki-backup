See also:
* [Known packages that build with rustpkg](https://github.com/mozilla/rust/wiki/Rustpkg)
* [Travis CI Status](http://hiho.io/rust-ci/)

## Audio

See [[Computer Graphics and Game Development]].

## Collections

See [[Containers]].

## Compression

We want compression/decompression support for TAR and ZIP file formats.

* [alexcrichton/rust-compress](https://github.com/alexcrichton/rust-compress): compression algorithms, all written in rust [<img src="https://travis-ci.org/alexcrichton/rust-compress.png?branch=master">](https://travis-ci.org/alexcrichton/rust-compress)
* [erickt/rustzlib](https://github.com/erickt/rustzlib): libzlib bindings
* [thestinger/rust-snappy](https://github.com/thestinger/rust-snappy): libsnappy bindings

## Computation

* GMP
  * [thestinger/rust-gmp](https://github.com/thestinger/rust-gmp)
* OpenCL
  * [eholk/rust-opencl](https://github.com/eholk/rust-opencl): OpenCL bindings [<img src="https://travis-ci.org/eholk/rust-opencl.png?branch=master">](https://travis-ci.org/eholk/rust-opencl)
 
## Concurrency
 * task management, actor, OTP, [[Bikeshed mapreduce]], pools
 
## Crypto

* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto): [<img src="https://travis-ci.org/DaGenix/rust-crypto.png?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* LibNSS
  * [mletterle/rust-nss](https://github.com/mletterle/rust-nss)
* libsodium
  * [dnaq/sodiumoxide](https://github.com/dnaq/sodiumoxide)
* OpenSSL
  * [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl): [<img src="https://travis-ci.org/sfackler/rust-openssl.png?branch=master">](https://travis-ci.org/sfackler/rust-openssl)
  
## Database Access

* NoSql
  * LevelDB
      * [thestinger/rust-leveldb](https://github.com/thestinger/rust-leveldb)
  * MongoDB
      * [10gen-interns/mongo-rust-driver-prototype](https://github.com/10gen-interns/mongo-rust-driver-prototype)
  * Redis
      * [mitsuhiko/redis-rs](https://github.com/mitsuhiko/redis-rs)
      * [mneumann/rust-redis](https://github.com/mneumann/rust-redis) [<img src="https://travis-ci.org/mneumann/rust-redis.png?branch=master">](https://travis-ci.org/mneumann/rust-redis)
  * Sqlite
* SQL
  * PostgreSql
      * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres): [<img src="https://travis-ci.org/sfackler/rust-postgres.png?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite
      * [linuxfood/rustsqlite](https://github.com/linuxfood/rustsqlite): Sqlite3 bindings [<img src="https://travis-ci.org/kud1ing/rustsqlite.png?branch=master">](https://travis-ci.org/kud1ing/rustsqlite)
 
## Date and Time

Wanted library: [[Lib datetime]]

  * [luisbg/rust-datetime](https://github.com/luisbg/rust-datetime)
  * [tedhorst/rust_datetime](https://github.com/tedhorst/rust_datetime)
  
## Embedded Languages
* Lua
  * [kballard/rust-lua](https://github.com/kballard/rust-lua) (Lua 5.1): [<img src="https://travis-ci.org/kballard/rust-lua.png?branch=master">](https://travis-ci.org/kballard/rust-lua)

## Encoding
* [Base64](https://github.com/mozilla/rust/blob/master/src/libextra/base64.rs)
* Cap'n Proto
    * [dwrensha/capnproto-rust](https://github.com/dwrensha/capnproto-rust):  [<img src="https://travis-ci.org/dwrensha/capnproto-rust.png?branch=master">](https://travis-ci.org/dwrensha/capnproto-rust)
* Character Encoding
    * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding): [<img src="https://travis-ci.org/lifthrasiir/rust-encoding.png?branch=rust-0.9-pre">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CSV
  * [grahame/rust-csv](https://github.com/grahame/rust-csv)
  * [koko1000ban/rust-csv-parser](https://github.com/koko1000ban/rust-csv-parser)
* HTML
    * [veddan/rust-htmlescape](https://github.com/veddan/rust-htmlescape):  [<img src="https://travis-ci.org/veddan/rust-htmlescape.png?branch=master">](https://travis-ci.org/veddan/rust-htmlescape)
* [JSON](https://github.com/mozilla/rust/blob/master/src/libextra/json.rs)
* MsgPck
  * [mneumann/rust-msgpack](https://github.com/mneumann/rust-msgpack):  [<img src="https://travis-ci.org/mneumann/rust-msgpack.png?branch=master">](https://travis-ci.org/mneumann/rust-msgpack)
  * [omasanori/msgpack-rust](https://github.com/omasanori/msgpack-rust)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf):  [<img src="https://travis-ci.org/stepancheg/rust-protobuf.png?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
  * [tildeio/buffoon](https://github.com/tildeio/buffoon)
* S-Expressions
  * [darkf/rust_sexpr](https://github.com/darkf/rust_sexpr)
* Thrift
  * see https://github.com/mozilla/rust/issues/1677
* TOML
  * [mneumann/rust-toml](https://github.com/mneumann/rust-toml)
* Tnetstring
  * [erickt/rust-tnetstring](https://github.com/erickt/rust-tnetstring):  [<img src="https://travis-ci.org/erickt/rust-tnetstring.png?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
* XML
   * [bjz/sax-rs](https://github.com/bjz/sax-rs): bindings to libxml2's SAX parser [<img src="https://travis-ci.org/bjz/sax-rs.png?branch=master">](https://travis-ci.org/bjz/sax-rs)
   * [Florob/RustyXML](https://github.com/Florob/RustyXML): an XML parser written in Rust

## Graphics

See [[Computer Graphics and Game Development]].

## GUI

* Cocoa
  * [mozilla-servo/rust-cocoa](https://github.com/mozilla-servo/rust-cocoa)
* Curses
  * [pnkfelix/rust-curses](https://github.com/pnkfelix/rust-curses)
* Gtk
  * [JeremyLetang/rgtk](https://github.com/JeremyLetang/rgtk)
* ncurses
  * [doomsplayer/ncurses-rust](https://github.com/doomsplayer/ncurses-rust)
  * [drhodes/rust-ncurses](https://github.com/drhodes/rust-ncurses)
  * [eevee/amulet](https://github.com/eevee/amulet)
  * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs): [![Build Status](https://travis-ci.org/jeaye/ncurses-rs.png?branch=master)](https://travis-ci.org/jeaye/ncurses-rs.png)
* Termbox
  * [apribadi/rust-termbox](https://github.com/apribadi/rust-termbox)
* wxWidgets
  * [kenz-gelsoft/wxRust](https://github.com/kenz-gelsoft/wxRust): [![Build Status](https://travis-ci.org/kenz-gelsoft/wxRust.png?branch=master)](https://travis-ci.org/kenz-gelsoft/wxRust)
	  
## IO
 * AIO, SIO, stdio
 * [filesystem](https://github.com/mozilla/rust/blob/master/src/libstd/os.rs)
 * [path manipulation](https://github.com/mozilla/rust/blob/master/src/libstd/path.rs)
 * <> or fileinput.
 * timers
 
## Localizability
 * one aspect of L10n is to map a key to a text, based on the current locale (eg Java's [ResourceBundle](http://docs.oracle.com/javase/7/docs/api/java/util/ResourceBundle.html) or [GNU gettext](http://www.gnu.org/software/gettext/))
 * another aspect is to format a string based on the current locale (eg Java's [MessageFormat](http://docs.oracle.com/javase/7/docs/api/java/text/MessageFormat.html))
 * See [issue #4630](https://github.com/mozilla/rust/issues/4630)
 
## Mathematics

* [bjz/cgmath-rs](https://github.com/bjz/cgmath-rs) (Linear algebra and math library for graphics)
* [bjz/lmath-rs](https://github.com/bjz/lmath-rs)
* [cmr/linalg](https://github.com/cmr/linalg) (Linear algebra library)

## Misc
* low-level OS services
* Simple search on a filesystem (eg Ruby's [glob](http://ruby-doc.org/core-2.0/Dir.html#method-c-glob))
* unit testing
* FFI, ctypes
* dlopen, os processes
* standard predicates
 * text, numeric, sorted
* error-trapping wrappers, in-place task?
 * Consistent error handling
* quotas, accounting
* reflection

## Networking

* GUID
* HTTP
    * [rust-http](https://github.com/chris-morgan/rust-http):  [<img src="https://travis-ci.org/chris-morgan/rust-http.png?branch=master">](https://travis-ci.org/chris-morgan/rust-http)
    * [WebeWizard/libhttpd](https://github.com/WebeWizard/libhttpd)
* [URI/URL](https://github.com/mozilla/rust/blob/master/src/libextra/url.rs)
    * [SimonSapin/rust-url](https://github.com/SimonSapin/rust-url)
* [UUID](https://github.com/mozilla/rust/blob/master/src/libextra/uuid.rs)
* NanoMsg
  * [glycerine/rust-nanomsg](https://github.com/glycerine/rust-nanomsg)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq):  [<img src="https://travis-ci.org/erickt/rust-zmq.png?branch=master">](https://travis-ci.org/erickt/rust-zmq)

## Operating system specific

* Windows
  * [klutzy/rust-windows](https://github.com/klutzy/rust-windows): Win32/Win64 wrapper for Rust

## Parser Generator

* [erickt/ragel](https://github.com/erickt/ragel)
* [jesse99/rparse](https://github.com/jesse99/rparse)
* [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg)

## Random Numbers
* [random](https://github.com/mozilla/rust/blob/master/src/libcstd/rand.rs)

## Regular Expressions
See https://github.com/mozilla/rust/issues/3591

* [sanxiyn/rree](https://github.com/sanxiyn/rree)
* PCRE
  * [cadencemarseille/rust-pcre](https://github.com/cadencemarseille/rust-pcre): [![cadencemarseille/rust-pcre Build Status](https://travis-ci.org/cadencemarseille/rust-pcre.png?branch=master)](https://travis-ci.org/cadencemarseille/rust-pcre)
  * [erickt/rustpcre](https://github.com/erickt/rustpcre)
  * [glennsl/rust-re](https://github.com/glennsl/rust-re)
  * [uasi/rust-pcre](https://github.com/uasi/rust-pcre):  [<img src="https://travis-ci.org/uasi/rust-pcre.png?branch=master">](https://travis-ci.org/uasi/rust-pcre)

## String manipulation
* Slicing w/o copy, stringref
* Ropes
* Tokenizer
* Unicode
  * [Unicode](https://github.com/mozilla/rust/blob/master/src/libextra/unicode.rs)
  * Convertions between text encodings. Ideally, with a customizable way of handling conversion errors.
  * Unicode normalization (NFD, NFC, NFKD, NFKC)
  * Collator (locale sensitive string comparison), with a configurable degree of strictness

## Template engine

* Mustache
  * [erickt/rust-mustache](https://github.com/erickt/rust-mustache): [<img src="https://travis-ci.org/erickt/rust-mustache.png?branch=master">](https://travis-ci.org/erickt/rust-mustache)


## Testing

* QuickCheck
  * [mcandre/rustcheck](https://github.com/mcandre/rustcheck)


## Web Programming

* [erickt/rust-mongrel2](https://github.com/erickt/rust-mongrel2): bindings for the [Mongrel2](http://mongrel2.org) webserver
* [skade/widmann](https://github.com/skade/widmann): [<img src="https://travis-ci.org/skade/widmann.png?branch=master">](https://travis-ci.org/skade/widmann)