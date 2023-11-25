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
# Warmup Iteration   1: 5.225 ops/ms
# Warmup Iteration   2: 12.169 ops/ms
# Warmup Iteration   3: 12.558 ops/ms
Iteration   1: 12.667 ops/ms
Iteration   2: 12.662 ops/ms
Iteration   3: 12.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.669 ±(99.9%) 0.152 ops/ms [Average]
  (min, avg, max) = (12.662, 12.669, 12.679), stdev = 0.008
  CI (99.9%): [12.517, 12.822] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.640 ops/ms
# Warmup Iteration   2: 13.449 ops/ms
# Warmup Iteration   3: 13.404 ops/ms
Iteration   1: 13.382 ops/ms
Iteration   2: 13.270 ops/ms
Iteration   3: 13.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.354 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (13.270, 13.354, 13.411), stdev = 0.074
  CI (99.9%): [11.998, 14.711] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 12.912 ops/ms
# Warmup Iteration   3: 12.972 ops/ms
Iteration   1: 13.008 ops/ms
Iteration   2: 13.073 ops/ms
Iteration   3: 12.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.003 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (12.929, 13.003, 13.073), stdev = 0.072
  CI (99.9%): [11.686, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.617 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (10.456, 10.617, 10.712), stdev = 0.141
  CI (99.9%): [8.054, 13.181] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.489 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.470, 2.489, 2.517), stdev = 0.025
  CI (99.9%): [2.035, 2.944] (assumes normal distribution)


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.429, 2.439, 2.450), stdev = 0.010
  CI (99.9%): [2.251, 2.627] (assumes normal distribution)


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.003 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.504, 2.518, 2.526), stdev = 0.013
  CI (99.9%): [2.288, 2.748] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.005 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.958, 2.964, 2.969), stdev = 0.006
  CI (99.9%): [2.862, 3.065] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  6.753 ms/op
                 createUser·p0.9999: 13.874 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   3.401 ms/op
                 createUser·p0.999:  6.738 ms/op
                 createUser·p0.9999: 13.009 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  7.926 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391498
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 189319 
    [ 2.500,  3.750) = 198530 
    [ 3.750,  5.000) = 2882 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.956 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.845 ms/op
                 existUser·p0.9999: 17.067 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.672 ms/op
                 existUser·p0.9999: 11.358 ms/op
                 existUser·p1.00:   12.435 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.582 ms/op
                 existUser·p0.9999: 11.664 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391160
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 192059 
    [ 2.500,  3.750) = 195779 
    [ 3.750,  5.000) = 2293 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.356 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     18.126 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  6.999 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  6.121 ms/op
                 getUser·p0.9999: 13.238 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.356 ms/op
                 getUser·p0.9999: 11.096 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387742
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 193720 
    [ 2.500,  3.750) = 189180 
    [ 3.750,  5.000) = 3511 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.041 ms/op
     p(99.9900) =     13.389 ms/op
     p(99.9990) =     13.934 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.492 ms/op
                 listUser·p0.9999: 12.135 ms/op
                 listUser·p1.00:   13.304 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.261 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.795 ms/op
                 listUser·p0.9999: 12.556 ms/op
                 listUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320183
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 96300 
    [ 2.500,  3.750) = 184546 
    [ 3.750,  5.000) = 31844 
    [ 5.000,  6.250) = 5993 
    [ 6.250,  7.500) = 659 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.631 ms/op
     p(99.9900) =     12.419 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.669 ± 0.152  ops/ms
ClientPb.existUser                       thrpt       3  13.354 ± 1.357  ops/ms
ClientPb.getUser                         thrpt       3  13.003 ± 1.317  ops/ms
ClientPb.listUser                        thrpt       3  10.617 ± 2.563  ops/ms
ClientPb.createUser                       avgt       3   2.489 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.188   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.101   ms/op
ClientPb.createUser                     sample  391498   2.450 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.869           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.172           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.825           ms/op
ClientPb.existUser                      sample  391160   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.807           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.356           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.678           ms/op
ClientPb.getUser                        sample  387742   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.139           ms/op
ClientPb.listUser                       sample  320183   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.419           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.402           ms/op
