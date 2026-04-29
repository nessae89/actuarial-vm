
# v3 Binding Model

OP_ASSERT_SOLVENCY v3 removes script-level witness binding and enforces correctness via AVM execution trace consistency.

Binding is validated by reconstructing proportional relationships across committed trace state.

This preserves:
- constant-time L1 verification
- fail-closed solvency guarantees
- minimal script footprint

This approach reduces the witness tampering surface by enforcing trace-consistent validation while maintaining the existing watcher model.

No additional trust assumptions are introduced beyond trace integrity.
