# MiniMax H3 preliminary source branch

This public branch reconstructs the archived v3 candidate and the validated load-sync transformation. Full source is committed; no source ZIP is needed to inspect it. `source-provenance.json` records the original upstream commit, fixed archive SHA and11 server trace input/output/helper hashes. Those hashes refer to selected source boundaries, not11 independent output files or all server files. `.gitmodules` pins unchanged JSON/spdlog dependencies.

Changes cover visual frame layout, device metadata movement, host offsets, rank output placement, contiguous/synchronized weight loading and guarded trace hooks. Native core remains InfiniLM/InfiniCore. Trace/observer switches remainoff by default; Nine gated H3 switch remains0. The original reference/evaluation entry is retained. Historical job scripts may create temporary runtime entry copies with VAE precision handling; these are disclosed in the total submission repository and are not proof of official permission for auxiliary precision policy.

In the existing gfx936 vendor environment, source the AFS setup and run `git submodule update --init third_party/spdlog third_party/json`. After the public Core native/Python profiles have built into the same isolated prefix, run this as a separate28-minute job from the writable job workspace:

```bash
python3 /absolute/InfiniLM-MiniMax-H3/competition/build_from_git.py extension
```

This uses the same source-driven build adapter as Core, offline pybind/xmake dependencies, vendor Torch CXX11 ABI and a private installation prefix. It does not change weights or reference scoring. Existing evidence proves selected source hashes, a prior isolated library rebuild and one full H3 first-forward. Qwen output parity, full quality, clean-system setup and consecutive-case validation remain incomplete. New public Git adapter rebuild has not run on GPU here; do not label this source publication as new runtime acceptance.
