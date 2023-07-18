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
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.034 ops/ms
# Warmup Iteration   3: 9.172 ops/ms
Iteration   1: 9.845 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.800 ±(99.9%) 2.959 ops/ms [Average]
  (min, avg, max) = (9.620, 9.800, 9.935), stdev = 0.162
  CI (99.9%): [6.841, 12.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.692 ops/ms
# Warmup Iteration   2: 9.446 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 10.403 ops/ms
Iteration   3: 9.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.140 ±(99.9%) 4.317 ops/ms [Average]
  (min, avg, max) = (9.945, 10.140, 10.403), stdev = 0.237
  CI (99.9%): [5.823, 14.457] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ops/ms
# Warmup Iteration   2: 8.998 ops/ms
# Warmup Iteration   3: 9.790 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 10.088 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.092 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (10.053, 10.092, 10.136), stdev = 0.042
  CI (99.9%): [9.334, 10.851] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.607 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.279 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.475 ±(99.9%) 3.408 ops/ms [Average]
  (min, avg, max) = (8.279, 8.475, 8.651), stdev = 0.187
  CI (99.9%): [5.067, 11.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.003 ms/op
Iteration   1: 3.144 ±(99.9%) 0.007 ms/op
Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
Iteration   3: 3.214 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.157 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.114, 3.157, 3.214), stdev = 0.051
  CI (99.9%): [2.221, 4.093] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.005 ms/op
Iteration   1: 3.074 ±(99.9%) 0.003 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.074 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.088 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.074, 3.088, 3.117), stdev = 0.025
  CI (99.9%): [2.639, 3.537] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.220 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
Iteration   3: 3.130 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.132 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.099, 3.132, 3.169), stdev = 0.035
  CI (99.9%): [2.494, 3.771] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.586 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.007 ms/op
Iteration   1: 3.697 ±(99.9%) 0.010 ms/op
Iteration   2: 3.762 ±(99.9%) 0.006 ms/op
Iteration   3: 3.760 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.740 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.697, 3.740, 3.762), stdev = 0.037
  CI (99.9%): [3.066, 4.413] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.054 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.804 ms/op
                 createUser·p0.999:  12.124 ms/op
                 createUser·p0.9999: 22.019 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.274 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  18.978 ms/op
                 createUser·p0.9999: 27.368 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.614 ms/op
                 createUser·p0.9999: 20.586 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295806
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19958 
    [ 2.500,  5.000) = 269209 
    [ 5.000,  7.500) = 5648 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     16.816 ms/op
     p(99.9900) =     24.229 ms/op
     p(99.9990) =     27.592 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 21.056 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  10.340 ms/op
                 existUser·p0.9999: 24.970 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 23.618 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306612
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12638 
    [ 2.500,  5.000) = 288859 
    [ 5.000,  7.500) = 4292 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.163 ms/op
     p(99.9900) =     23.637 ms/op
     p(99.9990) =     25.485 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.311 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 21.191 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  9.490 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 23.898 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293318
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19601 
    [ 2.500,  5.000) = 267050 
    [ 5.000,  7.500) = 5862 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 179 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     23.091 ms/op
     p(99.9990) =     24.119 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.302 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.013 ms/op
Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 24.209 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 3.731 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 15.052 ms/op
                 listUser·p1.00:   15.548 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250309
  mean =      3.833 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 240852 
    [ 5.000,  7.500) = 7293 
    [ 7.500, 10.000) = 1441 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.005 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     14.583 ms/op
     p(99.9900) =     22.673 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.800 ± 2.959  ops/ms
ClientPb.existUser                       thrpt       3  10.140 ± 4.317  ops/ms
ClientPb.getUser                         thrpt       3  10.092 ± 0.759  ops/ms
ClientPb.listUser                        thrpt       3   8.475 ± 3.408  ops/ms
ClientPb.createUser                       avgt       3   3.157 ± 0.936   ms/op
ClientPb.existUser                        avgt       3   3.088 ± 0.449   ms/op
ClientPb.getUser                          avgt       3   3.132 ± 0.638   ms/op
ClientPb.listUser                         avgt       3   3.740 ± 0.674   ms/op
ClientPb.createUser                     sample  295806   3.249 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.816           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  306612   3.131 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.962           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.163           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.637           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.690           ms/op
ClientPb.getUser                        sample  293318   3.271 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.024           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.567           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.091           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.314           ms/op
ClientPb.listUser                       sample  250309   3.833 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.005           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.583           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
