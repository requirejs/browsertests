#browsertests

Tests some basic capability and behavior of web browsers to help inform what is
possible for a browser-based module or script loader. Helped guide some
decisions in requirejs.

These tests are standalone tests that do not require a specific module loader.
To run them, run a web server that can serve this directory and open the
index.html file in a subdirectory to run that particular test.

These tests used to be in the requirejs repo at tests/browsertests, but was
moved to a separate repo so that GitHub would not classify the requirejs repo
as a PHP project.
