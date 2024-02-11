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
# Warmup Iteration   1: 5.275 ops/ms
# Warmup Iteration   2: 12.116 ops/ms
# Warmup Iteration   3: 12.447 ops/ms
Iteration   1: 12.641 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.611 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (12.568, 12.611, 12.641), stdev = 0.038
  CI (99.9%): [11.912, 13.310] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.242 ops/ms
# Warmup Iteration   2: 13.113 ops/ms
# Warmup Iteration   3: 13.206 ops/ms
Iteration   1: 13.017 ops/ms
Iteration   2: 13.043 ops/ms
Iteration   3: 13.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.048 ±(99.9%) 0.620 ops/ms [Average]
  (min, avg, max) = (13.017, 13.048, 13.084), stdev = 0.034
  CI (99.9%): [12.428, 13.668] (assumes normal distribution)


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
# Warmup Iteration   1: 8.071 ops/ms
# Warmup Iteration   2: 12.653 ops/ms
# Warmup Iteration   3: 12.888 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.927 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (12.850, 12.927, 13.005), stdev = 0.078
  CI (99.9%): [11.506, 14.348] (assumes normal distribution)


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
# Warmup Iteration   1: 6.977 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.705 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.730 ±(99.9%) 0.388 ops/ms [Average]
  (min, avg, max) = (10.705, 10.730, 10.743), stdev = 0.021
  CI (99.9%): [10.342, 11.117] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.499, 2.507, 2.516), stdev = 0.009
  CI (99.9%): [2.351, 2.662] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.432, 2.448, 2.462), stdev = 0.015
  CI (99.9%): [2.171, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.482, 2.494, 2.516), stdev = 0.019
  CI (99.9%): [2.150, 2.839] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.000, 3.011, 3.018), stdev = 0.010
  CI (99.9%): [2.836, 3.186] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.537 ms/op
                 createUser·p0.9999: 16.428 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.089 ms/op
                 createUser·p0.999:  10.235 ms/op
                 createUser·p0.9999: 13.312 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.730 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 11.127 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377512
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 180135 
    [ 2.500,  3.750) = 193075 
    [ 3.750,  5.000) = 3358 
    [ 5.000,  6.250) = 417 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.904 ms/op
     p(99.9900) =     14.578 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  6.839 ms/op
                 existUser·p0.9999: 13.564 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.775 ms/op
                 existUser·p0.9999: 12.860 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 12.810 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392097
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 194119 
    [ 2.500,  3.750) = 194521 
    [ 3.750,  5.000) = 2552 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.020 ms/op
     p(99.9900) =     13.235 ms/op
     p(99.9990) =     14.010 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.739 ms/op
                 getUser·p0.9999: 13.456 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  5.440 ms/op
                 getUser·p0.9999: 13.191 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  6.262 ms/op
                 getUser·p0.9999: 11.290 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387761
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 193179 
    [ 2.500,  3.750) = 190662 
    [ 3.750,  5.000) = 3199 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      6.007 ms/op
     p(99.9900) =     13.062 ms/op
     p(99.9990) =     13.666 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.150 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.772 ms/op
                 listUser·p1.00:   12.517 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.532 ms/op
                 listUser·p0.9999: 12.099 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314856
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 85989 
    [ 2.500,  3.750) = 187974 
    [ 3.750,  5.000) = 33864 
    [ 5.000,  6.250) = 5623 
    [ 6.250,  7.500) = 655 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.505 ms/op
     p(99.9900) =     11.723 ms/op
     p(99.9990) =     12.620 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.611 ± 0.699  ops/ms
ClientPb.existUser                       thrpt       3  13.048 ± 0.620  ops/ms
ClientPb.getUser                         thrpt       3  12.927 ± 1.421  ops/ms
ClientPb.listUser                        thrpt       3  10.730 ± 0.388  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.155   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.277   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.344   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.175   ms/op
ClientPb.createUser                     sample  377512   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.904           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.578           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  392097   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.235           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  387761   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.926           ms/op
ClientPb.listUser                       sample  314856   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.505           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.723           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
