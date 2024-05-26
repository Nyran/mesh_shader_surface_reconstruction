# Efficient Particle-Based Fluid Surface Reconstruction Using Mesh Shaders and Bidirectional Two-Level Grids

Yuki Nishidate and Issei Fujishiro. 2024. Efficient Particle-Based Fluid Surface Reconstruction Using Mesh Shaders and Bidirectional Two-Level Grids. Proc. ACM Comput. Graph. Interact. Tech. 7, 1, Article 1 (May 2024), 14 pages. https://doi.org/10.1145/3651285

# Build

```sh
# Clone
git clone ... --recursive

# Pull zip file using Git LFS (Please install)
git lfs install
git lfs pull

# !IMPORTANT!
# Please unzip the contents of 'asset/FluidBeach.zip' under 'asset/'

# Generate a project
cmake . -B build -DCMAKE_TOOLCHAIN_FILE=vcpkg/scripts/buildsystems/vcpkg.cmake

# Build using your IDE or compiler
```

# Cite

```
@article{10.1145/3651285,
    author = {Nishidate, Yuki and Fujishiro, Issei},
    title = {Efficient Particle-Based Fluid Surface Reconstruction Using Mesh Shaders and Bidirectional Two-Level Grids},
    year = {2024},
    issue_date = {May 2024},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    volume = {7},
    number = {1},
    url = {https://doi.org/10.1145/3651285},
    doi = {10.1145/3651285},
    journal = {Proc. ACM Comput. Graph. Interact. Tech.},
    month = {may},
    articleno = {1},
    numpages = {14},
}
```
