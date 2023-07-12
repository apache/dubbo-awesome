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
# Warmup Iteration   1: 1.881 ops/ms
# Warmup Iteration   2: 4.591 ops/ms
# Warmup Iteration   3: 7.546 ops/ms
Iteration   1: 8.551 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.499 ±(99.9%) 5.033 ops/ms [Average]
  (min, avg, max) = (8.201, 8.499, 8.745), stdev = 0.276
  CI (99.9%): [3.466, 13.532] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.586 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 8.575 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.727 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (8.515, 8.727, 8.922), stdev = 0.204
  CI (99.9%): [5.003, 12.451] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.596 ops/ms
Iteration   2: 8.966 ops/ms
Iteration   3: 8.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.750 ±(99.9%) 3.516 ops/ms [Average]
  (min, avg, max) = (8.596, 8.750, 8.966), stdev = 0.193
  CI (99.9%): [5.234, 12.266] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 5.551 ops/ms
# Warmup Iteration   3: 6.904 ops/ms
Iteration   1: 7.313 ops/ms
Iteration   2: 7.410 ops/ms
Iteration   3: 7.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.340 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (7.299, 7.340, 7.410), stdev = 0.060
  CI (99.9%): [6.238, 8.442] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.031 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.004 ms/op
Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
Iteration   2: 3.855 ±(99.9%) 0.012 ms/op
Iteration   3: 3.595 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.748 ±(99.9%) 2.477 ms/op [Average]
  (min, avg, max) = (3.595, 3.748, 3.855), stdev = 0.136
  CI (99.9%): [1.271, 6.224] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.504 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.007 ms/op
Iteration   1: 3.765 ±(99.9%) 0.007 ms/op
Iteration   2: 3.488 ±(99.9%) 0.008 ms/op
Iteration   3: 3.501 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.585 ±(99.9%) 2.849 ms/op [Average]
  (min, avg, max) = (3.488, 3.585, 3.765), stdev = 0.156
  CI (99.9%): [0.736, 6.434] (assumes normal distribution)


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
# Warmup Iteration   1: 10.594 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.005 ms/op
Iteration   1: 3.802 ±(99.9%) 0.008 ms/op
Iteration   2: 3.830 ±(99.9%) 0.003 ms/op
Iteration   3: 3.724 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.785 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.724, 3.785, 3.830), stdev = 0.055
  CI (99.9%): [2.777, 4.794] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.823 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.613 ±(99.9%) 0.007 ms/op
Iteration   1: 4.618 ±(99.9%) 0.009 ms/op
Iteration   2: 4.541 ±(99.9%) 0.012 ms/op
Iteration   3: 4.227 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.462 ±(99.9%) 3.776 ms/op [Average]
  (min, avg, max) = (4.227, 4.462, 4.618), stdev = 0.207
  CI (99.9%): [0.686, 8.238] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.840 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.013 ms/op
Iteration   1: 3.767 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  12.945 ms/op
                 createUser·p0.9999: 23.479 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.773 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   5.053 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  25.952 ms/op
                 createUser·p0.9999: 29.509 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.762 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  24.150 ms/op
                 createUser·p0.9999: 42.238 ms/op
                 createUser·p1.00:   44.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254784
  mean =      3.767 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 245089 
    [ 5.000, 10.000) = 9222 
    [10.000, 15.000) = 212 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 89 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     39.159 ms/op
     p(99.9990) =     44.106 ms/op
     p(99.9999) =     44.237 ms/op
    p(100.0000) =     44.237 ms/op


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
# Warmup Iteration   1: 9.172 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.012 ms/op
Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  10.693 ms/op
                 existUser·p0.9999: 24.423 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.792 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   6.918 ms/op
                 existUser·p0.999:  25.995 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 3.570 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257252
  mean =      3.730 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2914 
    [ 2.500,  5.000) = 243923 
    [ 5.000,  7.500) = 9065 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     32.271 ms/op
     p(99.9990) =     34.359 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 10.745 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.017 ms/op
Iteration   1: 3.821 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  9.720 ms/op
                 getUser·p0.9999: 21.910 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 5.588 ±(99.9%) 0.165 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   81.658 ms/op
                 getUser·p0.999:  138.598 ms/op
                 getUser·p0.9999: 182.616 ms/op
                 getUser·p1.00:   187.171 ms/op

Iteration   3: 5.921 ±(99.9%) 0.169 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   81.847 ms/op
                 getUser·p0.999:  136.577 ms/op
                 getUser·p0.9999: 160.017 ms/op
                 getUser·p1.00:   171.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 194981
  mean =      4.921 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 191891 
    [ 12.500,  25.000) = 491 
    [ 25.000,  37.500) = 333 
    [ 37.500,  50.000) = 323 
    [ 50.000,  62.500) = 307 
    [ 62.500,  75.000) = 360 
    [ 75.000,  87.500) = 377 
    [ 87.500, 100.000) = 322 
    [100.000, 112.500) = 224 
    [112.500, 125.000) = 165 
    [125.000, 137.500) = 79 
    [137.500, 150.000) = 72 
    [150.000, 162.500) = 18 
    [162.500, 175.000) = 11 
    [175.000, 187.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =     49.527 ms/op
     p(99.9000) =    124.387 ms/op
     p(99.9900) =    164.240 ms/op
     p(99.9990) =    186.673 ms/op
     p(99.9999) =    187.171 ms/op
    p(100.0000) =    187.171 ms/op


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
# Warmup Iteration   1: 18.175 ±(99.9%) 0.748 ms/op
# Warmup Iteration   2: 9.092 ±(99.9%) 0.296 ms/op
# Warmup Iteration   3: 5.182 ±(99.9%) 0.085 ms/op
Iteration   1: 4.669 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  22.217 ms/op
                 listUser·p0.9999: 57.278 ms/op
                 listUser·p1.00:   57.410 ms/op

Iteration   2: 4.392 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   9.039 ms/op
                 listUser·p0.999:  25.498 ms/op
                 listUser·p0.9999: 30.474 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 4.375 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 23.976 ms/op
                 listUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214396
  mean =      4.475 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 189921 
    [ 5.000, 10.000) = 23358 
    [10.000, 15.000) = 606 
    [15.000, 20.000) = 222 
    [20.000, 25.000) = 167 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     21.719 ms/op
     p(99.9900) =     51.338 ms/op
     p(99.9990) =     57.410 ms/op
     p(99.9999) =     57.410 ms/op
    p(100.0000) =     57.410 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3    8.499 ± 5.033  ops/ms
ClientPb.existUser                       thrpt       3    8.727 ± 3.724  ops/ms
ClientPb.getUser                         thrpt       3    8.750 ± 3.516  ops/ms
ClientPb.listUser                        thrpt       3    7.340 ± 1.102  ops/ms
ClientPb.createUser                       avgt       3    3.748 ± 2.477   ms/op
ClientPb.existUser                        avgt       3    3.585 ± 2.849   ms/op
ClientPb.getUser                          avgt       3    3.785 ± 1.008   ms/op
ClientPb.listUser                         avgt       3    4.462 ± 3.776   ms/op
ClientPb.createUser                     sample  254784    3.767 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample            1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample            3.666           ms/op
ClientPb.createUser:createUser·p0.90    sample            4.366           ms/op
ClientPb.createUser:createUser·p0.95    sample            4.776           ms/op
ClientPb.createUser:createUser·p0.99    sample            6.439           ms/op
ClientPb.createUser:createUser·p0.999   sample           21.692           ms/op
ClientPb.createUser:createUser·p0.9999  sample           39.159           ms/op
ClientPb.createUser:createUser·p1.00    sample           44.237           ms/op
ClientPb.existUser                      sample  257252    3.730 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample            1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample            3.650           ms/op
ClientPb.existUser:existUser·p0.90      sample            4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample            4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample            6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample           12.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample           32.271           ms/op
ClientPb.existUser:existUser·p1.00      sample           34.603           ms/op
ClientPb.getUser                        sample  194981    4.921 ± 0.068   ms/op
ClientPb.getUser:getUser·p0.00          sample            1.257           ms/op
ClientPb.getUser:getUser·p0.50          sample            3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample            4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample            5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           49.527           ms/op
ClientPb.getUser:getUser·p0.999         sample          124.387           ms/op
ClientPb.getUser:getUser·p0.9999        sample          164.240           ms/op
ClientPb.getUser:getUser·p1.00          sample          187.171           ms/op
ClientPb.listUser                       sample  214396    4.475 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample            1.636           ms/op
ClientPb.listUser:listUser·p0.50        sample            4.301           ms/op
ClientPb.listUser:listUser·p0.90        sample            5.095           ms/op
ClientPb.listUser:listUser·p0.95        sample            5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample            8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample           21.719           ms/op
ClientPb.listUser:listUser·p0.9999      sample           51.338           ms/op
ClientPb.listUser:listUser·p1.00        sample           57.410           ms/op
