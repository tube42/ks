ks
==

KS (kickstarter) is a minimal Java library for things that are commonly needed in UI and game projects:

 * Object pools
 * Containers for fast read (lists, stacks and so on)
 * Job schedulers
 * Job state machines



The main target for this library is game development, hence it has been designed to minimize object creation.

Get it
------

Source code (under LGP-v3):
::
 git clone https://github.com/tube42/ks.git


Bintray maven repository:

.. image:: https://api.bintray.com/packages/tube42/maven/ks/images/download.svg
    :target: https://bintray.com/tube42/maven/ks/_latestVersion

If you are using gradle with jcenter():
::
 dependencies {
    compile "se.tube42.ks:ks:0.3.1"
 }

Where 0.3.1 is the version you want to use...