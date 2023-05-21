# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.971 ops/ms
# Warmup Iteration   3: 9.012 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.355 ops/ms
Iteration   3: 9.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.536 ±(99.9%) 3.544 ops/ms [Average]
  (min, avg, max) = (9.355, 9.536, 9.741), stdev = 0.194
  CI (99.9%): [5.992, 13.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.303 ops/ms
# Warmup Iteration   2: 8.792 ops/ms
# Warmup Iteration   3: 9.678 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 9.699 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.985 ±(99.9%) 4.526 ops/ms [Average]
  (min, avg, max) = (9.699, 9.985, 10.151), stdev = 0.248
  CI (99.9%): [5.459, 14.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.237 ops/ms
# Warmup Iteration   2: 8.937 ops/ms
# Warmup Iteration   3: 9.387 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.682 ±(99.9%) 4.085 ops/ms [Average]
  (min, avg, max) = (9.424, 9.682, 9.828), stdev = 0.224
  CI (99.9%): [5.596, 13.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 6.987 ops/ms
# Warmup Iteration   3: 7.878 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.118 ±(99.9%) 3.170 ops/ms [Average]
  (min, avg, max) = (7.954, 8.118, 8.300), stdev = 0.174
  CI (99.9%): [4.947, 11.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.596 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.005 ms/op
Iteration   1: 3.464 ±(99.9%) 0.005 ms/op
Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
Iteration   3: 3.214 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.371 ±(99.9%) 2.499 ms/op [Average]
  (min, avg, max) = (3.214, 3.371, 3.464), stdev = 0.137
  CI (99.9%): [0.872, 5.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.483 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.322 ±(99.9%) 0.004 ms/op
Iteration   2: 3.150 ±(99.9%) 0.012 ms/op
Iteration   3: 3.095 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.189 ±(99.9%) 2.167 ms/op [Average]
  (min, avg, max) = (3.095, 3.189, 3.322), stdev = 0.119
  CI (99.9%): [1.022, 5.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.006 ms/op
Iteration   1: 3.318 ±(99.9%) 0.008 ms/op
Iteration   2: 3.284 ±(99.9%) 0.006 ms/op
Iteration   3: 3.360 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.321 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (3.284, 3.321, 3.360), stdev = 0.038
  CI (99.9%): [2.624, 4.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.666 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.008 ms/op
Iteration   1: 3.897 ±(99.9%) 0.013 ms/op
Iteration   2: 3.905 ±(99.9%) 0.012 ms/op
Iteration   3: 3.760 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.854 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.760, 3.854, 3.905), stdev = 0.081
  CI (99.9%): [2.369, 5.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  18.778 ms/op
                 createUser·p0.9999: 24.645 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.446 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  22.322 ms/op
                 createUser·p0.9999: 24.337 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.360 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  18.044 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282437
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12049 
    [ 2.500,  5.000) = 263796 
    [ 5.000,  7.500) = 5595 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     26.239 ms/op
     p(99.9990) =     33.396 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.553 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.613 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  16.660 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  14.702 ms/op
                 existUser·p0.9999: 26.058 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293583
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19164 
    [ 2.500,  5.000) = 269261 
    [ 5.000,  7.500) = 4285 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     25.601 ms/op
     p(99.9990) =     26.710 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.539 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 23.677 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.892 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 30.483 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  16.414 ms/op
                 getUser·p0.9999: 25.590 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287798
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7874 
    [ 2.500,  5.000) = 274987 
    [ 5.000,  7.500) = 3855 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     28.876 ms/op
     p(99.9990) =     30.901 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.621 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  18.582 ms/op
                 listUser·p0.9999: 26.979 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 3.923 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.339 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 15.483 ms/op
                 listUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245402
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 237047 
    [ 5.000,  7.500) = 6105 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     24.526 ms/op
     p(99.9990) =     27.248 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.536 ± 3.544  ops/ms
ClientPb.existUser                       thrpt       3   9.985 ± 4.526  ops/ms
ClientPb.getUser                         thrpt       3   9.682 ± 4.085  ops/ms
ClientPb.listUser                        thrpt       3   8.118 ± 3.170  ops/ms
ClientPb.createUser                       avgt       3   3.371 ± 2.499   ms/op
ClientPb.existUser                        avgt       3   3.189 ± 2.167   ms/op
ClientPb.getUser                          avgt       3   3.321 ± 0.697   ms/op
ClientPb.listUser                         avgt       3   3.854 ± 1.485   ms/op
ClientPb.createUser                     sample  282437   3.398 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.774           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.239           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  293583   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.601           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.870           ms/op
ClientPb.getUser                        sample  287798   3.332 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.844           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.876           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  245402   3.909 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.526           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
