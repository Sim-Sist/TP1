# SimSist-TP1
```bash
chmod +x run.sh
```
and then
```bash
./run.sh
```
to generate output files in folder _output_

The output files have the following formats:

**particles.txt:**

##### Header
- Number of particles
- Size of Space
- Length of critical radius
- One free line to put a comment/name. This can also be left blank.

##### Body
- Body of textfile consists of one line for each particle with its xy coordinates separated by a space

**neighbours.txt:**

##### Header
- The target cell to display its neighbours
- One free line to put a comment/name. This can also be left blank.

##### Body
- Body of textfile consists of one line for each particle with a list of all its neighbours separated by a space
