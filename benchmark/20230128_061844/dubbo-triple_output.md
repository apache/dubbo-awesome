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
# Warmup Iteration   1: 2.616 ops/ms
# Warmup Iteration   2: 6.236 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.808 ops/ms
Iteration   2: 10.111 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.085 ±(99.9%) 4.844 ops/ms [Average]
  (min, avg, max) = (9.808, 10.085, 10.337), stdev = 0.266
  CI (99.9%): [5.241, 14.929] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ops/ms
# Warmup Iteration   2: 9.636 ops/ms
# Warmup Iteration   3: 10.164 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.538 ±(99.9%) 3.830 ops/ms [Average]
  (min, avg, max) = (10.354, 10.538, 10.767), stdev = 0.210
  CI (99.9%): [6.708, 14.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 10.037 ops/ms
Iteration   1: 10.023 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 10.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.988 ±(99.9%) 3.275 ops/ms [Average]
  (min, avg, max) = (9.794, 9.988, 10.148), stdev = 0.179
  CI (99.9%): [6.714, 13.263] (assumes normal distribution)


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
# Warmup Iteration   1: 3.668 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.331 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.319 ±(99.9%) 0.351 ops/ms [Average]
  (min, avg, max) = (8.296, 8.319, 8.331), stdev = 0.019
  CI (99.9%): [7.967, 8.670] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.115 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.004 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
Iteration   3: 3.270 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.184, 3.214, 3.270), stdev = 0.049
  CI (99.9%): [2.329, 4.099] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.064 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.051, 3.101, 3.148), stdev = 0.049
  CI (99.9%): [2.213, 3.990] (assumes normal distribution)


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
# Warmup Iteration   1: 8.709 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.002 ms/op
Iteration   1: 3.330 ±(99.9%) 0.003 ms/op
Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
Iteration   3: 3.089 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.207 ±(99.9%) 2.197 ms/op [Average]
  (min, avg, max) = (3.089, 3.207, 3.330), stdev = 0.120
  CI (99.9%): [1.010, 5.404] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.934 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.005 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
Iteration   2: 3.817 ±(99.9%) 0.006 ms/op
Iteration   3: 3.811 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.698, 3.775, 3.817), stdev = 0.067
  CI (99.9%): [2.555, 4.996] (assumes normal distribution)


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
# Warmup Iteration   1: 7.423 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.009 ms/op
Iteration   1: 3.191 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  18.436 ms/op
                 createUser·p0.9999: 34.929 ms/op
                 createUser·p1.00:   35.324 ms/op

Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  16.219 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.502 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  13.926 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304914
  mean =      3.147 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21519 
    [ 2.500,  5.000) = 278169 
    [ 5.000,  7.500) = 4567 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     14.699 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.190 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 8.494 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  12.318 ms/op
                 existUser·p0.9999: 19.677 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   6.552 ms/op
                 existUser·p0.999:  14.418 ms/op
                 existUser·p0.9999: 21.172 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 19.549 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305482
  mean =      3.143 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23887 
    [ 2.500,  5.000) = 274780 
    [ 5.000,  7.500) = 5713 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     20.524 ms/op
     p(99.9990) =     23.187 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.807 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.010 ms/op
Iteration   1: 3.138 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  20.516 ms/op
                 getUser·p0.9999: 31.517 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 22.377 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  8.346 ms/op
                 getUser·p0.9999: 19.354 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304198
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11173 
    [ 2.500,  5.000) = 286989 
    [ 5.000,  7.500) = 5299 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     32.013 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 8.829 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
Iteration   1: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 20.351 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.932 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 17.875 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.807 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.868 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252384
  mean =      3.801 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 242031 
    [ 5.000,  7.500) = 8244 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     19.736 ms/op
     p(99.9990) =     21.218 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.085 ± 4.844  ops/ms
ClientPb.existUser                       thrpt       3  10.538 ± 3.830  ops/ms
ClientPb.getUser                         thrpt       3   9.988 ± 3.275  ops/ms
ClientPb.listUser                        thrpt       3   8.319 ± 0.351  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 0.885   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 0.889   ms/op
ClientPb.getUser                          avgt       3   3.207 ± 2.197   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 1.220   ms/op
ClientPb.createUser                     sample  304914   3.147 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.699           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  305482   3.143 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.524           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.888           ms/op
ClientPb.getUser                        sample  304198   3.153 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.474           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  252384   3.801 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.319           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.736           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.955           ms/op
