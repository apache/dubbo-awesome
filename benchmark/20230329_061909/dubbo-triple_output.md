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
# Warmup Iteration   1: 2.649 ops/ms
# Warmup Iteration   2: 6.006 ops/ms
# Warmup Iteration   3: 8.887 ops/ms
Iteration   1: 9.695 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 9.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.938 ±(99.9%) 4.583 ops/ms [Average]
  (min, avg, max) = (9.695, 9.938, 10.197), stdev = 0.251
  CI (99.9%): [5.354, 14.521] (assumes normal distribution)


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
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 9.019 ops/ms
# Warmup Iteration   3: 10.106 ops/ms
Iteration   1: 10.702 ops/ms
Iteration   2: 10.307 ops/ms
Iteration   3: 10.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.500 ±(99.9%) 3.603 ops/ms [Average]
  (min, avg, max) = (10.307, 10.500, 10.702), stdev = 0.198
  CI (99.9%): [6.897, 14.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ops/ms
# Warmup Iteration   2: 9.155 ops/ms
# Warmup Iteration   3: 9.444 ops/ms
Iteration   1: 9.468 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.902 ±(99.9%) 7.165 ops/ms [Average]
  (min, avg, max) = (9.468, 9.902, 10.233), stdev = 0.393
  CI (99.9%): [2.737, 17.067] (assumes normal distribution)


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
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 7.607 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 8.865 ops/ms
Iteration   2: 8.736 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.755 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (8.665, 8.755, 8.865), stdev = 0.102
  CI (99.9%): [6.900, 10.610] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.003 ms/op
Iteration   1: 3.142 ±(99.9%) 0.001 ms/op
Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
Iteration   3: 3.252 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.169 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.112, 3.169, 3.252), stdev = 0.074
  CI (99.9%): [1.822, 4.515] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.593 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 3.040 ±(99.9%) 0.007 ms/op
Iteration   2: 3.100 ±(99.9%) 0.005 ms/op
Iteration   3: 2.970 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.036 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (2.970, 3.036, 3.100), stdev = 0.065
  CI (99.9%): [1.849, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 7.383 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
Iteration   3: 3.212 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.140 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (3.085, 3.140, 3.212), stdev = 0.065
  CI (99.9%): [1.949, 4.330] (assumes normal distribution)


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
# Warmup Iteration   1: 7.934 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.765 ±(99.9%) 0.006 ms/op
Iteration   2: 3.790 ±(99.9%) 0.004 ms/op
Iteration   3: 3.697 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.751 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.697, 3.751, 3.790), stdev = 0.048
  CI (99.9%): [2.871, 4.630] (assumes normal distribution)


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
# Warmup Iteration   1: 7.289 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 34.339 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  12.121 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  17.484 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303880
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18462 
    [ 2.500,  5.000) = 280221 
    [ 5.000,  7.500) = 4393 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     17.309 ms/op
     p(99.9900) =     33.465 ms/op
     p(99.9990) =     35.843 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 7.489 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  12.182 ms/op
                 existUser·p0.9999: 19.879 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309179
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18748 
    [ 2.500,  5.000) = 285591 
    [ 5.000,  7.500) = 4117 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     22.926 ms/op
     p(99.9990) =     25.458 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 8.624 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.009 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  14.714 ms/op
                 getUser·p0.9999: 19.882 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 21.582 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.935 ms/op
                 getUser·p0.999:  12.537 ms/op
                 getUser·p0.9999: 17.748 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303274
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15894 
    [ 2.500,  5.000) = 280476 
    [ 5.000,  7.500) = 5930 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     13.660 ms/op
     p(99.9900) =     20.679 ms/op
     p(99.9990) =     22.110 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 8.957 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.012 ms/op
Iteration   1: 3.729 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.774 ms/op
                 listUser·p0.9999: 21.354 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.765 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.026 ms/op
                 listUser·p0.9999: 13.730 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.352 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255825
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 247059 
    [ 5.000,  7.500) = 6780 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.847 ms/op
     p(99.9900) =     20.100 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.938 ± 4.583  ops/ms
ClientPb.existUser                       thrpt       3  10.500 ± 3.603  ops/ms
ClientPb.getUser                         thrpt       3   9.902 ± 7.165  ops/ms
ClientPb.listUser                        thrpt       3   8.755 ± 1.855  ops/ms
ClientPb.createUser                       avgt       3   3.169 ± 1.347   ms/op
ClientPb.existUser                        avgt       3   3.036 ± 1.187   ms/op
ClientPb.getUser                          avgt       3   3.140 ± 1.191   ms/op
ClientPb.listUser                         avgt       3   3.751 ± 0.879   ms/op
ClientPb.createUser                     sample  303880   3.158 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.309           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.465           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372           ms/op
ClientPb.existUser                      sample  309179   3.102 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  303274   3.164 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.984           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.679           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.413           ms/op
ClientPb.listUser                       sample  255825   3.750 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.354           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.100           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
