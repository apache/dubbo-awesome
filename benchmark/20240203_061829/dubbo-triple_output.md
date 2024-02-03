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
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 12.320 ops/ms
# Warmup Iteration   3: 12.591 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.985 ops/ms
Iteration   3: 12.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.922 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (12.783, 12.922, 12.997), stdev = 0.120
  CI (99.9%): [10.730, 15.113] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.537 ops/ms
# Warmup Iteration   2: 13.439 ops/ms
# Warmup Iteration   3: 13.489 ops/ms
Iteration   1: 13.572 ops/ms
Iteration   2: 13.475 ops/ms
Iteration   3: 13.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.479 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (13.391, 13.479, 13.572), stdev = 0.091
  CI (99.9%): [11.826, 15.133] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.993 ops/ms
# Warmup Iteration   2: 12.795 ops/ms
# Warmup Iteration   3: 12.985 ops/ms
Iteration   1: 13.101 ops/ms
Iteration   2: 13.080 ops/ms
Iteration   3: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.088 ±(99.9%) 0.205 ops/ms [Average]
  (min, avg, max) = (13.080, 13.088, 13.101), stdev = 0.011
  CI (99.9%): [12.883, 13.292] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.781 ops/ms
# Warmup Iteration   2: 10.606 ops/ms
# Warmup Iteration   3: 10.803 ops/ms
Iteration   1: 10.902 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.837 ±(99.9%) 1.752 ops/ms [Average]
  (min, avg, max) = (10.727, 10.837, 10.902), stdev = 0.096
  CI (99.9%): [9.085, 12.589] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.477, 2.501, 2.537), stdev = 0.032
  CI (99.9%): [1.925, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.396 ±(99.9%) 0.004 ms/op
Iteration   1: 2.421 ±(99.9%) 0.004 ms/op
Iteration   2: 2.401 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.404 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.389, 2.404, 2.421), stdev = 0.016
  CI (99.9%): [2.106, 2.702] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.457, 2.462, 2.464), stdev = 0.004
  CI (99.9%): [2.389, 2.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.939 ±(99.9%) 0.005 ms/op
Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
Iteration   3: 2.933 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.935 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.933, 2.935, 2.939), stdev = 0.003
  CI (99.9%): [2.875, 2.995] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  7.604 ms/op
                 createUser·p0.9999: 14.189 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 12.370 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.845 ms/op
                 createUser·p0.999:  8.332 ms/op
                 createUser·p0.9999: 9.685 ms/op
                 createUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387259
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 189556 
    [ 2.500,  3.750) = 193884 
    [ 3.750,  5.000) = 2901 
    [ 5.000,  6.250) = 349 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 155 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.597 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.381 ±(99.9%) 0.005 ms/op
Iteration   1: 2.382 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  4.938 ms/op
                 existUser·p0.9999: 12.904 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  6.561 ms/op
                 existUser·p0.9999: 13.952 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  8.218 ms/op
                 existUser·p0.9999: 11.698 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401613
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 205475 
    [ 2.500,  3.750) = 193580 
    [ 3.750,  5.000) = 1808 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.485 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     13.285 ms/op
     p(99.9990) =     14.237 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  5.987 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.532 ms/op
                 getUser·p0.9999: 13.520 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  6.400 ms/op
                 getUser·p0.9999: 10.940 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389996
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 196824 
    [ 2.500,  3.750) = 188434 
    [ 3.750,  5.000) = 3679 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     13.666 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.922 ms/op
                 listUser·p0.9999: 11.503 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.761 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.037 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320582
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 93733 
    [ 2.500,  3.750) = 188792 
    [ 3.750,  5.000) = 31375 
    [ 5.000,  6.250) = 5437 
    [ 6.250,  7.500) = 510 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 296 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.789 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.922 ± 2.191  ops/ms
ClientPb.existUser                       thrpt       3  13.479 ± 1.653  ops/ms
ClientPb.getUser                         thrpt       3  13.088 ± 0.205  ops/ms
ClientPb.listUser                        thrpt       3  10.837 ± 1.752  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.576   ms/op
ClientPb.existUser                        avgt       3   2.404 ± 0.298   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.072   ms/op
ClientPb.listUser                         avgt       3   2.935 ± 0.060   ms/op
ClientPb.createUser                     sample  387259   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.597           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  401613   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.485           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.285           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  389996   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.466           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.832           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.779           ms/op
ClientPb.listUser                       sample  320582   2.992 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.723           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
