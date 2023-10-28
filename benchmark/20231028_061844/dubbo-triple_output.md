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
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 4.871 ops/ms
# Warmup Iteration   3: 8.743 ops/ms
Iteration   1: 9.013 ops/ms
Iteration   2: 9.006 ops/ms
Iteration   3: 9.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.012 ±(99.9%) 0.106 ops/ms [Average]
  (min, avg, max) = (9.006, 9.012, 9.017), stdev = 0.006
  CI (99.9%): [8.906, 9.118] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 8.629 ops/ms
# Warmup Iteration   3: 9.326 ops/ms
Iteration   1: 9.352 ops/ms
Iteration   2: 9.464 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.467 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (9.352, 9.467, 9.587), stdev = 0.118
  CI (99.9%): [7.322, 11.612] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 8.634 ops/ms
# Warmup Iteration   3: 8.713 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 9.015 ops/ms
Iteration   3: 9.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.052 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (8.966, 9.052, 9.176), stdev = 0.110
  CI (99.9%): [7.053, 11.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.365 ops/ms
# Warmup Iteration   2: 6.842 ops/ms
# Warmup Iteration   3: 7.424 ops/ms
Iteration   1: 7.302 ops/ms
Iteration   2: 7.479 ops/ms
Iteration   3: 7.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.446 ±(99.9%) 2.385 ops/ms [Average]
  (min, avg, max) = (7.302, 7.446, 7.557), stdev = 0.131
  CI (99.9%): [5.061, 9.831] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.557 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.005 ms/op
Iteration   1: 3.584 ±(99.9%) 0.003 ms/op
Iteration   2: 3.549 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.523 ±(99.9%) 1.409 ms/op [Average]
  (min, avg, max) = (3.436, 3.523, 3.584), stdev = 0.077
  CI (99.9%): [2.114, 4.932] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.982 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.003 ms/op
Iteration   1: 3.488 ±(99.9%) 0.002 ms/op
Iteration   2: 3.386 ±(99.9%) 0.004 ms/op
Iteration   3: 3.404 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.426 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.386, 3.426, 3.488), stdev = 0.054
  CI (99.9%): [2.434, 4.418] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.116 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.003 ms/op
Iteration   1: 3.639 ±(99.9%) 0.004 ms/op
Iteration   2: 3.445 ±(99.9%) 0.004 ms/op
Iteration   3: 3.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.509 ±(99.9%) 2.058 ms/op [Average]
  (min, avg, max) = (3.443, 3.509, 3.639), stdev = 0.113
  CI (99.9%): [1.451, 5.567] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.188 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.005 ms/op
Iteration   1: 4.284 ±(99.9%) 0.006 ms/op
Iteration   2: 4.281 ±(99.9%) 0.008 ms/op
Iteration   3: 4.349 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.305 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (4.281, 4.305, 4.349), stdev = 0.038
  CI (99.9%): [3.605, 5.004] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.900 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.010 ms/op
Iteration   1: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.341 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  22.308 ms/op
                 createUser·p0.9999: 24.903 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  24.538 ms/op
                 createUser·p0.9999: 29.127 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 3.619 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  20.173 ms/op
                 createUser·p0.9999: 28.841 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269831
  mean =      3.554 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3242 
    [ 2.500,  5.000) = 260310 
    [ 5.000,  7.500) = 4698 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     21.048 ms/op
     p(99.9900) =     28.771 ms/op
     p(99.9990) =     29.862 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.618 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  10.652 ms/op
                 existUser·p0.9999: 32.655 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  22.473 ms/op
                 existUser·p0.9999: 25.388 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.416 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  21.773 ms/op
                 existUser·p0.9999: 27.934 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278770
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6537 
    [ 2.500,  5.000) = 264785 
    [ 5.000,  7.500) = 5953 
    [ 7.500, 10.000) = 791 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     14.932 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     33.004 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.951 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.011 ms/op
Iteration   1: 3.707 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  21.812 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.343 ms/op
                 getUser·p0.999:  23.200 ms/op
                 getUser·p0.9999: 26.403 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 29.260 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269112
  mean =      3.566 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3585 
    [ 2.500,  5.000) = 256979 
    [ 5.000,  7.500) = 7395 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     21.321 ms/op
     p(99.9900) =     28.282 ms/op
     p(99.9990) =     30.701 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.897 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.313 ±(99.9%) 0.014 ms/op
Iteration   1: 4.339 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.393 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.688 ms/op
                 listUser·p0.999:  22.765 ms/op
                 listUser·p0.9999: 26.636 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.223 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  16.672 ms/op
                 listUser·p0.9999: 18.921 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.234 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.425 ms/op
                 listUser·p0.9999: 18.786 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225047
  mean =      4.265 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 214221 
    [ 5.000,  7.500) = 8458 
    [ 7.500, 10.000) = 1585 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     16.971 ms/op
     p(99.9900) =     25.755 ms/op
     p(99.9990) =     27.255 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.012 ± 0.106  ops/ms
ClientPb.existUser                       thrpt       3   9.467 ± 2.145  ops/ms
ClientPb.getUser                         thrpt       3   9.052 ± 1.999  ops/ms
ClientPb.listUser                        thrpt       3   7.446 ± 2.385  ops/ms
ClientPb.createUser                       avgt       3   3.523 ± 1.409   ms/op
ClientPb.existUser                        avgt       3   3.426 ± 0.992   ms/op
ClientPb.getUser                          avgt       3   3.509 ± 2.058   ms/op
ClientPb.listUser                         avgt       3   4.305 ± 0.699   ms/op
ClientPb.createUser                     sample  269831   3.554 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.509           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.048           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.771           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.671           ms/op
ClientPb.existUser                      sample  278770   3.441 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.384           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.932           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.063           ms/op
ClientPb.getUser                        sample  269112   3.566 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.384           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.321           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.282           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  225047   4.265 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.971           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.755           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
