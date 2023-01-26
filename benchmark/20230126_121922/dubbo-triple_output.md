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
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 6.362 ops/ms
# Warmup Iteration   3: 9.087 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 10.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.797 ±(99.9%) 3.839 ops/ms [Average]
  (min, avg, max) = (9.613, 9.797, 10.026), stdev = 0.210
  CI (99.9%): [5.958, 13.636] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ops/ms
# Warmup Iteration   2: 9.895 ops/ms
# Warmup Iteration   3: 10.152 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.427 ±(99.9%) 5.558 ops/ms [Average]
  (min, avg, max) = (10.098, 10.427, 10.699), stdev = 0.305
  CI (99.9%): [4.869, 15.985] (assumes normal distribution)


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
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 8.660 ops/ms
# Warmup Iteration   3: 9.419 ops/ms
Iteration   1: 9.911 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.140 ±(99.9%) 4.211 ops/ms [Average]
  (min, avg, max) = (9.911, 10.140, 10.373), stdev = 0.231
  CI (99.9%): [5.928, 14.351] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 8.021 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.558 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.466 ±(99.9%) 2.657 ops/ms [Average]
  (min, avg, max) = (8.298, 8.466, 8.558), stdev = 0.146
  CI (99.9%): [5.808, 11.123] (assumes normal distribution)


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
# Warmup Iteration   1: 8.515 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.004 ms/op
Iteration   1: 3.201 ±(99.9%) 0.006 ms/op
Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
Iteration   3: 3.235 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.180, 3.205, 3.235), stdev = 0.028
  CI (99.9%): [2.696, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 7.237 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
Iteration   3: 3.094 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (3.033, 3.101, 3.175), stdev = 0.071
  CI (99.9%): [1.797, 4.404] (assumes normal distribution)


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
# Warmup Iteration   1: 7.486 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.003 ms/op
Iteration   1: 3.212 ±(99.9%) 0.003 ms/op
Iteration   2: 3.144 ±(99.9%) 0.004 ms/op
Iteration   3: 3.255 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.203 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.144, 3.203, 3.255), stdev = 0.056
  CI (99.9%): [2.183, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 9.393 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.006 ms/op
Iteration   1: 3.898 ±(99.9%) 0.006 ms/op
Iteration   2: 3.747 ±(99.9%) 0.011 ms/op
Iteration   3: 3.621 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 2.534 ms/op [Average]
  (min, avg, max) = (3.621, 3.755, 3.898), stdev = 0.139
  CI (99.9%): [1.222, 6.289] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.949 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
Iteration   1: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  17.551 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.428 ms/op
                 createUser·p0.9999: 24.978 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287789
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11424 
    [ 2.500,  5.000) = 268867 
    [ 5.000,  7.500) = 6329 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.422 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.563 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 7.362 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  13.699 ms/op
                 existUser·p0.9999: 23.764 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  14.062 ms/op
                 existUser·p0.9999: 29.676 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304683
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20725 
    [ 2.500,  5.000) = 279482 
    [ 5.000,  7.500) = 3743 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     26.789 ms/op
     p(99.9990) =     29.981 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 8.656 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.010 ms/op
Iteration   1: 3.238 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  13.894 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  15.814 ms/op
                 getUser·p0.9999: 23.889 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300991
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7734 
    [ 2.500,  5.000) = 287563 
    [ 5.000,  7.500) = 4528 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     25.028 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.282 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.011 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.473 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.280 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.799 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252146
  mean =      3.805 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 245471 
    [ 5.000,  7.500) = 4899 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.902 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     26.207 ms/op
     p(99.9990) =     28.691 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.797 ± 3.839  ops/ms
ClientPb.existUser                       thrpt       3  10.427 ± 5.558  ops/ms
ClientPb.getUser                         thrpt       3  10.140 ± 4.211  ops/ms
ClientPb.listUser                        thrpt       3   8.466 ± 2.657  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 0.509   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 1.303   ms/op
ClientPb.getUser                          avgt       3   3.203 ± 1.020   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 2.534   ms/op
ClientPb.createUser                     sample  287789   3.335 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.422           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.592           ms/op
ClientPb.existUser                      sample  304683   3.151 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.789           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  300991   3.187 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.541           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.236           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  252146   3.805 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.661           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.902           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.458           ms/op
