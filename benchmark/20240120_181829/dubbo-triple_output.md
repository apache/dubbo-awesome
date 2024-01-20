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
# Warmup Iteration   1: 4.996 ops/ms
# Warmup Iteration   2: 12.082 ops/ms
# Warmup Iteration   3: 12.496 ops/ms
Iteration   1: 12.720 ops/ms
Iteration   2: 12.626 ops/ms
Iteration   3: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.693 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (12.626, 12.693, 12.734), stdev = 0.059
  CI (99.9%): [11.623, 13.763] (assumes normal distribution)


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
# Warmup Iteration   1: 8.195 ops/ms
# Warmup Iteration   2: 12.684 ops/ms
# Warmup Iteration   3: 12.830 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.877 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.821 ±(99.9%) 0.961 ops/ms [Average]
  (min, avg, max) = (12.772, 12.821, 12.877), stdev = 0.053
  CI (99.9%): [11.860, 13.783] (assumes normal distribution)


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
# Warmup Iteration   1: 7.984 ops/ms
# Warmup Iteration   2: 12.542 ops/ms
# Warmup Iteration   3: 12.793 ops/ms
Iteration   1: 12.901 ops/ms
Iteration   2: 13.057 ops/ms
Iteration   3: 12.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.970 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (12.901, 12.970, 13.057), stdev = 0.079
  CI (99.9%): [11.522, 14.417] (assumes normal distribution)


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
# Warmup Iteration   1: 6.821 ops/ms
# Warmup Iteration   2: 10.667 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.583 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (10.567, 10.583, 10.609), stdev = 0.023
  CI (99.9%): [10.171, 10.995] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
Iteration   3: 2.530 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.523, 2.533, 2.545), stdev = 0.012
  CI (99.9%): [2.322, 2.744] (assumes normal distribution)


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.422, 2.442, 2.455), stdev = 0.017
  CI (99.9%): [2.127, 2.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.003 ms/op
Iteration   1: 2.525 ±(99.9%) 0.003 ms/op
Iteration   2: 2.523 ±(99.9%) 0.003 ms/op
Iteration   3: 2.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.517, 2.521, 2.525), stdev = 0.004
  CI (99.9%): [2.448, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.987, 3.007, 3.024), stdev = 0.019
  CI (99.9%): [2.664, 3.351] (assumes normal distribution)


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
# Warmup Iteration   1: 4.382 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  11.143 ms/op
                 createUser·p0.9999: 13.291 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.052 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 11.776 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  8.390 ms/op
                 createUser·p0.9999: 11.455 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380991
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 184582 
    [ 2.500,  3.750) = 192717 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.799 ms/op
     p(99.9900) =     12.827 ms/op
     p(99.9990) =     13.516 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.006 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  5.743 ms/op
                 existUser·p0.9999: 13.433 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.310 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.457 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  9.321 ms/op
                 existUser·p0.9999: 22.872 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392639
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195128 
    [ 2.500,  5.000) = 196539 
    [ 5.000,  7.500) = 562 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     13.578 ms/op
     p(99.9990) =     23.862 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  7.593 ms/op
                 getUser·p0.9999: 13.339 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  7.877 ms/op
                 getUser·p0.9999: 13.142 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.918 ms/op
                 getUser·p0.999:  7.540 ms/op
                 getUser·p0.9999: 12.628 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385079
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 191745 
    [ 2.500,  3.750) = 189391 
    [ 3.750,  5.000) = 3064 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.331 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.869 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.045 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.821 ms/op
                 listUser·p0.9999: 11.188 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.474 ms/op
                 listUser·p0.9999: 10.643 ms/op
                 listUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316316
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 86818 
    [ 2.500,  3.750) = 189132 
    [ 3.750,  5.000) = 33010 
    [ 5.000,  6.250) = 5860 
    [ 6.250,  7.500) = 725 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.858 ms/op
     p(99.9990) =     11.507 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.693 ± 1.070  ops/ms
ClientPb.existUser                       thrpt       3  12.821 ± 0.961  ops/ms
ClientPb.getUser                         thrpt       3  12.970 ± 1.448  ops/ms
ClientPb.listUser                        thrpt       3  10.583 ± 0.412  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.211   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.344   ms/op
ClientPb.createUser                     sample  380991   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.799           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.827           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.809           ms/op
ClientPb.existUser                      sample  392639   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.536           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.578           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.084           ms/op
ClientPb.getUser                        sample  385079   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.755           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  316316   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.858           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.813           ms/op
