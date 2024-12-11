# CropboxUI
Placeholder repository for Cropbox Web UI functionality.

## Installation

```julia
using Pkg
Pkg.add(url="https://github.com/junhyukjeon/CropboxUI.git")

using CropboxUI
using Poplar

# Launch the UI with the Poplar model
launch_ui(Poplar.Model)
