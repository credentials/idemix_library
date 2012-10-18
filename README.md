Patches for IBM's Identity Mixer library.

The license of the Identity Mixer library (LICENSE.Identity_Mixer) does not
allow us to distribute the patched library. Hence we use this repository to
maintain the required patches to use the library in combination with smart
cards.

In order to use these patches you will have to download the sources yourself
from the Identity Mixer homepage (https://prime.inf.tu-dresden.de/idemix/).

Place the downloaded archive (IdentityMixer_2-3-4.zip) in this directory. To
prepare the sources, that is apply the patches, run:

    ant prepare

To build the Identity Mixer library, run:

    ant library

To create a Java archive (jar file) which includes the sources (useful for
development purposes), run:

    ant archive

