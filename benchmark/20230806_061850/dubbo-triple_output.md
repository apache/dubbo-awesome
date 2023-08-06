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
# Warmup Iteration   1: 1.137 ops/ms
# Warmup Iteration   2: 2.493 ops/ms
# Warmup Iteration   3: 5.400 ops/ms
Iteration   1: 5.639 ops/ms
Iteration   2: 5.613 ops/ms
Iteration   3: 5.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.743 ±(99.9%) 3.689 ops/ms [Average]
  (min, avg, max) = (5.613, 5.743, 5.976), stdev = 0.202
  CI (99.9%): [2.053, 9.432] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 5.024 ops/ms
# Warmup Iteration   3: 6.086 ops/ms
Iteration   1: 6.158 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.168 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (6.102, 6.168, 6.242), stdev = 0.070
  CI (99.9%): [4.883, 7.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.692 ops/ms
# Warmup Iteration   2: 4.636 ops/ms
# Warmup Iteration   3: 5.736 ops/ms
Iteration   1: 5.877 ops/ms
Iteration   2: 5.733 ops/ms
Iteration   3: 5.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.822 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (5.733, 5.822, 5.877), stdev = 0.078
  CI (99.9%): [4.398, 7.247] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.475 ops/ms
# Warmup Iteration   2: 3.740 ops/ms
# Warmup Iteration   3: 4.662 ops/ms
Iteration   1: 4.976 ops/ms
Iteration   2: 4.889 ops/ms
Iteration   3: 4.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.903 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (4.843, 4.903, 4.976), stdev = 0.068
  CI (99.9%): [3.664, 6.141] (assumes normal distribution)


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
# Warmup Iteration   1: 18.008 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.983 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.943 ±(99.9%) 0.009 ms/op
Iteration   1: 5.872 ±(99.9%) 0.012 ms/op
Iteration   2: 5.631 ±(99.9%) 0.017 ms/op
Iteration   3: 5.676 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.726 ±(99.9%) 2.330 ms/op [Average]
  (min, avg, max) = (5.631, 5.726, 5.872), stdev = 0.128
  CI (99.9%): [3.396, 8.057] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.022 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.137 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.181 ±(99.9%) 0.012 ms/op
Iteration   1: 5.247 ±(99.9%) 0.007 ms/op
Iteration   2: 5.312 ±(99.9%) 0.007 ms/op
Iteration   3: 5.309 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.289 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (5.247, 5.289, 5.312), stdev = 0.037
  CI (99.9%): [4.623, 5.956] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 19.498 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.499 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.008 ms/op
Iteration   1: 5.617 ±(99.9%) 0.006 ms/op
Iteration   2: 5.679 ±(99.9%) 0.007 ms/op
Iteration   3: 5.727 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.674 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (5.617, 5.674, 5.727), stdev = 0.055
  CI (99.9%): [4.673, 6.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.904 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.131 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.905 ±(99.9%) 0.012 ms/op
Iteration   1: 6.611 ±(99.9%) 0.015 ms/op
Iteration   2: 6.423 ±(99.9%) 0.013 ms/op
Iteration   3: 6.286 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.440 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (6.286, 6.440, 6.611), stdev = 0.163
  CI (99.9%): [3.462, 9.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.664 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.918 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.913 ±(99.9%) 0.028 ms/op
Iteration   1: 5.993 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   8.266 ms/op
                 createUser·p0.95:   9.552 ms/op
                 createUser·p0.99:   12.534 ms/op
                 createUser·p0.999:  25.613 ms/op
                 createUser·p0.9999: 28.311 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   2: 5.694 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.560 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  26.595 ms/op
                 createUser·p0.9999: 29.549 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 5.363 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.975 ms/op
                 createUser·p0.999:  29.385 ms/op
                 createUser·p0.9999: 31.917 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169162
  mean =      5.672 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 54284 
    [ 5.000,  7.500) = 100159 
    [ 7.500, 10.000) = 10438 
    [10.000, 12.500) = 2952 
    [12.500, 15.000) = 846 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     30.720 ms/op
     p(99.9990) =     32.221 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 15.453 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 5.808 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.342 ±(99.9%) 0.018 ms/op
Iteration   1: 5.274 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.944 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.979 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  19.357 ms/op
                 existUser·p0.9999: 26.376 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 5.220 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.191 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.113 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 25.125 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 5.185 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.482 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  14.680 ms/op
                 existUser·p0.9999: 29.158 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183613
  mean =      5.226 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 100085 
    [ 5.000,  7.500) = 75267 
    [ 7.500, 10.000) = 5981 
    [10.000, 12.500) = 1658 
    [12.500, 15.000) = 355 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     16.282 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     30.036 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 17.366 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.988 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.025 ms/op
Iteration   1: 5.768 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.315 ms/op
                 getUser·p0.95:   9.244 ms/op
                 getUser·p0.99:   13.074 ms/op
                 getUser·p0.999:  20.363 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 5.703 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.793 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.622 ms/op
                 getUser·p0.999:  28.705 ms/op
                 getUser·p0.9999: 29.707 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 5.464 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.668 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  31.949 ms/op
                 getUser·p0.9999: 36.045 ms/op
                 getUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169959
  mean =      5.642 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 52830 
    [ 5.000,  7.500) = 104736 
    [ 7.500, 10.000) = 8802 
    [10.000, 12.500) = 2261 
    [12.500, 15.000) = 860 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     35.259 ms/op
     p(99.9990) =     36.871 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 18.599 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 8.520 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.918 ±(99.9%) 0.034 ms/op
Iteration   1: 6.786 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   10.174 ms/op
                 listUser·p0.99:   13.615 ms/op
                 listUser·p0.999:  30.564 ms/op
                 listUser·p0.9999: 32.245 ms/op
                 listUser·p1.00:   37.028 ms/op

Iteration   2: 6.541 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.240 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  28.803 ms/op
                 listUser·p0.9999: 32.091 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 6.630 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   12.943 ms/op
                 listUser·p0.999:  26.270 ms/op
                 listUser·p0.9999: 34.800 ms/op
                 listUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144290
  mean =      6.651 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 3442 
    [ 5.000,  7.500) = 120629 
    [ 7.500, 10.000) = 14244 
    [10.000, 12.500) = 4102 
    [12.500, 15.000) = 1151 
    [15.000, 17.500) = 300 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 80 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      6.259 ms/op
     p(90.0000) =      7.971 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     13.271 ms/op
     p(99.9000) =     28.836 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     36.418 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.743 ± 3.689  ops/ms
ClientPb.existUser                       thrpt       3   6.168 ± 1.284  ops/ms
ClientPb.getUser                         thrpt       3   5.822 ± 1.425  ops/ms
ClientPb.listUser                        thrpt       3   4.903 ± 1.239  ops/ms
ClientPb.createUser                       avgt       3   5.726 ± 2.330   ms/op
ClientPb.existUser                        avgt       3   5.289 ± 0.666   ms/op
ClientPb.getUser                          avgt       3   5.674 ± 1.001   ms/op
ClientPb.listUser                         avgt       3   6.440 ± 2.978   ms/op
ClientPb.createUser                     sample  169162   5.672 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.444           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.720           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.244           ms/op
ClientPb.existUser                      sample  183613   5.226 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.324           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.282           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.310           ms/op
ClientPb.getUser                        sample  169959   5.642 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.960           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.247           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.421           ms/op
ClientPb.listUser                       sample  144290   6.651 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.259           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.271           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.836           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.028           ms/op
