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
# Warmup Iteration   1: 4.862 ops/ms
# Warmup Iteration   2: 11.678 ops/ms
# Warmup Iteration   3: 12.178 ops/ms
Iteration   1: 12.440 ops/ms
Iteration   2: 12.378 ops/ms
Iteration   3: 12.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.397 ±(99.9%) 0.676 ops/ms [Average]
  (min, avg, max) = (12.374, 12.397, 12.440), stdev = 0.037
  CI (99.9%): [11.721, 13.073] (assumes normal distribution)


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
# Warmup Iteration   1: 7.797 ops/ms
# Warmup Iteration   2: 12.660 ops/ms
# Warmup Iteration   3: 12.538 ops/ms
Iteration   1: 12.807 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.794 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (12.728, 12.794, 12.847), stdev = 0.060
  CI (99.9%): [11.696, 13.893] (assumes normal distribution)


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
# Warmup Iteration   1: 7.119 ops/ms
# Warmup Iteration   2: 12.206 ops/ms
# Warmup Iteration   3: 12.547 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.481 ops/ms
Iteration   3: 12.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.525 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (12.481, 12.525, 12.601), stdev = 0.066
  CI (99.9%): [11.329, 13.721] (assumes normal distribution)


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
# Warmup Iteration   1: 6.148 ops/ms
# Warmup Iteration   2: 10.253 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.538 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (10.465, 10.538, 10.582), stdev = 0.063
  CI (99.9%): [9.381, 11.695] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.527, 2.541, 2.563), stdev = 0.019
  CI (99.9%): [2.193, 2.890] (assumes normal distribution)


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.455 ±(99.9%) 0.003 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.433, 2.443, 2.455), stdev = 0.011
  CI (99.9%): [2.248, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.062 ms/op [Average]
  (min, avg, max) = (2.533, 2.536, 2.539), stdev = 0.003
  CI (99.9%): [2.474, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.999, 3.016, 3.032), stdev = 0.017
  CI (99.9%): [2.711, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.560 ms/op
                 createUser·p0.9999: 13.719 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.649 ms/op
                 createUser·p0.9999: 12.146 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 10.977 ms/op
                 createUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379077
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 181701 
    [ 2.500,  3.750) = 192960 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.094 ms/op
     p(99.9990) =     13.946 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  11.429 ms/op
                 existUser·p0.9999: 14.025 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.566 ms/op
                 existUser·p0.999:  5.974 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384122
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185728 
    [ 2.500,  3.750) = 194331 
    [ 3.750,  5.000) = 2927 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      6.879 ms/op
     p(99.9900) =     13.526 ms/op
     p(99.9990) =     14.215 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  10.647 ms/op
                 getUser·p0.9999: 14.806 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  5.538 ms/op
                 getUser·p0.9999: 12.801 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.454 ms/op
                 getUser·p0.9999: 12.108 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379709
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186851 
    [ 2.500,  3.750) = 188793 
    [ 3.750,  5.000) = 3084 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.788 ms/op
     p(99.9000) =      5.980 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     15.358 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 4.825 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.449 ms/op
                 listUser·p0.9999: 11.478 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.271 ms/op
                 listUser·p0.9999: 11.292 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.356 ms/op
                 listUser·p0.9999: 11.135 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322233
  mean =      2.976 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 98809 
    [ 2.500,  3.750) = 186616 
    [ 3.750,  5.000) = 29560 
    [ 5.000,  6.250) = 5909 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 173 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.367 ms/op
     p(99.9990) =     12.232 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.397 ± 0.676  ops/ms
ClientPb.existUser                       thrpt       3  12.794 ± 1.099  ops/ms
ClientPb.getUser                         thrpt       3  12.525 ± 1.196  ops/ms
ClientPb.listUser                        thrpt       3  10.538 ± 1.157  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.348   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.195   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.062   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.305   ms/op
ClientPb.createUser                     sample  379077   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.679           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.094           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.041           ms/op
ClientPb.existUser                      sample  384122   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.879           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  379709   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.788           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.980           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.794           ms/op
ClientPb.listUser                       sample  322233   2.976 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.952           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.367           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.288           ms/op
