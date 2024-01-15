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
# Warmup Iteration   1: 4.920 ops/ms
# Warmup Iteration   2: 12.033 ops/ms
# Warmup Iteration   3: 12.275 ops/ms
Iteration   1: 12.386 ops/ms
Iteration   2: 12.467 ops/ms
Iteration   3: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.454 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (12.386, 12.454, 12.510), stdev = 0.063
  CI (99.9%): [11.303, 13.605] (assumes normal distribution)


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
# Warmup Iteration   1: 8.223 ops/ms
# Warmup Iteration   2: 12.844 ops/ms
# Warmup Iteration   3: 13.093 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 13.007 ops/ms
Iteration   3: 12.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.985 ±(99.9%) 0.348 ops/ms [Average]
  (min, avg, max) = (12.973, 12.985, 13.007), stdev = 0.019
  CI (99.9%): [12.637, 13.333] (assumes normal distribution)


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
# Warmup Iteration   1: 7.331 ops/ms
# Warmup Iteration   2: 12.584 ops/ms
# Warmup Iteration   3: 12.743 ops/ms
Iteration   1: 12.966 ops/ms
Iteration   2: 12.960 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.935 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (12.878, 12.935, 12.966), stdev = 0.049
  CI (99.9%): [12.038, 13.832] (assumes normal distribution)


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
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.381 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.572 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (10.526, 10.572, 10.642), stdev = 0.061
  CI (99.9%): [9.450, 11.693] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
Iteration   3: 2.535 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (2.526, 2.530, 2.535), stdev = 0.004
  CI (99.9%): [2.448, 2.612] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.003 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.461, 2.465, 2.474), stdev = 0.007
  CI (99.9%): [2.337, 2.594] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.461, 2.471, 2.477), stdev = 0.009
  CI (99.9%): [2.315, 2.626] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.816 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.036, 3.047, 3.063), stdev = 0.014
  CI (99.9%): [2.783, 3.310] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.840 ms/op
                 createUser·p0.999:  11.187 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.753 ms/op
                 createUser·p0.9999: 11.786 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  9.063 ms/op
                 createUser·p0.9999: 11.548 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378157
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 179381 
    [ 2.500,  3.750) = 193848 
    [ 3.750,  5.000) = 3921 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      9.107 ms/op
     p(99.9900) =     13.356 ms/op
     p(99.9990) =     14.065 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.429 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 12.100 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387901
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 190891 
    [ 2.500,  3.750) = 194094 
    [ 3.750,  5.000) = 2206 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      7.047 ms/op
     p(99.9900) =     13.576 ms/op
     p(99.9990) =     14.804 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  9.053 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.346 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 12.825 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  6.981 ms/op
                 getUser·p0.9999: 10.846 ms/op
                 getUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382707
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 188338 
    [ 2.500,  3.750) = 188270 
    [ 3.750,  5.000) = 4619 
    [ 5.000,  6.250) = 922 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.426 ms/op
     p(99.9900) =     13.234 ms/op
     p(99.9990) =     14.550 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.304 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.239 ms/op
                 listUser·p0.9999: 12.550 ms/op
                 listUser·p1.00:   12.894 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.901 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318004
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 92458 
    [ 2.500,  3.750) = 185435 
    [ 3.750,  5.000) = 32301 
    [ 5.000,  6.250) = 6108 
    [ 6.250,  7.500) = 830 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.708 ms/op
     p(99.9990) =     12.806 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.454 ± 1.151  ops/ms
ClientPb.existUser                       thrpt       3  12.985 ± 0.348  ops/ms
ClientPb.getUser                         thrpt       3  12.935 ± 0.897  ops/ms
ClientPb.listUser                        thrpt       3  10.572 ± 1.122  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.082   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.129   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.156   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.263   ms/op
ClientPb.createUser                     sample  378157   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.107           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.356           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.022           ms/op
ClientPb.existUser                      sample  387901   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.047           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.760           ms/op
ClientPb.getUser                        sample  382707   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.631           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.426           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.234           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  318004   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.708           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.894           ms/op
