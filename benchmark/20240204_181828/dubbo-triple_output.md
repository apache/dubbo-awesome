# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.058 ops/ms
# Warmup Iteration   2: 11.788 ops/ms
# Warmup Iteration   3: 11.961 ops/ms
Iteration   1: 12.444 ops/ms
Iteration   2: 12.434 ops/ms
Iteration   3: 12.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.452 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (12.434, 12.452, 12.478), stdev = 0.023
  CI (99.9%): [12.031, 12.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 13.197 ops/ms
# Warmup Iteration   3: 13.279 ops/ms
Iteration   1: 13.291 ops/ms
Iteration   2: 13.234 ops/ms
Iteration   3: 13.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.278 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (13.234, 13.278, 13.310), stdev = 0.039
  CI (99.9%): [12.560, 13.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.231 ops/ms
# Warmup Iteration   2: 12.558 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.808 ops/ms
Iteration   2: 12.732 ops/ms
Iteration   3: 12.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.713 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (12.600, 12.713, 12.808), stdev = 0.105
  CI (99.9%): [10.790, 14.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.850 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.842 ops/ms
Iteration   2: 10.847 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.790 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (10.680, 10.790, 10.847), stdev = 0.095
  CI (99.9%): [9.060, 12.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.233 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.003 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.540, 2.545, 2.552), stdev = 0.006
  CI (99.9%): [2.439, 2.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.415, 2.433, 2.445), stdev = 0.016
  CI (99.9%): [2.143, 2.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.467, 2.479, 2.485), stdev = 0.011
  CI (99.9%): [2.282, 2.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
Iteration   2: 2.958 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.958, 2.972, 2.980), stdev = 0.012
  CI (99.9%): [2.749, 3.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  10.932 ms/op
                 createUser·p0.9999: 13.618 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  8.972 ms/op
                 createUser·p0.9999: 13.567 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.517 ms/op
                 createUser·p0.9999: 10.191 ms/op
                 createUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382959
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 184697 
    [ 2.500,  3.750) = 194164 
    [ 3.750,  5.000) = 3346 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.571 ms/op
     p(99.9900) =     13.422 ms/op
     p(99.9990) =     14.751 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.137 ms/op
                 existUser·p0.9999: 13.599 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.360 ms/op
                 existUser·p0.9999: 12.952 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.331 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391872
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 191124 
    [ 2.500,  3.750) = 197735 
    [ 3.750,  5.000) = 2258 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      7.023 ms/op
     p(99.9900) =     13.085 ms/op
     p(99.9990) =     13.698 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  10.736 ms/op
                 getUser·p0.9999: 13.985 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 14.687 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.689 ms/op
                 getUser·p0.9999: 13.262 ms/op
                 getUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381530
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 188742 
    [ 2.500,  3.750) = 186837 
    [ 3.750,  5.000) = 4498 
    [ 5.000,  6.250) = 875 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      8.002 ms/op
     p(99.9900) =     14.120 ms/op
     p(99.9990) =     15.659 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.594 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 12.976 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   13.648 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.672 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319584
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 93750 
    [ 2.500,  3.750) = 187458 
    [ 3.750,  5.000) = 31315 
    [ 5.000,  6.250) = 5544 
    [ 6.250,  7.500) = 677 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.863 ms/op
     p(99.9990) =     13.548 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.452 ± 0.421  ops/ms
ClientPb.existUser                       thrpt       3  13.278 ± 0.719  ops/ms
ClientPb.getUser                         thrpt       3  12.713 ± 1.923  ops/ms
ClientPb.listUser                        thrpt       3  10.790 ± 1.730  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.107   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.290   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.198   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.223   ms/op
ClientPb.createUser                     sample  382959   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.571           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.422           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.040           ms/op
ClientPb.existUser                      sample  391872   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.896           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.023           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.085           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.763           ms/op
ClientPb.getUser                        sample  381530   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.671           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.002           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.892           ms/op
ClientPb.listUser                       sample  319584   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.863           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
