# Running jobs on the cluster

Please see [the Research Computing website](https://rc-docs.northeastern.edu/en/latest/runningjobs/index.html) for full information.

## Headings for your batch script:

```
#!/bin/bash
#SBATCH -J SAMview                          # Job name
#SBATCH -N 2                                # Number of nodes
#SBATCH -n 16                               # Number of tasks
#SBATCH -o output_%j.txt                    # Standard output file
#SBATCH -e error_%j.txt                     # Standard error file

# Load necessary modules, if needed

# Go to specific location, if needed

# Command
```
