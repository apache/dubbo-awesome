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
# Warmup Iteration   1: 4.786 ops/ms
# Warmup Iteration   2: 11.855 ops/ms
# Warmup Iteration   3: 12.160 ops/ms
Iteration   1: 12.504 ops/ms
Iteration   2: 12.536 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.615 ±(99.9%) 2.996 ops/ms [Average]
  (min, avg, max) = (12.504, 12.615, 12.803), stdev = 0.164
  CI (99.9%): [9.618, 15.611] (assumes normal distribution)


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
# Warmup Iteration   1: 7.693 ops/ms
# Warmup Iteration   2: 12.896 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.936 ops/ms
Iteration   3: 12.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.940 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (12.901, 12.940, 12.981), stdev = 0.040
  CI (99.9%): [12.214, 13.666] (assumes normal distribution)


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
# Warmup Iteration   1: 7.612 ops/ms
# Warmup Iteration   2: 12.714 ops/ms
# Warmup Iteration   3: 12.666 ops/ms
Iteration   1: 12.928 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.811 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (12.673, 12.811, 12.928), stdev = 0.129
  CI (99.9%): [10.456, 15.167] (assumes normal distribution)


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
# Warmup Iteration   1: 6.579 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.672 ±(99.9%) 0.636 ops/ms [Average]
  (min, avg, max) = (10.649, 10.672, 10.712), stdev = 0.035
  CI (99.9%): [10.036, 11.307] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.509, 2.531, 2.551), stdev = 0.021
  CI (99.9%): [2.146, 2.917] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.443, 2.448, 2.452), stdev = 0.004
  CI (99.9%): [2.370, 2.525] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.509, 2.521, 2.532), stdev = 0.012
  CI (99.9%): [2.310, 2.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.001, 3.012, 3.024), stdev = 0.012
  CI (99.9%): [2.802, 3.223] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  10.389 ms/op
                 createUser·p0.9999: 13.667 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.832 ms/op
                 createUser·p0.9999: 12.780 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  8.317 ms/op
                 createUser·p0.9999: 10.158 ms/op
                 createUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381631
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 182542 
    [ 2.500,  3.750) = 194729 
    [ 3.750,  5.000) = 3445 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.326 ms/op
     p(99.9900) =     13.399 ms/op
     p(99.9990) =     14.186 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  5.917 ms/op
                 existUser·p0.9999: 13.927 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  5.880 ms/op
                 existUser·p0.9999: 12.701 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.474 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  9.330 ms/op
                 existUser·p0.9999: 14.141 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389362
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 191842 
    [ 2.500,  3.750) = 192855 
    [ 3.750,  5.000) = 3606 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.481 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     17.276 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  12.466 ms/op
                 getUser·p0.9999: 16.073 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.613 ms/op
                 getUser·p0.999:  10.863 ms/op
                 getUser·p0.9999: 14.080 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  8.288 ms/op
                 getUser·p0.9999: 11.294 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380370
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 186998 
    [ 2.500,  3.750) = 187120 
    [ 3.750,  5.000) = 4896 
    [ 5.000,  6.250) = 842 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.221 ms/op
     p(99.9000) =      8.358 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.316 ms/op
                 listUser·p0.9999: 20.072 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.724 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.549 ms/op
                 listUser·p0.9999: 12.094 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.404 ms/op
                 listUser·p0.9999: 11.975 ms/op
                 listUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316467
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91504 
    [ 2.500,  5.000) = 217020 
    [ 5.000,  7.500) = 7244 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     18.073 ms/op
     p(99.9990) =     21.409 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.615 ± 2.996  ops/ms
ClientPb.existUser                       thrpt       3  12.940 ± 0.726  ops/ms
ClientPb.getUser                         thrpt       3  12.811 ± 2.356  ops/ms
ClientPb.listUser                        thrpt       3  10.672 ± 0.636  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.077   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.211   ms/op
ClientPb.createUser                     sample  381631   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.326           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.399           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  389362   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.481           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.727           ms/op
ClientPb.getUser                        sample  380370   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.221           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.358           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.221           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.646           ms/op
ClientPb.listUser                       sample  316467   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.073           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
