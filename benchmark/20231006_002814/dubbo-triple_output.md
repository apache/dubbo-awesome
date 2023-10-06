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
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 4.595 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.888 ops/ms
Iteration   3: 8.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.803 ±(99.9%) 4.398 ops/ms [Average]
  (min, avg, max) = (8.531, 8.803, 8.990), stdev = 0.241
  CI (99.9%): [4.405, 13.201] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.516 ops/ms
# Warmup Iteration   2: 8.092 ops/ms
# Warmup Iteration   3: 9.029 ops/ms
Iteration   1: 9.122 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.120 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (8.995, 9.120, 9.241), stdev = 0.123
  CI (99.9%): [6.878, 11.361] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 8.342 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 8.960 ops/ms
Iteration   3: 8.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.838 ±(99.9%) 2.103 ops/ms [Average]
  (min, avg, max) = (8.731, 8.838, 8.960), stdev = 0.115
  CI (99.9%): [6.735, 10.941] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 6.297 ops/ms
# Warmup Iteration   3: 7.408 ops/ms
Iteration   1: 7.279 ops/ms
Iteration   2: 7.495 ops/ms
Iteration   3: 7.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.417 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (7.279, 7.417, 7.495), stdev = 0.120
  CI (99.9%): [5.233, 9.602] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.927 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.004 ms/op
Iteration   1: 3.604 ±(99.9%) 0.005 ms/op
Iteration   2: 3.673 ±(99.9%) 0.006 ms/op
Iteration   3: 3.610 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.629 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.604, 3.629, 3.673), stdev = 0.038
  CI (99.9%): [2.937, 4.321] (assumes normal distribution)


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
# Warmup Iteration   1: 11.698 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.003 ms/op
Iteration   1: 3.542 ±(99.9%) 0.004 ms/op
Iteration   2: 3.454 ±(99.9%) 0.003 ms/op
Iteration   3: 3.414 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.470 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.414, 3.470, 3.542), stdev = 0.065
  CI (99.9%): [2.281, 4.660] (assumes normal distribution)


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
# Warmup Iteration   1: 10.891 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.006 ms/op
Iteration   1: 3.580 ±(99.9%) 0.006 ms/op
Iteration   2: 3.623 ±(99.9%) 0.008 ms/op
Iteration   3: 3.652 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.619 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.580, 3.619, 3.652), stdev = 0.036
  CI (99.9%): [2.956, 4.281] (assumes normal distribution)


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
# Warmup Iteration   1: 13.324 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.007 ms/op
Iteration   1: 4.406 ±(99.9%) 0.007 ms/op
Iteration   2: 4.250 ±(99.9%) 0.009 ms/op
Iteration   3: 4.244 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.300 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (4.244, 4.300, 4.406), stdev = 0.092
  CI (99.9%): [2.620, 5.981] (assumes normal distribution)


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
# Warmup Iteration   1: 12.142 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.015 ms/op
Iteration   1: 3.608 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  22.496 ms/op
                 createUser·p0.9999: 34.751 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   2: 3.588 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  24.084 ms/op
                 createUser·p0.9999: 26.849 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267349
  mean =      3.591 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4089 
    [ 2.500,  5.000) = 253285 
    [ 5.000,  7.500) = 7580 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     22.271 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     35.214 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.794 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.010 ms/op
Iteration   1: 3.529 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  20.294 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.768 ms/op
                 existUser·p0.999:  21.916 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  14.829 ms/op
                 existUser·p0.9999: 27.485 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276169
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4931 
    [ 2.500,  5.000) = 261950 
    [ 5.000,  7.500) = 7376 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     26.063 ms/op
     p(99.9990) =     27.992 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 10.042 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.016 ms/op
Iteration   1: 3.772 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  19.997 ms/op
                 getUser·p0.9999: 26.806 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.630 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  21.190 ms/op
                 getUser·p0.9999: 26.121 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.578 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 28.086 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262304
  mean =      3.658 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1448 
    [ 2.500,  5.000) = 249590 
    [ 5.000,  7.500) = 8080 
    [ 7.500, 10.000) = 2493 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     21.125 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.893 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 13.842 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.297 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.015 ms/op
Iteration   1: 4.333 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  22.717 ms/op
                 listUser·p0.9999: 28.627 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 4.337 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  17.703 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 4.208 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  16.055 ms/op
                 listUser·p0.9999: 19.367 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223647
  mean =      4.292 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 212142 
    [ 5.000,  7.500) = 7294 
    [ 7.500, 10.000) = 3041 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     25.970 ms/op
     p(99.9990) =     29.221 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.803 ± 4.398  ops/ms
ClientPb.existUser                       thrpt       3   9.120 ± 2.242  ops/ms
ClientPb.getUser                         thrpt       3   8.838 ± 2.103  ops/ms
ClientPb.listUser                        thrpt       3   7.417 ± 2.184  ops/ms
ClientPb.createUser                       avgt       3   3.629 ± 0.692   ms/op
ClientPb.existUser                        avgt       3   3.470 ± 1.190   ms/op
ClientPb.getUser                          avgt       3   3.619 ± 0.662   ms/op
ClientPb.listUser                         avgt       3   4.300 ± 1.681   ms/op
ClientPb.createUser                     sample  267349   3.591 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.738           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.271           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.524           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.389           ms/op
ClientPb.existUser                      sample  276169   3.475 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.171           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.063           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  262304   3.658 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.432           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.125           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.066           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  223647   4.292 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.970           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
