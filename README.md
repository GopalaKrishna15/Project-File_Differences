# Project-File_Differences
In this project you will find differences in the contents of two files. In particular, you will find the location of the first character in every line that differs between two input files. You might want to do something like this if you are comparing how something has changed.  It is convenient to present to the user the first difference in the lines to allow them to see what has happened.

### Output format:
The written python code prints the line number in which there is a difference between the two files and then it prints this full line from the first file and then it prints this line till the first difference.

#### Sample file1.txt:
Sample Document

Fusce convallis metus id felis luctus adipiscing. Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Fusce vel dui. Sed augue ipsum, egestas nec, vestibulum et, malesuada adipiscing, dui. Phasellus viverra nulla ut metus varius laoreet.

Nulla facilisi. Phasellus accumsan cursus velit. Curabitur at lacus ac velit ornare lobortis. Maecenas vestibulum mollis diam. Phasellus blandit leo ut odio.

Praesent ac massa at ligula laoreet iaculis. Pellentesque dapibus hendrerit tortor. Nam commodo suscipit quam. Sed a libero. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede.

Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Curabitur ullamcorper ultricies nisi. Pellentesque posuere. Fusce fermentum. Morbi vestibulum volutpat enim.

In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Curabitur a felis in nunc fringilla tristique. Donec mollis hendrerit risus. Vestibulum turpis sem, aliquet eget, lobortis pellentesque, rutrum eu, nisl. Proin magna.
#### Sample file2.txt:
Sample Document

Fusce convallis metus id felis luctus adipiscing. Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Fusce vel dui. Sed augue ipsum, egestas nec, vestibulum et, malesuada adipiscin, dui. Phasellus viverra nulla ut metus varius laoreet.

Nulla facilisi. Phasellus accumsan cursus velit. Curabitr at lacus ac velit ornare lobortis. Maecenas vestibulum mollis diam. Phasellus blandit leo ut odio.

Praesent ac massa at ligula laoreet iaculis. Pellentesque dapibus hendrerit tortor. Nam commodo suscipit quam. Sed a libero. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede.

Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Curabitur ullamcorper ultricies nisi. Pellentesque posuere. Fusce fermentum. Morbi vestibulum volutpat enim.

In enim justo, rhoncus ut, imperdiet a,venenatis vitae, justo. Curabitur a felis in nunc fringilla tristique. Donec mollis hendrerit risus. Vestibulum turpis sem, aliquet eget, lobortis pellentesque, rutrum eu, nisl. Proin magna.

#### Sample Output
Line 3:
Fusce convallis metus id felis luctus adipiscing. Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Fusce vel dui. Sed augue ipsum, egestas nec, vestibulum et, malesuada adipiscing, dui. Phasellus viverra nulla ut metus varius laoreet.

Fusce convallis metus id felis luctus adipiscing. Pellentesque egestas, neque sit amet convallis pulvinar, justo nulla eleifend augue, ac auctor orci leo non est. Fusce vel dui. Sed augue ipsum, egestas nec, vestibulum et, malesuada adipiscin

Line 5:
Nulla facilisi. Phasellus accumsan cursus velit. Curabitur at lacus ac velit ornare lobortis. Maecenas vestibulum mollis diam. Phasellus blandit leo ut odio.

Nulla facilisi. Phasellus accumsan cursus velit. Curabit

Line 11:
In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Curabitur a felis in nunc fringilla tristique. Donec mollis hendrerit risus. Vestibulum turpis sem, aliquet eget, lobortis pellentesque, rutrum eu, nisl. Proin magna.

In enim justo, rhoncus ut, imperdiet a,
