To build the image run

	$ docker build -t gabrieleteotino/tensorflow-pandas:latest .

The build will compile pandas, so you have to wait a few minutes.


To use the image run

	$ docker run -it -v /Users/gabriele/tensorflow:/workspace -p 80:8888 gabrieleteotino/tensorflow-pandas

Substitute /Users/gabriele/tensorflow with the folder containing your github clone of this repository.
Substitute port 80 with whatever you have free on your docker host