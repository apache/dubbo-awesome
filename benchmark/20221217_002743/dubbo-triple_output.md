# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 5.055 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.791 ops/ms
Iteration   2: 9.119 ops/ms
Iteration   3: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.119 ±(99.9%) 5.984 ops/ms [Average]
  (min, avg, max) = (8.791, 9.119, 9.447), stdev = 0.328
  CI (99.9%): [3.136, 15.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 8.315 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.322 ops/ms
Iteration   2: 9.782 ops/ms
Iteration   3: 9.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.669 ±(99.9%) 5.592 ops/ms [Average]
  (min, avg, max) = (9.322, 9.669, 9.903), stdev = 0.307
  CI (99.9%): [4.077, 15.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.848 ops/ms
# Warmup Iteration   2: 8.012 ops/ms
# Warmup Iteration   3: 8.832 ops/ms
Iteration   1: 9.047 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.196 ±(99.9%) 2.631 ops/ms [Average]
  (min, avg, max) = (9.047, 9.196, 9.335), stdev = 0.144
  CI (99.9%): [6.565, 11.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.636 ops/ms
# Warmup Iteration   2: 6.508 ops/ms
# Warmup Iteration   3: 7.575 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 7.744 ops/ms
Iteration   3: 7.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.893 ±(99.9%) 3.075 ops/ms [Average]
  (min, avg, max) = (7.744, 7.893, 8.076), stdev = 0.169
  CI (99.9%): [4.818, 10.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.479 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.007 ms/op
Iteration   1: 3.343 ±(99.9%) 0.013 ms/op
Iteration   2: 3.517 ±(99.9%) 0.009 ms/op
Iteration   3: 3.452 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.343, 3.437, 3.517), stdev = 0.088
  CI (99.9%): [1.827, 5.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.699 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.006 ms/op
Iteration   1: 3.260 ±(99.9%) 0.004 ms/op
Iteration   2: 3.359 ±(99.9%) 0.005 ms/op
Iteration   3: 3.412 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.343 ±(99.9%) 1.405 ms/op [Average]
  (min, avg, max) = (3.260, 3.343, 3.412), stdev = 0.077
  CI (99.9%): [1.938, 4.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.948 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.005 ms/op
Iteration   1: 3.489 ±(99.9%) 0.009 ms/op
Iteration   2: 3.529 ±(99.9%) 0.009 ms/op
Iteration   3: 3.474 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.497 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (3.474, 3.497, 3.529), stdev = 0.028
  CI (99.9%): [2.979, 4.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.284 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
Iteration   1: 4.095 ±(99.9%) 0.006 ms/op
Iteration   2: 3.902 ±(99.9%) 0.017 ms/op
Iteration   3: 4.101 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.033 ±(99.9%) 2.066 ms/op [Average]
  (min, avg, max) = (3.902, 4.033, 4.101), stdev = 0.113
  CI (99.9%): [1.967, 6.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.675 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  20.853 ms/op
                 createUser·p0.9999: 22.866 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.610 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  23.016 ms/op
                 createUser·p0.9999: 25.400 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.584 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269607
  mean =      3.560 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5634 
    [ 2.500,  5.000) = 255799 
    [ 5.000,  7.500) = 6716 
    [ 7.500, 10.000) = 805 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.446 ms/op
     p(99.9000) =     19.818 ms/op
     p(99.9900) =     31.886 ms/op
     p(99.9990) =     36.412 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.409 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.012 ms/op
Iteration   1: 3.380 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  23.637 ms/op
                 existUser·p0.9999: 31.311 ms/op
                 existUser·p1.00:   32.408 ms/op

Iteration   2: 3.509 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  9.615 ms/op
                 existUser·p0.9999: 27.088 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 3.463 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.798 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   7.585 ms/op
                 existUser·p0.999:  24.438 ms/op
                 existUser·p0.9999: 32.196 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277996
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13006 
    [ 2.500,  5.000) = 258147 
    [ 5.000,  7.500) = 5346 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     33.189 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.223 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.012 ms/op
Iteration   1: 3.576 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.948 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   7.541 ms/op
                 getUser·p0.999:  22.217 ms/op
                 getUser·p0.9999: 33.886 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  23.608 ms/op
                 getUser·p0.9999: 31.613 ms/op
                 getUser·p1.00:   33.260 ms/op

Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  13.220 ms/op
                 getUser·p0.9999: 30.466 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272460
  mean =      3.520 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2160 
    [ 2.500,  5.000) = 260282 
    [ 5.000,  7.500) = 8269 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     19.810 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.124 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.015 ms/op
Iteration   1: 4.222 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  23.319 ms/op
                 listUser·p0.9999: 27.871 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  18.426 ms/op
                 listUser·p0.9999: 24.026 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.226 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234481
  mean =      4.092 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 221648 
    [ 5.000,  7.500) = 9773 
    [ 7.500, 10.000) = 2160 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     17.467 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     28.734 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.119 ± 5.984  ops/ms
ClientPb.existUser                       thrpt       3   9.669 ± 5.592  ops/ms
ClientPb.getUser                         thrpt       3   9.196 ± 2.631  ops/ms
ClientPb.listUser                        thrpt       3   7.893 ± 3.075  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 1.611   ms/op
ClientPb.existUser                        avgt       3   3.343 ± 1.405   ms/op
ClientPb.getUser                          avgt       3   3.497 ± 0.518   ms/op
ClientPb.listUser                         avgt       3   4.033 ± 2.066   ms/op
ClientPb.createUser                     sample  269607   3.560 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.446           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.818           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  277996   3.450 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.589           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  272460   3.520 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.417           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.850           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  234481   4.092 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.109           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.099           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.869           ms/op
