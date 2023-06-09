### Local Terminal Instructions
- You need to ssh into the cluster while forwarding to a chosen port
  - An example is as follow `ssh -L 8888:localhost:8888 bbogale@tellico.icl.utk.edu`

### Cluster Terminal Instructions
- You need to have apptainer loaded
  - `module load apptainer`
- You need to have openmpi loaded
  - `spack load openmpi`
