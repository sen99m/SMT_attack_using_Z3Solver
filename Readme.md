# Logic Locking

## Oracle

```
./a.out
```

## Locked Code
```
obfuscated.c
```
The file contains the locked logic of the function used by oracle. \
The function 'arf' takes all the inputs as arguments along with 7 keys.

## SAT attack

### Installing dependencies
```
sudo apt-get update
sudo apt-get install python3
pip3 install z3-solver
```
### Running the code

#### Executing Oracle
```
./a.out 1 2 3 4 5 6 7 8 9 10 11
```
The oracle expects 11 arguments passed at runtime.

#### Executing Python code
```
python3 solver.py
```
The DIP values are already added to the solver. Thus, executing the file will provide the values for the keys.