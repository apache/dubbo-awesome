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
# Warmup Iteration   1: 2.485 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 9.432 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.738 ±(99.9%) 5.067 ops/ms [Average]
  (min, avg, max) = (9.557, 9.738, 10.057), stdev = 0.278
  CI (99.9%): [4.671, 14.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 9.740 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.200 ops/ms
Iteration   3: 10.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.262 ±(99.9%) 2.915 ops/ms [Average]
  (min, avg, max) = (10.143, 10.262, 10.443), stdev = 0.160
  CI (99.9%): [7.347, 13.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 9.851 ops/ms
Iteration   1: 9.480 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.957 ±(99.9%) 7.729 ops/ms [Average]
  (min, avg, max) = (9.480, 9.957, 10.291), stdev = 0.424
  CI (99.9%): [2.227, 17.686] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.534 ops/ms
Iteration   3: 8.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 3.660 ops/ms [Average]
  (min, avg, max) = (8.188, 8.420, 8.537), stdev = 0.201
  CI (99.9%): [4.760, 12.080] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.003 ms/op
Iteration   1: 3.225 ±(99.9%) 0.007 ms/op
Iteration   2: 3.163 ±(99.9%) 0.011 ms/op
Iteration   3: 3.118 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.169 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.118, 3.169, 3.225), stdev = 0.053
  CI (99.9%): [2.193, 4.145] (assumes normal distribution)


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
# Warmup Iteration   1: 6.688 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.004 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.067 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.040, 3.067, 3.108), stdev = 0.036
  CI (99.9%): [2.411, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 8.764 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.003 ms/op
Iteration   1: 3.279 ±(99.9%) 0.007 ms/op
Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
Iteration   3: 3.248 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.153, 3.227, 3.279), stdev = 0.065
  CI (99.9%): [2.033, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 9.479 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.006 ms/op
Iteration   1: 3.894 ±(99.9%) 0.004 ms/op
Iteration   2: 3.749 ±(99.9%) 0.008 ms/op
Iteration   3: 3.727 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.790 ±(99.9%) 1.652 ms/op [Average]
  (min, avg, max) = (3.727, 3.790, 3.894), stdev = 0.091
  CI (99.9%): [2.138, 5.441] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
Iteration   1: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  16.537 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 22.495 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  16.024 ms/op
                 createUser·p0.9999: 23.388 ms/op
                 createUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302223
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24771 
    [ 2.500,  5.000) = 271173 
    [ 5.000,  7.500) = 5478 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.242 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 6.823 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
Iteration   1: 3.189 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  12.283 ms/op
                 existUser·p0.9999: 20.741 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  12.681 ms/op
                 existUser·p0.9999: 23.163 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.259 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303381
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26804 
    [ 2.500,  5.000) = 271490 
    [ 5.000,  7.500) = 4283 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     12.642 ms/op
     p(99.9900) =     22.697 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 8.534 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.011 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  9.452 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  19.674 ms/op
                 getUser·p0.9999: 21.888 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  9.943 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303032
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7054 
    [ 2.500,  5.000) = 289329 
    [ 5.000,  7.500) = 5730 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.444 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 8.637 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.011 ms/op
Iteration   1: 3.717 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 23.082 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.257 ms/op
                 listUser·p0.9999: 15.816 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   3: 3.740 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.683 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 17.185 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253285
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 245183 
    [ 5.000,  7.500) = 6025 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.112 ms/op
     p(99.9000) =     14.446 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.738 ± 5.067  ops/ms
ClientPb.existUser                       thrpt       3  10.262 ± 2.915  ops/ms
ClientPb.getUser                         thrpt       3   9.957 ± 7.729  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 3.660  ops/ms
ClientPb.createUser                       avgt       3   3.169 ± 0.976   ms/op
ClientPb.existUser                        avgt       3   3.067 ± 0.655   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 1.194   ms/op
ClientPb.listUser                         avgt       3   3.790 ± 1.652   ms/op
ClientPb.createUser                     sample  302223   3.176 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.988           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.773           ms/op
ClientPb.existUser                      sample  303381   3.165 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.642           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.697           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  303032   3.168 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.702           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.303           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.496           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.036           ms/op
ClientPb.listUser                       sample  253285   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.040           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.112           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.446           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.366           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
