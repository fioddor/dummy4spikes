# dummy4spikes
Dummy project for my spikes (tiny PoC) on git or github tooling and procedures.

Let's test
* a ff (smooth) fetch.
* a ff (smooth) rebase.
* ok: I checked that Repository>Pull works at least for ff.
* github-desktop guides the user in handling conflicts:
  1. + It detects the clash
  2. + It merges and marks the conflict in the local clone (unstaged).
  3. + It asks the user to solve the conflict and offers to commit the resolution.
  4. + It applies the solution to the conflict.
  5. - It visualizes a sequence: 0->A, then 0->B, then B->AB, which feels weird and cofusing.
  6. + git log --graph --oneline showsdiff  the merge as a branch.
  7. + git diff visualizes as requested (no preffered sequence).
* Detects github-desktop conflicts upfront?
