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
# Warmup Iteration   1: 2.605 ops/ms
# Warmup Iteration   2: 5.981 ops/ms
# Warmup Iteration   3: 9.011 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 9.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.083 ±(99.9%) 3.416 ops/ms [Average]
  (min, avg, max) = (9.968, 10.083, 10.299), stdev = 0.187
  CI (99.9%): [6.667, 13.499] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 9.279 ops/ms
# Warmup Iteration   3: 10.377 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 9.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.289 ±(99.9%) 9.334 ops/ms [Average]
  (min, avg, max) = (9.699, 10.289, 10.613), stdev = 0.512
  CI (99.9%): [0.955, 19.623] (assumes normal distribution)


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
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 9.584 ops/ms
Iteration   1: 10.320 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.186 ±(99.9%) 2.844 ops/ms [Average]
  (min, avg, max) = (10.015, 10.186, 10.320), stdev = 0.156
  CI (99.9%): [7.342, 13.030] (assumes normal distribution)


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
# Warmup Iteration   1: 3.193 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.592 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (8.539, 8.592, 8.638), stdev = 0.050
  CI (99.9%): [7.680, 9.505] (assumes normal distribution)


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
# Warmup Iteration   1: 8.700 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.005 ms/op
Iteration   1: 3.150 ±(99.9%) 0.003 ms/op
Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
Iteration   3: 3.128 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.125 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.097, 3.125, 3.150), stdev = 0.027
  CI (99.9%): [2.641, 3.609] (assumes normal distribution)


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
# Warmup Iteration   1: 7.254 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.003 ms/op
Iteration   1: 3.274 ±(99.9%) 0.006 ms/op
Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
Iteration   3: 3.226 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.184 ±(99.9%) 2.116 ms/op [Average]
  (min, avg, max) = (3.053, 3.184, 3.274), stdev = 0.116
  CI (99.9%): [1.068, 5.301] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.636 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.237 ±(99.9%) 0.002 ms/op
Iteration   3: 3.286 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 1.475 ms/op [Average]
  (min, avg, max) = (3.128, 3.217, 3.286), stdev = 0.081
  CI (99.9%): [1.742, 4.691] (assumes normal distribution)


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
# Warmup Iteration   1: 9.724 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.007 ms/op
Iteration   1: 3.791 ±(99.9%) 0.006 ms/op
Iteration   2: 3.886 ±(99.9%) 0.006 ms/op
Iteration   3: 3.795 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.824 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.791, 3.824, 3.886), stdev = 0.054
  CI (99.9%): [2.844, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 8.491 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.132 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 32.025 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 21.888 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.548 ms/op
                 createUser·p0.999:  12.155 ms/op
                 createUser·p0.9999: 20.159 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300482
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18120 
    [ 2.500,  5.000) = 277374 
    [ 5.000,  7.500) = 4181 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.554 ms/op
     p(99.9990) =     33.290 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 7.470 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
Iteration   1: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  12.007 ms/op
                 existUser·p0.9999: 19.104 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.191 ms/op
                 existUser·p0.9999: 21.085 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  14.985 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312023
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26003 
    [ 2.500,  5.000) = 279880 
    [ 5.000,  7.500) = 5330 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     21.397 ms/op
     p(99.9990) =     23.749 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 7.592 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.010 ms/op
Iteration   1: 3.147 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  19.048 ms/op
                 getUser·p0.9999: 29.983 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  10.659 ms/op
                 getUser·p0.9999: 22.089 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  9.983 ms/op
                 getUser·p0.9999: 22.798 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302871
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9331 
    [ 2.500,  5.000) = 286486 
    [ 5.000,  7.500) = 6164 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     27.399 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 8.971 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
Iteration   1: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 3.774 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 16.562 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.695 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.534 ms/op
                 listUser·p0.9999: 14.320 ms/op
                 listUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255066
  mean =      3.760 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 247147 
    [ 5.000,  7.500) = 5889 
    [ 7.500, 10.000) = 1318 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     21.971 ms/op
     p(99.9990) =     23.033 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.083 ± 3.416  ops/ms
ClientPb.existUser                       thrpt       3  10.289 ± 9.334  ops/ms
ClientPb.getUser                         thrpt       3  10.186 ± 2.844  ops/ms
ClientPb.listUser                        thrpt       3   8.592 ± 0.912  ops/ms
ClientPb.createUser                       avgt       3   3.125 ± 0.484   ms/op
ClientPb.existUser                        avgt       3   3.184 ± 2.116   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 1.475   ms/op
ClientPb.listUser                         avgt       3   3.824 ± 0.980   ms/op
ClientPb.createUser                     sample  300482   3.196 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.708           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.554           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  312023   3.076 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.989           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.397           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.921           ms/op
ClientPb.getUser                        sample  302871   3.169 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  255066   3.760 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.971           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.134           ms/op
