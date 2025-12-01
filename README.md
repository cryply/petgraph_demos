<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Rust Graph Algorithms with Jupyter

This repository contains Jupyter notebooks demonstrating graph algorithms implemented in Rust using the `petgraph` crate. The notebooks cover algorithms such as Kosaraju's Strongly Connected Components and Dijkstra's shortest path, providing interactive exploration of graph data structures and algorithms.

## Project Purpose

- Explore graph algorithms in Rust interactively.
- Leverage the `petgraph` crate for efficient graph operations and visualization.
- Use Jupyter notebooks for rapid prototyping and educational purposes.
- Showcase the capabilities of the `evcxr` project, which enables Rust code execution within Jupyter notebooks.


## How to Run

1. Install Rust and Cargo if not already present.
2. Install the `evcxr_jupyter` kernel:

```sh
cargo install evcxr_jupyter
evcxr_jupyter --install
```

3. Launch Jupyter Notebook:

```sh
jupyter notebook
```

4. Open the notebooks in this repository and select the Rust (Evcxr) kernel.
5. Run cells as needed; you can use `:dep petgraph` in a cell to add the petgraph crate.

## License

This repository is licensed under the Apache License 2.0, which is permissive and suitable for open-source projects involving Rust and Jupyter notebooks.[^1]

## Why Evcxr?

The `evcxr` project enables interactive Rust programming in Jupyter notebooks, making it possible to:

- Rapidly prototype and test graph algorithms.
- Visualize graph structures and algorithm outputs.
- Integrate with the broader Jupyter ecosystem for data analysis and education.[^2][^3][^4]


## Dependencies

- Rust toolchain
- Jupyter Notebook
- evcxr_jupyter kernel
- petgraph crate


## Usage Notes

- Use `:dep petgraph` in notebook cells to add the petgraph dependency.
- The notebooks demonstrate usage of graph algorithms and visualization with petgraph and evcxr.
- For more details, refer to the petgraph and evcxr documentation.[^5][^6][^7]

***

This setup allows for fast experimentation and learning of graph algorithms in Rust, leveraging the power of interactive notebooks and modern Rust crates.
<span style="display:none">[^10][^11][^12][^13][^14][^15][^16][^17][^18][^19][^20][^8][^9]</span>

<div align="center">⁂</div>

[^1]: https://stackoverflow.com/questions/60866453/what-is-the-correct-way-to-embed-license-information-into-a-jupyter-notebook-fil

[^2]: https://depth-first.com/articles/2020/09/21/interactive-rust-in-a-repl-and-jupyter-notebook-with-evcxr/

[^3]: https://ratulmaharaj.com/posts/interactive-rust-with-jupyter-notebooks/

[^4]: https://crates.io/crates/evcxr_jupyter

[^5]: https://docs.rs/petgraph-evcxr

[^6]: https://docs.rs/petgraph/

[^7]: https://github.com/evcxr/evcxr

[^8]: https://www.reddit.com/r/rust/comments/e0zhb3/this_review_of_the_petgraph_library_shows_the/

[^9]: https://github.com/timthelion/petgraph-evcxr

[^10]: https://ultrasaurus.com/2019/08/graph-in-rust-using-petgraph/

[^11]: https://www.reddit.com/r/rust/comments/16wudrv/getting_started_with_rust_and_jupyter_notebooks/

[^12]: https://www.40tude.fr/docs/06_programmation/rust/001_rust_jupyter/rust_jupyter.html

[^13]: https://crates.io/users/timthelion

[^14]: https://www.youtube.com/watch?v=0UEMn3yUoLo

[^15]: https://github.com/ml-tooling/best-of-jupyter

[^16]: https://stackoverflow.com/questions/49087693/create-a-petgraph-graph-from-a-vecstring-string-loaded-from-json

[^17]: https://developers.stellar.org/docs/tools/developer-tools/jupyter-notebooks

[^18]: https://github.com/runtimed/runtimed

[^19]: https://www.reddit.com/r/rust/comments/ho1nzx/get_started_with_rust_and_evcxr_for_rust_jupyter/

[^20]: https://shadow.github.io/docs/rust/petgraph/graph/struct.Graph.html

