### To build on Mac

```
g++ main.cxx -std=c++0x -Wall -o raam -lpthread
```

### Data matrix (`data/times.csv`) should have the format

```
origin,destination,cost
19001960100,19085290500,83.7470933221921
19001960100,19001960200,25.3895788908598
19001960100,19001960300,21.2815596194004
19001960100,19003950100,81.3646602630358
```

### Supply/Demand (`data/doc_pop.csv`) is of the format 

```
geoid,doc,pop
17001000100,0,4627
17001000201,0,1986
17001000202,0,2999
17001000400,3,4322
```

### To run

```
./raam
```
