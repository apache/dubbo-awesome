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
# Warmup Iteration   1: 5.045 ops/ms
# Warmup Iteration   2: 11.918 ops/ms
# Warmup Iteration   3: 12.240 ops/ms
Iteration   1: 12.340 ops/ms
Iteration   2: 12.358 ops/ms
Iteration   3: 12.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.365 ±(99.9%) 0.520 ops/ms [Average]
  (min, avg, max) = (12.340, 12.365, 12.396), stdev = 0.028
  CI (99.9%): [11.845, 12.885] (assumes normal distribution)


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
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 13.131 ops/ms
# Warmup Iteration   3: 13.203 ops/ms
Iteration   1: 13.208 ops/ms
Iteration   2: 13.273 ops/ms
Iteration   3: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.219 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (13.175, 13.219, 13.273), stdev = 0.050
  CI (99.9%): [12.305, 14.132] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.943 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.745 ops/ms
Iteration   2: 12.797 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.813 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (12.745, 12.813, 12.896), stdev = 0.077
  CI (99.9%): [11.413, 14.213] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.787 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.470 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.540 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (10.477, 10.540, 10.573), stdev = 0.054
  CI (99.9%): [9.552, 11.527] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.487 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (2.471, 2.487, 2.516), stdev = 0.025
  CI (99.9%): [2.026, 2.948] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.417, 2.439, 2.459), stdev = 0.021
  CI (99.9%): [2.058, 2.820] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.003 ms/op
Iteration   2: 2.475 ±(99.9%) 0.003 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.473, 2.478, 2.486), stdev = 0.007
  CI (99.9%): [2.349, 2.607] (assumes normal distribution)


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.968, 2.971, 2.975), stdev = 0.004
  CI (99.9%): [2.901, 3.040] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  10.770 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.845 ms/op
                 createUser·p0.9999: 12.014 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 13.543 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381838
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 184517 
    [ 2.500,  3.750) = 192775 
    [ 3.750,  5.000) = 3516 
    [ 5.000,  6.250) = 457 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.874 ms/op
     p(99.9990) =     14.938 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.465 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.294 ms/op
                 existUser·p0.9999: 12.913 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  5.547 ms/op
                 existUser·p0.9999: 14.844 ms/op
                 existUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387499
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 188332 
    [ 2.500,  3.750) = 196087 
    [ 3.750,  5.000) = 2415 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.410 ms/op
     p(99.9900) =     13.705 ms/op
     p(99.9990) =     14.961 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  8.903 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  9.775 ms/op
                 getUser·p0.9999: 12.812 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  5.805 ms/op
                 getUser·p0.9999: 11.684 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383318
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 189144 
    [ 2.500,  3.750) = 187730 
    [ 3.750,  5.000) = 5138 
    [ 5.000,  6.250) = 778 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     13.774 ms/op
     p(99.9990) =     14.590 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.990 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.362 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.069 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.710 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.298 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313982
  mean =      3.055 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 84800 
    [ 2.500,  3.750) = 186648 
    [ 3.750,  5.000) = 34679 
    [ 5.000,  6.250) = 6168 
    [ 6.250,  7.500) = 869 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 297 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     13.975 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.365 ± 0.520  ops/ms
ClientPb.existUser                       thrpt       3  13.219 ± 0.914  ops/ms
ClientPb.getUser                         thrpt       3  12.813 ± 1.400  ops/ms
ClientPb.listUser                        thrpt       3  10.540 ± 0.987  ops/ms
ClientPb.createUser                       avgt       3   2.487 ± 0.461   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.381   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.129   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.069   ms/op
ClientPb.createUser                     sample  381838   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.690           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.874           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.055           ms/op
ClientPb.existUser                      sample  387499   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.410           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.057           ms/op
ClientPb.getUser                        sample  383318   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.668           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.774           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  313982   3.055 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.237           ms/op
