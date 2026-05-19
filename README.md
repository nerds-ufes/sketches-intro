# sketches-intro

![Python](https://img.shields.io/badge/python-3.8+-blue) 
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange) 
![License](https://img.shields.io/badge/license-MIT-green)


Introductory Jupyter notebook on probabilistic data structures applied to network traffic analysis.

## Structures covered

- **Bitmap** — exact membership for small universes
- **Bloom Filter** — approximate membership with controlled false positive rate
- **Count-Min Sketch** — approximate frequency counting for data streams

## Dataset

Synthetic stream of 1,000,000 packets with Zipf-distributed destination IPs (α=1.3), replicating real backbone traffic behavior.

## Requirements

```bash
pip install numpy matplotlib jupyter
```

## Usage

```bash
jupyter notebook sketches-intro.ipynb
```

## References

- Bloom, B. H. (1970). Space/time trade-offs in hash coding with allowable errors. *Communications of the ACM*.
- Cormode, G., & Muthukrishnan, S. (2005). An improved data stream summary: the count-min sketch. *Journal of Algorithms*.

---
LPRM / Departamento de Informática — Universidade Federal do Espírito Santo (Ufes)
