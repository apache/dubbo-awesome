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
# Warmup Iteration   1: 4.742 ops/ms
# Warmup Iteration   2: 12.014 ops/ms
# Warmup Iteration   3: 12.241 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.581 ops/ms
Iteration   3: 12.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.563 ±(99.9%) 0.641 ops/ms [Average]
  (min, avg, max) = (12.522, 12.563, 12.585), stdev = 0.035
  CI (99.9%): [11.922, 13.204] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.798 ops/ms
# Warmup Iteration   2: 12.903 ops/ms
# Warmup Iteration   3: 12.786 ops/ms
Iteration   1: 12.878 ops/ms
Iteration   2: 12.821 ops/ms
Iteration   3: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.854 ±(99.9%) 0.543 ops/ms [Average]
  (min, avg, max) = (12.821, 12.854, 12.878), stdev = 0.030
  CI (99.9%): [12.311, 13.397] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 12.299 ops/ms
# Warmup Iteration   3: 12.441 ops/ms
Iteration   1: 12.603 ops/ms
Iteration   2: 12.666 ops/ms
Iteration   3: 12.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.638 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (12.603, 12.638, 12.666), stdev = 0.032
  CI (99.9%): [12.046, 13.231] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ops/ms
# Warmup Iteration   2: 10.292 ops/ms
# Warmup Iteration   3: 10.580 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.552 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (10.452, 10.552, 10.606), stdev = 0.086
  CI (99.9%): [8.975, 12.129] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.569 ±(99.9%) 0.003 ms/op
Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.558, 2.571, 2.588), stdev = 0.015
  CI (99.9%): [2.294, 2.848] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.491 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.477, 2.491, 2.499), stdev = 0.012
  CI (99.9%): [2.270, 2.711] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.499, 2.504, 2.516), stdev = 0.010
  CI (99.9%): [2.329, 2.680] (assumes normal distribution)


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.031 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.015, 3.031, 3.051), stdev = 0.019
  CI (99.9%): [2.687, 3.375] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.515 ms/op
                 createUser·p0.9999: 11.606 ms/op
                 createUser·p1.00:   12.091 ms/op

Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  8.384 ms/op
                 createUser·p0.9999: 11.150 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376826
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 181206 
    [ 2.500,  3.750) = 190519 
    [ 3.750,  5.000) = 3959 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.956 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.433 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  7.305 ms/op
                 existUser·p0.9999: 15.708 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.684 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  9.499 ms/op
                 existUser·p0.9999: 12.188 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391897
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 193085 
    [ 2.500,  3.750) = 194895 
    [ 3.750,  5.000) = 2928 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      7.211 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.965 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  12.345 ms/op
                 getUser·p0.9999: 13.717 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 13.098 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.956 ms/op
                 getUser·p0.9999: 11.945 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381620
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 188227 
    [ 2.500,  3.750) = 187799 
    [ 3.750,  5.000) = 4151 
    [ 5.000,  6.250) = 848 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 144 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     13.498 ms/op
     p(99.9990) =     14.192 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.845 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  11.141 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.624 ms/op
                 listUser·p0.9999: 11.819 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315346
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 88061 
    [ 2.500,  3.750) = 185697 
    [ 3.750,  5.000) = 33179 
    [ 5.000,  6.250) = 6879 
    [ 6.250,  7.500) = 747 
    [ 7.500,  8.750) = 171 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.710 ms/op
     p(99.9900) =     15.694 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.563 ± 0.641  ops/ms
ClientPb.existUser                       thrpt       3  12.854 ± 0.543  ops/ms
ClientPb.getUser                         thrpt       3  12.638 ± 0.592  ops/ms
ClientPb.listUser                        thrpt       3  10.552 ± 1.577  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.277   ms/op
ClientPb.existUser                        avgt       3   2.491 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.176   ms/op
ClientPb.listUser                         avgt       3   3.031 ± 0.344   ms/op
ClientPb.createUser                     sample  376826   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.691           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.956           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.778           ms/op
ClientPb.existUser                      sample  391897   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.211           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.384           ms/op
ClientPb.getUser                        sample  381620   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.962           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  315346   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.710           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.694           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.793           ms/op
