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
# Warmup Iteration   1: 2.613 ops/ms
# Warmup Iteration   2: 5.642 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.962 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 10.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.992 ±(99.9%) 4.568 ops/ms [Average]
  (min, avg, max) = (9.758, 9.992, 10.256), stdev = 0.250
  CI (99.9%): [5.424, 14.559] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.516 ops/ms
# Warmup Iteration   2: 9.399 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.500 ±(99.9%) 6.148 ops/ms [Average]
  (min, avg, max) = (10.114, 10.500, 10.731), stdev = 0.337
  CI (99.9%): [4.353, 16.648] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ops/ms
# Warmup Iteration   2: 9.217 ops/ms
# Warmup Iteration   3: 9.720 ops/ms
Iteration   1: 10.381 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.198 ±(99.9%) 2.984 ops/ms [Average]
  (min, avg, max) = (10.067, 10.198, 10.381), stdev = 0.164
  CI (99.9%): [7.214, 13.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.260 ops/ms
# Warmup Iteration   2: 8.213 ops/ms
# Warmup Iteration   3: 8.237 ops/ms
Iteration   1: 8.664 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.666 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (8.601, 8.666, 8.732), stdev = 0.065
  CI (99.9%): [7.475, 9.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
Iteration   3: 3.132 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.118 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.106, 3.118, 3.132), stdev = 0.013
  CI (99.9%): [2.878, 3.357] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.979 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.004 ms/op
Iteration   1: 3.227 ±(99.9%) 0.004 ms/op
Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
Iteration   3: 3.073 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (3.071, 3.123, 3.227), stdev = 0.089
  CI (99.9%): [1.491, 4.756] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.321 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.005 ms/op
Iteration   1: 3.261 ±(99.9%) 0.005 ms/op
Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.156 ±(99.9%) 1.824 ms/op [Average]
  (min, avg, max) = (3.062, 3.156, 3.261), stdev = 0.100
  CI (99.9%): [1.332, 4.979] (assumes normal distribution)


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
# Warmup Iteration   1: 8.204 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.722 ±(99.9%) 0.008 ms/op
Iteration   2: 3.711 ±(99.9%) 0.006 ms/op
Iteration   3: 3.725 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.711, 3.719, 3.725), stdev = 0.008
  CI (99.9%): [3.581, 3.858] (assumes normal distribution)


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
# Warmup Iteration   1: 8.355 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  18.293 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.353 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.074 ms/op
                 createUser·p0.999:  21.866 ms/op
                 createUser·p0.9999: 24.327 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.757 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 20.459 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287720
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18887 
    [ 2.500,  5.000) = 261454 
    [ 5.000,  7.500) = 6272 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     23.961 ms/op
     p(99.9990) =     24.817 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 9.335 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.216 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  10.626 ms/op
                 existUser·p0.9999: 25.299 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.064 ms/op
                 existUser·p0.999:  13.699 ms/op
                 existUser·p0.9999: 25.858 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.125 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  12.132 ms/op
                 existUser·p0.9999: 23.323 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298655
  mean =      3.214 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24896 
    [ 2.500,  5.000) = 267381 
    [ 5.000,  7.500) = 5593 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.737 ms/op
     p(99.9900) =     24.917 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 8.986 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.530 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  20.245 ms/op
                 getUser·p0.9999: 24.902 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  20.393 ms/op
                 getUser·p0.9999: 23.821 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  17.807 ms/op
                 getUser·p0.9999: 27.009 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273593
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7841 
    [ 2.500,  5.000) = 256505 
    [ 5.000,  7.500) = 7964 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     18.311 ms/op
     p(99.9900) =     25.535 ms/op
     p(99.9990) =     27.477 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 11.908 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.013 ms/op
Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.781 ms/op
                 listUser·p0.9999: 22.302 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 4.233 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.536 ms/op
                 listUser·p0.999:  16.259 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.991 ms/op
                 listUser·p0.999:  14.590 ms/op
                 listUser·p0.9999: 17.978 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238229
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 226752 
    [ 5.000,  7.500) = 8773 
    [ 7.500, 10.000) = 1941 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     23.646 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.992 ± 4.568  ops/ms
ClientPb.existUser                       thrpt       3  10.500 ± 6.148  ops/ms
ClientPb.getUser                         thrpt       3  10.198 ± 2.984  ops/ms
ClientPb.listUser                        thrpt       3   8.666 ± 1.191  ops/ms
ClientPb.createUser                       avgt       3   3.118 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 1.633   ms/op
ClientPb.getUser                          avgt       3   3.156 ± 1.824   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.139   ms/op
ClientPb.createUser                     sample  287720   3.334 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.382           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.961           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  298655   3.214 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.958           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  273593   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.311           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.535           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  238229   4.029 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.386           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.529           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
