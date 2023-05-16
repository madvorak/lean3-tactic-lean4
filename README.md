| Lean 3         | Lean 4         | requires                            |
| -------------- | -------------- | ----------------------------------- |
| all_goals      | all_goals      | [core]                              |
| any_goals      | any_goals      | [core]                              |
| apply          | apply          | [core]                              |
| assumption     | assumption     | [core]                              |
| by_cases       | by_cases       | [core]                              |
| by_contradiction | [by_contra](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/ByContra.html)    | import Mathlib.Tactic.ByContra      |
| cases          | [cases'](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Cases.html)         | import Mathlib.Tactic.Cases         |
| congr          | congr          | [core]                              |
| contradiction  | contradiction  | [core]                              |
| contrapose     | [contrapose](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Contrapose.html)     | import Mathlib.Tactic.Contrapose    |
| convert        | [convert](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Convert.html)        | import Mathlib.Tactic.Convert       |
| convert_to     | [convert_to](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Convert.html)     | import Mathlib.Tactic.Convert       |
| exact          | exact          | [core]                              |
| exfalso        | [exfalso](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html)        | import Std.Tactic.Basic             |
| field_simp     | [field_simp](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/FieldSimp.html)     | import Mathlib.Tactic.FieldSimp     |
| finish         | —              | —                                   |
| have           | [have](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Have.html)           | import Mathlib.Tactic.Have          |
| hint           | —              | —                                   |
| induction      | [induction'](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Cases.html)     | import Mathlib.Tactic.Cases         |
| intro          | intro          | [core]                              |
| intros         | intro          | [core]                              |
| iterate        | [iterate](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html)        | import Std.Tactic.Basic             |
| left           | [left](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LeftRight.html)           | import Mathlib.Tactic.LeftRight     |
| library_search | [library_search](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LibrarySearch.html) | import Mathlib.Tactic.LibrarySearch |
| linarith       | [linarith](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Linarith.html)       | import Mathlib.Tactic.Linarith      |
| push_neg       | [push_neg](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/PushNeg.html)       | import Mathlib.Tactic.PushNeg       |
| rcases         | [rcases](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/RCases.html)         | import Std.Tactic.RCases            |
| refl           | rfl            | [core]                              |
| repeat         | [repeat'](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html)        | import Std.Tactic.Basic             |
| right          | [right](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LeftRight.html)          | import Mathlib.Tactic.LeftRight     |
| ring           | [ring](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Ring.html)           | import Mathlib.Tactic.Ring          |
| rintro         | [rintro](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/RCases.html)         | import Std.Tactic.RCases            |
| rw             | rw             | [core]                              |
| simp           | simp           | [core]                              |
| sorry          | sorry          | [core]                              |
| specialize     | specialize     | [core]                              |
| split          | constructor    | [core]                              |
| split_ifs      | split          | [core]                              |
| squeeze_simp   | [simp?](https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/SimpTrace.html)          | import Std.Tactic.SimpTrace         |
| suggest        | [library_search](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LibrarySearch.html) | import Mathlib.Tactic.LibrarySearch |
| swap           | [swap](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/PermuteGoals.html)           | import Mathlib.Tactic.PermuteGoals  |
| symmetry       | [symm](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Relation/Symm.html)           | import Mathlib.Tactic.Relation.Symm |
| tauto          | [tauto](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Tauto.html)          | import Mathlib.Tactic.Tauto         |
| try            | try            | [core]                              |
| unfold         | unfold         | [core]                              |
| use            | [use](https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Use.html)            | import Mathlib.Tactic.Use           |
