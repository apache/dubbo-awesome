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
# Warmup Iteration   1: 4.524 ops/ms
# Warmup Iteration   2: 11.555 ops/ms
# Warmup Iteration   3: 12.152 ops/ms
Iteration   1: 12.301 ops/ms
Iteration   2: 12.464 ops/ms
Iteration   3: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.371 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (12.301, 12.371, 12.464), stdev = 0.084
  CI (99.9%): [10.834, 13.908] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.337 ops/ms
# Warmup Iteration   2: 13.035 ops/ms
# Warmup Iteration   3: 12.900 ops/ms
Iteration   1: 12.857 ops/ms
Iteration   2: 13.003 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.974 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (12.857, 12.974, 13.064), stdev = 0.106
  CI (99.9%): [11.037, 14.911] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ops/ms
# Warmup Iteration   2: 12.414 ops/ms
# Warmup Iteration   3: 12.762 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 12.809 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.812 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (12.734, 12.812, 12.892), stdev = 0.079
  CI (99.9%): [11.365, 14.258] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.407 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.562 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.531 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (10.488, 10.531, 10.562), stdev = 0.039
  CI (99.9%): [9.825, 11.238] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.513, 2.534, 2.551), stdev = 0.020
  CI (99.9%): [2.174, 2.895] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.006 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.455, 2.461, 2.473), stdev = 0.010
  CI (99.9%): [2.279, 2.643] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.489, 2.492, 2.494), stdev = 0.003
  CI (99.9%): [2.443, 2.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.007, 3.019, 3.026), stdev = 0.011
  CI (99.9%): [2.825, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.727 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  11.603 ms/op
                 createUser·p0.9999: 18.723 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.728 ms/op
                 createUser·p0.9999: 13.320 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.337 ms/op
                 createUser·p0.9999: 11.187 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380804
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 182889 
    [ 2.500,  3.750) = 193197 
    [ 3.750,  5.000) = 3630 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.513 ms/op
     p(99.9900) =     13.860 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  7.484 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.800 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  8.292 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390121
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 191553 
    [ 2.500,  3.750) = 195329 
    [ 3.750,  5.000) = 2519 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.937 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.259 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  8.315 ms/op
                 getUser·p0.9999: 12.352 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  7.940 ms/op
                 getUser·p0.9999: 11.476 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381628
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187980 
    [ 2.500,  3.750) = 188362 
    [ 3.750,  5.000) = 3551 
    [ 5.000,  6.250) = 1089 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.001 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  8.823 ms/op
                 listUser·p0.9999: 10.604 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.383 ms/op
                 listUser·p0.9999: 13.294 ms/op
                 listUser·p1.00:   14.090 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.706 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315293
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 84634 
    [ 2.500,  3.750) = 189641 
    [ 3.750,  5.000) = 33423 
    [ 5.000,  6.250) = 6069 
    [ 6.250,  7.500) = 752 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     12.132 ms/op
     p(99.9990) =     13.949 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.371 ± 1.537  ops/ms
ClientPb.existUser                       thrpt       3  12.974 ± 1.937  ops/ms
ClientPb.getUser                         thrpt       3  12.812 ± 1.446  ops/ms
ClientPb.listUser                        thrpt       3  10.531 ± 0.706  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.360   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.182   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.049   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.194   ms/op
ClientPb.createUser                     sample  380804   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.860           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.842           ms/op
ClientPb.existUser                      sample  390121   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.963           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.937           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  381628   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.889           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.001           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  315293   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.090           ms/op
