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
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.738 ops/ms
Iteration   3: 9.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.774 ±(99.9%) 2.735 ops/ms [Average]
  (min, avg, max) = (9.646, 9.774, 9.939), stdev = 0.150
  CI (99.9%): [7.039, 12.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 9.302 ops/ms
# Warmup Iteration   3: 10.166 ops/ms
Iteration   1: 10.039 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.945 ±(99.9%) 3.470 ops/ms [Average]
  (min, avg, max) = (9.726, 9.945, 10.070), stdev = 0.190
  CI (99.9%): [6.475, 13.415] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ops/ms
# Warmup Iteration   2: 9.066 ops/ms
# Warmup Iteration   3: 9.340 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.817 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (9.704, 9.817, 9.875), stdev = 0.098
  CI (99.9%): [8.036, 11.597] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.050 ops/ms
# Warmup Iteration   2: 7.679 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.603 ops/ms
Iteration   3: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (8.527, 8.561, 8.603), stdev = 0.039
  CI (99.9%): [7.853, 9.269] (assumes normal distribution)


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
# Warmup Iteration   1: 8.453 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.003 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
Iteration   2: 3.123 ±(99.9%) 0.005 ms/op
Iteration   3: 3.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.217 ±(99.9%) 2.011 ms/op [Average]
  (min, avg, max) = (3.123, 3.217, 3.339), stdev = 0.110
  CI (99.9%): [1.206, 5.228] (assumes normal distribution)


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
# Warmup Iteration   1: 6.725 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.004 ms/op
Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
Iteration   3: 3.109 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.108 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (3.105, 3.108, 3.111), stdev = 0.003
  CI (99.9%): [3.048, 3.169] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.884 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.006 ms/op
Iteration   1: 3.142 ±(99.9%) 0.002 ms/op
Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
Iteration   3: 3.155 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.136 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.111, 3.136, 3.155), stdev = 0.023
  CI (99.9%): [2.720, 3.551] (assumes normal distribution)


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
# Warmup Iteration   1: 8.403 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.007 ms/op
Iteration   1: 3.801 ±(99.9%) 0.009 ms/op
Iteration   2: 3.744 ±(99.9%) 0.008 ms/op
Iteration   3: 3.674 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.740 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.674, 3.740, 3.801), stdev = 0.064
  CI (99.9%): [2.575, 4.904] (assumes normal distribution)


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
# Warmup Iteration   1: 8.359 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.134 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  14.628 ms/op
                 createUser·p0.9999: 23.992 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 30.039 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.622 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296184
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26878 
    [ 2.500,  5.000) = 262947 
    [ 5.000,  7.500) = 5584 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     14.459 ms/op
     p(99.9900) =     29.185 ms/op
     p(99.9990) =     30.313 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 7.414 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 22.332 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.084 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  13.684 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 20.275 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311334
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29303 
    [ 2.500,  5.000) = 277034 
    [ 5.000,  7.500) = 4088 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.445 ms/op
     p(99.9900) =     22.175 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 7.617 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.012 ms/op
Iteration   1: 3.303 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  12.884 ms/op
                 getUser·p0.9999: 27.382 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.141 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  10.552 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  14.981 ms/op
                 getUser·p0.9999: 21.074 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297561
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16554 
    [ 2.500,  5.000) = 272965 
    [ 5.000,  7.500) = 6966 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.922 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.700 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.012 ms/op
Iteration   1: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.101 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.410 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.669 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   3.961 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 17.245 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.723 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 13.655 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258765
  mean =      3.710 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 75 
    [ 2.500,  3.750) = 209541 
    [ 3.750,  5.000) = 41916 
    [ 5.000,  6.250) = 2705 
    [ 6.250,  7.500) = 2603 
    [ 7.500,  8.750) = 896 
    [ 8.750, 10.000) = 324 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 232 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.774 ± 2.735  ops/ms
ClientPb.existUser                       thrpt       3   9.945 ± 3.470  ops/ms
ClientPb.getUser                         thrpt       3   9.817 ± 1.780  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 0.708  ops/ms
ClientPb.createUser                       avgt       3   3.217 ± 2.011   ms/op
ClientPb.existUser                        avgt       3   3.108 ± 0.060   ms/op
ClientPb.getUser                          avgt       3   3.136 ± 0.416   ms/op
ClientPb.listUser                         avgt       3   3.740 ± 1.164   ms/op
ClientPb.createUser                     sample  296184   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.459           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.185           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  311334   3.082 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.810           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.445           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.175           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.970           ms/op
ClientPb.getUser                        sample  297561   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.844           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.739           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  258765   3.710 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.229           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.923           ms/op
