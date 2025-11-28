# drac-uv

Use `uv` on Digital Research Alliance of Canada compute clusters like Vulcan. Recommended by [Mila](https://docs.mila.quebec/Userguide_portability.html#uv).

```
# Install UV
curl -LsSf https://astral.sh/uv/install.sh | sh

export UV_CONSTRAINT=/cvmfs/soft.computecanada.ca/config/python/constraints.txt

uv sync
```
