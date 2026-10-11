# metrics-exporter

A minimal metrics registry with counters, gauges and histograms.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install metrics-exporter
```

## Usage

```python
from metrics_exporter import metricsExporter

result = metricsExporter("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
