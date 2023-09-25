# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.125 ops/ms
# Warmup Iteration   2: 5.703 ops/ms
# Warmup Iteration   3: 8.541 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 9.450 ops/ms
Iteration   3: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.200 ±(99.9%) 4.101 ops/ms [Average]
  (min, avg, max) = (9.013, 9.200, 9.450), stdev = 0.225
  CI (99.9%): [5.100, 13.301] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ops/ms
# Warmup Iteration   2: 8.753 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.497 ops/ms
Iteration   2: 9.753 ops/ms
Iteration   3: 9.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.596 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (9.497, 9.596, 9.753), stdev = 0.138
  CI (99.9%): [7.083, 12.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 8.314 ops/ms
# Warmup Iteration   3: 9.188 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 9.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.477 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (9.334, 9.477, 9.554), stdev = 0.123
  CI (99.9%): [7.226, 11.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.888 ops/ms
# Warmup Iteration   2: 7.155 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.846 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (7.723, 7.846, 7.917), stdev = 0.108
  CI (99.9%): [5.884, 9.809] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.842 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.004 ms/op
Iteration   1: 3.452 ±(99.9%) 0.008 ms/op
Iteration   2: 3.497 ±(99.9%) 0.006 ms/op
Iteration   3: 3.415 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.415, 3.455, 3.497), stdev = 0.041
  CI (99.9%): [2.704, 4.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.674 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.003 ms/op
Iteration   1: 3.248 ±(99.9%) 0.005 ms/op
Iteration   2: 3.236 ±(99.9%) 0.005 ms/op
Iteration   3: 3.323 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.269 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.236, 3.269, 3.323), stdev = 0.047
  CI (99.9%): [2.415, 4.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.423 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.004 ms/op
Iteration   1: 3.381 ±(99.9%) 0.008 ms/op
Iteration   2: 3.388 ±(99.9%) 0.006 ms/op
Iteration   3: 3.342 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.371 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.342, 3.371, 3.388), stdev = 0.025
  CI (99.9%): [2.919, 3.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.076 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.005 ms/op
Iteration   1: 4.157 ±(99.9%) 0.006 ms/op
Iteration   2: 4.084 ±(99.9%) 0.005 ms/op
Iteration   3: 4.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.308 ms/op [Average]
  (min, avg, max) = (4.014, 4.085, 4.157), stdev = 0.072
  CI (99.9%): [2.777, 5.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.316 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.010 ms/op
Iteration   1: 3.606 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  20.063 ms/op
                 createUser·p0.9999: 32.678 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  21.705 ms/op
                 createUser·p0.9999: 24.738 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  18.532 ms/op
                 createUser·p0.9999: 22.637 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273138
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7146 
    [ 2.500,  5.000) = 257080 
    [ 5.000,  7.500) = 7752 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     31.873 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.941 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.007 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  17.574 ms/op
                 existUser·p0.9999: 24.817 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.900 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  18.272 ms/op
                 existUser·p0.9999: 24.783 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  21.725 ms/op
                 existUser·p0.9999: 24.327 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289402
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4162 
    [ 2.500,  5.000) = 279317 
    [ 5.000,  7.500) = 4952 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     19.687 ms/op
     p(99.9900) =     24.676 ms/op
     p(99.9990) =     26.130 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.886 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.449 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  8.753 ms/op
                 getUser·p0.9999: 22.392 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  19.899 ms/op
                 getUser·p0.9999: 22.735 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  18.057 ms/op
                 getUser·p0.9999: 25.767 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277799
  mean =      3.451 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4592 
    [ 2.500,  5.000) = 267367 
    [ 5.000,  7.500) = 4728 
    [ 7.500, 10.000) = 738 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     13.258 ms/op
     p(99.9900) =     24.583 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.530 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.013 ms/op
Iteration   1: 4.160 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  18.651 ms/op
                 listUser·p0.9999: 23.875 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 4.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.655 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.072 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 20.757 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235005
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 226657 
    [ 5.000,  7.500) = 6717 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.204 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.200 ± 4.101  ops/ms
ClientPb.existUser                       thrpt       3   9.596 ± 2.513  ops/ms
ClientPb.getUser                         thrpt       3   9.477 ± 2.251  ops/ms
ClientPb.listUser                        thrpt       3   7.846 ± 1.962  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 0.751   ms/op
ClientPb.existUser                        avgt       3   3.269 ± 0.854   ms/op
ClientPb.getUser                          avgt       3   3.371 ± 0.452   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.308   ms/op
ClientPb.createUser                     sample  273138   3.512 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  289402   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.614           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.687           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.676           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  277799   3.451 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.583           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  235005   4.082 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.675           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.314           ms/op
