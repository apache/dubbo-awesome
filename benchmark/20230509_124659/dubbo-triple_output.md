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
# Warmup Iteration   1: 1.024 ops/ms
# Warmup Iteration   2: 2.235 ops/ms
# Warmup Iteration   3: 4.846 ops/ms
Iteration   1: 5.045 ops/ms
Iteration   2: 5.371 ops/ms
Iteration   3: 5.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.265 ±(99.9%) 3.478 ops/ms [Average]
  (min, avg, max) = (5.045, 5.265, 5.379), stdev = 0.191
  CI (99.9%): [1.787, 8.743] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.421 ops/ms
# Warmup Iteration   2: 4.214 ops/ms
# Warmup Iteration   3: 5.424 ops/ms
Iteration   1: 5.699 ops/ms
Iteration   2: 5.537 ops/ms
Iteration   3: 5.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.672 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (5.537, 5.672, 5.779), stdev = 0.123
  CI (99.9%): [3.429, 7.915] (assumes normal distribution)


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
# Warmup Iteration   1: 1.544 ops/ms
# Warmup Iteration   2: 4.335 ops/ms
# Warmup Iteration   3: 5.356 ops/ms
Iteration   1: 5.364 ops/ms
Iteration   2: 5.577 ops/ms
Iteration   3: 5.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.405 ±(99.9%) 2.832 ops/ms [Average]
  (min, avg, max) = (5.275, 5.405, 5.577), stdev = 0.155
  CI (99.9%): [2.573, 8.237] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.393 ops/ms
# Warmup Iteration   2: 3.399 ops/ms
# Warmup Iteration   3: 4.376 ops/ms
Iteration   1: 4.500 ops/ms
Iteration   2: 4.874 ops/ms
Iteration   3: 4.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.692 ±(99.9%) 3.410 ops/ms [Average]
  (min, avg, max) = (4.500, 4.692, 4.874), stdev = 0.187
  CI (99.9%): [1.281, 8.102] (assumes normal distribution)


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
# Warmup Iteration   1: 18.644 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.031 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.135 ±(99.9%) 0.013 ms/op
Iteration   1: 5.856 ±(99.9%) 0.013 ms/op
Iteration   2: 5.929 ±(99.9%) 0.010 ms/op
Iteration   3: 5.824 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.869 ±(99.9%) 0.981 ms/op [Average]
  (min, avg, max) = (5.824, 5.869, 5.929), stdev = 0.054
  CI (99.9%): [4.889, 6.850] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.160 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.215 ±(99.9%) 0.008 ms/op
Iteration   1: 5.914 ±(99.9%) 0.011 ms/op
Iteration   2: 5.938 ±(99.9%) 0.007 ms/op
Iteration   3: 5.644 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.832 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (5.644, 5.832, 5.938), stdev = 0.163
  CI (99.9%): [2.854, 8.810] (assumes normal distribution)


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
# Warmup Iteration   1: 18.347 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.161 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.093 ±(99.9%) 0.008 ms/op
Iteration   1: 6.120 ±(99.9%) 0.013 ms/op
Iteration   2: 6.062 ±(99.9%) 0.009 ms/op
Iteration   3: 6.010 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.064 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (6.010, 6.064, 6.120), stdev = 0.055
  CI (99.9%): [5.058, 7.070] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.747 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 8.313 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.746 ±(99.9%) 0.013 ms/op
Iteration   1: 6.880 ±(99.9%) 0.012 ms/op
Iteration   2: 6.815 ±(99.9%) 0.013 ms/op
Iteration   3: 6.834 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.843 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (6.815, 6.843, 6.880), stdev = 0.033
  CI (99.9%): [6.235, 7.451] (assumes normal distribution)


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
# Warmup Iteration   1: 18.629 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 7.554 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.535 ±(99.9%) 0.035 ms/op
Iteration   1: 5.917 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.134 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.815 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  18.677 ms/op
                 createUser·p0.9999: 32.440 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   2: 5.954 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.766 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  27.011 ms/op
                 createUser·p0.9999: 31.942 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 6.009 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.253 ms/op
                 createUser·p0.50:   5.685 ms/op
                 createUser·p0.90:   7.717 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  29.378 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160942
  mean =      5.960 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 45189 
    [ 5.000,  7.500) = 96350 
    [ 7.500, 10.000) = 15869 
    [10.000, 12.500) = 2522 
    [12.500, 15.000) = 572 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 90 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.380 ms/op
     p(99.9000) =     27.003 ms/op
     p(99.9900) =     32.044 ms/op
     p(99.9990) =     33.491 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 16.784 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.907 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.987 ±(99.9%) 0.026 ms/op
Iteration   1: 5.670 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.307 ms/op
                 existUser·p0.99:   10.961 ms/op
                 existUser·p0.999:  24.353 ms/op
                 existUser·p0.9999: 27.331 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   2: 5.811 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.695 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.537 ms/op
                 existUser·p0.95:   8.684 ms/op
                 existUser·p0.99:   12.386 ms/op
                 existUser·p0.999:  31.261 ms/op
                 existUser·p0.9999: 36.667 ms/op
                 existUser·p1.00:   37.093 ms/op

Iteration   3: 6.056 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   5.538 ms/op
                 existUser·p0.90:   8.102 ms/op
                 existUser·p0.95:   9.486 ms/op
                 existUser·p0.99:   13.647 ms/op
                 existUser·p0.999:  21.535 ms/op
                 existUser·p0.9999: 42.187 ms/op
                 existUser·p1.00:   42.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164264
  mean =      5.841 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 55124 
    [ 5.000, 10.000) = 104616 
    [10.000, 15.000) = 3910 
    [15.000, 20.000) = 420 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     23.239 ms/op
     p(99.9900) =     39.518 ms/op
     p(99.9990) =     42.949 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


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
# Warmup Iteration   1: 17.990 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 7.302 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.061 ±(99.9%) 0.026 ms/op
Iteration   1: 6.184 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   5.759 ms/op
                 getUser·p0.90:   8.389 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   13.140 ms/op
                 getUser·p0.999:  22.439 ms/op
                 getUser·p0.9999: 31.317 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   2: 5.997 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   9.142 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  28.344 ms/op
                 getUser·p0.9999: 32.233 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   3: 6.199 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   8.798 ms/op
                 getUser·p0.95:   10.085 ms/op
                 getUser·p0.99:   13.418 ms/op
                 getUser·p0.999:  20.283 ms/op
                 getUser·p0.9999: 30.600 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 156664
  mean =      6.125 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 45582 
    [ 5.000,  7.500) = 85791 
    [ 7.500, 10.000) = 19330 
    [10.000, 12.500) = 4000 
    [12.500, 15.000) = 1168 
    [15.000, 17.500) = 376 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      8.421 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     13.074 ms/op
     p(99.9000) =     23.397 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     33.625 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 19.732 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.851 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.294 ±(99.9%) 0.034 ms/op
Iteration   1: 7.073 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   13.550 ms/op
                 listUser·p0.999:  30.310 ms/op
                 listUser·p0.9999: 33.177 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   2: 7.225 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   6.717 ms/op
                 listUser·p0.90:   9.454 ms/op
                 listUser·p0.95:   10.748 ms/op
                 listUser·p0.99:   14.533 ms/op
                 listUser·p0.999:  31.688 ms/op
                 listUser·p0.9999: 34.153 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   3: 6.843 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  30.755 ms/op
                 listUser·p0.9999: 34.755 ms/op
                 listUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136421
  mean =      7.043 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 3940 
    [ 5.000,  7.500) = 95745 
    [ 7.500, 10.000) = 28357 
    [10.000, 12.500) = 6037 
    [12.500, 15.000) = 1478 
    [15.000, 17.500) = 398 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 101 
    [32.500, 35.000) = 72 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      6.595 ms/op
     p(90.0000) =      9.110 ms/op
     p(95.0000) =     10.355 ms/op
     p(99.0000) =     13.795 ms/op
     p(99.9000) =     30.919 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     35.407 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.265 ± 3.478  ops/ms
ClientPb.existUser                       thrpt       3   5.672 ± 2.243  ops/ms
ClientPb.getUser                         thrpt       3   5.405 ± 2.832  ops/ms
ClientPb.listUser                        thrpt       3   4.692 ± 3.410  ops/ms
ClientPb.createUser                       avgt       3   5.869 ± 0.981   ms/op
ClientPb.existUser                        avgt       3   5.832 ± 2.978   ms/op
ClientPb.getUser                          avgt       3   6.064 ± 1.006   ms/op
ClientPb.listUser                         avgt       3   6.843 ± 0.608   ms/op
ClientPb.createUser                     sample  160942   5.960 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.766           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.651           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.380           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.003           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.044           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  164264   5.841 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.782           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.518           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.992           ms/op
ClientPb.getUser                        sample  156664   6.125 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.552           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.074           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.397           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  136421   7.043 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.595           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.795           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.919           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.455           ms/op
