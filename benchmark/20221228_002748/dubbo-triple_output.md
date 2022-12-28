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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 6.377 ops/ms
# Warmup Iteration   3: 8.834 ops/ms
Iteration   1: 8.839 ops/ms
Iteration   2: 9.238 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.950 ±(99.9%) 4.585 ops/ms [Average]
  (min, avg, max) = (8.774, 8.950, 9.238), stdev = 0.251
  CI (99.9%): [4.365, 13.536] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.893 ops/ms
# Warmup Iteration   3: 9.540 ops/ms
Iteration   1: 9.663 ops/ms
Iteration   2: 9.689 ops/ms
Iteration   3: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.640 ±(99.9%) 1.180 ops/ms [Average]
  (min, avg, max) = (9.566, 9.640, 9.689), stdev = 0.065
  CI (99.9%): [8.460, 10.819] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.276 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 8.950 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.167 ops/ms
Iteration   3: 9.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.301 ±(99.9%) 3.403 ops/ms [Average]
  (min, avg, max) = (9.167, 9.301, 9.514), stdev = 0.187
  CI (99.9%): [5.898, 12.703] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 7.080 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 8.302 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.241 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (8.108, 8.241, 8.313), stdev = 0.115
  CI (99.9%): [6.135, 10.348] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.856 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.012 ms/op
Iteration   1: 3.520 ±(99.9%) 0.004 ms/op
Iteration   2: 3.458 ±(99.9%) 0.006 ms/op
Iteration   3: 3.323 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.434 ±(99.9%) 1.836 ms/op [Average]
  (min, avg, max) = (3.323, 3.434, 3.520), stdev = 0.101
  CI (99.9%): [1.598, 5.270] (assumes normal distribution)


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
# Warmup Iteration   1: 9.943 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.007 ms/op
Iteration   1: 3.312 ±(99.9%) 0.006 ms/op
Iteration   2: 3.382 ±(99.9%) 0.006 ms/op
Iteration   3: 3.294 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.294, 3.329, 3.382), stdev = 0.047
  CI (99.9%): [2.477, 4.182] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.601 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.005 ms/op
Iteration   1: 3.462 ±(99.9%) 0.005 ms/op
Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
Iteration   3: 3.486 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.375, 3.441, 3.486), stdev = 0.058
  CI (99.9%): [2.379, 4.503] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.951 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.950 ±(99.9%) 0.016 ms/op
Iteration   2: 3.910 ±(99.9%) 0.013 ms/op
Iteration   3: 4.034 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.965 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.910, 3.965, 4.034), stdev = 0.063
  CI (99.9%): [2.808, 5.122] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.443 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.793 ms/op
                 createUser·p0.999:  19.658 ms/op
                 createUser·p0.9999: 22.058 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.222 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.925 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 28.037 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285058
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12136 
    [ 2.500,  5.000) = 268953 
    [ 5.000,  7.500) = 3267 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 205 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     19.724 ms/op
     p(99.9900) =     26.492 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 7.974 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  10.919 ms/op
                 existUser·p0.9999: 29.051 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   2: 3.431 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  10.058 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.236 ms/op
                 existUser·p0.999:  22.191 ms/op
                 existUser·p0.9999: 29.065 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287754
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14779 
    [ 2.500,  5.000) = 269070 
    [ 5.000,  7.500) = 3091 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     28.588 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 9.101 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
Iteration   1: 3.445 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  21.798 ms/op
                 getUser·p0.9999: 23.738 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.420 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  10.000 ms/op
                 getUser·p0.9999: 26.167 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.892 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 27.669 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279788
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5645 
    [ 2.500,  5.000) = 267228 
    [ 5.000,  7.500) = 5605 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     20.140 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 9.457 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 27.492 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.161 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.722 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 19.866 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  15.014 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238157
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 226563 
    [ 5.000,  7.500) = 9442 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.286 ms/op
     p(99.9000) =     16.562 ms/op
     p(99.9900) =     25.808 ms/op
     p(99.9990) =     27.765 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.950 ± 4.585  ops/ms
ClientPb.existUser                       thrpt       3   9.640 ± 1.180  ops/ms
ClientPb.getUser                         thrpt       3   9.301 ± 3.403  ops/ms
ClientPb.listUser                        thrpt       3   8.241 ± 2.107  ops/ms
ClientPb.createUser                       avgt       3   3.434 ± 1.836   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.853   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 1.062   ms/op
ClientPb.listUser                         avgt       3   3.965 ± 1.157   ms/op
ClientPb.createUser                     sample  285058   3.364 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.407           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.724           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  287754   3.333 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.587           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.682           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.588           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  279788   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.140           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  238157   4.027 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.198           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.286           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.562           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.808           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
