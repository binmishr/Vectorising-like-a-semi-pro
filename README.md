# Vectorising-like-a-semi-pro

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=====================



This is a short practical post about programming with R. Take it for what it
is and nothing more…

R is slow! That is what they keep telling us (they being someone who “knows”
about “real” programming and has another language that they for some reason fail
to be critical about).

R is a weird thing. Especially for people who has been trained in a classical
programming language. One of the main reasons for this is its vectorised nature,
which is not just about the fact that vectors are prevalent in the language, but
is an underlying principle that should guide the design of efficient algorithms
in the language. IF you write R like you write C (or Python), then sure it is
slow, but really, you are just using it wrong.

This post will take you through the design of a vectorised function. The genesis
of the function comes from my generative art, but I thought it was so nice and
self-contained that it would make a good blog post. If that seems like something
that could take your mind off the pandemic, then buckle up!
