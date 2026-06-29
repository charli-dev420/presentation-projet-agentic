# Scenario: Unity Asset Loop

## Flow

1. A user describes the Unity target and asset constraints.
2. CodexToUnity frames a job and expected manifest.
3. LocalAssetFactory handles generation or dry-run, normalization, and sockets.
4. Unity receives a manifest and import checklist.
5. A human reviews scene, scale, pivot, materials, and usability.

## Public Output

A written summary and diagram. No GLB/FBX/OBJ, workflow, endpoint, local path, model config, generated private asset, or Unity build is published.
