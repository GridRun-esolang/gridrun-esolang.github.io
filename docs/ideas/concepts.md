---
layout: "default"
title: "concepts"
description: "ideas"
---

## operations

- add / sum
- multiply
- div & mod
- negate

## queue

- apply / execute queue
- clear queue

## periphery

- input
- output

## variable index

```
move down         move up
<-------- pointer ------>
             |
             V
| -2 | -1 |  0 |  1 |  2 |
--------------------------
|    |    |    |    |    |
                  Λ
                  |
            random access
```

## control flow

### return to previous branching

```
       Λ
       |
       | /-------|
       |V        |
-----> o -----> -|
       |
       V
```

### goto / jump

```
-----> o
        \
         V
         o ----->
```

### hop/bridge

```
     |
     |
-----)----->
     |
     V
```

## branching

### additive (a) junction: compare 2

```
               a
               |
               V
a <= b  <----- o -----> a >= b
               Λ
               |
               b


```

### executive (e) junction: based on turn intention

turn left:
```
       Λ
       |
-----> o
```

turn right:
```
-----> o
       |
       V
```

### (i) junction

### operative (o) junction: comparison from queue

```
     a < b
       Λ
       |
-----> o -----> a = b
       |
       V
     a > b
```

### unconditional (u) junction

```
       Λ
       |
-----> o ----->
       |
       V
```

