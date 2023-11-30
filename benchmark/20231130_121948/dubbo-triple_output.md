# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 11.812 ops/ms
# Warmup Iteration   3: 12.034 ops/ms
Iteration   1: 12.397 ops/ms
Iteration   2: 12.394 ops/ms
Iteration   3: 12.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.417 ±(99.9%) 0.680 ops/ms [Average]
  (min, avg, max) = (12.394, 12.417, 12.460), stdev = 0.037
  CI (99.9%): [11.737, 13.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.261 ops/ms
# Warmup Iteration   2: 12.852 ops/ms
# Warmup Iteration   3: 13.065 ops/ms
Iteration   1: 12.917 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 12.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.936 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (12.917, 12.936, 12.947), stdev = 0.016
  CI (99.9%): [12.637, 13.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.747 ops/ms
# Warmup Iteration   2: 12.497 ops/ms
# Warmup Iteration   3: 12.732 ops/ms
Iteration   1: 12.762 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.836 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (12.727, 12.836, 13.018), stdev = 0.159
  CI (99.9%): [9.938, 15.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.709 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.581 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.574 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (10.544, 10.574, 10.592), stdev = 0.026
  CI (99.9%): [10.100, 11.049] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (2.485, 2.532, 2.561), stdev = 0.041
  CI (99.9%): [1.792, 3.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.702 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.437, 2.441, 2.448), stdev = 0.006
  CI (99.9%): [2.336, 2.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.523, 2.528, 2.539), stdev = 0.009
  CI (99.9%): [2.356, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
Iteration   3: 3.033 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.033, 3.044, 3.059), stdev = 0.013
  CI (99.9%): [2.799, 3.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.692 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  11.096 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  10.391 ms/op
                 createUser·p0.9999: 12.049 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  9.663 ms/op
                 createUser·p0.9999: 13.605 ms/op
                 createUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377432
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 179894 
    [ 2.500,  3.750) = 192751 
    [ 3.750,  5.000) = 3492 
    [ 5.000,  6.250) = 761 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.709 ms/op
     p(99.9900) =     15.045 ms/op
     p(99.9990) =     16.981 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.536 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.747 ms/op
                 existUser·p0.999:  8.437 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.668 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  7.085 ms/op
                 existUser·p0.9999: 13.492 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387829
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190793 
    [ 2.500,  5.000) = 196288 
    [ 5.000,  7.500) = 396 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     13.934 ms/op
     p(99.9990) =     27.402 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  11.092 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  9.344 ms/op
                 getUser·p0.9999: 13.211 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  8.136 ms/op
                 getUser·p0.9999: 10.846 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379649
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 185125 
    [ 2.500,  3.750) = 188384 
    [ 3.750,  5.000) = 4845 
    [ 5.000,  6.250) = 687 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.756 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 14.115 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.483 ms/op
                 listUser·p0.9999: 11.214 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.385 ms/op
                 listUser·p0.9999: 11.632 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314959
  mean =      3.045 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 89337 
    [ 2.500,  3.750) = 182823 
    [ 3.750,  5.000) = 34278 
    [ 5.000,  6.250) = 6792 
    [ 6.250,  7.500) = 908 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.887 ms/op
     p(99.9990) =     15.071 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.417 ± 0.680  ops/ms
ClientPb.existUser                       thrpt       3  12.936 ± 0.299  ops/ms
ClientPb.getUser                         thrpt       3  12.836 ± 2.898  ops/ms
ClientPb.listUser                        thrpt       3  10.574 ± 0.475  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.739   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.106   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.246   ms/op
ClientPb.createUser                     sample  377432   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.833           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.039           ms/op
ClientPb.existUser                      sample  387829   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.832           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.934           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  379649   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.200           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.943           ms/op
ClientPb.listUser                       sample  314959   3.045 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.887           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.925           ms/op
