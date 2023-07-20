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
# Warmup Iteration   1: 0.895 ops/ms
# Warmup Iteration   2: 1.995 ops/ms
# Warmup Iteration   3: 4.678 ops/ms
Iteration   1: 5.085 ops/ms
Iteration   2: 5.310 ops/ms
Iteration   3: 5.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.208 ±(99.9%) 2.076 ops/ms [Average]
  (min, avg, max) = (5.085, 5.208, 5.310), stdev = 0.114
  CI (99.9%): [3.131, 7.284] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.406 ops/ms
# Warmup Iteration   2: 4.116 ops/ms
# Warmup Iteration   3: 5.400 ops/ms
Iteration   1: 5.492 ops/ms
Iteration   2: 5.651 ops/ms
Iteration   3: 5.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.607 ±(99.9%) 1.830 ops/ms [Average]
  (min, avg, max) = (5.492, 5.607, 5.678), stdev = 0.100
  CI (99.9%): [3.777, 7.437] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.560 ops/ms
# Warmup Iteration   2: 4.086 ops/ms
# Warmup Iteration   3: 5.341 ops/ms
Iteration   1: 5.229 ops/ms
Iteration   2: 5.222 ops/ms
Iteration   3: 5.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.276 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (5.222, 5.276, 5.376), stdev = 0.087
  CI (99.9%): [3.689, 6.863] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 3.508 ops/ms
# Warmup Iteration   3: 4.533 ops/ms
Iteration   1: 4.448 ops/ms
Iteration   2: 4.435 ops/ms
Iteration   3: 4.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.489 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (4.435, 4.489, 4.585), stdev = 0.083
  CI (99.9%): [2.972, 6.007] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 21.564 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.883 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.189 ±(99.9%) 0.011 ms/op
Iteration   1: 6.324 ±(99.9%) 0.008 ms/op
Iteration   2: 6.116 ±(99.9%) 0.017 ms/op
Iteration   3: 6.012 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.151 ±(99.9%) 2.894 ms/op [Average]
  (min, avg, max) = (6.012, 6.151, 6.324), stdev = 0.159
  CI (99.9%): [3.256, 9.045] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 19.991 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.921 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.182 ±(99.9%) 0.010 ms/op
Iteration   1: 5.999 ±(99.9%) 0.011 ms/op
Iteration   2: 6.226 ±(99.9%) 0.008 ms/op
Iteration   3: 5.971 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.065 ±(99.9%) 2.552 ms/op [Average]
  (min, avg, max) = (5.971, 6.065, 6.226), stdev = 0.140
  CI (99.9%): [3.513, 8.618] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.967 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.444 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.012 ms/op
Iteration   1: 5.903 ±(99.9%) 0.009 ms/op
Iteration   2: 6.146 ±(99.9%) 0.011 ms/op
Iteration   3: 6.145 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.065 ±(99.9%) 2.551 ms/op [Average]
  (min, avg, max) = (5.903, 6.065, 6.146), stdev = 0.140
  CI (99.9%): [3.514, 8.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.777 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.749 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 7.327 ±(99.9%) 0.014 ms/op
Iteration   1: 7.169 ±(99.9%) 0.015 ms/op
Iteration   2: 6.917 ±(99.9%) 0.015 ms/op
Iteration   3: 6.800 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.962 ±(99.9%) 3.441 ms/op [Average]
  (min, avg, max) = (6.800, 6.962, 7.169), stdev = 0.189
  CI (99.9%): [3.521, 10.403] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.140 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 7.199 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.454 ±(99.9%) 0.036 ms/op
Iteration   1: 5.978 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   7.489 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   11.960 ms/op
                 createUser·p0.999:  23.924 ms/op
                 createUser·p0.9999: 34.797 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   2: 5.827 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.572 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 29.197 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 5.816 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.537 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.190 ms/op
                 createUser·p0.999:  30.209 ms/op
                 createUser·p0.9999: 34.373 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163446
  mean =      5.872 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 47638 
    [ 5.000,  7.500) = 99627 
    [ 7.500, 10.000) = 13049 
    [10.000, 12.500) = 2216 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     34.056 ms/op
     p(99.9990) =     36.689 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.105 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.445 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.672 ±(99.9%) 0.023 ms/op
Iteration   1: 5.662 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.340 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  17.532 ms/op
                 existUser·p0.9999: 25.474 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 5.408 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.548 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  23.615 ms/op
                 existUser·p0.9999: 28.904 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   3: 5.676 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   7.242 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   10.977 ms/op
                 existUser·p0.999:  25.786 ms/op
                 existUser·p0.9999: 29.134 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171935
  mean =      5.579 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 69857 
    [ 5.000,  7.500) = 89009 
    [ 7.500, 10.000) = 10624 
    [10.000, 12.500) = 1681 
    [12.500, 15.000) = 436 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     28.829 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.271 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 7.039 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.084 ±(99.9%) 0.025 ms/op
Iteration   1: 5.811 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.470 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.356 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.616 ms/op
                 getUser·p0.999:  28.573 ms/op
                 getUser·p0.9999: 32.604 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   2: 6.270 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.589 ms/op
                 getUser·p0.50:   5.800 ms/op
                 getUser·p0.90:   8.421 ms/op
                 getUser·p0.95:   9.961 ms/op
                 getUser·p0.99:   14.254 ms/op
                 getUser·p0.999:  27.886 ms/op
                 getUser·p0.9999: 32.113 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 6.148 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.720 ms/op
                 getUser·p0.50:   5.767 ms/op
                 getUser·p0.90:   7.873 ms/op
                 getUser·p0.95:   9.077 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  17.925 ms/op
                 getUser·p0.9999: 37.736 ms/op
                 getUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 157985
  mean =      6.070 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 40526 
    [ 5.000,  7.500) = 97884 
    [ 7.500, 10.000) = 14565 
    [10.000, 12.500) = 3174 
    [12.500, 15.000) = 1077 
    [15.000, 17.500) = 396 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.470 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     13.025 ms/op
     p(99.9000) =     27.624 ms/op
     p(99.9900) =     35.075 ms/op
     p(99.9990) =     37.979 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.187 ±(99.9%) 0.425 ms/op
# Warmup Iteration   2: 7.990 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 7.100 ±(99.9%) 0.030 ms/op
Iteration   1: 6.942 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   9.896 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  26.207 ms/op
                 listUser·p0.9999: 32.916 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 6.750 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.608 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  26.870 ms/op
                 listUser·p0.9999: 30.934 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   3: 7.072 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.603 ms/op
                 listUser·p0.90:   9.077 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.910 ms/op
                 listUser·p0.999:  33.481 ms/op
                 listUser·p0.9999: 37.518 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138761
  mean =      6.919 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3859 
    [ 5.000,  7.500) = 101606 
    [ 7.500, 10.000) = 26594 
    [10.000, 12.500) = 4737 
    [12.500, 15.000) = 1030 
    [15.000, 17.500) = 393 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      6.488 ms/op
     p(90.0000) =      8.831 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     13.222 ms/op
     p(99.9000) =     27.279 ms/op
     p(99.9900) =     36.643 ms/op
     p(99.9990) =     38.055 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.208 ± 2.076  ops/ms
ClientPb.existUser                       thrpt       3   5.607 ± 1.830  ops/ms
ClientPb.getUser                         thrpt       3   5.276 ± 1.587  ops/ms
ClientPb.listUser                        thrpt       3   4.489 ± 1.517  ops/ms
ClientPb.createUser                       avgt       3   6.151 ± 2.894   ms/op
ClientPb.existUser                        avgt       3   6.065 ± 2.552   ms/op
ClientPb.getUser                          avgt       3   6.065 ± 2.551   ms/op
ClientPb.listUser                         avgt       3   6.962 ± 3.441   ms/op
ClientPb.createUser                     sample  163446   5.872 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.487           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.471           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.906           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.056           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  171935   5.579 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.245           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.077           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.584           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.202           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.829           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  157985   6.070 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.159           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.025           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.624           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.075           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  138761   6.919 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.200           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.488           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.945           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.279           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.207           ms/op
