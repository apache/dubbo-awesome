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
# Warmup Iteration   1: 1.370 ops/ms
# Warmup Iteration   2: 3.084 ops/ms
# Warmup Iteration   3: 5.900 ops/ms
Iteration   1: 6.886 ops/ms
Iteration   2: 7.091 ops/ms
Iteration   3: 8.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.352 ±(99.9%) 11.630 ops/ms [Average]
  (min, avg, max) = (6.886, 7.352, 8.078), stdev = 0.637
  CI (99.9%): [≈ 0, 18.982] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 6.474 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 7.930 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.146 ±(99.9%) 5.445 ops/ms [Average]
  (min, avg, max) = (7.930, 8.146, 8.486), stdev = 0.298
  CI (99.9%): [2.700, 13.591] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 5.743 ops/ms
# Warmup Iteration   3: 7.168 ops/ms
Iteration   1: 7.671 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 7.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.726 ±(99.9%) 2.651 ops/ms [Average]
  (min, avg, max) = (7.616, 7.726, 7.891), stdev = 0.145
  CI (99.9%): [5.074, 10.377] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 6.576 ops/ms
Iteration   1: 7.009 ops/ms
Iteration   2: 6.419 ops/ms
Iteration   3: 6.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.800 ±(99.9%) 6.022 ops/ms [Average]
  (min, avg, max) = (6.419, 6.800, 7.009), stdev = 0.330
  CI (99.9%): [0.778, 12.821] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 13.290 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.532 ±(99.9%) 0.009 ms/op
Iteration   1: 4.133 ±(99.9%) 0.011 ms/op
Iteration   2: 4.610 ±(99.9%) 0.008 ms/op
Iteration   3: 4.315 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.353 ±(99.9%) 4.386 ms/op [Average]
  (min, avg, max) = (4.133, 4.353, 4.610), stdev = 0.240
  CI (99.9%): [≈ 0, 8.739] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.125 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.006 ms/op
Iteration   1: 4.336 ±(99.9%) 0.006 ms/op
Iteration   2: 3.940 ±(99.9%) 0.005 ms/op
Iteration   3: 3.866 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.048 ±(99.9%) 4.614 ms/op [Average]
  (min, avg, max) = (3.866, 4.048, 4.336), stdev = 0.253
  CI (99.9%): [≈ 0, 8.661] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.879 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.007 ms/op
Iteration   1: 4.437 ±(99.9%) 0.004 ms/op
Iteration   2: 4.104 ±(99.9%) 0.007 ms/op
Iteration   3: 4.408 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.316 ±(99.9%) 3.370 ms/op [Average]
  (min, avg, max) = (4.104, 4.316, 4.437), stdev = 0.185
  CI (99.9%): [0.946, 7.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.934 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.149 ±(99.9%) 0.005 ms/op
Iteration   1: 4.728 ±(99.9%) 0.013 ms/op
Iteration   2: 5.164 ±(99.9%) 0.009 ms/op
Iteration   3: 5.066 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.986 ±(99.9%) 4.169 ms/op [Average]
  (min, avg, max) = (4.728, 4.986, 5.164), stdev = 0.228
  CI (99.9%): [0.817, 9.154] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.234 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 6.345 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.010 ±(99.9%) 0.025 ms/op
Iteration   1: 4.225 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  13.117 ms/op
                 createUser·p0.9999: 31.883 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   2: 3.960 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.730 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  26.453 ms/op
                 createUser·p0.9999: 32.533 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 4.266 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.960 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 40.829 ms/op
                 createUser·p1.00:   41.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231380
  mean =      4.146 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212374 
    [ 5.000, 10.000) = 18146 
    [10.000, 15.000) = 543 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 53 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 89 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     24.891 ms/op
     p(99.9900) =     39.378 ms/op
     p(99.9990) =     41.574 ms/op
     p(99.9999) =     41.615 ms/op
    p(100.0000) =     41.615 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.252 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.868 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.014 ms/op
Iteration   1: 4.335 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   8.733 ms/op
                 existUser·p0.999:  14.641 ms/op
                 existUser·p0.9999: 27.873 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   2: 4.230 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  15.425 ms/op
                 existUser·p0.9999: 30.027 ms/op
                 existUser·p1.00:   31.195 ms/op

Iteration   3: 4.261 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.023 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 32.374 ms/op
                 existUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 224439
  mean =      4.275 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 196472 
    [ 5.000,  7.500) = 23397 
    [ 7.500, 10.000) = 3174 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     14.771 ms/op
     p(99.9900) =     31.133 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.657 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.489 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.015 ms/op
Iteration   1: 4.339 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  15.835 ms/op
                 getUser·p0.9999: 35.669 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   2: 4.251 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  14.358 ms/op
                 getUser·p0.9999: 28.262 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   3: 4.361 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.200 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 29.983 ms/op
                 getUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 222299
  mean =      4.316 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 196552 
    [ 5.000,  7.500) = 19827 
    [ 7.500, 10.000) = 4510 
    [10.000, 12.500) = 852 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     32.990 ms/op
     p(99.9990) =     36.161 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.029 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 5.806 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.196 ±(99.9%) 0.020 ms/op
Iteration   1: 4.924 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  27.662 ms/op
                 listUser·p0.9999: 31.114 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 4.954 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  25.786 ms/op
                 listUser·p0.9999: 29.781 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 4.928 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   10.049 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 29.442 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194300
  mean =      4.935 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 143283 
    [ 5.000,  7.500) = 43762 
    [ 7.500, 10.000) = 5476 
    [10.000, 12.500) = 1105 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 113 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     30.446 ms/op
     p(99.9990) =     31.426 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.352 ± 11.630  ops/ms
ClientPb.existUser                       thrpt       3   8.146 ±  5.445  ops/ms
ClientPb.getUser                         thrpt       3   7.726 ±  2.651  ops/ms
ClientPb.listUser                        thrpt       3   6.800 ±  6.022  ops/ms
ClientPb.createUser                       avgt       3   4.353 ±  4.386   ms/op
ClientPb.existUser                        avgt       3   4.048 ±  4.614   ms/op
ClientPb.getUser                          avgt       3   4.316 ±  3.370   ms/op
ClientPb.listUser                         avgt       3   4.986 ±  4.169   ms/op
ClientPb.createUser                     sample  231380   4.146 ±  0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.426            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.825            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.669            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.380            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.891            ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.378            ms/op
ClientPb.createUser:createUser·p1.00    sample          41.615            ms/op
ClientPb.existUser                      sample  224439   4.275 ±  0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.440            ms/op
ClientPb.existUser:existUser·p0.50      sample           4.002            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.218            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.021            ms/op
ClientPb.existUser:existUser·p0.99      sample           8.552            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.771            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.133            ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899            ms/op
ClientPb.getUser                        sample  222299   4.316 ±  0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.569            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.026            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.153            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.455            ms/op
ClientPb.getUser:getUser·p0.99          sample           9.060            ms/op
ClientPb.getUser:getUser·p0.999         sample          14.729            ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.990            ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438            ms/op
ClientPb.listUser                       sample  194300   4.935 ±  0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.978            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.816            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.004            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814            ms/op
ClientPb.listUser:listUser·p0.999       sample          26.378            ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.446            ms/op
ClientPb.listUser:listUser·p1.00        sample          31.457            ms/op
