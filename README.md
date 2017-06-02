# problem statement
removes files & dirs ignored by git

# example usage

> note: in examples, VERSION represents a version of the git.clean pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/git.clean#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/git.clean#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/git.clean#VERSION }
  inputs: { srcDir, opts }
  outputs: { srcDir }
```
