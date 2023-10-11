# financial-c
University project on C++ in finance.

## running the code
You can utilize the fact, that the whole repository is packaged into a `nix` flake. Make sure you install the `nix` package manager, which can be done via `sh <(curl -L https://nixos.org/nix/install) --daemon` as per [the official instructions](https://nixos.org/download.html). 

Afterwards, you can run the without even having to check out the repository:

`nix run github:staneesh/financial-c`

Alternatively, clone the repository and do a `nix run`.
