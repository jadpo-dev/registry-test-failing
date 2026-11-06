# Tally

A test fixture for the jadpo.dev package registry's staging environment. It isn't meant for use.

`Tally.tally.total(amounts)` is meant to add a list of amounts. It leaves out the last one on purpose, so the
package's test fails and the publishing bar refuses it.
