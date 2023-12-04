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
# Warmup Iteration   1: 4.685 ops/ms
# Warmup Iteration   2: 11.864 ops/ms
# Warmup Iteration   3: 12.148 ops/ms
Iteration   1: 12.186 ops/ms
Iteration   2: 12.354 ops/ms
Iteration   3: 12.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.286 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (12.186, 12.286, 12.354), stdev = 0.088
  CI (99.9%): [10.674, 13.899] (assumes normal distribution)


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
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 12.791 ops/ms
# Warmup Iteration   3: 12.942 ops/ms
Iteration   1: 12.872 ops/ms
Iteration   2: 12.815 ops/ms
Iteration   3: 12.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.832 ±(99.9%) 0.636 ops/ms [Average]
  (min, avg, max) = (12.809, 12.832, 12.872), stdev = 0.035
  CI (99.9%): [12.196, 13.469] (assumes normal distribution)


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
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 12.376 ops/ms
# Warmup Iteration   3: 12.346 ops/ms
Iteration   1: 12.935 ops/ms
Iteration   2: 12.720 ops/ms
Iteration   3: 12.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.768 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (12.648, 12.768, 12.935), stdev = 0.149
  CI (99.9%): [10.047, 15.488] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.012 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.534 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (10.506, 10.534, 10.572), stdev = 0.034
  CI (99.9%): [9.911, 11.156] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.563 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.536, 2.563, 2.593), stdev = 0.029
  CI (99.9%): [2.041, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.412 ±(99.9%) 0.003 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.418 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.412, 2.420, 2.431), stdev = 0.010
  CI (99.9%): [2.245, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.548 ±(99.9%) 0.005 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.541 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.529, 2.541, 2.548), stdev = 0.010
  CI (99.9%): [2.359, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
Iteration   3: 3.049 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.058 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.049, 3.058, 3.070), stdev = 0.011
  CI (99.9%): [2.862, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.394 ms/op
                 createUser·p0.9999: 14.514 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.286 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  9.556 ms/op
                 createUser·p0.9999: 12.957 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 10.905 ms/op
                 createUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374032
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 176707 
    [ 2.500,  3.750) = 192014 
    [ 3.750,  5.000) = 4058 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     14.136 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.888 ms/op
                 existUser·p0.9999: 14.516 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.577 ms/op
                 existUser·p0.999:  7.088 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 12.458 ms/op
                 existUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388443
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 193134 
    [ 2.500,  3.750) = 191929 
    [ 3.750,  5.000) = 2653 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.396 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.712 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 14.610 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 11.675 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377236
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 182653 
    [ 2.500,  3.750) = 188467 
    [ 3.750,  5.000) = 4698 
    [ 5.000,  6.250) = 842 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     16.091 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.493 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 12.804 ms/op
                 listUser·p1.00:   13.124 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.766 ms/op
                 listUser·p0.9999: 11.082 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316226
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 88410 
    [ 2.500,  3.750) = 186566 
    [ 3.750,  5.000) = 33149 
    [ 5.000,  6.250) = 6540 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.417 ms/op
     p(99.9900) =     11.848 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.286 ± 1.613  ops/ms
ClientPb.existUser                       thrpt       3  12.832 ± 0.636  ops/ms
ClientPb.getUser                         thrpt       3  12.768 ± 2.720  ops/ms
ClientPb.listUser                        thrpt       3  10.534 ± 0.622  ops/ms
ClientPb.createUser                       avgt       3   2.563 ± 0.522   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.175   ms/op
ClientPb.getUser                          avgt       3   2.541 ± 0.182   ms/op
ClientPb.listUser                         avgt       3   3.058 ± 0.196   ms/op
ClientPb.createUser                     sample  374032   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.136           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.122           ms/op
ClientPb.existUser                      sample  388443   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.396           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.319           ms/op
ClientPb.getUser                        sample  377236   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.204           ms/op
ClientPb.listUser                       sample  316226   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.124           ms/op
