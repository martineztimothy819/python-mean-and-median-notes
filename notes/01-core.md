# Compare mean and median: implementation

## What the example does

The median resists isolated outliers more than the arithmetic mean. Empty input is rejected because neither statistic is defined here.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  1,
  2,
  3
]
```

Expected result:

```json
{
  "mean": 2,
  "median": 2
}
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
