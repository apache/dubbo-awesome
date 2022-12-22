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
# Warmup Iteration   1: 1.043 ops/ms
# Warmup Iteration   2: 2.378 ops/ms
# Warmup Iteration   3: 5.249 ops/ms
Iteration   1: 5.753 ops/ms
Iteration   2: 5.674 ops/ms
Iteration   3: 5.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.756 ±(99.9%) 1.531 ops/ms [Average]
  (min, avg, max) = (5.674, 5.756, 5.842), stdev = 0.084
  CI (99.9%): [4.226, 7.287] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.721 ops/ms
# Warmup Iteration   2: 4.252 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 5.644 ops/ms
Iteration   2: 5.790 ops/ms
Iteration   3: 5.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.727 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (5.644, 5.727, 5.790), stdev = 0.075
  CI (99.9%): [4.356, 7.098] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.477 ops/ms
# Warmup Iteration   2: 4.527 ops/ms
# Warmup Iteration   3: 5.661 ops/ms
Iteration   1: 5.562 ops/ms
Iteration   2: 5.757 ops/ms
Iteration   3: 5.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.699 ±(99.9%) 2.173 ops/ms [Average]
  (min, avg, max) = (5.562, 5.699, 5.778), stdev = 0.119
  CI (99.9%): [3.526, 7.872] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.449 ops/ms
# Warmup Iteration   2: 3.625 ops/ms
# Warmup Iteration   3: 4.886 ops/ms
Iteration   1: 4.845 ops/ms
Iteration   2: 5.074 ops/ms
Iteration   3: 4.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.913 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (4.820, 4.913, 5.074), stdev = 0.140
  CI (99.9%): [2.357, 7.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.342 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 7.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.014 ms/op
Iteration   1: 5.660 ±(99.9%) 0.013 ms/op
Iteration   2: 5.711 ±(99.9%) 0.011 ms/op
Iteration   3: 5.713 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.695 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (5.660, 5.695, 5.713), stdev = 0.030
  CI (99.9%): [5.146, 6.243] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.193 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.291 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.289 ±(99.9%) 0.011 ms/op
Iteration   1: 5.257 ±(99.9%) 0.008 ms/op
Iteration   2: 5.357 ±(99.9%) 0.010 ms/op
Iteration   3: 5.090 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.235 ±(99.9%) 2.458 ms/op [Average]
  (min, avg, max) = (5.090, 5.235, 5.357), stdev = 0.135
  CI (99.9%): [2.777, 7.693] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.789 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.443 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.010 ms/op
Iteration   1: 5.219 ±(99.9%) 0.016 ms/op
Iteration   2: 5.914 ±(99.9%) 0.010 ms/op
Iteration   3: 5.691 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.608 ±(99.9%) 6.470 ms/op [Average]
  (min, avg, max) = (5.219, 5.608, 5.914), stdev = 0.355
  CI (99.9%): [≈ 0, 12.078] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.031 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.898 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.476 ±(99.9%) 0.011 ms/op
Iteration   1: 6.354 ±(99.9%) 0.015 ms/op
Iteration   2: 6.123 ±(99.9%) 0.023 ms/op
Iteration   3: 6.241 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.239 ±(99.9%) 2.113 ms/op [Average]
  (min, avg, max) = (6.123, 6.239, 6.354), stdev = 0.116
  CI (99.9%): [4.126, 8.352] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.118 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 6.943 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.298 ±(99.9%) 0.031 ms/op
Iteration   1: 5.544 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   10.764 ms/op
                 createUser·p0.999:  24.268 ms/op
                 createUser·p0.9999: 29.506 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 5.547 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.373 ms/op
                 createUser·p0.99:   9.683 ms/op
                 createUser·p0.999:  15.991 ms/op
                 createUser·p0.9999: 27.278 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 5.204 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  27.591 ms/op
                 createUser·p0.9999: 34.359 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176866
  mean =      5.427 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 82673 
    [ 5.000,  7.500) = 83921 
    [ 7.500, 10.000) = 8301 
    [10.000, 12.500) = 1375 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.147 ms/op
     p(99.9000) =     20.235 ms/op
     p(99.9900) =     31.978 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.305 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.819 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.456 ±(99.9%) 0.022 ms/op
Iteration   1: 5.293 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.356 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 29.204 ms/op
                 existUser·p1.00:   32.965 ms/op

Iteration   2: 5.196 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 30.633 ms/op
                 existUser·p1.00:   35.062 ms/op

Iteration   3: 5.308 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.594 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  31.698 ms/op
                 existUser·p0.9999: 35.714 ms/op
                 existUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182192
  mean =      5.265 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 100372 
    [ 5.000,  7.500) = 73196 
    [ 7.500, 10.000) = 6645 
    [10.000, 12.500) = 1445 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     20.304 ms/op
     p(99.9900) =     34.589 ms/op
     p(99.9990) =     36.409 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.699 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 6.062 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.546 ±(99.9%) 0.020 ms/op
Iteration   1: 5.539 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   7.979 ms/op
                 getUser·p0.99:   11.104 ms/op
                 getUser·p0.999:  31.419 ms/op
                 getUser·p0.9999: 41.303 ms/op
                 getUser·p1.00:   41.681 ms/op

Iteration   2: 5.672 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.597 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  27.613 ms/op
                 getUser·p0.9999: 31.961 ms/op
                 getUser·p1.00:   32.670 ms/op

Iteration   3: 5.458 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.684 ms/op
                 getUser·p0.999:  27.276 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172622
  mean =      5.555 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 71344 
    [ 5.000, 10.000) = 98728 
    [10.000, 15.000) = 2107 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 145 
    [30.000, 35.000) = 77 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     28.029 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     41.633 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 20.557 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 8.002 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.626 ±(99.9%) 0.026 ms/op
Iteration   1: 6.179 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  27.597 ms/op
                 listUser·p0.9999: 30.150 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 6.469 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  29.234 ms/op
                 listUser·p0.9999: 32.278 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   3: 6.532 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.963 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  22.449 ms/op
                 listUser·p0.9999: 32.650 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150197
  mean =      6.390 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7298 
    [ 5.000,  7.500) = 124649 
    [ 7.500, 10.000) = 13963 
    [10.000, 12.500) = 3098 
    [12.500, 15.000) = 655 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 110 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.548 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     27.977 ms/op
     p(99.9900) =     32.242 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.756 ± 1.531  ops/ms
ClientPb.existUser                       thrpt       3   5.727 ± 1.371  ops/ms
ClientPb.getUser                         thrpt       3   5.699 ± 2.173  ops/ms
ClientPb.listUser                        thrpt       3   4.913 ± 2.556  ops/ms
ClientPb.createUser                       avgt       3   5.695 ± 0.549   ms/op
ClientPb.existUser                        avgt       3   5.235 ± 2.458   ms/op
ClientPb.getUser                          avgt       3   5.608 ± 6.470   ms/op
ClientPb.listUser                         avgt       3   6.239 ± 2.113   ms/op
ClientPb.createUser                     sample  176866   5.427 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.667           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.147           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.235           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.978           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  182192   5.265 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.397           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.109           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.589           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487           ms/op
ClientPb.getUser                        sample  172622   5.555 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.105           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.987           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.994           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.029           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.372           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.681           ms/op
ClientPb.listUser                       sample  150197   6.390 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.977           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.242           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.620           ms/op
