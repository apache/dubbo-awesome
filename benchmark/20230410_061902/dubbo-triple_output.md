# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 3.931 ops/ms
# Warmup Iteration   3: 7.573 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.108 ±(99.9%) 4.376 ops/ms [Average]
  (min, avg, max) = (7.910, 8.108, 8.374), stdev = 0.240
  CI (99.9%): [3.732, 12.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ops/ms
# Warmup Iteration   2: 8.161 ops/ms
# Warmup Iteration   3: 9.033 ops/ms
Iteration   1: 9.016 ops/ms
Iteration   2: 9.016 ops/ms
Iteration   3: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.910 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (8.697, 8.910, 9.016), stdev = 0.184
  CI (99.9%): [5.556, 12.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.467 ops/ms
# Warmup Iteration   2: 7.269 ops/ms
# Warmup Iteration   3: 8.230 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.585 ±(99.9%) 4.062 ops/ms [Average]
  (min, avg, max) = (8.339, 8.585, 8.773), stdev = 0.223
  CI (99.9%): [4.523, 12.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.438 ops/ms
# Warmup Iteration   2: 6.519 ops/ms
# Warmup Iteration   3: 6.777 ops/ms
Iteration   1: 6.929 ops/ms
Iteration   2: 7.183 ops/ms
Iteration   3: 7.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.067 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (6.929, 7.067, 7.183), stdev = 0.128
  CI (99.9%): [4.728, 9.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.207 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.012 ms/op
Iteration   1: 3.676 ±(99.9%) 0.012 ms/op
Iteration   2: 3.447 ±(99.9%) 0.013 ms/op
Iteration   3: 3.488 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.537 ±(99.9%) 2.219 ms/op [Average]
  (min, avg, max) = (3.447, 3.537, 3.676), stdev = 0.122
  CI (99.9%): [1.318, 5.757] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.212 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.013 ms/op
Iteration   1: 3.745 ±(99.9%) 0.005 ms/op
Iteration   2: 3.517 ±(99.9%) 0.008 ms/op
Iteration   3: 3.578 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.613 ±(99.9%) 2.150 ms/op [Average]
  (min, avg, max) = (3.517, 3.613, 3.745), stdev = 0.118
  CI (99.9%): [1.463, 5.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.106 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.009 ms/op
Iteration   1: 3.695 ±(99.9%) 0.012 ms/op
Iteration   2: 3.662 ±(99.9%) 0.013 ms/op
Iteration   3: 3.721 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.693 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.662, 3.693, 3.721), stdev = 0.029
  CI (99.9%): [3.156, 4.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.096 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.016 ms/op
Iteration   1: 4.218 ±(99.9%) 0.014 ms/op
Iteration   2: 4.104 ±(99.9%) 0.015 ms/op
Iteration   3: 4.085 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.136 ±(99.9%) 1.308 ms/op [Average]
  (min, avg, max) = (4.085, 4.136, 4.218), stdev = 0.072
  CI (99.9%): [2.827, 5.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.952 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.014 ms/op
Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  21.511 ms/op
                 createUser·p0.9999: 23.906 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.465 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  21.998 ms/op
                 createUser·p0.9999: 27.538 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277534
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6542 
    [ 2.500,  5.000) = 264799 
    [ 5.000,  7.500) = 5248 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     21.282 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     28.119 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.349 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.010 ms/op
Iteration   1: 3.381 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 30.411 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.526 ms/op
                 existUser·p0.9999: 29.302 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 3.402 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.405 ms/op
                 existUser·p0.999:  25.029 ms/op
                 existUser·p0.9999: 30.736 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282735
  mean =      3.396 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9045 
    [ 2.500,  5.000) = 265075 
    [ 5.000,  7.500) = 7692 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.035 ms/op
     p(99.9000) =     10.785 ms/op
     p(99.9900) =     30.340 ms/op
     p(99.9990) =     31.813 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.338 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.013 ms/op
Iteration   1: 3.560 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  21.346 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.572 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  9.916 ms/op
                 getUser·p0.9999: 27.069 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  22.518 ms/op
                 getUser·p0.9999: 29.525 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269253
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3521 
    [ 2.500,  5.000) = 256620 
    [ 5.000,  7.500) = 7829 
    [ 7.500, 10.000) = 976 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.508 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     29.849 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.391 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.012 ms/op
Iteration   1: 4.222 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  22.060 ms/op
                 listUser·p0.9999: 25.699 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   2: 4.208 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 20.395 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.213 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  17.172 ms/op
                 listUser·p0.9999: 22.689 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227777
  mean =      4.214 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 216609 
    [ 5.000,  7.500) = 7591 
    [ 7.500, 10.000) = 2467 
    [10.000, 12.500) = 414 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     24.583 ms/op
     p(99.9990) =     26.178 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.108 ± 4.376  ops/ms
ClientPb.existUser                       thrpt       3   8.910 ± 3.353  ops/ms
ClientPb.getUser                         thrpt       3   8.585 ± 4.062  ops/ms
ClientPb.listUser                        thrpt       3   7.067 ± 2.339  ops/ms
ClientPb.createUser                       avgt       3   3.537 ± 2.219   ms/op
ClientPb.existUser                        avgt       3   3.613 ± 2.150   ms/op
ClientPb.getUser                          avgt       3   3.693 ± 0.537   ms/op
ClientPb.listUser                         avgt       3   4.136 ± 1.308   ms/op
ClientPb.createUser                     sample  277534   3.457 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.427           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.282           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.083           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  282735   3.396 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.497           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.035           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.785           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.340           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  269253   3.564 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.508           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.059           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.377           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  227777   4.214 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.354           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.662           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968           ms/op
