# anonymize_pathSlides
This is a program to remove the slide label from whole-slide images in the following formats: .svs, .ndpi, .mrxs. Works with Python3

# Modified on 4-1-26 to work with Python 3 and remove macro label from slides as well
# Note: Only run on copies of the image file, as this application directly modifies the provided file path

#!/usr/bin/env python3
#
#  anonymize-slide.py - Delete the slide and macro label from a whole-slide image
#
#  Original copyright:
#    (c) 2007-2013 Carnegie Mellon University
#    (c) 2011      Google, Inc.
#    (c) 2014      Benjamin Gilbert

#
#  License: GPLv2 (same as original)
#
