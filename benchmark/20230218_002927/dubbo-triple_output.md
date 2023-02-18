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
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 4.485 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.268 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (8.158, 8.268, 8.460), stdev = 0.167
  CI (99.9%): [5.222, 11.314] (assumes normal distribution)


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
# Warmup Iteration   1: 3.220 ops/ms
# Warmup Iteration   2: 8.232 ops/ms
# Warmup Iteration   3: 8.776 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 8.866 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.108 ±(99.9%) 6.074 ops/ms [Average]
  (min, avg, max) = (8.866, 9.108, 9.488), stdev = 0.333
  CI (99.9%): [3.034, 15.182] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.645 ops/ms
# Warmup Iteration   2: 7.269 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.498 ops/ms
Iteration   2: 8.730 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.671 ±(99.9%) 2.770 ops/ms [Average]
  (min, avg, max) = (8.498, 8.671, 8.784), stdev = 0.152
  CI (99.9%): [5.901, 11.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.271 ops/ms
# Warmup Iteration   2: 6.277 ops/ms
# Warmup Iteration   3: 6.763 ops/ms
Iteration   1: 7.300 ops/ms
Iteration   2: 7.355 ops/ms
Iteration   3: 7.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.244 ±(99.9%) 2.702 ops/ms [Average]
  (min, avg, max) = (7.076, 7.244, 7.355), stdev = 0.148
  CI (99.9%): [4.542, 9.946] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.740 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.695 ±(99.9%) 0.010 ms/op
Iteration   2: 3.667 ±(99.9%) 0.014 ms/op
Iteration   3: 3.627 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.663 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.627, 3.663, 3.695), stdev = 0.034
  CI (99.9%): [3.047, 4.279] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.411 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.003 ms/op
Iteration   1: 3.674 ±(99.9%) 0.008 ms/op
Iteration   2: 3.488 ±(99.9%) 0.003 ms/op
Iteration   3: 3.573 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.578 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (3.488, 3.578, 3.674), stdev = 0.093
  CI (99.9%): [1.879, 5.277] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.131 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.006 ms/op
Iteration   1: 3.890 ±(99.9%) 0.006 ms/op
Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
Iteration   3: 3.711 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.772 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (3.711, 3.772, 3.890), stdev = 0.102
  CI (99.9%): [1.902, 5.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.738 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.657 ±(99.9%) 0.005 ms/op
Iteration   1: 4.611 ±(99.9%) 0.011 ms/op
Iteration   2: 4.563 ±(99.9%) 0.014 ms/op
Iteration   3: 4.614 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.596 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (4.563, 4.596, 4.614), stdev = 0.029
  CI (99.9%): [4.075, 5.117] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.027 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.017 ms/op
Iteration   1: 3.683 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  16.926 ms/op
                 createUser·p0.9999: 31.107 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 3.572 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  25.035 ms/op
                 createUser·p0.9999: 30.212 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   3: 3.791 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  27.298 ms/op
                 createUser·p0.9999: 44.789 ms/op
                 createUser·p1.00:   46.858 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260800
  mean =      3.680 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 252214 
    [ 5.000, 10.000) = 8096 
    [10.000, 15.000) = 138 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 154 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     24.622 ms/op
     p(99.9900) =     41.741 ms/op
     p(99.9990) =     46.568 ms/op
     p(99.9999) =     46.858 ms/op
    p(100.0000) =     46.858 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.297 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
Iteration   1: 3.770 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.505 ms/op
                 existUser·p0.999:  22.544 ms/op
                 existUser·p0.9999: 25.003 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 3.557 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  11.863 ms/op
                 existUser·p0.9999: 29.033 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 3.680 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  25.199 ms/op
                 existUser·p0.9999: 30.287 ms/op
                 existUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 261859
  mean =      3.667 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1637 
    [ 2.500,  5.000) = 252763 
    [ 5.000,  7.500) = 6171 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     17.049 ms/op
     p(99.9900) =     29.092 ms/op
     p(99.9990) =     30.532 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.506 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.014 ms/op
Iteration   1: 3.868 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  15.144 ms/op
                 getUser·p0.9999: 29.350 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  24.347 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 3.712 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.584 ms/op
                 getUser·p0.999:  22.268 ms/op
                 getUser·p0.9999: 33.605 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 252848
  mean =      3.797 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 596 
    [ 2.500,  5.000) = 244678 
    [ 5.000,  7.500) = 5364 
    [ 7.500, 10.000) = 1490 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     21.801 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     34.110 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 12.303 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.635 ±(99.9%) 0.017 ms/op
Iteration   1: 4.654 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  25.378 ms/op
                 listUser·p0.9999: 34.423 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 4.730 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  17.788 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.697 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  17.166 ms/op
                 listUser·p0.9999: 26.816 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204457
  mean =      4.694 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 174339 
    [ 5.000,  7.500) = 25419 
    [ 7.500, 10.000) = 3528 
    [10.000, 12.500) = 592 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.756 ms/op
     p(99.9000) =     18.958 ms/op
     p(99.9900) =     33.136 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.268 ± 3.046  ops/ms
ClientPb.existUser                       thrpt       3   9.108 ± 6.074  ops/ms
ClientPb.getUser                         thrpt       3   8.671 ± 2.770  ops/ms
ClientPb.listUser                        thrpt       3   7.244 ± 2.702  ops/ms
ClientPb.createUser                       avgt       3   3.663 ± 0.616   ms/op
ClientPb.existUser                        avgt       3   3.578 ± 1.699   ms/op
ClientPb.getUser                          avgt       3   3.772 ± 1.870   ms/op
ClientPb.listUser                         avgt       3   4.596 ± 0.521   ms/op
ClientPb.createUser                     sample  260800   3.680 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.622           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.741           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.858           ms/op
ClientPb.existUser                      sample  261859   3.667 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.049           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.092           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.573           ms/op
ClientPb.getUser                        sample  252848   3.797 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.925           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.801           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.047           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  204457   4.694 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.756           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.136           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
