---
layout: "default"
title: "instructions"
description: "ideas"
---

c/v | letter | instruction | comment
--- | --- | --- | ---
v | a | apply    | HEAD operation queue -> HEAD operand queue => HEAD var index
  | b | branch   | unconditional 3-way branching
  | c | compare  | 3-way branching: `a > b` -> left, `a = b` -> forward, `a < b` -> right
  | d | division | add [div & mod] operation to HEAD operation queue
v | e | execute  | execute turn intention
  | f |          |
  | g |          |
  | h |          |
v | i | input    | read value from input
  | j |          |
  | k |          |
  | l | left     | add (-90˚) to **e**xecute turn intention
  | m |          |
  | n | nop      | no operation
v | o | output   | write value to output
  | p |          |
  | q | queue    | add HEAD var index to HEAD operand queue
  | r | right    | add(90˚) to **e**xecute turn intention
  | s | sum      | add **s**um operation to HEAD operation queue
  | t |          |
v | u |          |
  | v |          |
  | w |          |
  | x | eXecute  | reverse HEAD to the last **e**xecute junction
  | y |          |
  | z |          |

# history

- 2021-11-14: initial start
