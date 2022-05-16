# Configuration files for running DBS-Pro pipeline

## To run 
1. Download [DBS-Pro version 0.3](https://github.com/FrickTobias/DBS-Pro/tree/v0.3).
```{bash}
git clone https://github.com/FrickTobias/DBS-Pro
cd DBS-Pro
git checkout v0.3
```

2. Setup environment follow the instructions [here](https://github.com/FrickTobias/DBS-Pro/tree/v0.3#setup).
3. Initialize working directory using (Ex. using hashing samples)

```{bash}
dbspro init -s hashing_samples.csv --abc hashing_ABCs.fasta hashing_out
```

4. Move into the generated dir `hashing_out` and run analysis

```{bash}
cd hashing_out && dbspro run
```
