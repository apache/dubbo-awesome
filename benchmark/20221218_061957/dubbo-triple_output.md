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
# Warmup Iteration   1: 2.550 ops/ms
# Warmup Iteration   2: 6.102 ops/ms
# Warmup Iteration   3: 9.010 ops/ms
Iteration   1: 9.945 ops/ms
Iteration   2: 9.908 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.842 ±(99.9%) 2.680 ops/ms [Average]
  (min, avg, max) = (9.674, 9.842, 9.945), stdev = 0.147
  CI (99.9%): [7.162, 12.522] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.748 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.669 ±(99.9%) 2.287 ops/ms [Average]
  (min, avg, max) = (10.524, 10.669, 10.748), stdev = 0.125
  CI (99.9%): [8.382, 12.956] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ops/ms
# Warmup Iteration   2: 8.940 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 10.170 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.021 ±(99.9%) 4.548 ops/ms [Average]
  (min, avg, max) = (9.733, 10.021, 10.170), stdev = 0.249
  CI (99.9%): [5.473, 14.569] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ops/ms
# Warmup Iteration   2: 7.975 ops/ms
# Warmup Iteration   3: 8.373 ops/ms
Iteration   1: 8.510 ops/ms
Iteration   2: 8.817 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.590 ±(99.9%) 3.649 ops/ms [Average]
  (min, avg, max) = (8.442, 8.590, 8.817), stdev = 0.200
  CI (99.9%): [4.940, 12.239] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.008 ms/op
Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
Iteration   3: 3.114 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.110 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (3.089, 3.110, 3.125), stdev = 0.018
  CI (99.9%): [2.773, 3.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.104 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.004 ms/op
Iteration   1: 3.189 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (3.025, 3.113, 3.189), stdev = 0.083
  CI (99.9%): [1.604, 4.622] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.004 ms/op
Iteration   1: 3.238 ±(99.9%) 0.005 ms/op
Iteration   2: 3.194 ±(99.9%) 0.006 ms/op
Iteration   3: 3.219 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.194, 3.217, 3.238), stdev = 0.022
  CI (99.9%): [2.814, 3.619] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.428 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.006 ms/op
Iteration   1: 3.812 ±(99.9%) 0.008 ms/op
Iteration   2: 3.717 ±(99.9%) 0.008 ms/op
Iteration   3: 3.820 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.783 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.717, 3.783, 3.820), stdev = 0.057
  CI (99.9%): [2.737, 4.829] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.360 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  11.385 ms/op
                 createUser·p0.9999: 26.991 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  9.071 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.331 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  14.186 ms/op
                 createUser·p0.9999: 18.781 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299364
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19424 
    [ 2.500,  5.000) = 274714 
    [ 5.000,  7.500) = 4378 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.360 ms/op
     p(99.9000) =     14.051 ms/op
     p(99.9900) =     22.254 ms/op
     p(99.9990) =     27.690 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.025 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.770 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  14.370 ms/op
                 existUser·p0.9999: 21.240 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 20.965 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312139
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23995 
    [ 2.500,  5.000) = 283561 
    [ 5.000,  7.500) = 3928 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     21.358 ms/op
     p(99.9990) =     21.931 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.685 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   6.037 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  10.278 ms/op
                 getUser·p0.9999: 33.094 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  12.912 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299886
  mean =      3.201 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10760 
    [ 2.500,  5.000) = 282446 
    [ 5.000,  7.500) = 5687 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.285 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.430 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.011 ms/op
Iteration   1: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  15.479 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.691 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.076 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.770 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.359 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 17.369 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257397
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 250580 
    [ 5.000,  7.500) = 4953 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.054 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.920 ms/op
     p(99.9900) =     20.506 ms/op
     p(99.9990) =     21.556 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.842 ± 2.680  ops/ms
ClientPb.existUser                       thrpt       3  10.669 ± 2.287  ops/ms
ClientPb.getUser                         thrpt       3  10.021 ± 4.548  ops/ms
ClientPb.listUser                        thrpt       3   8.590 ± 3.649  ops/ms
ClientPb.createUser                       avgt       3   3.110 ± 0.336   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 1.509   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 0.402   ms/op
ClientPb.listUser                         avgt       3   3.783 ± 1.046   ms/op
ClientPb.createUser                     sample  299364   3.206 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.360           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.051           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  312139   3.070 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.034           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.358           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.741           ms/op
ClientPb.getUser                        sample  299886   3.201 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.727           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.285           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.621           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  257397   3.726 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.054           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.920           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.506           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.479           ms/op
