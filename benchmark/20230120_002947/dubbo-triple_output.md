# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.241 ops/ms
# Warmup Iteration   2: 2.525 ops/ms
# Warmup Iteration   3: 5.407 ops/ms
Iteration   1: 5.660 ops/ms
Iteration   2: 5.987 ops/ms
Iteration   3: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.934 ±(99.9%) 4.572 ops/ms [Average]
  (min, avg, max) = (5.660, 5.934, 6.153), stdev = 0.251
  CI (99.9%): [1.361, 10.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.795 ops/ms
# Warmup Iteration   2: 5.285 ops/ms
# Warmup Iteration   3: 5.782 ops/ms
Iteration   1: 6.228 ops/ms
Iteration   2: 6.217 ops/ms
Iteration   3: 6.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.244 ±(99.9%) 0.698 ops/ms [Average]
  (min, avg, max) = (6.217, 6.244, 6.288), stdev = 0.038
  CI (99.9%): [5.546, 6.942] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.800 ops/ms
# Warmup Iteration   2: 5.153 ops/ms
# Warmup Iteration   3: 5.853 ops/ms
Iteration   1: 5.991 ops/ms
Iteration   2: 5.894 ops/ms
Iteration   3: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.986 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (5.894, 5.986, 6.072), stdev = 0.089
  CI (99.9%): [4.356, 7.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 4.674 ops/ms
# Warmup Iteration   3: 5.174 ops/ms
Iteration   1: 5.056 ops/ms
Iteration   2: 5.084 ops/ms
Iteration   3: 5.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.091 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (5.056, 5.091, 5.133), stdev = 0.039
  CI (99.9%): [4.379, 5.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.258 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.387 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.562 ±(99.9%) 0.014 ms/op
Iteration   1: 5.641 ±(99.9%) 0.009 ms/op
Iteration   2: 5.469 ±(99.9%) 0.010 ms/op
Iteration   3: 5.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.538 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (5.469, 5.538, 5.641), stdev = 0.091
  CI (99.9%): [3.885, 7.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.451 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.104 ±(99.9%) 0.009 ms/op
Iteration   1: 4.956 ±(99.9%) 0.008 ms/op
Iteration   2: 5.090 ±(99.9%) 0.007 ms/op
Iteration   3: 5.019 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.021 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (4.956, 5.021, 5.090), stdev = 0.067
  CI (99.9%): [3.792, 6.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.195 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.944 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.201 ±(99.9%) 0.010 ms/op
Iteration   1: 5.445 ±(99.9%) 0.009 ms/op
Iteration   2: 5.552 ±(99.9%) 0.007 ms/op
Iteration   3: 5.511 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.503 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (5.445, 5.503, 5.552), stdev = 0.054
  CI (99.9%): [4.512, 6.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 21.626 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 8.411 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.866 ±(99.9%) 0.014 ms/op
Iteration   1: 6.740 ±(99.9%) 0.018 ms/op
Iteration   2: 6.408 ±(99.9%) 0.015 ms/op
Iteration   3: 6.155 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.434 ±(99.9%) 5.353 ms/op [Average]
  (min, avg, max) = (6.155, 6.434, 6.740), stdev = 0.293
  CI (99.9%): [1.082, 11.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.065 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.635 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.012 ±(99.9%) 0.028 ms/op
Iteration   1: 5.474 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.261 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   11.370 ms/op
                 createUser·p0.999:  23.053 ms/op
                 createUser·p0.9999: 28.125 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   2: 5.398 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.036 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  24.142 ms/op
                 createUser·p0.9999: 36.393 ms/op
                 createUser·p1.00:   38.273 ms/op

Iteration   3: 5.172 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.445 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  27.924 ms/op
                 createUser·p0.9999: 30.534 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179635
  mean =      5.345 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 85705 
    [ 5.000,  7.500) = 83571 
    [ 7.500, 10.000) = 7951 
    [10.000, 12.500) = 1664 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     24.129 ms/op
     p(99.9900) =     34.673 ms/op
     p(99.9990) =     38.116 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.929 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.145 ±(99.9%) 0.018 ms/op
Iteration   1: 5.581 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   7.324 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   10.977 ms/op
                 existUser·p0.999:  26.138 ms/op
                 existUser·p0.9999: 31.826 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   2: 5.432 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.782 ms/op
                 existUser·p0.99:   11.059 ms/op
                 existUser·p0.999:  21.415 ms/op
                 existUser·p0.9999: 28.545 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 5.170 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  31.425 ms/op
                 existUser·p0.9999: 37.135 ms/op
                 existUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178034
  mean =      5.389 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 84384 
    [ 5.000,  7.500) = 82240 
    [ 7.500, 10.000) = 8621 
    [10.000, 12.500) = 1826 
    [12.500, 15.000) = 502 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     25.326 ms/op
     p(99.9900) =     35.874 ms/op
     p(99.9990) =     37.952 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.209 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.005 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.599 ±(99.9%) 0.022 ms/op
Iteration   1: 5.389 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.478 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  24.838 ms/op
                 getUser·p0.9999: 26.970 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 5.591 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.356 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  26.858 ms/op
                 getUser·p0.9999: 30.159 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 5.646 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.417 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.208 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 30.944 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173255
  mean =      5.540 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 65330 
    [ 5.000,  7.500) = 95677 
    [ 7.500, 10.000) = 9087 
    [10.000, 12.500) = 2103 
    [12.500, 15.000) = 653 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      8.151 ms/op
     p(99.0000) =     11.279 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     30.420 ms/op
     p(99.9990) =     31.663 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.532 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 7.869 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.481 ±(99.9%) 0.027 ms/op
Iteration   1: 6.540 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   13.681 ms/op
                 listUser·p0.999:  27.820 ms/op
                 listUser·p0.9999: 30.387 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 6.850 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.864 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   14.126 ms/op
                 listUser·p0.999:  30.987 ms/op
                 listUser·p0.9999: 36.940 ms/op
                 listUser·p1.00:   38.142 ms/op

Iteration   3: 6.809 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  26.085 ms/op
                 listUser·p0.9999: 29.370 ms/op
                 listUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142502
  mean =      6.730 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5911 
    [ 5.000,  7.500) = 110748 
    [ 7.500, 10.000) = 18770 
    [10.000, 12.500) = 5060 
    [12.500, 15.000) = 1195 
    [15.000, 17.500) = 435 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      6.308 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.582 ms/op
     p(99.9000) =     28.115 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     37.975 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.934 ± 4.572  ops/ms
ClientPb.existUser                       thrpt       3   6.244 ± 0.698  ops/ms
ClientPb.getUser                         thrpt       3   5.986 ± 1.630  ops/ms
ClientPb.listUser                        thrpt       3   5.091 ± 0.712  ops/ms
ClientPb.createUser                       avgt       3   5.538 ± 1.653   ms/op
ClientPb.existUser                        avgt       3   5.021 ± 1.229   ms/op
ClientPb.getUser                          avgt       3   5.503 ± 0.990   ms/op
ClientPb.listUser                         avgt       3   6.434 ± 5.353   ms/op
ClientPb.createUser                     sample  179635   5.345 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.445           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.129           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.273           ms/op
ClientPb.existUser                      sample  178034   5.389 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.046           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.856           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.879           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.326           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.874           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.207           ms/op
ClientPb.getUser                        sample  173255   5.540 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.261           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.151           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.279           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.707           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  142502   6.730 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.618           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.308           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.582           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.115           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.455           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
