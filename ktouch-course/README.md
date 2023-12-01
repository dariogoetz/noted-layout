# Generate KTouch courses for Noted layout

This minor project contains everything to generate a first usable KTouch course
for Noted. While not perfect, it is sufficient to get started to learn the
layout.


## Usage

In order to generate the `noted.xml` layout file and the `ktouch-course.xml`
course file one has to run `make`. After that, these files will be generated.

Once the files are available, they have to be imported by KTouch.


## TODO

- The noted XML file has minor flaws. For instance, the Neo2-Y is mapped to
  Noted-M3. This cannot be fixed easily using scripting, At the same time, it
  does not interfere with most of the courses, so it can be left.

- It seems as if a better corpus could be used to sample real words from. Any
  suggestions are highly welcome.
