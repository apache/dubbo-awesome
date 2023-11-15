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
# Warmup Iteration   1: 4.748 ops/ms
# Warmup Iteration   2: 11.678 ops/ms
# Warmup Iteration   3: 11.881 ops/ms
Iteration   1: 12.345 ops/ms
Iteration   2: 12.210 ops/ms
Iteration   3: 12.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.313 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (12.210, 12.313, 12.384), stdev = 0.091
  CI (99.9%): [10.647, 13.979] (assumes normal distribution)


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
# Warmup Iteration   1: 8.023 ops/ms
# Warmup Iteration   2: 12.833 ops/ms
# Warmup Iteration   3: 12.874 ops/ms
Iteration   1: 12.989 ops/ms
Iteration   2: 13.090 ops/ms
Iteration   3: 12.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (12.938, 13.006, 13.090), stdev = 0.078
  CI (99.9%): [11.591, 14.420] (assumes normal distribution)


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
# Warmup Iteration   1: 7.806 ops/ms
# Warmup Iteration   2: 12.395 ops/ms
# Warmup Iteration   3: 12.451 ops/ms
Iteration   1: 12.508 ops/ms
Iteration   2: 12.486 ops/ms
Iteration   3: 12.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.529 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (12.486, 12.529, 12.594), stdev = 0.057
  CI (99.9%): [11.490, 13.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.294 ops/ms
# Warmup Iteration   2: 10.357 ops/ms
# Warmup Iteration   3: 10.253 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.489 ±(99.9%) 0.310 ops/ms [Average]
  (min, avg, max) = (10.470, 10.489, 10.502), stdev = 0.017
  CI (99.9%): [10.179, 10.799] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.505, 2.523, 2.535), stdev = 0.016
  CI (99.9%): [2.232, 2.813] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.530 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.505, 2.530, 2.559), stdev = 0.027
  CI (99.9%): [2.039, 3.022] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.593 ±(99.9%) 0.004 ms/op
Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
Iteration   3: 2.597 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.588 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.575, 2.588, 2.597), stdev = 0.012
  CI (99.9%): [2.373, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 5.290 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.005 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.114 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.103 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.070, 3.103, 3.124), stdev = 0.029
  CI (99.9%): [2.578, 3.628] (assumes normal distribution)


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 2.751 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.621 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 23.718 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 19.838 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 11.669 ms/op
                 createUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369377
  mean =      2.596 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 171982 
    [ 2.500,  5.000) = 195665 
    [ 5.000,  7.500) = 1284 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      9.326 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     23.941 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.702 ms/op
                 existUser·p0.999:  9.725 ms/op
                 existUser·p0.9999: 14.535 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 13.376 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   3.918 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 13.048 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380526
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 183702 
    [ 2.500,  3.750) = 192002 
    [ 3.750,  5.000) = 3732 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.885 ms/op
     p(99.9900) =     13.794 ms/op
     p(99.9990) =     15.027 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  12.179 ms/op
                 getUser·p0.9999: 14.461 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.012 ms/op
                 getUser·p0.999:  10.786 ms/op
                 getUser·p0.9999: 14.051 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.174 ms/op
                 getUser·p0.95:   3.334 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.046 ms/op
                 getUser·p0.9999: 13.315 ms/op
                 getUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371472
  mean =      2.582 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 178579 
    [ 2.500,  3.750) = 185686 
    [ 3.750,  5.000) = 5828 
    [ 5.000,  6.250) = 947 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.367 ms/op
     p(99.9900) =     14.167 ms/op
     p(99.9990) =     14.837 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.009 ms/op
Iteration   1: 3.115 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  10.420 ms/op
                 listUser·p0.9999: 13.209 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.468 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.589 ms/op
                 listUser·p0.9999: 12.761 ms/op
                 listUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309764
  mean =      3.096 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 75965 
    [ 2.500,  3.750) = 188141 
    [ 3.750,  5.000) = 37180 
    [ 5.000,  6.250) = 6841 
    [ 6.250,  7.500) = 831 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.834 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.450 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.313 ± 1.666  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 1.414  ops/ms
ClientPb.getUser                         thrpt       3  12.529 ± 1.039  ops/ms
ClientPb.listUser                        thrpt       3  10.489 ± 0.310  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.291   ms/op
ClientPb.existUser                        avgt       3   2.530 ± 0.492   ms/op
ClientPb.getUser                          avgt       3   2.588 ± 0.215   ms/op
ClientPb.listUser                         avgt       3   3.103 ± 0.525   ms/op
ClientPb.createUser                     sample  369377   2.596 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.995           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.326           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  380526   2.520 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.885           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.794           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  371472   2.582 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.073           ms/op
ClientPb.listUser                       sample  309764   3.096 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.871           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.834           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.796           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
