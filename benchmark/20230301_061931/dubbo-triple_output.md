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
# Warmup Iteration   1: 1.085 ops/ms
# Warmup Iteration   2: 2.028 ops/ms
# Warmup Iteration   3: 5.179 ops/ms
Iteration   1: 5.559 ops/ms
Iteration   2: 5.706 ops/ms
Iteration   3: 5.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.714 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (5.559, 5.714, 5.878), stdev = 0.159
  CI (99.9%): [2.808, 8.620] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.746 ops/ms
# Warmup Iteration   2: 4.562 ops/ms
# Warmup Iteration   3: 5.929 ops/ms
Iteration   1: 5.989 ops/ms
Iteration   2: 6.035 ops/ms
Iteration   3: 6.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.037 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (5.989, 6.037, 6.087), stdev = 0.049
  CI (99.9%): [5.147, 6.926] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 4.255 ops/ms
# Warmup Iteration   3: 5.713 ops/ms
Iteration   1: 6.013 ops/ms
Iteration   2: 5.871 ops/ms
Iteration   3: 5.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.923 ±(99.9%) 1.433 ops/ms [Average]
  (min, avg, max) = (5.871, 5.923, 6.013), stdev = 0.079
  CI (99.9%): [4.490, 7.356] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.420 ops/ms
# Warmup Iteration   2: 4.158 ops/ms
# Warmup Iteration   3: 5.134 ops/ms
Iteration   1: 4.984 ops/ms
Iteration   2: 5.137 ops/ms
Iteration   3: 5.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.058 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (4.984, 5.058, 5.137), stdev = 0.076
  CI (99.9%): [3.667, 6.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.600 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 7.008 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.799 ±(99.9%) 0.022 ms/op
Iteration   1: 5.711 ±(99.9%) 0.010 ms/op
Iteration   2: 5.510 ±(99.9%) 0.014 ms/op
Iteration   3: 5.483 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.568 ±(99.9%) 2.277 ms/op [Average]
  (min, avg, max) = (5.483, 5.568, 5.711), stdev = 0.125
  CI (99.9%): [3.291, 7.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.659 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.144 ±(99.9%) 0.010 ms/op
Iteration   1: 5.122 ±(99.9%) 0.016 ms/op
Iteration   2: 5.249 ±(99.9%) 0.007 ms/op
Iteration   3: 5.070 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.147 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (5.070, 5.147, 5.249), stdev = 0.092
  CI (99.9%): [3.467, 6.826] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.553 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.451 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.009 ms/op
Iteration   1: 5.287 ±(99.9%) 0.012 ms/op
Iteration   2: 5.282 ±(99.9%) 0.010 ms/op
Iteration   3: 5.307 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.292 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (5.282, 5.292, 5.307), stdev = 0.013
  CI (99.9%): [5.055, 5.529] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.258 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 8.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.349 ±(99.9%) 0.015 ms/op
Iteration   1: 6.369 ±(99.9%) 0.012 ms/op
Iteration   2: 6.597 ±(99.9%) 0.014 ms/op
Iteration   3: 6.415 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.460 ±(99.9%) 2.202 ms/op [Average]
  (min, avg, max) = (6.369, 6.460, 6.597), stdev = 0.121
  CI (99.9%): [4.258, 8.663] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.095 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 6.959 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.110 ±(99.9%) 0.032 ms/op
Iteration   1: 5.627 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   8.323 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  27.398 ms/op
                 createUser·p0.9999: 31.969 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   2: 5.658 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   8.012 ms/op
                 createUser·p0.99:   11.960 ms/op
                 createUser·p0.999:  26.329 ms/op
                 createUser·p0.9999: 29.083 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 5.367 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.966 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  27.448 ms/op
                 createUser·p0.9999: 36.375 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172938
  mean =      5.548 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 64572 
    [ 5.000,  7.500) = 97107 
    [ 7.500, 10.000) = 8838 
    [10.000, 12.500) = 1541 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.946 ms/op
     p(99.0000) =     10.692 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     34.125 ms/op
     p(99.9990) =     36.605 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.957 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 5.927 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.632 ±(99.9%) 0.024 ms/op
Iteration   1: 5.210 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.406 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  21.909 ms/op
                 existUser·p0.9999: 24.446 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 5.365 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.286 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   11.502 ms/op
                 existUser·p0.999:  20.395 ms/op
                 existUser·p0.9999: 25.502 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 5.214 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.447 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  31.421 ms/op
                 existUser·p0.9999: 35.774 ms/op
                 existUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182336
  mean =      5.262 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 101256 
    [ 5.000,  7.500) = 71919 
    [ 7.500, 10.000) = 6652 
    [10.000, 12.500) = 1538 
    [12.500, 15.000) = 554 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     21.845 ms/op
     p(99.9900) =     35.016 ms/op
     p(99.9990) =     36.319 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.486 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 7.161 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.659 ±(99.9%) 0.025 ms/op
Iteration   1: 5.664 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.157 ms/op
                 getUser·p0.999:  16.138 ms/op
                 getUser·p0.9999: 27.373 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 5.633 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   12.419 ms/op
                 getUser·p0.999:  26.201 ms/op
                 getUser·p0.9999: 41.964 ms/op
                 getUser·p1.00:   42.402 ms/op

Iteration   3: 5.720 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   12.272 ms/op
                 getUser·p0.999:  27.591 ms/op
                 getUser·p0.9999: 42.718 ms/op
                 getUser·p1.00:   46.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169111
  mean =      5.672 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60725 
    [ 5.000, 10.000) = 104319 
    [10.000, 15.000) = 3465 
    [15.000, 20.000) = 432 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     20.167 ms/op
     p(99.9900) =     41.943 ms/op
     p(99.9990) =     45.413 ms/op
     p(99.9999) =     46.137 ms/op
    p(100.0000) =     46.137 ms/op


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
# Warmup Iteration   1: 22.144 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.163 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.869 ±(99.9%) 0.032 ms/op
Iteration   1: 6.485 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   6.087 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  33.504 ms/op
                 listUser·p0.9999: 37.356 ms/op
                 listUser·p1.00:   40.960 ms/op

Iteration   2: 6.113 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  28.793 ms/op
                 listUser·p0.9999: 31.787 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 6.375 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.737 ms/op
                 listUser·p0.999:  22.725 ms/op
                 listUser·p0.9999: 30.985 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151865
  mean =      6.321 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6911 
    [ 5.000, 10.000) = 140799 
    [10.000, 15.000) = 3469 
    [15.000, 20.000) = 332 
    [20.000, 25.000) = 100 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 103 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     29.692 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     39.260 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.714 ± 2.906  ops/ms
ClientPb.existUser                       thrpt       3   6.037 ± 0.890  ops/ms
ClientPb.getUser                         thrpt       3   5.923 ± 1.433  ops/ms
ClientPb.listUser                        thrpt       3   5.058 ± 1.391  ops/ms
ClientPb.createUser                       avgt       3   5.568 ± 2.277   ms/op
ClientPb.existUser                        avgt       3   5.147 ± 1.680   ms/op
ClientPb.getUser                          avgt       3   5.292 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   6.460 ± 2.202   ms/op
ClientPb.createUser                     sample  172938   5.548 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.946           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.692           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.608           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.125           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  182336   5.262 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.277           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.584           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.016           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.372           ms/op
ClientPb.getUser                        sample  169111   5.672 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.470           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.184           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.239           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.137           ms/op
ClientPb.listUser                       sample  151865   6.321 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.062           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.372           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.960           ms/op
