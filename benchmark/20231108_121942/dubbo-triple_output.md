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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 12.191 ops/ms
# Warmup Iteration   3: 12.431 ops/ms
Iteration   1: 12.736 ops/ms
Iteration   2: 12.955 ops/ms
Iteration   3: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.827 ±(99.9%) 2.083 ops/ms [Average]
  (min, avg, max) = (12.736, 12.827, 12.955), stdev = 0.114
  CI (99.9%): [10.745, 14.910] (assumes normal distribution)


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
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 12.975 ops/ms
# Warmup Iteration   3: 13.021 ops/ms
Iteration   1: 12.969 ops/ms
Iteration   2: 13.093 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.030 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (12.969, 13.030, 13.093), stdev = 0.062
  CI (99.9%): [11.896, 14.164] (assumes normal distribution)


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
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 12.362 ops/ms
# Warmup Iteration   3: 12.575 ops/ms
Iteration   1: 12.625 ops/ms
Iteration   2: 12.749 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.693 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (12.625, 12.693, 12.749), stdev = 0.063
  CI (99.9%): [11.543, 13.843] (assumes normal distribution)


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
# Warmup Iteration   1: 6.352 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.460 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (10.406, 10.460, 10.494), stdev = 0.047
  CI (99.9%): [9.599, 11.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.003 ms/op
Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.510, 2.530, 2.556), stdev = 0.024
  CI (99.9%): [2.092, 2.967] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.058 ms/op [Average]
  (min, avg, max) = (2.456, 2.460, 2.461), stdev = 0.003
  CI (99.9%): [2.402, 2.517] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.481, 2.503, 2.521), stdev = 0.020
  CI (99.9%): [2.136, 2.870] (assumes normal distribution)


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.061 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.046, 3.061, 3.077), stdev = 0.016
  CI (99.9%): [2.777, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 15.062 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 16.983 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 10.668 ms/op
                 createUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380226
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 182940 
    [ 2.500,  3.750) = 192701 
    [ 3.750,  5.000) = 3333 
    [ 5.000,  6.250) = 723 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.578 ms/op
     p(99.9900) =     15.154 ms/op
     p(99.9990) =     17.819 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.824 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  8.439 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  6.831 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  6.935 ms/op
                 existUser·p0.9999: 10.341 ms/op
                 existUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389414
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193650 
    [ 2.500,  5.000) = 194933 
    [ 5.000,  7.500) = 445 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     14.162 ms/op
     p(99.9990) =     23.039 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 16.898 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.359 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  9.080 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 10.682 ms/op
                 getUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377551
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 183575 
    [ 2.500,  3.750) = 186768 
    [ 3.750,  5.000) = 5470 
    [ 5.000,  6.250) = 1129 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.871 ms/op
     p(99.9900) =     14.569 ms/op
     p(99.9990) =     17.422 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.666 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.593 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 12.298 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.809 ms/op
                 listUser·p0.9999: 12.676 ms/op
                 listUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311852
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 82396 
    [ 2.500,  3.750) = 184124 
    [ 3.750,  5.000) = 36295 
    [ 5.000,  6.250) = 7410 
    [ 6.250,  7.500) = 813 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     13.418 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.827 ± 2.083  ops/ms
ClientPb.existUser                       thrpt       3  13.030 ± 1.134  ops/ms
ClientPb.getUser                         thrpt       3  12.693 ± 1.150  ops/ms
ClientPb.listUser                        thrpt       3  10.460 ± 0.862  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.058   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.367   ms/op
ClientPb.listUser                         avgt       3   3.061 ± 0.285   ms/op
ClientPb.createUser                     sample  380226   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.614           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.578           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.154           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.022           ms/op
ClientPb.existUser                      sample  389414   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.784           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.193           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  377551   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.781           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.871           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.569           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.727           ms/op
ClientPb.listUser                       sample  311852   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.763           ms/op
