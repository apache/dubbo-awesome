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
# Warmup Iteration   1: 2.501 ops/ms
# Warmup Iteration   2: 6.236 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 9.959 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.011 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (9.924, 10.011, 10.149), stdev = 0.121
  CI (99.9%): [7.804, 12.217] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ops/ms
# Warmup Iteration   2: 9.327 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 10.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.363 ±(99.9%) 7.129 ops/ms [Average]
  (min, avg, max) = (10.016, 10.363, 10.786), stdev = 0.391
  CI (99.9%): [3.234, 17.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ops/ms
# Warmup Iteration   2: 9.033 ops/ms
# Warmup Iteration   3: 10.002 ops/ms
Iteration   1: 10.176 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 10.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.054 ±(99.9%) 3.090 ops/ms [Average]
  (min, avg, max) = (9.861, 10.054, 10.176), stdev = 0.169
  CI (99.9%): [6.964, 13.144] (assumes normal distribution)


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
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 7.953 ops/ms
# Warmup Iteration   3: 8.429 ops/ms
Iteration   1: 8.471 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.568 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (8.471, 8.568, 8.634), stdev = 0.086
  CI (99.9%): [6.995, 10.141] (assumes normal distribution)


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
# Warmup Iteration   1: 8.813 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.005 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
Iteration   3: 3.052 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.055 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.045, 3.055, 3.069), stdev = 0.012
  CI (99.9%): [2.830, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 6.895 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (2.981, 3.055, 3.136), stdev = 0.077
  CI (99.9%): [1.643, 4.466] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.272 ±(99.9%) 0.007 ms/op
Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
Iteration   3: 3.135 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.194 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (3.135, 3.194, 3.272), stdev = 0.071
  CI (99.9%): [1.904, 4.484] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.641 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.004 ms/op
Iteration   1: 3.727 ±(99.9%) 0.005 ms/op
Iteration   2: 3.655 ±(99.9%) 0.007 ms/op
Iteration   3: 3.676 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.686 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.655, 3.686, 3.727), stdev = 0.037
  CI (99.9%): [3.005, 4.366] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.399 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  11.488 ms/op
                 createUser·p0.9999: 20.900 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.160 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.234 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 22.672 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  15.235 ms/op
                 createUser·p0.9999: 19.877 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305070
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23579 
    [ 2.500,  5.000) = 277333 
    [ 5.000,  7.500) = 3439 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     17.332 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.867 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.653 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 23.146 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.165 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.922 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 21.066 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309768
  mean =      3.097 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18125 
    [ 2.500,  5.000) = 285632 
    [ 5.000,  7.500) = 5052 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 8.078 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.011 ms/op
Iteration   1: 3.199 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  16.912 ms/op
                 getUser·p0.9999: 21.628 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  15.677 ms/op
                 getUser·p0.9999: 26.371 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303590
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10833 
    [ 2.500,  5.000) = 285957 
    [ 5.000,  7.500) = 5843 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     27.586 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 9.016 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.546 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  16.137 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.675 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.055 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 18.901 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.857 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259193
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 252339 
    [ 5.000,  7.500) = 5237 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.563 ms/op
     p(99.9900) =     19.893 ms/op
     p(99.9990) =     21.038 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.011 ± 2.206  ops/ms
ClientPb.existUser                       thrpt       3  10.363 ± 7.129  ops/ms
ClientPb.getUser                         thrpt       3  10.054 ± 3.090  ops/ms
ClientPb.listUser                        thrpt       3   8.568 ± 1.573  ops/ms
ClientPb.createUser                       avgt       3   3.055 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 1.412   ms/op
ClientPb.getUser                          avgt       3   3.194 ± 1.290   ms/op
ClientPb.listUser                         avgt       3   3.686 ± 0.680   ms/op
ClientPb.createUser                     sample  305070   3.143 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.924           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.118           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.134           ms/op
ClientPb.existUser                      sample  309768   3.097 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.368           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  303590   3.161 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.993           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.778           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  259193   3.701 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.563           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.893           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
