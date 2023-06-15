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
# Warmup Iteration   1: 1.050 ops/ms
# Warmup Iteration   2: 2.234 ops/ms
# Warmup Iteration   3: 5.274 ops/ms
Iteration   1: 5.485 ops/ms
Iteration   2: 5.970 ops/ms
Iteration   3: 6.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.861 ±(99.9%) 6.124 ops/ms [Average]
  (min, avg, max) = (5.485, 5.861, 6.129), stdev = 0.336
  CI (99.9%): [≈ 0, 11.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.564 ops/ms
# Warmup Iteration   2: 5.028 ops/ms
# Warmup Iteration   3: 6.107 ops/ms
Iteration   1: 6.202 ops/ms
Iteration   2: 6.200 ops/ms
Iteration   3: 6.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.222 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (6.200, 6.222, 6.262), stdev = 0.035
  CI (99.9%): [5.575, 6.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.495 ops/ms
# Warmup Iteration   2: 4.572 ops/ms
# Warmup Iteration   3: 5.817 ops/ms
Iteration   1: 5.860 ops/ms
Iteration   2: 5.575 ops/ms
Iteration   3: 5.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.760 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (5.575, 5.760, 5.860), stdev = 0.161
  CI (99.9%): [2.825, 8.695] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 4.092 ops/ms
# Warmup Iteration   3: 5.008 ops/ms
Iteration   1: 4.730 ops/ms
Iteration   2: 4.910 ops/ms
Iteration   3: 4.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.866 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (4.730, 4.866, 4.956), stdev = 0.120
  CI (99.9%): [2.684, 7.047] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.582 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.632 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.979 ±(99.9%) 0.008 ms/op
Iteration   1: 5.562 ±(99.9%) 0.021 ms/op
Iteration   2: 5.687 ±(99.9%) 0.019 ms/op
Iteration   3: 5.545 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.598 ±(99.9%) 1.417 ms/op [Average]
  (min, avg, max) = (5.545, 5.598, 5.687), stdev = 0.078
  CI (99.9%): [4.181, 7.015] (assumes normal distribution)


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
# Warmup Iteration   1: 16.609 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.011 ms/op
Iteration   1: 5.233 ±(99.9%) 0.013 ms/op
Iteration   2: 5.127 ±(99.9%) 0.010 ms/op
Iteration   3: 5.102 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.154 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (5.102, 5.154, 5.233), stdev = 0.070
  CI (99.9%): [3.877, 6.430] (assumes normal distribution)


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
# Warmup Iteration   1: 17.714 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.126 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.304 ±(99.9%) 0.013 ms/op
Iteration   1: 5.310 ±(99.9%) 0.013 ms/op
Iteration   2: 5.482 ±(99.9%) 0.016 ms/op
Iteration   3: 5.379 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.390 ±(99.9%) 1.584 ms/op [Average]
  (min, avg, max) = (5.310, 5.390, 5.482), stdev = 0.087
  CI (99.9%): [3.806, 6.974] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.918 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 8.049 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.301 ±(99.9%) 0.022 ms/op
Iteration   1: 6.272 ±(99.9%) 0.015 ms/op
Iteration   2: 6.455 ±(99.9%) 0.009 ms/op
Iteration   3: 6.245 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.324 ±(99.9%) 2.091 ms/op [Average]
  (min, avg, max) = (6.245, 6.324, 6.455), stdev = 0.115
  CI (99.9%): [4.233, 8.415] (assumes normal distribution)


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
# Warmup Iteration   1: 17.389 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.769 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.985 ±(99.9%) 0.028 ms/op
Iteration   1: 5.535 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  25.820 ms/op
                 createUser·p0.9999: 30.354 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 5.309 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.521 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   9.847 ms/op
                 createUser·p0.999:  27.519 ms/op
                 createUser·p0.9999: 33.126 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 5.439 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   10.573 ms/op
                 createUser·p0.999:  28.450 ms/op
                 createUser·p0.9999: 32.805 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176725
  mean =      5.426 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 75509 
    [ 5.000,  7.500) = 92000 
    [ 7.500, 10.000) = 7273 
    [10.000, 12.500) = 1163 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.187 ms/op
     p(99.9000) =     26.354 ms/op
     p(99.9900) =     32.680 ms/op
     p(99.9990) =     34.306 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 15.769 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.400 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.553 ±(99.9%) 0.022 ms/op
Iteration   1: 5.060 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  24.799 ms/op
                 existUser·p0.9999: 28.510 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   2: 5.140 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.144 ms/op
                 existUser·p0.95:   7.133 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  29.517 ms/op
                 existUser·p0.9999: 35.717 ms/op
                 existUser·p1.00:   36.110 ms/op

Iteration   3: 5.227 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.494 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  20.316 ms/op
                 existUser·p0.9999: 31.089 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186635
  mean =      5.142 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 111703 
    [ 5.000,  7.500) = 67106 
    [ 7.500, 10.000) = 5417 
    [10.000, 12.500) = 1519 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     34.756 ms/op
     p(99.9990) =     35.997 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 17.961 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.598 ±(99.9%) 0.019 ms/op
Iteration   1: 5.322 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.267 ms/op
                 getUser·p0.95:   7.012 ms/op
                 getUser·p0.99:   9.609 ms/op
                 getUser·p0.999:  22.796 ms/op
                 getUser·p0.9999: 29.097 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   2: 5.578 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.064 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   8.126 ms/op
                 getUser·p0.99:   11.863 ms/op
                 getUser·p0.999:  29.642 ms/op
                 getUser·p0.9999: 45.925 ms/op
                 getUser·p1.00:   52.494 ms/op

Iteration   3: 5.447 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.168 ms/op
                 getUser·p0.99:   9.732 ms/op
                 getUser·p0.999:  28.803 ms/op
                 getUser·p0.9999: 37.298 ms/op
                 getUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176161
  mean =      5.447 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 68323 
    [ 5.000, 10.000) = 105486 
    [10.000, 15.000) = 1894 
    [15.000, 20.000) = 177 
    [20.000, 25.000) = 79 
    [25.000, 30.000) = 99 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 27 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     27.711 ms/op
     p(99.9900) =     42.624 ms/op
     p(99.9990) =     52.444 ms/op
     p(99.9999) =     52.494 ms/op
    p(100.0000) =     52.494 ms/op


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
# Warmup Iteration   1: 19.964 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.946 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.362 ±(99.9%) 0.025 ms/op
Iteration   1: 6.643 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   13.910 ms/op
                 listUser·p0.999:  29.164 ms/op
                 listUser·p0.9999: 35.068 ms/op
                 listUser·p1.00:   35.848 ms/op

Iteration   2: 6.148 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   11.737 ms/op
                 listUser·p0.999:  30.542 ms/op
                 listUser·p0.9999: 34.996 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   3: 6.426 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   9.173 ms/op
                 listUser·p0.99:   12.730 ms/op
                 listUser·p0.999:  25.698 ms/op
                 listUser·p0.9999: 35.391 ms/op
                 listUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149960
  mean =      6.399 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 6507 
    [ 5.000,  7.500) = 127051 
    [ 7.500, 10.000) = 12034 
    [10.000, 12.500) = 2768 
    [12.500, 15.000) = 786 
    [15.000, 17.500) = 367 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.681 ms/op
     p(99.9000) =     29.524 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.012 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.861 ± 6.124  ops/ms
ClientPb.existUser                       thrpt       3   6.222 ± 0.646  ops/ms
ClientPb.getUser                         thrpt       3   5.760 ± 2.935  ops/ms
ClientPb.listUser                        thrpt       3   4.866 ± 2.181  ops/ms
ClientPb.createUser                       avgt       3   5.598 ± 1.417   ms/op
ClientPb.existUser                        avgt       3   5.154 ± 1.276   ms/op
ClientPb.getUser                          avgt       3   5.390 ± 1.584   ms/op
ClientPb.listUser                         avgt       3   6.324 ± 2.091   ms/op
ClientPb.createUser                     sample  176725   5.426 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.769           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.187           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.680           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  186635   5.142 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.316           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.756           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.110           ms/op
ClientPb.getUser                        sample  176161   5.447 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.064           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.397           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.624           ms/op
ClientPb.getUser:getUser·p1.00          sample          52.494           ms/op
ClientPb.listUser                       sample  149960   6.399 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.396           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.681           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.524           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.996           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.176           ms/op
