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
# Warmup Iteration   1: 5.212 ops/ms
# Warmup Iteration   2: 12.092 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.656 ops/ms
Iteration   2: 12.612 ops/ms
Iteration   3: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.682 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (12.612, 12.682, 12.779), stdev = 0.087
  CI (99.9%): [11.100, 14.265] (assumes normal distribution)


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
# Warmup Iteration   1: 8.184 ops/ms
# Warmup Iteration   2: 12.837 ops/ms
# Warmup Iteration   3: 12.986 ops/ms
Iteration   1: 13.011 ops/ms
Iteration   2: 12.998 ops/ms
Iteration   3: 13.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.026 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (12.998, 13.026, 13.068), stdev = 0.037
  CI (99.9%): [12.351, 13.701] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ops/ms
# Warmup Iteration   2: 12.646 ops/ms
# Warmup Iteration   3: 12.784 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 12.798 ops/ms
Iteration   3: 12.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.855 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (12.798, 12.855, 12.885), stdev = 0.049
  CI (99.9%): [11.957, 13.753] (assumes normal distribution)


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
# Warmup Iteration   1: 6.915 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.568 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.525, 10.568, 10.610), stdev = 0.042
  CI (99.9%): [9.794, 11.341] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.514, 2.544, 2.558), stdev = 0.025
  CI (99.9%): [2.083, 3.004] (assumes normal distribution)


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.469, 2.475, 2.479), stdev = 0.005
  CI (99.9%): [2.378, 2.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.460, 2.470, 2.476), stdev = 0.009
  CI (99.9%): [2.310, 2.629] (assumes normal distribution)


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.007 ms/op
Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
Iteration   3: 3.007 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.978, 2.991, 3.007), stdev = 0.015
  CI (99.9%): [2.716, 3.266] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.499 ms/op
                 createUser·p0.9999: 13.304 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  8.259 ms/op
                 createUser·p0.9999: 12.337 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  7.939 ms/op
                 createUser·p0.9999: 10.017 ms/op
                 createUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382885
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 186202 
    [ 2.500,  3.750) = 193089 
    [ 3.750,  5.000) = 2735 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.955 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     13.531 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.883 ms/op
                 existUser·p0.9999: 13.748 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.416 ms/op
                 existUser·p0.9999: 12.963 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.861 ms/op
                 existUser·p0.9999: 11.029 ms/op
                 existUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385557
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 194360 
    [ 2.500,  3.750) = 187911 
    [ 3.750,  5.000) = 2459 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.041 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.830 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  10.608 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  8.435 ms/op
                 getUser·p0.9999: 12.864 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.229 ms/op
                 getUser·p0.999:  8.233 ms/op
                 getUser·p0.9999: 10.823 ms/op
                 getUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385482
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192069 
    [ 2.500,  3.750) = 189047 
    [ 3.750,  5.000) = 3155 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.311 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.020 ms/op
                 listUser·p0.9999: 10.125 ms/op
                 listUser·p1.00:   10.420 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.479 ms/op
                 listUser·p0.999:  9.770 ms/op
                 listUser·p0.9999: 11.081 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.228 ms/op
                 listUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320213
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 95312 
    [ 2.500,  3.750) = 186439 
    [ 3.750,  5.000) = 31291 
    [ 5.000,  6.250) = 5711 
    [ 6.250,  7.500) = 639 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.122 ms/op
     p(99.9900) =     10.666 ms/op
     p(99.9990) =     12.098 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.682 ± 1.582  ops/ms
ClientPb.existUser                       thrpt       3  13.026 ± 0.675  ops/ms
ClientPb.getUser                         thrpt       3  12.855 ± 0.898  ops/ms
ClientPb.listUser                        thrpt       3  10.568 ± 0.774  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.460   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.097   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.160   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.275   ms/op
ClientPb.createUser                     sample  382885   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.648           ms/op
ClientPb.existUser                      sample  385557   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  385482   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.311           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.911           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.335           ms/op
ClientPb.listUser                       sample  320213   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.877           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.666           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
