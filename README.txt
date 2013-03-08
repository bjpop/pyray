################################################################################
#
# Description:
#
# This module implements a simple ray tracer. Its features are:
#
#    - Multiple point (white) light sources.
#    - Multiple coloured objects (spheres, planes).
#    - Ambient illumination (simulating scattered light).
#    - Diffuse illumination (simulating light scattering surfaces).
#    - Specular illumination using the Phong model (simulating highlights).
#    - Reflective illumination (simulating mirrored surfaces).
#    - Shadows.
#
# It was written for the purposes of demonstrating Ray Tracing in an 
# Advanced Lecture of the University of Melbourne subject COMP10001
# Foundations of Computing. As such the emphasis is on simplicity and
# clarity over performance. There are many ways to make this program
# faster, but usually at the expence of code readability.
#
# Authors:
#
# Bernie Pope (bjpope@unimelb.edu.au)
#
# Date created:
#
# 17 August 2012
#
# Date modified and reason:
#
# 21 August 2012: more documentation added 
# 22 August 2012: plane objects added
# 23 August 2012: command line argument parser added
#
################################################################################
