| Lean 3           | Lean 4                              | requires                            |
| --------------   | --------------                      | ----------------------------------- |
| all_goals        | [all_goals][all_goals_lk]           | [core]                              |
| any_goals        | [any_goals][any_goals_lk]           | [core]                              |
| apply            | [apply][apply_lk]                   | [core]                              |
| assumption       | [assumption][assumption_lk]         | [core]                              |
| by_cases         | [by_cases][by_cases_lk]             | import Mathlib.Tactic.Basic         |
| by_contradiction | [by_contra][by_contra_lk]           | import Std.Tactic.Basic             |
| by_contra        | [by_contra][by_contra_lk]           | import Std.Tactic.Basic             |
| by_contra'       | [by_contra'][by_contra'_lk]         | import Mathlib.Tactic.ByContra      |
| cases            | [cases'][cases'_lk]                 | import Mathlib.Tactic.Cases         |
| congr            | [congr][congr_lk]                   | [core]                              |
| contradiction    | [contradiction][contradiction_lk]   | [core]                              |
| contrapose       | [contrapose][contrapose_lk]         | import Mathlib.Tactic.Contrapose    |
| convert          | [convert][convert_lk]               | import Mathlib.Tactic.Convert       |
| convert_to       | [convert_to][convert_to_lk]         | import Mathlib.Tactic.Convert       |
| exact            | [exact][exact_lk]                   | [core]                              |
| exfalso          | [exfalso][exfalso_lk]               | import Std.Tactic.Basic             |
| field_simp       | [field_simp][field_simp_lk]         | import Mathlib.Tactic.FieldSimp     |
| finish           | —                                   | —                                   |
| have             | [have][have_lk]                     | import Mathlib.Tactic.Have          |
| hint             | —                                   | —                                   |
| induction        | [induction'][induction'_lk]         | import Mathlib.Tactic.Cases         |
| intro            | [intro][intro_lk]                   | [core]                              |
| intros           | [intro][intro_lk]                   | [core]                              |
| iterate          | [iterate][iterate_lk]               | import Std.Tactic.Basic             |
| left             | [left][left_lk]                     | import Mathlib.Tactic.LeftRight     |
| library_search   | [library_search][library_search_lk] | import Mathlib.Tactic.LibrarySearch |
| linarith         | [linarith][linarith_lk]             | import Mathlib.Tactic.Linarith      |
| push_neg         | [push_neg][push_neg_lk]             | import Mathlib.Tactic.PushNeg       |
| rcases           | [rcases][rcases_lk]                 | import Std.Tactic.RCases            |
| refl             | [rfl][rfl_lk]                       | [core]                              |
| repeat           | [repeat'][repeat'_lk]               | import Std.Tactic.Basic             |
| right            | [right][right_lk]                   | import Mathlib.Tactic.LeftRight     |
| ring             | [ring][ring_lk]                     | import Mathlib.Tactic.Ring          |
| rintro           | [rintro][rintro_lk]                 | import Std.Tactic.RCases            |
| rw               | [rw][rw_lk]                         | [core]                              |
| simp             | [simp][simp_lk]                     | [core]                              |
| sorry            | [sorry][sorry_lk]                   | [core]                              |
| specialize       | [specialize][specialize_lk]         | [core]                              |
| split            | [constructor][constructor_lk]       | [core]                              |
| split_ifs        | [split][split_lk]                   | [core]                              |
| squeeze_simp     | [simp?][simp?_lk]                   | import Std.Tactic.SimpTrace         |
| suggest          | [library_search][library_search_lk] | import Mathlib.Tactic.LibrarySearch |
| swap             | [swap][swap_lk]                     | import Mathlib.Tactic.PermuteGoals  |
| symmetry         | [symm][symm_lk]                     | import Mathlib.Tactic.Relation.Symm |
| tauto            | [tauto][tauto_lk]                   | import Mathlib.Tactic.Tauto         |
| try              | [try][try_lk]                       | [core]                              |
| unfold           | [unfold][unfold_lk]                 | [core]                              |
| use              | [use][use_lk]                       | import Mathlib.Tactic.Use           |

<!--  Autogenerated links  -->
<!--  `autolinks` removes modifications from here on  -->
[right_lk]:           https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LeftRight.html#Mathlib.Tactic.tacticRight "right"
[linarith_lk]:        https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Linarith/Frontend.html#linarith "linarith"
[have_lk]:            https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Have.html#have "have"
[use_lk]:             https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Use.html#use "use"
[rintro_lk]:          https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/RCases.html#rintro "rintro"
[rcases_lk]:          https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/RCases.html#rcases "rcases"
[by_contra_lk]:       https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html#Std.Tactic.byContra "by_contra"
[by_contra'_lk]:      https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/ByContra.html#by_contra "by_contra'"
[iterate_lk]:         https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html#Std.Tactic.tacticIterate____ "iterate"
[repeat'_lk]:         https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html#Std.Tactic.tacticRepeat'_ "repeat'"
[left_lk]:            https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LeftRight.html#Mathlib.Tactic.tacticLeft "left"
[convert_to_lk]:      https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Convert.html#convert_to "convert_to"
[field_simp_lk]:      https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/FieldSimp.html#field_simp "field_simp"
[exfalso_lk]:         https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/Basic.html#exfalso "exfalso"
[cases'_lk]:          https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Cases.html#cases' "cases'"
[simp?_lk]:           https://leanprover-community.github.io/mathlib4_docs/Std/Tactic/SimpTrace.html#simp? "simp?"
[induction'_lk]:      https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Cases.html#induction' "induction'"
[contrapose_lk]:      https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Contrapose.html#contrapose "contrapose"
[push_neg_lk]:        https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/PushNeg.html#push_neg "push_neg"
[library_search_lk]:  https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/LibrarySearch.html#library_search "library_search"
[tauto_lk]:           https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Tauto.html#tauto "tauto"
[swap_lk]:            https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/PermuteGoals.html#Mathlib.Tactic.tacticSwap "swap"
[ring_lk]:            https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Ring/Basic.html#ring "ring"
[convert_lk]:         https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Convert.html#convert "convert"
[symm_lk]:            https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Relation/Symm.html#symm "symm"
[all_goals_lk]:       https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.allGoals "all_goals"
[any_goals_lk]:       https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.anyGoals "any_goals"
[apply_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.apply "apply"
[assumption_lk]:      https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.assumption "assumption"
[by_cases_lk]:        https://leanprover-community.github.io/mathlib4_docs/Mathlib/Tactic/Basic.html#Mathlib.Tactic.tacticBy_cases_ "by_cases"
[congr_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.congr "congr"
[contradiction_lk]:   https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.contradiction "contradiction"
[exact_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.exact "exact"
[intro_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.intro "intro"
[rfl_lk]:             https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.tacticRfl "rfl"
[rw_lk]:              https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.rwSeq "rw"
[simp_lk]:            https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.simp "simp"
[sorry_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.tacticSorry "sorry"
[specialize_lk]:      https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.specialize "specialize"
[constructor_lk]:     https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.constructor "constructor"
[split_lk]:           https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.split "split"
[try_lk]:             https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.tacticTry_ "try"
[unfold_lk]:          https://leanprover-community.github.io/mathlib4_docs/Init/Tactics.html#Lean.Parser.Tactic.unfold "unfold"
