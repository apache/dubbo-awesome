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
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.535 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.182 ops/ms
Iteration   3: 9.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.172 ±(99.9%) 1.977 ops/ms [Average]
  (min, avg, max) = (9.058, 9.172, 9.274), stdev = 0.108
  CI (99.9%): [7.195, 11.149] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 9.410 ops/ms
Iteration   2: 9.639 ops/ms
Iteration   3: 9.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.548 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (9.410, 9.548, 9.639), stdev = 0.121
  CI (99.9%): [7.332, 11.764] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 8.357 ops/ms
# Warmup Iteration   3: 8.632 ops/ms
Iteration   1: 9.378 ops/ms
Iteration   2: 9.071 ops/ms
Iteration   3: 9.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.235 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (9.071, 9.235, 9.378), stdev = 0.154
  CI (99.9%): [6.421, 12.049] (assumes normal distribution)


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
# Warmup Iteration   1: 2.638 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 7.717 ops/ms
Iteration   3: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.747 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (7.717, 7.747, 7.777), stdev = 0.030
  CI (99.9%): [7.203, 8.291] (assumes normal distribution)


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.008 ms/op
Iteration   1: 3.485 ±(99.9%) 0.007 ms/op
Iteration   2: 3.491 ±(99.9%) 0.005 ms/op
Iteration   3: 3.624 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.533 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (3.485, 3.533, 3.624), stdev = 0.079
  CI (99.9%): [2.097, 4.970] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.148 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.002 ms/op
Iteration   1: 3.480 ±(99.9%) 0.004 ms/op
Iteration   2: 3.241 ±(99.9%) 0.006 ms/op
Iteration   3: 3.406 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 2.233 ms/op [Average]
  (min, avg, max) = (3.241, 3.376, 3.480), stdev = 0.122
  CI (99.9%): [1.143, 5.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.505 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.004 ms/op
Iteration   1: 3.560 ±(99.9%) 0.007 ms/op
Iteration   2: 3.432 ±(99.9%) 0.011 ms/op
Iteration   3: 3.422 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.471 ±(99.9%) 1.402 ms/op [Average]
  (min, avg, max) = (3.422, 3.471, 3.560), stdev = 0.077
  CI (99.9%): [2.069, 4.874] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.722 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.007 ms/op
Iteration   1: 4.067 ±(99.9%) 0.009 ms/op
Iteration   2: 4.062 ±(99.9%) 0.006 ms/op
Iteration   3: 4.055 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.061 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (4.055, 4.061, 4.067), stdev = 0.006
  CI (99.9%): [3.952, 4.171] (assumes normal distribution)


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
# Warmup Iteration   1: 9.293 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.012 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  23.599 ms/op
                 createUser·p0.9999: 28.528 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.556 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.968 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  26.771 ms/op
                 createUser·p0.9999: 30.081 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  19.322 ms/op
                 createUser·p0.9999: 31.385 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275432
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6915 
    [ 2.500,  5.000) = 260635 
    [ 5.000,  7.500) = 6725 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     30.734 ms/op
     p(99.9990) =     32.194 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.760 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.009 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  23.995 ms/op
                 existUser·p0.9999: 27.837 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  26.767 ms/op
                 existUser·p0.9999: 29.571 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.790 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  17.564 ms/op
                 existUser·p0.9999: 32.959 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286284
  mean =      3.351 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10961 
    [ 2.500,  5.000) = 269653 
    [ 5.000,  7.500) = 4377 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 106 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.129 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     33.166 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.576 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
Iteration   1: 3.416 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  24.040 ms/op
                 getUser·p0.9999: 27.643 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 3.563 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  26.615 ms/op
                 getUser·p0.9999: 30.312 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.831 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.243 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 30.535 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275062
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10675 
    [ 2.500,  5.000) = 257002 
    [ 5.000,  7.500) = 6341 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     17.529 ms/op
     p(99.9900) =     29.901 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 11.258 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.014 ms/op
Iteration   1: 4.067 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  25.681 ms/op
                 listUser·p0.9999: 29.327 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 22.933 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  17.262 ms/op
                 listUser·p0.9999: 23.986 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235401
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 224830 
    [ 5.000,  7.500) = 7958 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     28.800 ms/op
     p(99.9990) =     30.628 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.172 ± 1.977  ops/ms
ClientPb.existUser                       thrpt       3   9.548 ± 2.216  ops/ms
ClientPb.getUser                         thrpt       3   9.235 ± 2.814  ops/ms
ClientPb.listUser                        thrpt       3   7.747 ± 0.544  ops/ms
ClientPb.createUser                       avgt       3   3.533 ± 1.437   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 2.233   ms/op
ClientPb.getUser                          avgt       3   3.471 ± 1.402   ms/op
ClientPb.listUser                         avgt       3   4.061 ± 0.109   ms/op
ClientPb.createUser                     sample  275432   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.407           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.628           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  286284   3.351 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.129           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.325           ms/op
ClientPb.getUser                        sample  275062   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.529           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.901           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.719           ms/op
ClientPb.listUser                       sample  235401   4.075 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.800           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.097           ms/op
