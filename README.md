# financial-c
University project on C++ in finance.

## running the code
The whole repository is packaged into a `nix` flake, which makes building, running and obtaining reproducible results trivial.
Make sure you install the `nix` package manager, which can be done via the follwing snippet from [the official instructions](https://nixos.org/download.html):
```bash
sh <(curl -L https://nixos.org/nix/install) --daemon
```

Afterwards, you can run the code without even having to check out the repository:
```bash
nix run github:staneesh/financial-c
```

Alternatively, clone the repository and do a `nix run`.
