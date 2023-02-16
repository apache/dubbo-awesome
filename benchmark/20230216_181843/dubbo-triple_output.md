# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.517 ops/ms
# Warmup Iteration   2: 6.321 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.650 ops/ms
Iteration   2: 9.591 ops/ms
Iteration   3: 10.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.767 ±(99.9%) 4.647 ops/ms [Average]
  (min, avg, max) = (9.591, 9.767, 10.059), stdev = 0.255
  CI (99.9%): [5.119, 14.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.145 ops/ms
# Warmup Iteration   2: 9.225 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 10.005 ops/ms
Iteration   2: 10.464 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.377 ±(99.9%) 6.146 ops/ms [Average]
  (min, avg, max) = (10.005, 10.377, 10.662), stdev = 0.337
  CI (99.9%): [4.231, 16.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ops/ms
# Warmup Iteration   2: 9.497 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.081 ±(99.9%) 5.187 ops/ms [Average]
  (min, avg, max) = (9.787, 10.081, 10.355), stdev = 0.284
  CI (99.9%): [4.894, 15.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 7.906 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.542 ops/ms
Iteration   2: 8.627 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.536 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (8.439, 8.536, 8.627), stdev = 0.094
  CI (99.9%): [6.819, 10.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.735 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.004 ms/op
Iteration   1: 3.199 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
Iteration   3: 3.184 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.127, 3.170, 3.199), stdev = 0.038
  CI (99.9%): [2.477, 3.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.935 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.100 ±(99.9%) 0.005 ms/op
Iteration   2: 2.949 ±(99.9%) 0.004 ms/op
Iteration   3: 3.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.026 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (2.949, 3.026, 3.100), stdev = 0.075
  CI (99.9%): [1.650, 4.402] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.590 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.004 ms/op
Iteration   1: 3.099 ±(99.9%) 0.002 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.078 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.059, 3.078, 3.099), stdev = 0.020
  CI (99.9%): [2.713, 3.443] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.581 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.005 ms/op
Iteration   1: 3.759 ±(99.9%) 0.010 ms/op
Iteration   2: 3.737 ±(99.9%) 0.005 ms/op
Iteration   3: 3.719 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.719, 3.738, 3.759), stdev = 0.020
  CI (99.9%): [3.369, 4.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.599 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 20.157 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 27.977 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305142
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13449 
    [ 2.500,  5.000) = 286265 
    [ 5.000,  7.500) = 4721 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     26.427 ms/op
     p(99.9990) =     28.434 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 19.251 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.523 ms/op
                 existUser·p0.9999: 21.737 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.256 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314410
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24303 
    [ 2.500,  5.000) = 284370 
    [ 5.000,  7.500) = 4847 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     22.759 ms/op
     p(99.9990) =     24.239 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.358 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  18.543 ms/op
                 getUser·p0.9999: 22.506 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  15.914 ms/op
                 getUser·p0.9999: 24.035 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  16.495 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294774
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18930 
    [ 2.500,  5.000) = 267734 
    [ 5.000,  7.500) = 7132 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     25.368 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.187 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.873 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.669 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   3: 3.807 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 19.490 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256309
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 247149 
    [ 5.000,  7.500) = 7279 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     19.995 ms/op
     p(99.9990) =     22.143 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.767 ± 4.647  ops/ms
ClientPb.existUser                       thrpt       3  10.377 ± 6.146  ops/ms
ClientPb.getUser                         thrpt       3  10.081 ± 5.187  ops/ms
ClientPb.listUser                        thrpt       3   8.536 ± 1.717  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 0.694   ms/op
ClientPb.existUser                        avgt       3   3.026 ± 1.376   ms/op
ClientPb.getUser                          avgt       3   3.078 ± 0.365   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 0.370   ms/op
ClientPb.createUser                     sample  305142   3.145 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.518           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.173           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.427           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  314410   3.053 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.759           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.838           ms/op
ClientPb.getUser                        sample  294774   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.785           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.200           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  256309   3.747 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.995           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
