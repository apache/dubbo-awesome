# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ops/ms
# Warmup Iteration   2: 12.084 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.627 ops/ms
Iteration   2: 12.769 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.710 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (12.627, 12.710, 12.769), stdev = 0.074
  CI (99.9%): [11.356, 14.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.267 ops/ms
# Warmup Iteration   2: 12.872 ops/ms
# Warmup Iteration   3: 13.050 ops/ms
Iteration   1: 13.078 ops/ms
Iteration   2: 12.850 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.976 ±(99.9%) 2.117 ops/ms [Average]
  (min, avg, max) = (12.850, 12.976, 13.078), stdev = 0.116
  CI (99.9%): [10.859, 15.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ops/ms
# Warmup Iteration   2: 12.641 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 12.859 ops/ms
Iteration   2: 12.655 ops/ms
Iteration   3: 12.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.723 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (12.655, 12.723, 12.859), stdev = 0.118
  CI (99.9%): [10.570, 14.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.537 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.658 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (10.596, 10.658, 10.711), stdev = 0.058
  CI (99.9%): [9.599, 11.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.516, 2.528, 2.541), stdev = 0.013
  CI (99.9%): [2.299, 2.758] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.458 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.461 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.458, 2.464, 2.473), stdev = 0.008
  CI (99.9%): [2.320, 2.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.470, 2.487, 2.501), stdev = 0.016
  CI (99.9%): [2.202, 2.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.005, 3.014, 3.023), stdev = 0.009
  CI (99.9%): [2.856, 3.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  11.112 ms/op
                 createUser·p0.9999: 17.826 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.048 ms/op
                 createUser·p0.9999: 12.419 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.826 ms/op
                 createUser·p0.9999: 11.959 ms/op
                 createUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377265
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 179209 
    [ 2.500,  3.750) = 193809 
    [ 3.750,  5.000) = 3422 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.892 ms/op
     p(99.9900) =     13.177 ms/op
     p(99.9990) =     18.693 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 13.666 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  8.604 ms/op
                 existUser·p0.9999: 13.145 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387248
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 189830 
    [ 2.500,  3.750) = 194184 
    [ 3.750,  5.000) = 2488 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.498 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.420 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  11.015 ms/op
                 getUser·p0.9999: 13.381 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 14.130 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 11.731 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378032
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 184130 
    [ 2.500,  3.750) = 188215 
    [ 3.750,  5.000) = 4477 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     13.373 ms/op
     p(99.9990) =     15.033 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.601 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.618 ms/op
                 listUser·p0.999:  10.191 ms/op
                 listUser·p0.9999: 11.582 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.230 ms/op
                 listUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316631
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 88262 
    [ 2.500,  3.750) = 187241 
    [ 3.750,  5.000) = 33439 
    [ 5.000,  6.250) = 6104 
    [ 6.250,  7.500) = 778 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.394 ms/op
     p(99.9900) =     11.234 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.710 ± 1.354  ops/ms
ClientPb.existUser                       thrpt       3  12.976 ± 2.117  ops/ms
ClientPb.getUser                         thrpt       3  12.723 ± 2.153  ops/ms
ClientPb.listUser                        thrpt       3  10.658 ± 1.059  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.230   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.144   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.285   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.157   ms/op
ClientPb.createUser                     sample  377265   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.887           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.177           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.874           ms/op
ClientPb.existUser                      sample  387248   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.498           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  378032   2.537 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.951           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.373           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  316631   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.234           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.977           ms/op
