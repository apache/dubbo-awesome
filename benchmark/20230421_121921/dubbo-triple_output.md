# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 8.803 ops/ms
Iteration   2: 9.175 ops/ms
Iteration   3: 8.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.763 ±(99.9%) 7.919 ops/ms [Average]
  (min, avg, max) = (8.310, 8.763, 9.175), stdev = 0.434
  CI (99.9%): [0.843, 16.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 8.443 ops/ms
# Warmup Iteration   3: 9.387 ops/ms
Iteration   1: 9.265 ops/ms
Iteration   2: 9.445 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.361 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (9.265, 9.361, 9.445), stdev = 0.091
  CI (99.9%): [7.708, 11.015] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 8.429 ops/ms
Iteration   2: 9.263 ops/ms
Iteration   3: 8.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.869 ±(99.9%) 7.635 ops/ms [Average]
  (min, avg, max) = (8.429, 8.869, 9.263), stdev = 0.419
  CI (99.9%): [1.234, 16.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.697 ops/ms
# Warmup Iteration   2: 7.144 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.744 ops/ms
Iteration   3: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.920 ±(99.9%) 4.137 ops/ms [Average]
  (min, avg, max) = (7.744, 7.920, 8.176), stdev = 0.227
  CI (99.9%): [3.783, 12.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.154 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.006 ms/op
Iteration   1: 3.520 ±(99.9%) 0.006 ms/op
Iteration   2: 3.454 ±(99.9%) 0.003 ms/op
Iteration   3: 3.396 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.457 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.396, 3.457, 3.520), stdev = 0.062
  CI (99.9%): [2.326, 4.588] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.439 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.005 ms/op
Iteration   1: 3.306 ±(99.9%) 0.007 ms/op
Iteration   2: 3.301 ±(99.9%) 0.005 ms/op
Iteration   3: 3.303 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (3.301, 3.304, 3.306), stdev = 0.002
  CI (99.9%): [3.264, 3.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.004 ms/op
Iteration   1: 3.468 ±(99.9%) 0.006 ms/op
Iteration   2: 3.417 ±(99.9%) 0.005 ms/op
Iteration   3: 3.407 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.407, 3.431, 3.468), stdev = 0.033
  CI (99.9%): [2.832, 4.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.854 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
Iteration   1: 4.191 ±(99.9%) 0.006 ms/op
Iteration   2: 3.970 ±(99.9%) 0.015 ms/op
Iteration   3: 4.051 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.071 ±(99.9%) 2.037 ms/op [Average]
  (min, avg, max) = (3.970, 4.071, 4.191), stdev = 0.112
  CI (99.9%): [2.033, 6.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.521 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.014 ms/op
Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.861 ms/op
                 createUser·p0.999:  21.334 ms/op
                 createUser·p0.9999: 25.654 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.569 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  22.426 ms/op
                 createUser·p0.9999: 24.774 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 27.303 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274584
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10362 
    [ 2.500,  5.000) = 256804 
    [ 5.000,  7.500) = 6398 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     26.527 ms/op
     p(99.9990) =     27.714 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.977 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
Iteration   1: 3.298 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.426 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 20.805 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.338 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.868 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  22.010 ms/op
                 existUser·p0.9999: 26.359 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.774 ms/op
                 existUser·p0.999:  22.148 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284326
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9709 
    [ 2.500,  5.000) = 268988 
    [ 5.000,  7.500) = 4536 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.037 ms/op
     p(99.9900) =     26.284 ms/op
     p(99.9990) =     27.306 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.077 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.010 ms/op
Iteration   1: 3.626 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  15.862 ms/op
                 getUser·p0.9999: 21.468 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.527 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  21.143 ms/op
                 getUser·p0.9999: 25.777 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 29.972 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271653
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8796 
    [ 2.500,  5.000) = 253786 
    [ 5.000,  7.500) = 7043 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     16.078 ms/op
     p(99.9900) =     28.601 ms/op
     p(99.9990) =     30.549 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.815 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.014 ms/op
Iteration   1: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  20.437 ms/op
                 listUser·p0.9999: 24.988 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   2: 4.151 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  15.961 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234152
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 226636 
    [ 5.000,  7.500) = 4891 
    [ 7.500, 10.000) = 1512 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     23.173 ms/op
     p(99.9990) =     26.847 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.763 ± 7.919  ops/ms
ClientPb.existUser                       thrpt       3   9.361 ± 1.653  ops/ms
ClientPb.getUser                         thrpt       3   8.869 ± 7.635  ops/ms
ClientPb.listUser                        thrpt       3   7.920 ± 4.137  ops/ms
ClientPb.createUser                       avgt       3   3.457 ± 1.131   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 0.040   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 0.599   ms/op
ClientPb.listUser                         avgt       3   4.071 ± 2.037   ms/op
ClientPb.createUser                     sample  274584   3.496 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.048           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.594           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.527           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  284326   3.375 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.454           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.037           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.284           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  271653   3.535 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.300           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.078           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  234152   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.489           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.173           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.460           ms/op
