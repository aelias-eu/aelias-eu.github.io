## Compare two binary files side-by-side
```diff -y <(xxd file1) <(xxd file2)```

```colordiff -y <(xxd file1) <(xxd file2)```

show only different lines:

```colordiff -y <(xxd file1) <(xxd file2 )|grep "\ |\ "```

