fantom-rs-architecture
======================
Architecture of Fantom Foundation Rust projects

## Dependencies
[Graphviz](https://www.graphviz.org)

## Regenerate diagrams
```bash
for f in *.dot; do dot -Tpng "$f" -o "${f%.*}".png; done
```
