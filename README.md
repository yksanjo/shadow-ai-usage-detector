# Shadow AI Usage Detector

Identify unmanaged AI tool usage and policy violations across org.

## Priority Metadata

- ID: 112
- Domain: security-agent
- TTE (days): 4
- Exposure score: 8/10
- Wave: 1
- Priority score: 7.20

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
