| Lean 3      | Lean 4      | requires                      |
| ----------- | ----------- | ----------------------------- |
| apply       | apply       | [in core]                     |
| assumption  | assumption  | [in core]                     |
| cases       | cases'      | import Mathlib.Tactic.Cases   |
| convert     | convert     | import Mathlib.Tactic.Convert |
| convert_to  | convert_to  | import Mathlib.Tactic.Convert |
| exact       | exact       | [in core]                     |
| induction   | induction'  | import Mathlib.Tactic.Cases   |
| intro       | intro       | [in core]                     |
| intros      | intro       | [in core]                     |
| left        | left        | import Mathlib.Tactic.LeftRight |
| library_search | library_search | import Mathlib.Tactic.LibrarySearch |
| linarith    | linarith    | import Mathlib.Tactic.LibrarySearch |
| refl        | rfl         | [in core]                     |
| right       | right       | import Mathlib.Tactic.LeftRight |
| ring        | ring        | import Mathlib.Tactic.Ring    |
| rw foo      | rw [foo]    | [in core]                     |
| split       | constructor | [in core]                     |
| suggest     | library_search | import Mathlib.Tactic.LibrarySearch |
| unfold      | unfold      | [in core]                     |
| use         | use         | import Mathlib.Tactic.Use     |
