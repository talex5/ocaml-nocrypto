0.3.0 (2014-12-21):
* removed ad-hoc key marshalling functions as key material typically comes
  non-trivially encoded anyways
* changed how module interfaces for the packed module are handled:
  `module type of` constructs are gone
* more consistent errors in rsa
* small api breakage here and there

0.2.2 (2014-11-04):
* replaced hashing sources with the ones from hs-cryptohash
  (https://github.com/vincenthz/hs-cryptohash) by Vincent Hanquez
* renamed various symbols likely to conflict with other crypto libraries

0.2.0 (2014-10-30):
* DSA (initial version contributed by Hannes Mehnert <hannes@mehnert.org>)
* CCM mode for AES (contributed by Hannes Mehnert <hannes@mehnert.org>)
* switched from hand written stubs to ctypes for intefacing with the C code
* packed the module to avoid clobbering global namespace; some modules renamed
* various bugfixes and improvements

0.1.0 (2014-07-08):
* initial (beta) release
