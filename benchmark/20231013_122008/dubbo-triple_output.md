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
# Warmup Iteration   1: 2.020 ops/ms
# Warmup Iteration   2: 4.888 ops/ms
# Warmup Iteration   3: 8.334 ops/ms
Iteration   1: 9.087 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 8.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.097 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (8.983, 9.097, 9.220), stdev = 0.119
  CI (99.9%): [6.934, 11.259] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.774 ops/ms
# Warmup Iteration   2: 8.137 ops/ms
# Warmup Iteration   3: 9.657 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.666 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.660 ±(99.9%) 0.506 ops/ms [Average]
  (min, avg, max) = (9.630, 9.660, 9.684), stdev = 0.028
  CI (99.9%): [9.154, 10.166] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.510 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.596 ops/ms
Iteration   1: 8.866 ops/ms
Iteration   2: 9.277 ops/ms
Iteration   3: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.123 ±(99.9%) 4.085 ops/ms [Average]
  (min, avg, max) = (8.866, 9.123, 9.277), stdev = 0.224
  CI (99.9%): [5.038, 13.208] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 7.152 ops/ms
# Warmup Iteration   3: 7.494 ops/ms
Iteration   1: 7.678 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 7.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.700 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (7.676, 7.700, 7.745), stdev = 0.039
  CI (99.9%): [6.986, 8.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.125 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.005 ms/op
Iteration   1: 3.535 ±(99.9%) 0.004 ms/op
Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
Iteration   3: 3.408 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.408, 3.474, 3.535), stdev = 0.064
  CI (99.9%): [2.307, 4.640] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.603 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.003 ms/op
Iteration   1: 3.360 ±(99.9%) 0.005 ms/op
Iteration   2: 3.353 ±(99.9%) 0.003 ms/op
Iteration   3: 3.293 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.293, 3.335, 3.360), stdev = 0.037
  CI (99.9%): [2.655, 4.015] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.742 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.004 ms/op
Iteration   1: 3.538 ±(99.9%) 0.002 ms/op
Iteration   2: 3.456 ±(99.9%) 0.005 ms/op
Iteration   3: 3.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.511 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.456, 3.511, 3.538), stdev = 0.047
  CI (99.9%): [2.655, 4.366] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.808 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.005 ms/op
Iteration   1: 4.005 ±(99.9%) 0.008 ms/op
Iteration   2: 4.155 ±(99.9%) 0.006 ms/op
Iteration   3: 4.170 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.110 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (4.005, 4.110, 4.170), stdev = 0.091
  CI (99.9%): [2.442, 5.778] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.647 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.013 ms/op
Iteration   1: 3.570 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 22.480 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 26.801 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   3: 3.491 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  24.602 ms/op
                 createUser·p0.9999: 32.545 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272309
  mean =      3.523 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7369 
    [ 2.500,  5.000) = 256914 
    [ 5.000,  7.500) = 6364 
    [ 7.500, 10.000) = 911 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     20.951 ms/op
     p(99.9900) =     29.411 ms/op
     p(99.9990) =     33.081 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.206 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
Iteration   1: 3.339 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  20.658 ms/op
                 existUser·p0.9999: 22.768 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.474 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  22.508 ms/op
                 existUser·p0.9999: 27.883 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  13.285 ms/op
                 existUser·p0.9999: 28.035 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281043
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8264 
    [ 2.500,  5.000) = 263225 
    [ 5.000,  7.500) = 7048 
    [ 7.500, 10.000) = 1925 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     17.887 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     28.906 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.379 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.012 ms/op
Iteration   1: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  20.005 ms/op
                 getUser·p0.9999: 22.071 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.497 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  20.297 ms/op
                 getUser·p0.9999: 23.948 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.559 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  16.468 ms/op
                 getUser·p0.9999: 30.805 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273714
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6573 
    [ 2.500,  5.000) = 257280 
    [ 5.000,  7.500) = 8062 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     29.532 ms/op
     p(99.9990) =     31.499 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.485 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.014 ms/op
Iteration   1: 4.229 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  20.111 ms/op
                 listUser·p0.9999: 21.969 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 4.221 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.911 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 30.638 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227523
  mean =      4.219 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 217040 
    [ 5.000,  7.500) = 6777 
    [ 7.500, 10.000) = 2532 
    [10.000, 12.500) = 472 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     20.035 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     32.204 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.097 ± 2.163  ops/ms
ClientPb.existUser                       thrpt       3   9.660 ± 0.506  ops/ms
ClientPb.getUser                         thrpt       3   9.123 ± 4.085  ops/ms
ClientPb.listUser                        thrpt       3   7.700 ± 0.714  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.166   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 0.680   ms/op
ClientPb.getUser                          avgt       3   3.511 ± 0.855   ms/op
ClientPb.listUser                         avgt       3   4.110 ± 1.668   ms/op
ClientPb.createUser                     sample  272309   3.523 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.951           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.358           ms/op
ClientPb.existUser                      sample  281043   3.414 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.422           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  273714   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.532           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.588           ms/op
ClientPb.listUser                       sample  227523   4.219 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.035           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.032           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
