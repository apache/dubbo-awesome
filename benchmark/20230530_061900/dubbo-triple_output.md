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
# Warmup Iteration   1: 1.288 ops/ms
# Warmup Iteration   2: 3.411 ops/ms
# Warmup Iteration   3: 5.775 ops/ms
Iteration   1: 5.555 ops/ms
Iteration   2: 5.854 ops/ms
Iteration   3: 5.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.725 ±(99.9%) 2.808 ops/ms [Average]
  (min, avg, max) = (5.555, 5.725, 5.854), stdev = 0.154
  CI (99.9%): [2.917, 8.534] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.830 ops/ms
# Warmup Iteration   2: 5.592 ops/ms
# Warmup Iteration   3: 5.949 ops/ms
Iteration   1: 6.250 ops/ms
Iteration   2: 5.999 ops/ms
Iteration   3: 6.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.146 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (5.999, 6.146, 6.250), stdev = 0.131
  CI (99.9%): [3.754, 8.538] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.798 ops/ms
# Warmup Iteration   2: 5.251 ops/ms
# Warmup Iteration   3: 5.973 ops/ms
Iteration   1: 5.368 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 5.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.673 ±(99.9%) 4.833 ops/ms [Average]
  (min, avg, max) = (5.368, 5.673, 5.828), stdev = 0.265
  CI (99.9%): [0.840, 10.506] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 4.180 ops/ms
# Warmup Iteration   3: 4.755 ops/ms
Iteration   1: 5.013 ops/ms
Iteration   2: 5.109 ops/ms
Iteration   3: 5.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.074 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (5.013, 5.074, 5.109), stdev = 0.053
  CI (99.9%): [4.103, 6.046] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 17.128 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.389 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.135 ±(99.9%) 0.007 ms/op
Iteration   1: 5.748 ±(99.9%) 0.011 ms/op
Iteration   2: 5.664 ±(99.9%) 0.009 ms/op
Iteration   3: 5.178 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.530 ±(99.9%) 5.614 ms/op [Average]
  (min, avg, max) = (5.178, 5.530, 5.748), stdev = 0.308
  CI (99.9%): [≈ 0, 11.144] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.381 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.807 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.264 ±(99.9%) 0.008 ms/op
Iteration   1: 5.530 ±(99.9%) 0.013 ms/op
Iteration   2: 5.182 ±(99.9%) 0.009 ms/op
Iteration   3: 5.430 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.381 ±(99.9%) 3.277 ms/op [Average]
  (min, avg, max) = (5.182, 5.381, 5.530), stdev = 0.180
  CI (99.9%): [2.104, 8.658] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.666 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.645 ±(99.9%) 0.015 ms/op
Iteration   1: 5.802 ±(99.9%) 0.006 ms/op
Iteration   2: 5.397 ±(99.9%) 0.017 ms/op
Iteration   3: 5.303 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.501 ±(99.9%) 4.839 ms/op [Average]
  (min, avg, max) = (5.303, 5.501, 5.802), stdev = 0.265
  CI (99.9%): [0.662, 10.339] (assumes normal distribution)


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
# Warmup Iteration   1: 19.040 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 7.275 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.645 ±(99.9%) 0.012 ms/op
Iteration   1: 6.588 ±(99.9%) 0.010 ms/op
Iteration   2: 6.398 ±(99.9%) 0.010 ms/op
Iteration   3: 6.215 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.400 ±(99.9%) 3.397 ms/op [Average]
  (min, avg, max) = (6.215, 6.400, 6.588), stdev = 0.186
  CI (99.9%): [3.003, 9.797] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.497 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.602 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.968 ±(99.9%) 0.025 ms/op
Iteration   1: 5.554 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 28.647 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   2: 5.412 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.787 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   9.980 ms/op
                 createUser·p0.999:  29.161 ms/op
                 createUser·p0.9999: 35.002 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   3: 5.644 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.266 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  24.457 ms/op
                 createUser·p0.9999: 35.499 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173375
  mean =      5.535 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 63969 
    [ 5.000,  7.500) = 98273 
    [ 7.500, 10.000) = 9334 
    [10.000, 12.500) = 1239 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     24.158 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.198 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.309 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.559 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.715 ±(99.9%) 0.022 ms/op
Iteration   1: 5.291 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   10.335 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 39.311 ms/op
                 existUser·p1.00:   40.829 ms/op

Iteration   2: 5.294 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.470 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   8.847 ms/op
                 existUser·p0.999:  23.767 ms/op
                 existUser·p0.9999: 27.327 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 5.333 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.971 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  28.572 ms/op
                 existUser·p0.9999: 34.800 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180851
  mean =      5.306 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 83724 
    [ 5.000, 10.000) = 95666 
    [10.000, 15.000) = 1168 
    [15.000, 20.000) = 102 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 58 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 32 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     21.664 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     40.299 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.618 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.944 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.773 ±(99.9%) 0.021 ms/op
Iteration   1: 5.688 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.111 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  23.772 ms/op
                 getUser·p0.9999: 28.488 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   2: 5.511 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   7.815 ms/op
                 getUser·p0.99:   10.437 ms/op
                 getUser·p0.999:  26.000 ms/op
                 getUser·p0.9999: 32.158 ms/op
                 getUser·p1.00:   32.866 ms/op

Iteration   3: 5.576 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   5.288 ms/op
                 getUser·p0.90:   7.102 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  26.334 ms/op
                 getUser·p0.9999: 30.656 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171635
  mean =      5.591 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 63103 
    [ 5.000,  7.500) = 97087 
    [ 7.500, 10.000) = 9024 
    [10.000, 12.500) = 1775 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.028 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     24.680 ms/op
     p(99.9900) =     31.179 ms/op
     p(99.9990) =     32.843 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 18.482 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.145 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.312 ±(99.9%) 0.023 ms/op
Iteration   1: 6.127 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.994 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.799 ms/op
                 listUser·p0.999:  28.148 ms/op
                 listUser·p0.9999: 35.047 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   2: 6.478 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  29.062 ms/op
                 listUser·p0.9999: 32.377 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   3: 6.510 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   12.191 ms/op
                 listUser·p0.999:  25.167 ms/op
                 listUser·p0.9999: 28.120 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150720
  mean =      6.367 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 21267 
    [ 5.000,  7.500) = 106929 
    [ 7.500, 10.000) = 18856 
    [10.000, 12.500) = 2492 
    [12.500, 15.000) = 595 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      7.938 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     11.809 ms/op
     p(99.9000) =     27.329 ms/op
     p(99.9900) =     32.716 ms/op
     p(99.9990) =     35.388 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.725 ± 2.808  ops/ms
ClientPb.existUser                       thrpt       3   6.146 ± 2.392  ops/ms
ClientPb.getUser                         thrpt       3   5.673 ± 4.833  ops/ms
ClientPb.listUser                        thrpt       3   5.074 ± 0.971  ops/ms
ClientPb.createUser                       avgt       3   5.530 ± 5.614   ms/op
ClientPb.existUser                        avgt       3   5.381 ± 3.277   ms/op
ClientPb.getUser                          avgt       3   5.501 ± 4.839   ms/op
ClientPb.listUser                         avgt       3   6.400 ± 3.397   ms/op
ClientPb.createUser                     sample  173375   5.535 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.011           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.158           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  180851   5.306 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.601           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.470           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.829           ms/op
ClientPb.getUser                        sample  171635   5.591 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.028           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.680           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.179           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.866           ms/op
ClientPb.listUser                       sample  150720   6.367 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.809           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.329           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.716           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.455           ms/op
