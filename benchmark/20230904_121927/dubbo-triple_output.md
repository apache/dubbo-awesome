# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.414 ops/ms
# Warmup Iteration   2: 6.378 ops/ms
# Warmup Iteration   3: 9.079 ops/ms
Iteration   1: 9.614 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 10.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.917 ±(99.9%) 5.638 ops/ms [Average]
  (min, avg, max) = (9.614, 9.917, 10.232), stdev = 0.309
  CI (99.9%): [4.278, 15.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ops/ms
# Warmup Iteration   2: 9.107 ops/ms
# Warmup Iteration   3: 10.154 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.261 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (10.229, 10.261, 10.305), stdev = 0.039
  CI (99.9%): [9.547, 10.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
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
# Warmup Iteration   2: 8.819 ops/ms
# Warmup Iteration   3: 9.531 ops/ms
Iteration   1: 9.841 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.894 ±(99.9%) 5.240 ops/ms [Average]
  (min, avg, max) = (9.637, 9.894, 10.204), stdev = 0.287
  CI (99.9%): [4.655, 15.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.067 ops/ms
# Warmup Iteration   2: 7.310 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.609 ops/ms
Iteration   3: 8.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.563 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (8.537, 8.563, 8.609), stdev = 0.040
  CI (99.9%): [7.827, 9.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.003 ms/op
Iteration   1: 3.346 ±(99.9%) 0.005 ms/op
Iteration   2: 3.391 ±(99.9%) 0.004 ms/op
Iteration   3: 3.273 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.337 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.273, 3.337, 3.391), stdev = 0.060
  CI (99.9%): [2.248, 4.425] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.227 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.005 ms/op
Iteration   1: 3.114 ±(99.9%) 0.004 ms/op
Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
Iteration   3: 3.105 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.146 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.105, 3.146, 3.218), stdev = 0.063
  CI (99.9%): [2.000, 4.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.933 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.004 ms/op
Iteration   1: 3.239 ±(99.9%) 0.005 ms/op
Iteration   2: 3.200 ±(99.9%) 0.006 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.189 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.128, 3.189, 3.239), stdev = 0.056
  CI (99.9%): [2.164, 4.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.305 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.004 ms/op
Iteration   1: 3.803 ±(99.9%) 0.007 ms/op
Iteration   2: 3.742 ±(99.9%) 0.004 ms/op
Iteration   3: 3.900 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.815 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (3.742, 3.815, 3.900), stdev = 0.080
  CI (99.9%): [2.356, 5.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.987 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
Iteration   1: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  13.737 ms/op
                 createUser·p0.9999: 27.592 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 22.065 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.914 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  18.019 ms/op
                 createUser·p0.9999: 24.291 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296161
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21001 
    [ 2.500,  5.000) = 268674 
    [ 5.000,  7.500) = 4932 
    [ 7.500, 10.000) = 1077 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.756 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.626 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.277 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.228 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 24.776 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  14.081 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297375
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21730 
    [ 2.500,  5.000) = 267624 
    [ 5.000,  7.500) = 6974 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.769 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     23.676 ms/op
     p(99.9990) =     25.076 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  16.727 ms/op
                 getUser·p0.9999: 20.088 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.446 ms/op
                 getUser·p0.9999: 22.373 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  14.751 ms/op
                 getUser·p0.9999: 20.689 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298258
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12398 
    [ 2.500,  5.000) = 278558 
    [ 5.000,  7.500) = 5689 
    [ 7.500, 10.000) = 1104 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     14.618 ms/op
     p(99.9900) =     21.710 ms/op
     p(99.9990) =     23.304 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.838 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.013 ms/op
Iteration   1: 3.910 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  17.335 ms/op
                 listUser·p0.9999: 31.844 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   2: 3.821 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  13.621 ms/op
                 listUser·p0.9999: 16.411 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 19.946 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248559
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 239198 
    [ 5.000,  7.500) = 5989 
    [ 7.500, 10.000) = 2496 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     14.655 ms/op
     p(99.9900) =     30.741 ms/op
     p(99.9990) =     32.557 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.917 ± 5.638  ops/ms
ClientPb.existUser                       thrpt       3  10.261 ± 0.714  ops/ms
ClientPb.getUser                         thrpt       3   9.894 ± 5.240  ops/ms
ClientPb.listUser                        thrpt       3   8.563 ± 0.736  ops/ms
ClientPb.createUser                       avgt       3   3.337 ± 1.089   ms/op
ClientPb.existUser                        avgt       3   3.146 ± 1.145   ms/op
ClientPb.getUser                          avgt       3   3.189 ± 1.025   ms/op
ClientPb.listUser                         avgt       3   3.815 ± 1.459   ms/op
ClientPb.createUser                     sample  296161   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.853           ms/op
ClientPb.existUser                      sample  297375   3.227 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.769           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.676           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  298258   3.215 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.200           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.710           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.757           ms/op
ClientPb.listUser                       sample  248559   3.862 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.655           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.866           ms/op
