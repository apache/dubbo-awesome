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
# Warmup Iteration   1: 5.195 ops/ms
# Warmup Iteration   2: 12.427 ops/ms
# Warmup Iteration   3: 12.425 ops/ms
Iteration   1: 12.697 ops/ms
Iteration   2: 12.688 ops/ms
Iteration   3: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.709 ±(99.9%) 0.532 ops/ms [Average]
  (min, avg, max) = (12.688, 12.709, 12.742), stdev = 0.029
  CI (99.9%): [12.177, 13.242] (assumes normal distribution)


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
# Warmup Iteration   1: 8.387 ops/ms
# Warmup Iteration   2: 12.889 ops/ms
# Warmup Iteration   3: 12.915 ops/ms
Iteration   1: 13.033 ops/ms
Iteration   2: 13.042 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.993 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (12.905, 12.993, 13.042), stdev = 0.077
  CI (99.9%): [11.595, 14.392] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.070 ops/ms
# Warmup Iteration   2: 12.668 ops/ms
# Warmup Iteration   3: 12.893 ops/ms
Iteration   1: 12.805 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.830 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (12.755, 12.830, 12.930), stdev = 0.090
  CI (99.9%): [11.190, 14.470] (assumes normal distribution)


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
# Warmup Iteration   1: 6.750 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.709 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.678 ±(99.9%) 0.546 ops/ms [Average]
  (min, avg, max) = (10.644, 10.678, 10.696), stdev = 0.030
  CI (99.9%): [10.132, 11.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.503, 2.509, 2.518), stdev = 0.008
  CI (99.9%): [2.360, 2.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.003 ms/op
Iteration   2: 2.403 ±(99.9%) 0.002 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (2.403, 2.432, 2.458), stdev = 0.028
  CI (99.9%): [1.926, 2.938] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.502, 2.505, 2.509), stdev = 0.004
  CI (99.9%): [2.439, 2.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.005 ms/op
Iteration   1: 2.953 ±(99.9%) 0.005 ms/op
Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
Iteration   3: 2.965 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.953, 2.962, 2.967), stdev = 0.007
  CI (99.9%): [2.825, 3.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  9.678 ms/op
                 createUser·p0.9999: 14.287 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.556 ms/op
                 createUser·p0.9999: 10.361 ms/op
                 createUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378212
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 180432 
    [ 2.500,  3.750) = 192834 
    [ 3.750,  5.000) = 4094 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.598 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.512 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  10.800 ms/op
                 existUser·p0.9999: 13.820 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  8.545 ms/op
                 existUser·p0.9999: 14.059 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 11.344 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384857
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185475 
    [ 2.500,  3.750) = 195676 
    [ 3.750,  5.000) = 2876 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     13.837 ms/op
     p(99.9990) =     14.325 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  12.125 ms/op
                 getUser·p0.9999: 14.251 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 13.058 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.194 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  8.379 ms/op
                 getUser·p0.9999: 10.295 ms/op
                 getUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376138
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 182349 
    [ 2.500,  3.750) = 188827 
    [ 3.750,  5.000) = 4100 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.717 ms/op
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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.633 ms/op
                 listUser·p1.00:   12.894 ms/op

Iteration   2: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.806 ms/op
                 listUser·p0.9999: 12.896 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314132
  mean =      3.053 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 84083 
    [ 2.500,  3.750) = 188177 
    [ 3.750,  5.000) = 34238 
    [ 5.000,  6.250) = 6194 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 199 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.779 ms/op
     p(99.9900) =     11.747 ms/op
     p(99.9990) =     13.351 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.709 ± 0.532  ops/ms
ClientPb.existUser                       thrpt       3  12.993 ± 1.399  ops/ms
ClientPb.getUser                         thrpt       3  12.830 ± 1.640  ops/ms
ClientPb.listUser                        thrpt       3  10.678 ± 0.546  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.149   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.506   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.066   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.137   ms/op
ClientPb.createUser                     sample  378212   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.809           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.598           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  384857   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.799           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.837           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  376138   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  314132   3.053 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.934           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.747           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
