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
# Warmup Iteration   1: 2.494 ops/ms
# Warmup Iteration   2: 6.531 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 10.115 ops/ms
Iteration   3: 10.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.978 ±(99.9%) 3.597 ops/ms [Average]
  (min, avg, max) = (9.752, 9.978, 10.115), stdev = 0.197
  CI (99.9%): [6.381, 13.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 8.713 ops/ms
# Warmup Iteration   3: 10.033 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.376 ops/ms
Iteration   3: 10.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.410 ±(99.9%) 5.091 ops/ms [Average]
  (min, avg, max) = (10.150, 10.410, 10.705), stdev = 0.279
  CI (99.9%): [5.319, 15.501] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 10.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.151 ±(99.9%) 2.444 ops/ms [Average]
  (min, avg, max) = (10.032, 10.151, 10.296), stdev = 0.134
  CI (99.9%): [7.707, 12.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.273 ops/ms
# Warmup Iteration   2: 7.803 ops/ms
# Warmup Iteration   3: 8.610 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.486 ±(99.9%) 1.593 ops/ms [Average]
  (min, avg, max) = (8.413, 8.486, 8.583), stdev = 0.087
  CI (99.9%): [6.893, 10.080] (assumes normal distribution)


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
# Warmup Iteration   1: 8.021 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.005 ms/op
Iteration   1: 3.235 ±(99.9%) 0.006 ms/op
Iteration   2: 3.247 ±(99.9%) 0.006 ms/op
Iteration   3: 3.042 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.175 ±(99.9%) 2.102 ms/op [Average]
  (min, avg, max) = (3.042, 3.175, 3.247), stdev = 0.115
  CI (99.9%): [1.072, 5.277] (assumes normal distribution)


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
# Warmup Iteration   1: 7.465 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.004 ms/op
Iteration   1: 3.126 ±(99.9%) 0.005 ms/op
Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
Iteration   3: 3.096 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.070, 3.097, 3.126), stdev = 0.028
  CI (99.9%): [2.586, 3.608] (assumes normal distribution)


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
# Warmup Iteration   1: 7.024 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.005 ms/op
Iteration   1: 3.113 ±(99.9%) 0.003 ms/op
Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.113, 3.163, 3.202), stdev = 0.046
  CI (99.9%): [2.327, 3.999] (assumes normal distribution)


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
# Warmup Iteration   1: 9.088 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.008 ms/op
Iteration   1: 3.767 ±(99.9%) 0.006 ms/op
Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
Iteration   3: 3.661 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.697 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.661, 3.697, 3.767), stdev = 0.061
  CI (99.9%): [2.590, 4.804] (assumes normal distribution)


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
# Warmup Iteration   1: 7.117 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.011 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  9.668 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.225 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  13.397 ms/op
                 createUser·p0.9999: 37.552 ms/op
                 createUser·p1.00:   38.732 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  10.132 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298888
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22636 
    [ 2.500,  5.000) = 272517 
    [ 5.000,  7.500) = 3061 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     11.046 ms/op
     p(99.9900) =     35.659 ms/op
     p(99.9990) =     38.082 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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
# Warmup Iteration   1: 7.779 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.099 ms/op
                 existUser·p0.9999: 22.080 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.716 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  8.228 ms/op
                 existUser·p0.9999: 21.507 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  13.420 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306903
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10859 
    [ 2.500,  5.000) = 291456 
    [ 5.000,  7.500) = 3832 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     21.395 ms/op
     p(99.9990) =     22.542 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 6.804 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
Iteration   1: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  15.679 ms/op
                 getUser·p0.9999: 20.963 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 22.582 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  18.907 ms/op
                 getUser·p0.9999: 28.582 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291307
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12567 
    [ 2.500,  5.000) = 271257 
    [ 5.000,  7.500) = 6333 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     18.330 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     29.443 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 9.307 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
Iteration   1: 3.714 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.022 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 36.962 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.819 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  13.246 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   16.237 ms/op

Iteration   3: 3.689 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.491 ms/op
                 listUser·p0.999:  12.222 ms/op
                 listUser·p0.9999: 13.774 ms/op
                 listUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259403
  mean =      3.699 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 253383 
    [ 5.000,  7.500) = 4241 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.978 ± 3.597  ops/ms
ClientPb.existUser                       thrpt       3  10.410 ± 5.091  ops/ms
ClientPb.getUser                         thrpt       3  10.151 ± 2.444  ops/ms
ClientPb.listUser                        thrpt       3   8.486 ± 1.593  ops/ms
ClientPb.createUser                       avgt       3   3.175 ± 2.102   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.511   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 0.836   ms/op
ClientPb.listUser                         avgt       3   3.697 ± 1.107   ms/op
ClientPb.createUser                     sample  298888   3.210 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.527           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.046           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.659           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.732           ms/op
ClientPb.existUser                      sample  306903   3.129 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.689           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.395           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.807           ms/op
ClientPb.getUser                        sample  291307   3.291 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.330           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  259403   3.699 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.704           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.996           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
