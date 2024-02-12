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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.511 ops/ms
Iteration   1: 12.606 ops/ms
Iteration   2: 12.604 ops/ms
Iteration   3: 12.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.636 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (12.604, 12.636, 12.697), stdev = 0.053
  CI (99.9%): [11.669, 13.603] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ops/ms
# Warmup Iteration   2: 13.202 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.452 ops/ms
Iteration   2: 13.291 ops/ms
Iteration   3: 13.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.350 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (13.291, 13.350, 13.452), stdev = 0.089
  CI (99.9%): [11.735, 14.965] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.499 ops/ms
# Warmup Iteration   2: 12.183 ops/ms
# Warmup Iteration   3: 12.472 ops/ms
Iteration   1: 12.727 ops/ms
Iteration   2: 12.626 ops/ms
Iteration   3: 12.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.658 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (12.622, 12.658, 12.727), stdev = 0.059
  CI (99.9%): [11.582, 13.735] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.563 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.688 ±(99.9%) 0.586 ops/ms [Average]
  (min, avg, max) = (10.651, 10.688, 10.710), stdev = 0.032
  CI (99.9%): [10.101, 11.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.527, 2.535, 2.545), stdev = 0.009
  CI (99.9%): [2.370, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.003 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.417, 2.428, 2.445), stdev = 0.015
  CI (99.9%): [2.158, 2.698] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.003 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.504, 2.517, 2.529), stdev = 0.013
  CI (99.9%): [2.286, 2.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
Iteration   3: 2.962 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.961, 2.971, 2.991), stdev = 0.017
  CI (99.9%): [2.665, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  7.864 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.791 ms/op
                 createUser·p0.999:  8.512 ms/op
                 createUser·p0.9999: 12.370 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  7.216 ms/op
                 createUser·p0.9999: 10.903 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385473
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 185313 
    [ 2.500,  3.750) = 196044 
    [ 3.750,  5.000) = 3273 
    [ 5.000,  6.250) = 377 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.661 ms/op
     p(99.9900) =     12.982 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.387 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
Iteration   1: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.266 ms/op
                 existUser·p0.9999: 13.742 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.378 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.382 ms/op
                 existUser·p0.999:  5.298 ms/op
                 existUser·p0.9999: 10.732 ms/op
                 existUser·p1.00:   11.207 ms/op

Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400298
  mean =      2.396 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 199216 
    [ 2.500,  3.750) = 198577 
    [ 3.750,  5.000) = 1764 
    [ 5.000,  6.250) = 340 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      5.898 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  10.954 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  7.518 ms/op
                 getUser·p0.9999: 13.485 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  5.603 ms/op
                 getUser·p0.9999: 11.342 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386819
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 192170 
    [ 2.500,  3.750) = 190041 
    [ 3.750,  5.000) = 3650 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      7.661 ms/op
     p(99.9900) =     13.413 ms/op
     p(99.9990) =     13.835 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.715 ms/op
                 listUser·p0.9999: 10.125 ms/op
                 listUser·p1.00:   10.535 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.859 ms/op
                 listUser·p0.9999: 10.933 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.439 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322678
  mean =      2.972 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 98325 
    [ 2.500,  3.750) = 187607 
    [ 3.750,  5.000) = 29924 
    [ 5.000,  6.250) = 5399 
    [ 6.250,  7.500) = 630 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     10.924 ms/op
     p(99.9990) =     11.671 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.636 ± 0.967  ops/ms
ClientPb.existUser                       thrpt       3  13.350 ± 1.615  ops/ms
ClientPb.getUser                         thrpt       3  12.658 ± 1.076  ops/ms
ClientPb.listUser                        thrpt       3  10.688 ± 0.586  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.165   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.270   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.307   ms/op
ClientPb.createUser                     sample  385473   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.817           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  400298   2.396 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.898           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  386819   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.413           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.074           ms/op
ClientPb.listUser                       sample  322678   2.972 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.754           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.924           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.731           ms/op
