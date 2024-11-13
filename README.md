| Lean 3           | Lean 4        | requires                            |
| ---------------- | ------------- | ----------------------------------- |
| all_goals        | all_goals     | [core]                              |
| any_goals        | any_goals     | [core]                              |
| apply            | apply         | [core]                              |
| assumption       | assumption    | [core]                              |
| by_cases         | by_cases      | [core]                              |
| by_contradiction | by_contra     | import Mathlib.Tactic.ByContra      |
| by_contra        | by_contra     | import Mathlib.Tactic.ByContra      |
| cases            | cases'        | import Mathlib.Tactic.Cases         |
| congr            | congr         | [core]                              |
| contradiction    | contradiction | [core]                              |
| contrapose       | contrapose    | import Mathlib.Tactic.Contrapose    |
| convert          | convert       | import Mathlib.Tactic.Convert       |
| convert_to       | convert_to    | import Mathlib.Tactic.Convert       |
| exact            | exact         | [core]                              |
| exfalso          | exfalso       | [core]                              |
| field_simp       | field_simp    | import Mathlib.Tactic.FieldSimp     |
| finish           | —             | —                                   |
| have             | have          | import Mathlib.Tactic.Have          |
| hint             | hint          | import Mathlib.Tactic.Hint          |
| induction        | induction'    | import Mathlib.Tactic.Cases         |
| intro            | intro         | [core]                              |
| intros           | intro         | [core]                              |
| iterate          | iterate       | [core]                              |
| left             | left          | [core]                              |
| library_search   | exact?        | [core]                              |
| linarith         | linarith      | import Mathlib.Tactic.Linarith      |
| omega            | omega         | [core]                              |
| push_neg         | push_neg      | import Mathlib.Tactic.PushNeg       |
| rcases           | rcases        | [core]                              |
| refl             | rfl           | [core]                              |
| repeat           | repeat'       | [core]                              |
| right            | right         | [core]                              |
| ring             | ring          | import Mathlib.Tactic.Ring          |
| rintro           | rintro        | [core]                              |
| rw               | rw            | [core]                              |
| simp             | simp          | [core]                              |
| sorry            | sorry         | [core]                              |
| specialize       | specialize    | [core]                              |
| split            | constructor   | [core]                              |
| split_ifs        | split         | [core]                              |
| squeeze_simp     | simp?         | [core]                              |
| suggest          | apply?        | [core]                              |
| swap             | swap          | import Batteries.Tactic.PermuteGoals|
| symmetry         | symm          | import Mathlib.Tactic.Relation.Symm |
| tauto            | tauto         | import Mathlib.Tactic.Tauto         |
| try              | try           | [core]                              |
| unfold           | unfold        | [core]                              |
| use              | use           | import Mathlib.Tactic.Use           |
