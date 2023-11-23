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
# Warmup Iteration   1: 4.461 ops/ms
# Warmup Iteration   2: 12.081 ops/ms
# Warmup Iteration   3: 12.418 ops/ms
Iteration   1: 12.678 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.729 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (12.634, 12.729, 12.874), stdev = 0.128
  CI (99.9%): [10.394, 15.063] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.254 ops/ms
# Warmup Iteration   2: 12.937 ops/ms
# Warmup Iteration   3: 13.013 ops/ms
Iteration   1: 12.958 ops/ms
Iteration   2: 13.108 ops/ms
Iteration   3: 13.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.097 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (12.958, 13.097, 13.225), stdev = 0.134
  CI (99.9%): [10.649, 15.545] (assumes normal distribution)


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
# Warmup Iteration   1: 7.753 ops/ms
# Warmup Iteration   2: 12.467 ops/ms
# Warmup Iteration   3: 12.729 ops/ms
Iteration   1: 12.627 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.701 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (12.627, 12.701, 12.744), stdev = 0.065
  CI (99.9%): [11.519, 13.883] (assumes normal distribution)


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
# Warmup Iteration   1: 6.722 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.571 ops/ms
Iteration   1: 10.662 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.599 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (10.544, 10.599, 10.662), stdev = 0.059
  CI (99.9%): [9.517, 11.681] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.555 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.547, 2.555, 2.572), stdev = 0.014
  CI (99.9%): [2.301, 2.810] (assumes normal distribution)


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.005 ms/op
Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
Iteration   3: 2.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.412, 2.418, 2.423), stdev = 0.005
  CI (99.9%): [2.319, 2.518] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.459, 2.473, 2.483), stdev = 0.012
  CI (99.9%): [2.248, 2.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.841 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
Iteration   3: 3.032 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.027 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (3.023, 3.027, 3.032), stdev = 0.005
  CI (99.9%): [2.945, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  7.869 ms/op
                 createUser·p0.9999: 13.764 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 12.845 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  7.039 ms/op
                 createUser·p0.9999: 10.930 ms/op
                 createUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389146
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 192396 
    [ 2.500,  3.750) = 193023 
    [ 3.750,  5.000) = 2816 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.927 ms/op
     p(99.9900) =     13.371 ms/op
     p(99.9990) =     14.012 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  7.669 ms/op
                 existUser·p0.9999: 13.281 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  5.887 ms/op
                 existUser·p0.9999: 10.662 ms/op
                 existUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393758
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 195845 
    [ 2.500,  3.750) = 194349 
    [ 3.750,  5.000) = 2622 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.547 ms/op
     p(99.9900) =     13.734 ms/op
     p(99.9990) =     14.845 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  6.905 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  8.539 ms/op
                 getUser·p0.9999: 12.702 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  7.432 ms/op
                 getUser·p0.9999: 10.994 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384531
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 189740 
    [ 2.500,  3.750) = 189126 
    [ 3.750,  5.000) = 3973 
    [ 5.000,  6.250) = 1112 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      8.216 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.413 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 14.025 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.114 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319695
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 96534 
    [ 2.500,  3.750) = 182897 
    [ 3.750,  5.000) = 32223 
    [ 5.000,  6.250) = 6557 
    [ 6.250,  7.500) = 673 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     12.223 ms/op
     p(99.9990) =     14.133 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.729 ± 2.335  ops/ms
ClientPb.existUser                       thrpt       3  13.097 ± 2.448  ops/ms
ClientPb.getUser                         thrpt       3  12.701 ± 1.182  ops/ms
ClientPb.listUser                        thrpt       3  10.599 ± 1.082  ops/ms
ClientPb.createUser                       avgt       3   2.555 ± 0.255   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.225   ms/op
ClientPb.listUser                         avgt       3   3.027 ± 0.082   ms/op
ClientPb.createUser                     sample  389146   2.465 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.857           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.927           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.371           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  393758   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.547           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.734           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.597           ms/op
ClientPb.getUser                        sample  384531   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.751           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  319695   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.223           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
