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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 5.440 ops/ms
# Warmup Iteration   3: 8.605 ops/ms
Iteration   1: 8.942 ops/ms
Iteration   2: 8.976 ops/ms
Iteration   3: 9.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.002 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (8.942, 9.002, 9.089), stdev = 0.077
  CI (99.9%): [7.597, 10.407] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 8.556 ops/ms
# Warmup Iteration   3: 9.193 ops/ms
Iteration   1: 9.315 ops/ms
Iteration   2: 9.478 ops/ms
Iteration   3: 9.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.537 ±(99.9%) 4.673 ops/ms [Average]
  (min, avg, max) = (9.315, 9.537, 9.817), stdev = 0.256
  CI (99.9%): [4.864, 14.210] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 8.628 ops/ms
# Warmup Iteration   3: 9.117 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 9.343 ops/ms
Iteration   3: 9.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.262 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (9.060, 9.262, 9.383), stdev = 0.176
  CI (99.9%): [6.054, 12.471] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.627 ops/ms
# Warmup Iteration   2: 7.043 ops/ms
# Warmup Iteration   3: 7.558 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.841 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (7.755, 7.841, 7.929), stdev = 0.087
  CI (99.9%): [6.256, 9.427] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.627 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.007 ms/op
Iteration   1: 3.520 ±(99.9%) 0.005 ms/op
Iteration   2: 3.444 ±(99.9%) 0.006 ms/op
Iteration   3: 3.372 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.372, 3.445, 3.520), stdev = 0.074
  CI (99.9%): [2.102, 4.789] (assumes normal distribution)


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
# Warmup Iteration   1: 8.277 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.004 ms/op
Iteration   1: 3.239 ±(99.9%) 0.008 ms/op
Iteration   2: 3.350 ±(99.9%) 0.005 ms/op
Iteration   3: 3.279 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.289 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.239, 3.289, 3.350), stdev = 0.056
  CI (99.9%): [2.262, 4.317] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.096 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.009 ms/op
Iteration   1: 3.660 ±(99.9%) 0.011 ms/op
Iteration   2: 3.676 ±(99.9%) 0.005 ms/op
Iteration   3: 3.703 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.680 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.660, 3.680, 3.703), stdev = 0.022
  CI (99.9%): [3.280, 4.079] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.066 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.008 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
Iteration   2: 4.004 ±(99.9%) 0.010 ms/op
Iteration   3: 4.141 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (4.004, 4.064, 4.141), stdev = 0.070
  CI (99.9%): [2.779, 5.348] (assumes normal distribution)


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
# Warmup Iteration   1: 10.505 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.013 ms/op
Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  20.108 ms/op
                 createUser·p0.9999: 25.384 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  23.003 ms/op
                 createUser·p0.9999: 25.480 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  21.006 ms/op
                 createUser·p0.9999: 31.171 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278213
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9270 
    [ 2.500,  5.000) = 262666 
    [ 5.000,  7.500) = 5133 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     20.702 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 8.925 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  20.317 ms/op
                 existUser·p0.9999: 24.204 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.250 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  14.405 ms/op
                 existUser·p0.9999: 33.046 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  14.129 ms/op
                 existUser·p0.9999: 26.270 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288457
  mean =      3.327 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11761 
    [ 2.500,  5.000) = 270947 
    [ 5.000,  7.500) = 4680 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.926 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     33.333 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 10.246 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.012 ms/op
Iteration   1: 3.587 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 31.651 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   2: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  21.696 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.110 ms/op
                 getUser·p0.999:  9.430 ms/op
                 getUser·p0.9999: 28.748 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278534
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7577 
    [ 2.500,  5.000) = 262849 
    [ 5.000,  7.500) = 6855 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     32.906 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 9.691 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.015 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 4.099 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.115 ms/op
                 listUser·p0.999:  15.448 ms/op
                 listUser·p0.9999: 17.641 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.820 ms/op
                 listUser·p0.999:  14.745 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242107
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 233401 
    [ 5.000,  7.500) = 6261 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     28.305 ms/op
     p(99.9990) =     30.391 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.002 ± 1.405  ops/ms
ClientPb.existUser                       thrpt       3   9.537 ± 4.673  ops/ms
ClientPb.getUser                         thrpt       3   9.262 ± 3.208  ops/ms
ClientPb.listUser                        thrpt       3   7.841 ± 1.586  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 1.343   ms/op
ClientPb.existUser                        avgt       3   3.289 ± 1.027   ms/op
ClientPb.getUser                          avgt       3   3.680 ± 0.399   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 1.284   ms/op
ClientPb.createUser                     sample  278213   3.449 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.702           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.540           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  288457   3.327 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.276           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  278534   3.445 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.998           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.228           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.932           ms/op
ClientPb.listUser                       sample  242107   3.967 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.182           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.056           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.305           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.900           ms/op
