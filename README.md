fantom-rs-architecture
======================
Architecture of Fantom Foundation Rust projects

## Dependencies
[Graphviz](https://www.graphviz.org)

## Regenerate diagrams

### Linux (Bash)
```bash
for f in *.dot; do
  dot -Tpng "$f" -o "${f%.*}".png;
done
```
### Windows (CMD)
```cmd
for %%f in (*.dot) do (
  dot -Tpng "%%f" -o "%%~nf".png
)
```
