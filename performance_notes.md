ESP32-C3:

default:

20:01:05.733 init

20:01:05.733 instructions to spawn:1918

20:01:05.733 instructions to spawn (same prio):2095

20:01:05.733 instructions to spawn (higher prio):1903

20:01:05.733 instructions to spawn (lower prio):1393

20:01:05.733 instructions to spawn (hardware task):704

inlined prio handling:

21:54:58.023 init

21:54:58.023 instructions to spawn:1903

21:54:58.023 instructions to spawn (same prio):2088

21:54:58.023 instructions to spawn (higher prio):1898

21:54:58.023 instructions to spawn (lower prio):1391

21:54:58.023 instructions to spawn (hardware task):697

rtic prio handling:

22:05:17.000 init

22:05:17.000 instructions to spawn:1910

22:05:17.000 instructions to spawn (same prio):2079

22:05:17.000 instructions to spawn (higher prio):1906

22:05:17.000 instructions to spawn (lower prio):1370

22:05:17.000 instructions to spawn (hardware task):707

non-sucky runtime:

00:36:15.588 instructions to spawn:1297

00:36:15.588 instructions to spawn (same prio):1337

00:36:15.588 instructions to spawn (higher prio):1285

00:36:15.588 instructions to spawn (lower prio):1270

00:36:15.588 instructions to spawn (hardware task):66

non-sucky runtime + less-sucky atomics (atomic-polyfill)

16:10:44.358 Instructions spawn:129

16:10:44.358 Instructions spawn(same prio):177

16:10:44.358 Instructions spawn(higher prio):118

16:10:44.358 Instructions spawn(lower prio):242

16:10:44.358 Instructions dispatch(hardware task):66


