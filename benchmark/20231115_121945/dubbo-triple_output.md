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
# Warmup Iteration   1: 4.254 ops/ms
# Warmup Iteration   2: 12.040 ops/ms
# Warmup Iteration   3: 12.240 ops/ms
Iteration   1: 12.492 ops/ms
Iteration   2: 12.477 ops/ms
Iteration   3: 12.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.519 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (12.477, 12.519, 12.587), stdev = 0.059
  CI (99.9%): [11.435, 13.603] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 8.022 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 12.931 ops/ms
Iteration   2: 12.891 ops/ms
Iteration   3: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 0.397 ops/ms [Average]
  (min, avg, max) = (12.891, 12.905, 12.931), stdev = 0.022
  CI (99.9%): [12.508, 13.303] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.534 ops/ms
# Warmup Iteration   3: 12.759 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 13.028 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.765 ±(99.9%) 4.165 ops/ms [Average]
  (min, avg, max) = (12.615, 12.765, 13.028), stdev = 0.228
  CI (99.9%): [8.600, 16.931] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.235 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.482 ±(99.9%) 0.533 ops/ms [Average]
  (min, avg, max) = (10.461, 10.482, 10.516), stdev = 0.029
  CI (99.9%): [9.949, 11.016] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.003 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (2.501, 2.552, 2.592), stdev = 0.047
  CI (99.9%): [1.698, 3.405] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.464, 2.476, 2.495), stdev = 0.017
  CI (99.9%): [2.172, 2.779] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.506, 2.519, 2.542), stdev = 0.020
  CI (99.9%): [2.155, 2.883] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 3.009 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (3.009, 3.014, 3.018), stdev = 0.005
  CI (99.9%): [2.929, 3.100] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.673 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  12.240 ms/op
                 createUser·p0.9999: 14.269 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  7.819 ms/op
                 createUser·p0.9999: 10.011 ms/op
                 createUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381234
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 183319 
    [ 2.500,  3.750) = 193358 
    [ 3.750,  5.000) = 3522 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.499 ms/op
     p(99.9900) =     13.695 ms/op
     p(99.9990) =     14.417 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  11.214 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  5.562 ms/op
                 existUser·p0.9999: 14.418 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 13.487 ms/op
                 existUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383353
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 186654 
    [ 2.500,  3.750) = 192973 
    [ 3.750,  5.000) = 2872 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.959 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     15.147 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  12.555 ms/op
                 getUser·p0.9999: 14.168 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 13.570 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  8.201 ms/op
                 getUser·p0.9999: 10.882 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384400
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 190267 
    [ 2.500,  3.750) = 189362 
    [ 3.750,  5.000) = 3213 
    [ 5.000,  6.250) = 901 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     14.411 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.873 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 12.064 ms/op
                 listUser·p1.00:   13.779 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.544 ms/op
                 listUser·p0.999:  9.859 ms/op
                 listUser·p0.9999: 12.325 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 12.201 ms/op
                 listUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319734
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 97022 
    [ 2.500,  3.750) = 183750 
    [ 3.750,  5.000) = 31479 
    [ 5.000,  6.250) = 6018 
    [ 6.250,  7.500) = 610 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     12.222 ms/op
     p(99.9990) =     13.347 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.519 ± 1.084  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 0.397  ops/ms
ClientPb.getUser                         thrpt       3  12.765 ± 4.165  ops/ms
ClientPb.listUser                        thrpt       3  10.482 ± 0.533  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.854   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.304   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.364   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.086   ms/op
ClientPb.createUser                     sample  381234   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.878           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.695           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  383353   2.501 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.221           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  384400   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.782           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.959           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.008           ms/op
ClientPb.listUser                       sample  319734   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.736           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.222           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.779           ms/op
