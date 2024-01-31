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
# Warmup Iteration   1: 4.282 ops/ms
# Warmup Iteration   2: 11.460 ops/ms
# Warmup Iteration   3: 11.949 ops/ms
Iteration   1: 12.431 ops/ms
Iteration   2: 12.475 ops/ms
Iteration   3: 12.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.495 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (12.431, 12.495, 12.578), stdev = 0.075
  CI (99.9%): [11.125, 13.864] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.821 ops/ms
# Warmup Iteration   2: 12.775 ops/ms
# Warmup Iteration   3: 12.857 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.798 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (12.684, 12.798, 12.924), stdev = 0.121
  CI (99.9%): [10.595, 15.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.198 ops/ms
# Warmup Iteration   2: 12.472 ops/ms
# Warmup Iteration   3: 12.887 ops/ms
Iteration   1: 12.878 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.792 ±(99.9%) 2.537 ops/ms [Average]
  (min, avg, max) = (12.631, 12.792, 12.878), stdev = 0.139
  CI (99.9%): [10.255, 15.328] (assumes normal distribution)


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
# Warmup Iteration   1: 6.694 ops/ms
# Warmup Iteration   2: 10.456 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.721 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.681 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (10.642, 10.681, 10.721), stdev = 0.040
  CI (99.9%): [9.955, 11.407] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.572 ±(99.9%) 0.003 ms/op
Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.559, 2.569, 2.576), stdev = 0.009
  CI (99.9%): [2.401, 2.737] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.003 ms/op
Iteration   3: 2.446 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.446, 2.452, 2.458), stdev = 0.006
  CI (99.9%): [2.338, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.003 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (2.488, 2.515, 2.538), stdev = 0.026
  CI (99.9%): [2.049, 2.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (3.001, 3.014, 3.037), stdev = 0.020
  CI (99.9%): [2.652, 3.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  12.123 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   3: 2.605 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  6.941 ms/op
                 createUser·p0.9999: 12.152 ms/op
                 createUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369766
  mean =      2.594 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 175124 
    [ 2.500,  3.750) = 190675 
    [ 3.750,  5.000) = 2961 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.618 ms/op
     p(99.9900) =     14.908 ms/op
     p(99.9990) =     16.981 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.335 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  8.927 ms/op
                 existUser·p0.9999: 14.893 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  8.428 ms/op
                 existUser·p0.9999: 13.178 ms/op
                 existUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379517
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 186200 
    [ 2.500,  3.750) = 190193 
    [ 3.750,  5.000) = 2332 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.774 ms/op
     p(99.9900) =     15.861 ms/op
     p(99.9990) =     17.256 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.612 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.432 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  9.599 ms/op
                 getUser·p0.9999: 14.874 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  5.284 ms/op
                 getUser·p0.9999: 11.074 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375092
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 180808 
    [ 2.500,  3.750) = 187333 
    [ 3.750,  5.000) = 5087 
    [ 5.000,  6.250) = 1422 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.348 ms/op
     p(99.9900) =     13.443 ms/op
     p(99.9990) =     16.281 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.899 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.009 ms/op
Iteration   1: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 12.155 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.942 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.430 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312011
  mean =      3.074 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 83390 
    [ 2.500,  3.750) = 185527 
    [ 3.750,  5.000) = 34468 
    [ 5.000,  6.250) = 6851 
    [ 6.250,  7.500) = 997 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     13.351 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.495 ± 1.370  ops/ms
ClientPb.existUser                       thrpt       3  12.798 ± 2.203  ops/ms
ClientPb.getUser                         thrpt       3  12.792 ± 2.537  ops/ms
ClientPb.listUser                        thrpt       3  10.681 ± 0.726  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.168   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.113   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.466   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.363   ms/op
ClientPb.createUser                     sample  369766   2.594 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.687           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.908           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.138           ms/op
ClientPb.existUser                      sample  379517   2.527 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.498           ms/op
ClientPb.getUser                        sample  375092   2.557 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.764           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.348           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.443           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.367           ms/op
ClientPb.listUser                       sample  312011   3.074 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.904           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
