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
# Warmup Iteration   1: 5.200 ops/ms
# Warmup Iteration   2: 12.038 ops/ms
# Warmup Iteration   3: 12.258 ops/ms
Iteration   1: 12.506 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.544 ±(99.9%) 0.754 ops/ms [Average]
  (min, avg, max) = (12.506, 12.544, 12.588), stdev = 0.041
  CI (99.9%): [11.791, 13.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.262 ops/ms
# Warmup Iteration   2: 13.230 ops/ms
# Warmup Iteration   3: 13.233 ops/ms
Iteration   1: 13.248 ops/ms
Iteration   2: 13.220 ops/ms
Iteration   3: 13.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.213 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (13.171, 13.213, 13.248), stdev = 0.039
  CI (99.9%): [12.502, 13.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ops/ms
# Warmup Iteration   2: 12.689 ops/ms
# Warmup Iteration   3: 12.724 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.607 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.700 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (12.607, 12.700, 12.770), stdev = 0.084
  CI (99.9%): [11.167, 14.233] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.424 ops/ms
# Warmup Iteration   2: 10.404 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.543 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (10.487, 10.543, 10.584), stdev = 0.050
  CI (99.9%): [9.623, 11.464] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
Iteration   3: 2.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.504, 2.515, 2.527), stdev = 0.012
  CI (99.9%): [2.305, 2.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.433, 2.443, 2.454), stdev = 0.011
  CI (99.9%): [2.250, 2.635] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (2.517, 2.539, 2.576), stdev = 0.032
  CI (99.9%): [1.946, 3.132] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.720 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.052 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.039, 3.052, 3.074), stdev = 0.019
  CI (99.9%): [2.707, 3.396] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.517 ms/op
                 createUser·p0.999:  6.758 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  6.790 ms/op
                 createUser·p0.9999: 11.847 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.243 ms/op
                 createUser·p0.9999: 10.870 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386974
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 189656 
    [ 2.500,  3.750) = 194190 
    [ 3.750,  5.000) = 2405 
    [ 5.000,  6.250) = 223 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     12.866 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  6.208 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  5.475 ms/op
                 existUser·p0.9999: 9.909 ms/op
                 existUser·p1.00:   10.912 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  7.552 ms/op
                 existUser·p0.9999: 11.190 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393910
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 198420 
    [ 2.500,  3.750) = 192927 
    [ 3.750,  5.000) = 1796 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =      6.302 ms/op
     p(99.9900) =     13.504 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.928 ms/op
                 getUser·p0.9999: 14.767 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.459 ms/op
                 getUser·p0.9999: 12.213 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  9.137 ms/op
                 getUser·p0.9999: 11.223 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382194
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 189451 
    [ 2.500,  3.750) = 187320 
    [ 3.750,  5.000) = 3941 
    [ 5.000,  6.250) = 939 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      9.281 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     15.718 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.545 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.351 ms/op
                 listUser·p0.9999: 11.819 ms/op
                 listUser·p1.00:   13.369 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.066 ms/op
                 listUser·p0.9999: 10.861 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.151 ms/op
                 listUser·p0.9999: 10.780 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319828
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 94448 
    [ 2.500,  3.750) = 187048 
    [ 3.750,  5.000) = 31213 
    [ 5.000,  6.250) = 5735 
    [ 6.250,  7.500) = 572 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.194 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     13.169 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.544 ± 0.754  ops/ms
ClientPb.existUser                       thrpt       3  13.213 ± 0.711  ops/ms
ClientPb.getUser                         thrpt       3  12.700 ± 1.533  ops/ms
ClientPb.listUser                        thrpt       3  10.543 ± 0.920  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.210   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.193   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.593   ms/op
ClientPb.listUser                         avgt       3   3.052 ± 0.345   ms/op
ClientPb.createUser                     sample  386974   2.479 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.779           ms/op
ClientPb.existUser                      sample  393910   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.504           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.695           ms/op
ClientPb.getUser                        sample  382194   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.761           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.089           ms/op
ClientPb.listUser                       sample  319828   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.194           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
