# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ops/ms
# Warmup Iteration   2: 12.244 ops/ms
# Warmup Iteration   3: 12.619 ops/ms
Iteration   1: 12.888 ops/ms
Iteration   2: 12.592 ops/ms
Iteration   3: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.849 ±(99.9%) 4.377 ops/ms [Average]
  (min, avg, max) = (12.592, 12.849, 13.067), stdev = 0.240
  CI (99.9%): [8.472, 17.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.379 ops/ms
# Warmup Iteration   2: 13.329 ops/ms
# Warmup Iteration   3: 13.441 ops/ms
Iteration   1: 13.139 ops/ms
Iteration   2: 12.939 ops/ms
Iteration   3: 13.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.236 ±(99.9%) 6.495 ops/ms [Average]
  (min, avg, max) = (12.939, 13.236, 13.631), stdev = 0.356
  CI (99.9%): [6.742, 19.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.950 ops/ms
# Warmup Iteration   2: 12.551 ops/ms
# Warmup Iteration   3: 12.876 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 13.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.008 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (12.912, 13.008, 13.145), stdev = 0.122
  CI (99.9%): [10.789, 15.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.692 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.279 ±(99.9%) 4.334 ops/ms [Average]
  (min, avg, max) = (10.088, 10.279, 10.545), stdev = 0.238
  CI (99.9%): [5.945, 14.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.010 ms/op
Iteration   1: 2.478 ±(99.9%) 0.007 ms/op
Iteration   2: 2.478 ±(99.9%) 0.007 ms/op
Iteration   3: 2.487 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.478, 2.481, 2.487), stdev = 0.005
  CI (99.9%): [2.381, 2.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.007 ms/op
Iteration   1: 2.438 ±(99.9%) 0.006 ms/op
Iteration   2: 2.458 ±(99.9%) 0.008 ms/op
Iteration   3: 2.463 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.438, 2.453, 2.463), stdev = 0.013
  CI (99.9%): [2.209, 2.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.008 ms/op
Iteration   1: 2.454 ±(99.9%) 0.009 ms/op
Iteration   2: 2.461 ±(99.9%) 0.010 ms/op
Iteration   3: 2.444 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.453 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.444, 2.453, 2.461), stdev = 0.009
  CI (99.9%): [2.291, 2.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.010 ms/op
Iteration   1: 2.999 ±(99.9%) 0.010 ms/op
Iteration   2: 2.987 ±(99.9%) 0.009 ms/op
Iteration   3: 3.057 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (2.987, 3.014, 3.057), stdev = 0.038
  CI (99.9%): [2.325, 3.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.007 ms/op
Iteration   1: 2.599 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  13.091 ms/op
                 createUser·p0.9999: 16.798 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 2.633 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.357 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  9.855 ms/op
                 createUser·p0.9999: 21.819 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 2.596 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 16.298 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367556
  mean =      2.609 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174677 
    [ 2.500,  5.000) = 189034 
    [ 5.000,  7.500) = 2924 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =     11.221 ms/op
     p(99.9900) =     17.809 ms/op
     p(99.9990) =     22.304 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.007 ms/op
Iteration   1: 2.518 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.337 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  11.316 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 2.487 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 17.568 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 2.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 28.748 ms/op
                 existUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383988
  mean =      2.498 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206695 
    [ 2.500,  5.000) = 174113 
    [ 5.000,  7.500) = 2392 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     18.665 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.008 ms/op
Iteration   1: 2.569 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   2: 2.547 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.277 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.110 ms/op
                 getUser·p0.999:  12.214 ms/op
                 getUser·p0.9999: 16.473 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 2.554 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.360 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  10.792 ms/op
                 getUser·p0.9999: 14.377 ms/op
                 getUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375173
  mean =      2.557 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191580 
    [ 2.500,  5.000) = 179332 
    [ 5.000,  7.500) = 3236 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     11.384 ms/op
     p(99.9900) =     16.621 ms/op
     p(99.9990) =     18.555 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.011 ms/op
Iteration   1: 3.000 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.529 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.095 ms/op
                 listUser·p0.999:  11.407 ms/op
                 listUser·p0.9999: 14.151 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 3.071 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.341 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  11.647 ms/op
                 listUser·p0.9999: 14.775 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 3.048 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.490 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  10.813 ms/op
                 listUser·p0.9999: 15.614 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315623
  mean =      3.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109790 
    [ 2.500,  5.000) = 194194 
    [ 5.000,  7.500) = 9942 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.341 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     15.072 ms/op
     p(99.9990) =     27.350 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.849 ± 4.377  ops/ms
ClientPb.existUser                       thrpt       3  13.236 ± 6.495  ops/ms
ClientPb.getUser                         thrpt       3  13.008 ± 2.219  ops/ms
ClientPb.listUser                        thrpt       3  10.279 ± 4.334  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.100   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.244   ms/op
ClientPb.getUser                          avgt       3   2.453 ± 0.162   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.689   ms/op
ClientPb.createUser                     sample  367556   2.609 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.357           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.221           ms/op
ClientPb.createUser:createUser·p0.9999  sample          17.809           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.446           ms/op
ClientPb.existUser                      sample  383988   2.498 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.337           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          18.665           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  375173   2.557 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.384           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.621           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.644           ms/op
ClientPb.listUser                       sample  315623   3.039 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.341           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.239           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.072           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672           ms/op
