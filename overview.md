We have four repositories that you could look at in order to get a
better impression of what we are doing.

TODO: https://github.com/coding-the-humanities/TO-DO.git

The first is our TODO list, which encompasses everything our interns
have to do on a week to week basis. We start the week with reviewing
last week's protocol. After that we draft one for the coming week.

STATIC WEBSITE: https://github.com/coding-the-humanities/unacademic_static.git

The second is unacademic_static. This is the static website curriculum
that the interns are building. At the moment, We're using Gulp to
generate our web page from yaml files by pasting them into handlebars.
The website is static html at the moment, but we want to move to either 
angular or polymer in the next few weeks.

In a directory of the static website, we have our objective files in 
which we develop our curriculum.  Initially we were thinking about 
making our own file format, but we decided that this is too much for 
the moment. Now we are using YAML. 

Still, the basic idea seems the same. We want a very lightweight data
format that allows everyone to contribute and add their objectives, 
projects, and curriculums extremely easily.

MOBILE APP: https://github.com/coding-the-humanities/unacademic.git

The third is the mobile app of unacademic that Jan Hein is working one.
It uses yaml, gulp, angular, and ionic. Also, this version is fully
tested and uses es6 for its models. In a way the mobile app is leading
the development of our webbased version.

This one uses the same yaml objectives. We should separate that part out 
in a separate git submodule quite soon.

PROJECT SITE: https://github.com/coding-the-humanities/site.git

The fourth is the website of Coding the Humanities itself. The
repository is called 'site'.

We will also add you to our slack. This is the place where all our
communication happens.
