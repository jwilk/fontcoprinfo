#!/usr/bin/python

import fontforge
import sys

for filename in sys.argv[1:]:
    font = fontforge.open(filename)
    print '%s: %s' % (filename, font.copyright)

# vim:ts=4 sw=4 et
