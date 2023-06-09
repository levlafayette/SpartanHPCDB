# SpartanHPCDB
Processing datasets and using databases on the Spartan HPC


## Git

If you check this repository out be aware that it uses Git submodules to manage the reveal.js dependency. To also checkout reveal.js, you will have to either:

### Fetch it all in one hit
`git clone --recursive https://github.com/levlafayette/SpartanHPCDB`

Or:

### Take it step by step

`git clone https://github.com/levlafayette/SpartanHPCDB`   

`git submodule init`    

`git submodule update`   

To regenerate the slides

The SlideExtractor.jar in the root directory will re-create the slides if needed.

To run it ensure that the java version installed is java 8:

`java -version`

should return something along the lines of java version "1.8.0_65".

If it doesn't then install java 8 from here: `http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html`

Then in a command prompt in the root directory simply issue:

`java -jar SlideExtractor.jar`

You should see something like the following fly by:

`Working on: ./Lessons/Lesson_1.md`
`Writing to: ./Presentation/Lesson_1.html`
`Writing to: ./Presentation/index.html`

## Folders

The directories that make up this project are as follows:

* Lessons - The lesson(s);
* Planning - The plan used to create the course;
* Resources - Resources for this particular run of the training.
