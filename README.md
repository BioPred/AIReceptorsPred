# AIReceptorsPred

Prediction model and source code for AIReceptorsPred

For running the code, download or clone the repository.

1- Open AIReceptorsPred.py

2- Change the filname in Line 272 of code (for seq_record in SeqIO.parse("./data/adpative326.fasta", "fasta"))

3- Benchmark data is also provided in data folder, which can be used to test the predictor.

Note: Make sure model.pkl and std_scale.pkl are present in model folder. Also, currently the predictor only takes fasta file as input
