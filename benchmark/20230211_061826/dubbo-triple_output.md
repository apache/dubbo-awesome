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
# Warmup Iteration   1: 1.989 ops/ms
# Warmup Iteration   2: 5.390 ops/ms
# Warmup Iteration   3: 8.553 ops/ms
Iteration   1: 8.869 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.144 ±(99.9%) 4.478 ops/ms [Average]
  (min, avg, max) = (8.869, 9.144, 9.342), stdev = 0.245
  CI (99.9%): [4.666, 13.622] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 8.698 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 9.880 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 9.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.785 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (9.648, 9.785, 9.880), stdev = 0.122
  CI (99.9%): [7.564, 12.006] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 8.353 ops/ms
# Warmup Iteration   3: 9.082 ops/ms
Iteration   1: 9.410 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.387 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (9.294, 9.387, 9.456), stdev = 0.083
  CI (99.9%): [7.866, 10.908] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.831 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (7.686, 7.831, 7.952), stdev = 0.134
  CI (99.9%): [5.383, 10.279] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.000 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.003 ms/op
Iteration   1: 3.380 ±(99.9%) 0.007 ms/op
Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
Iteration   3: 3.293 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.329 ±(99.9%) 0.834 ms/op [Average]
  (min, avg, max) = (3.293, 3.329, 3.380), stdev = 0.046
  CI (99.9%): [2.495, 4.163] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.229 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.002 ms/op
Iteration   1: 3.353 ±(99.9%) 0.006 ms/op
Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
Iteration   3: 3.276 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.289 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (3.239, 3.289, 3.353), stdev = 0.058
  CI (99.9%): [2.234, 4.345] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.909 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.007 ms/op
Iteration   1: 3.512 ±(99.9%) 0.009 ms/op
Iteration   2: 3.464 ±(99.9%) 0.003 ms/op
Iteration   3: 3.439 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.472 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.439, 3.472, 3.512), stdev = 0.037
  CI (99.9%): [2.798, 4.146] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.775 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.012 ms/op
Iteration   1: 3.998 ±(99.9%) 0.014 ms/op
Iteration   2: 4.154 ±(99.9%) 0.006 ms/op
Iteration   3: 4.003 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.052 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (3.998, 4.052, 4.154), stdev = 0.089
  CI (99.9%): [2.430, 5.674] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.209 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.512 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.241 ms/op
                 createUser·p0.999:  21.131 ms/op
                 createUser·p0.9999: 30.504 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 3.548 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  22.413 ms/op
                 createUser·p0.9999: 25.624 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  19.181 ms/op
                 createUser·p0.9999: 27.880 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272910
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13593 
    [ 2.500,  5.000) = 251426 
    [ 5.000,  7.500) = 6584 
    [ 7.500, 10.000) = 733 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     19.830 ms/op
     p(99.9900) =     28.817 ms/op
     p(99.9990) =     30.959 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.044 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.392 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  18.743 ms/op
                 existUser·p0.9999: 22.778 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.378 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.218 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.082 ms/op
                 existUser·p0.9999: 25.314 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.415 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  23.134 ms/op
                 existUser·p0.9999: 32.539 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282799
  mean =      3.395 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13365 
    [ 2.500,  5.000) = 264035 
    [ 5.000,  7.500) = 4629 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     31.153 ms/op
     p(99.9990) =     33.419 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 9.660 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
Iteration   1: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  20.029 ms/op
                 getUser·p0.9999: 22.801 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  22.262 ms/op
                 getUser·p0.9999: 29.445 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278883
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4687 
    [ 2.500,  5.000) = 267396 
    [ 5.000,  7.500) = 5593 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     20.091 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.971 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 11.351 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.015 ms/op
Iteration   1: 4.088 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  23.003 ms/op
                 listUser·p0.9999: 31.490 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 3.947 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 4.115 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.001 ms/op
                 listUser·p0.999:  15.307 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236995
  mean =      4.049 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 225006 
    [ 5.000,  7.500) = 9781 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     29.259 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.144 ± 4.478  ops/ms
ClientPb.existUser                       thrpt       3   9.785 ± 2.221  ops/ms
ClientPb.getUser                         thrpt       3   9.387 ± 1.521  ops/ms
ClientPb.listUser                        thrpt       3   7.831 ± 2.448  ops/ms
ClientPb.createUser                       avgt       3   3.329 ± 0.834   ms/op
ClientPb.existUser                        avgt       3   3.289 ± 1.056   ms/op
ClientPb.getUser                          avgt       3   3.472 ± 0.674   ms/op
ClientPb.listUser                         avgt       3   4.052 ± 1.622   ms/op
ClientPb.createUser                     sample  272910   3.517 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.025           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.293           ms/op
ClientPb.existUser                      sample  282799   3.395 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.027           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.153           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  278883   3.440 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.091           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.410           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  236995   4.049 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.063           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.259           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
