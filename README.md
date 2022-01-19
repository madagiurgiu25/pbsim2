1. About PBSIM

Check the original repository https://github.com/yukiteruono/pbsim2

2. Simulate circular genome

Here we extended the package to enable reads simulation using a circular reference.

```
pbsim --depth 20
          --prefix depth20
          --sample-fastq sample/sample.fastq
          --sample-profile-id pf1
          --circular 1
          sample/sample.fasta
```

