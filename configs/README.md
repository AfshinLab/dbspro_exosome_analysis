# Configuration files for running DBS-Pro pipeline

## To run 
1. Setup DBS-Pro according to instructions in https://github.com/FrickTobias/DBS-Pro
2. Initialize working directory using (Ex. using hashing samples)

    dbspro init -s hashing_samples.csv --abc hashing_ABCs.fasta hashing_out

3. Move into the generated dir `hashing_out` and run analysis

    cd hashing_out && dbspro run
