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
# Warmup Iteration   1: 5.266 ops/ms
# Warmup Iteration   2: 11.934 ops/ms
# Warmup Iteration   3: 12.355 ops/ms
Iteration   1: 12.516 ops/ms
Iteration   2: 12.583 ops/ms
Iteration   3: 12.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.590 ±(99.9%) 1.424 ops/ms [Average]
  (min, avg, max) = (12.516, 12.590, 12.671), stdev = 0.078
  CI (99.9%): [11.166, 14.014] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.030 ops/ms
# Warmup Iteration   2: 12.870 ops/ms
# Warmup Iteration   3: 13.016 ops/ms
Iteration   1: 12.826 ops/ms
Iteration   2: 12.881 ops/ms
Iteration   3: 12.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.887 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (12.826, 12.887, 12.955), stdev = 0.065
  CI (99.9%): [11.705, 14.070] (assumes normal distribution)


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
# Warmup Iteration   1: 8.140 ops/ms
# Warmup Iteration   2: 12.345 ops/ms
# Warmup Iteration   3: 12.535 ops/ms
Iteration   1: 12.675 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.677 ±(99.9%) 0.101 ops/ms [Average]
  (min, avg, max) = (12.673, 12.677, 12.684), stdev = 0.006
  CI (99.9%): [12.576, 12.779] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.698 ops/ms
# Warmup Iteration   2: 10.339 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.373 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.385 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (10.373, 10.385, 10.395), stdev = 0.011
  CI (99.9%): [10.176, 10.593] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.515, 2.536, 2.553), stdev = 0.019
  CI (99.9%): [2.184, 2.887] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.440, 2.456, 2.475), stdev = 0.018
  CI (99.9%): [2.135, 2.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.495, 2.517, 2.531), stdev = 0.019
  CI (99.9%): [2.165, 2.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.912 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.005 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.079 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.069, 3.079, 3.090), stdev = 0.011
  CI (99.9%): [2.882, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.758 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.862 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 13.765 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.489 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   3: 2.600 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.222 ms/op
                 createUser·p0.999:  8.111 ms/op
                 createUser·p0.9999: 10.974 ms/op
                 createUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370233
  mean =      2.591 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 173165 
    [ 2.500,  3.750) = 190634 
    [ 3.750,  5.000) = 4894 
    [ 5.000,  6.250) = 917 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.477 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.460 ms/op
                 existUser·p0.9999: 12.509 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  7.587 ms/op
                 existUser·p0.9999: 19.766 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386731
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190282 
    [ 2.500,  5.000) = 195703 
    [ 5.000,  7.500) = 382 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.303 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     20.194 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  11.736 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.644 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  7.890 ms/op
                 getUser·p0.9999: 10.780 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378345
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 184946 
    [ 2.500,  3.750) = 187301 
    [ 3.750,  5.000) = 4512 
    [ 5.000,  6.250) = 1094 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.027 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 11.126 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.655 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  9.450 ms/op
                 listUser·p0.9999: 11.746 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313329
  mean =      3.061 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 86787 
    [ 2.500,  3.750) = 181384 
    [ 3.750,  5.000) = 35685 
    [ 5.000,  6.250) = 7724 
    [ 6.250,  7.500) = 996 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     12.056 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.590 ± 1.424  ops/ms
ClientPb.existUser                       thrpt       3  12.887 ± 1.182  ops/ms
ClientPb.getUser                         thrpt       3  12.677 ± 0.101  ops/ms
ClientPb.listUser                        thrpt       3  10.385 ± 0.209  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.351   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.322   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.351   ms/op
ClientPb.listUser                         avgt       3   3.079 ± 0.197   ms/op
ClientPb.createUser                     sample  370233   2.591 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.269           ms/op
ClientPb.existUser                      sample  386731   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.943           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.382           ms/op
ClientPb.getUser                        sample  378345   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.552           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  313329   3.061 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.124           ms/op
