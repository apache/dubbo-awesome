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
# Warmup Iteration   1: 1.360 ops/ms
# Warmup Iteration   2: 3.107 ops/ms
# Warmup Iteration   3: 6.373 ops/ms
Iteration   1: 6.627 ops/ms
Iteration   2: 7.276 ops/ms
Iteration   3: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.053 ±(99.9%) 6.737 ops/ms [Average]
  (min, avg, max) = (6.627, 7.053, 7.276), stdev = 0.369
  CI (99.9%): [0.316, 13.790] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 6.168 ops/ms
# Warmup Iteration   3: 7.522 ops/ms
Iteration   1: 7.895 ops/ms
Iteration   2: 7.821 ops/ms
Iteration   3: 7.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.694 ±(99.9%) 5.215 ops/ms [Average]
  (min, avg, max) = (7.367, 7.694, 7.895), stdev = 0.286
  CI (99.9%): [2.479, 12.910] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 5.673 ops/ms
# Warmup Iteration   3: 7.420 ops/ms
Iteration   1: 7.295 ops/ms
Iteration   2: 7.355 ops/ms
Iteration   3: 7.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.412 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (7.295, 7.412, 7.586), stdev = 0.153
  CI (99.9%): [4.613, 10.211] (assumes normal distribution)


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
# Warmup Iteration   1: 1.880 ops/ms
# Warmup Iteration   2: 4.792 ops/ms
# Warmup Iteration   3: 6.441 ops/ms
Iteration   1: 6.131 ops/ms
Iteration   2: 6.553 ops/ms
Iteration   3: 6.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.302 ±(99.9%) 4.058 ops/ms [Average]
  (min, avg, max) = (6.131, 6.302, 6.553), stdev = 0.222
  CI (99.9%): [2.244, 10.360] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.443 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.008 ms/op
Iteration   1: 4.407 ±(99.9%) 0.008 ms/op
Iteration   2: 4.365 ±(99.9%) 0.006 ms/op
Iteration   3: 4.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.377 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (4.359, 4.377, 4.407), stdev = 0.026
  CI (99.9%): [3.905, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 13.501 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.758 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.003 ms/op
Iteration   1: 4.087 ±(99.9%) 0.007 ms/op
Iteration   2: 4.288 ±(99.9%) 0.002 ms/op
Iteration   3: 4.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.148 ±(99.9%) 2.211 ms/op [Average]
  (min, avg, max) = (4.069, 4.148, 4.288), stdev = 0.121
  CI (99.9%): [1.937, 6.359] (assumes normal distribution)


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
# Warmup Iteration   1: 12.788 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.008 ms/op
Iteration   1: 4.457 ±(99.9%) 0.005 ms/op
Iteration   2: 4.185 ±(99.9%) 0.006 ms/op
Iteration   3: 4.042 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.228 ±(99.9%) 3.851 ms/op [Average]
  (min, avg, max) = (4.042, 4.228, 4.457), stdev = 0.211
  CI (99.9%): [0.377, 8.079] (assumes normal distribution)


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
# Warmup Iteration   1: 15.901 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.007 ms/op
Iteration   1: 4.880 ±(99.9%) 0.007 ms/op
Iteration   2: 5.057 ±(99.9%) 0.009 ms/op
Iteration   3: 4.943 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.960 ±(99.9%) 1.642 ms/op [Average]
  (min, avg, max) = (4.880, 4.960, 5.057), stdev = 0.090
  CI (99.9%): [3.318, 6.602] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.722 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.179 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.022 ms/op
Iteration   1: 4.479 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  17.885 ms/op
                 createUser·p0.9999: 28.667 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 4.249 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  25.093 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 4.349 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   8.266 ms/op
                 createUser·p0.999:  22.462 ms/op
                 createUser·p0.9999: 36.346 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 220216
  mean =      4.357 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 332 
    [ 2.500,  5.000) = 186423 
    [ 5.000,  7.500) = 28851 
    [ 7.500, 10.000) = 3731 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     37.853 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 14.405 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.014 ms/op
Iteration   1: 4.351 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   8.978 ms/op
                 existUser·p0.999:  16.318 ms/op
                 existUser·p0.9999: 28.923 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   2: 4.109 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  25.828 ms/op
                 existUser·p0.9999: 27.998 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.347 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  12.351 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 231294
  mean =      4.145 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 204076 
    [ 5.000,  7.500) = 22910 
    [ 7.500, 10.000) = 3268 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     32.858 ms/op
     p(99.9990) =     36.528 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 14.370 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.433 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.458 ±(99.9%) 0.018 ms/op
Iteration   1: 4.538 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.927 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  14.086 ms/op
                 getUser·p0.9999: 24.247 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 4.439 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 29.064 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   3: 4.319 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  12.353 ms/op
                 getUser·p0.9999: 34.773 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 216625
  mean =      4.430 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 180589 
    [ 5.000,  7.500) = 29884 
    [ 7.500, 10.000) = 5027 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     17.674 ms/op
     p(99.9900) =     33.205 ms/op
     p(99.9990) =     35.138 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 16.998 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.245 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.188 ±(99.9%) 0.020 ms/op
Iteration   1: 5.141 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  23.159 ms/op
                 listUser·p0.9999: 27.019 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   2: 5.129 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  21.910 ms/op
                 listUser·p0.9999: 30.912 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   3: 5.041 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 188114
  mean =      5.103 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 119560 
    [ 5.000,  7.500) = 60066 
    [ 7.500, 10.000) = 6775 
    [10.000, 12.500) = 1131 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     28.711 ms/op
     p(99.9990) =     31.495 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.053 ± 6.737  ops/ms
ClientPb.existUser                       thrpt       3   7.694 ± 5.215  ops/ms
ClientPb.getUser                         thrpt       3   7.412 ± 2.799  ops/ms
ClientPb.listUser                        thrpt       3   6.302 ± 4.058  ops/ms
ClientPb.createUser                       avgt       3   4.377 ± 0.472   ms/op
ClientPb.existUser                        avgt       3   4.148 ± 2.211   ms/op
ClientPb.getUser                          avgt       3   4.228 ± 3.851   ms/op
ClientPb.listUser                         avgt       3   4.960 ± 1.642   ms/op
ClientPb.createUser                     sample  220216   4.357 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.733           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.349           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.552           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  231294   4.145 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.029           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.274           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.842           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.858           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  216625   4.430 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.205           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  188114   5.103 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.193           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.249           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.711           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014           ms/op
