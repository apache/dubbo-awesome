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
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 3.449 ops/ms
# Warmup Iteration   3: 6.757 ops/ms
Iteration   1: 7.775 ops/ms
Iteration   2: 7.921 ops/ms
Iteration   3: 7.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.864 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (7.775, 7.864, 7.921), stdev = 0.078
  CI (99.9%): [6.445, 9.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.340 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (8.207, 8.340, 8.515), stdev = 0.158
  CI (99.9%): [5.452, 11.228] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 6.705 ops/ms
# Warmup Iteration   3: 7.645 ops/ms
Iteration   1: 7.763 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.939 ±(99.9%) 2.773 ops/ms [Average]
  (min, avg, max) = (7.763, 7.939, 8.035), stdev = 0.152
  CI (99.9%): [5.166, 10.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 5.252 ops/ms
# Warmup Iteration   3: 6.601 ops/ms
Iteration   1: 6.687 ops/ms
Iteration   2: 6.767 ops/ms
Iteration   3: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.692 ±(99.9%) 1.324 ops/ms [Average]
  (min, avg, max) = (6.622, 6.692, 6.767), stdev = 0.073
  CI (99.9%): [5.368, 8.016] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 11.129 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.005 ms/op
Iteration   1: 4.272 ±(99.9%) 0.004 ms/op
Iteration   2: 3.898 ±(99.9%) 0.014 ms/op
Iteration   3: 3.897 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.022 ±(99.9%) 3.950 ms/op [Average]
  (min, avg, max) = (3.897, 4.022, 4.272), stdev = 0.217
  CI (99.9%): [0.072, 7.972] (assumes normal distribution)


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
# Warmup Iteration   1: 12.918 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.895 ±(99.9%) 0.008 ms/op
Iteration   2: 3.870 ±(99.9%) 0.009 ms/op
Iteration   3: 3.846 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.871 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.846, 3.871, 3.895), stdev = 0.025
  CI (99.9%): [3.421, 4.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.688 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.005 ms/op
Iteration   1: 4.137 ±(99.9%) 0.006 ms/op
Iteration   2: 3.804 ±(99.9%) 0.011 ms/op
Iteration   3: 4.033 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.991 ±(99.9%) 3.110 ms/op [Average]
  (min, avg, max) = (3.804, 3.991, 4.137), stdev = 0.170
  CI (99.9%): [0.881, 7.101] (assumes normal distribution)


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
# Warmup Iteration   1: 15.389 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.673 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.006 ms/op
Iteration   1: 4.783 ±(99.9%) 0.008 ms/op
Iteration   2: 4.569 ±(99.9%) 0.016 ms/op
Iteration   3: 4.500 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.617 ±(99.9%) 2.692 ms/op [Average]
  (min, avg, max) = (4.500, 4.617, 4.783), stdev = 0.148
  CI (99.9%): [1.926, 7.309] (assumes normal distribution)


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
# Warmup Iteration   1: 13.134 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.241 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.017 ms/op
Iteration   1: 4.038 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   7.519 ms/op
                 createUser·p0.999:  21.234 ms/op
                 createUser·p0.9999: 25.990 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 3.932 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  23.573 ms/op
                 createUser·p0.9999: 26.112 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 3.921 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  22.344 ms/op
                 createUser·p0.9999: 29.476 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242109
  mean =      3.963 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 229361 
    [ 5.000,  7.500) = 10363 
    [ 7.500, 10.000) = 1144 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     22.268 ms/op
     p(99.9900) =     28.134 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 12.576 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.011 ms/op
Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.833 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  14.830 ms/op
                 existUser·p0.9999: 27.663 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 3.840 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  24.633 ms/op
                 existUser·p0.9999: 32.866 ms/op
                 existUser·p1.00:   33.391 ms/op

Iteration   3: 3.828 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 32.634 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251006
  mean =      3.826 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 857 
    [ 2.500,  5.000) = 238308 
    [ 5.000,  7.500) = 8727 
    [ 7.500, 10.000) = 2438 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     32.496 ms/op
     p(99.9990) =     33.584 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 13.564 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.015 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.929 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 26.280 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 4.118 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   7.754 ms/op
                 getUser·p0.999:  26.378 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   35.455 ms/op

Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.046 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  13.189 ms/op
                 getUser·p0.9999: 28.700 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239477
  mean =      4.008 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 253 
    [ 2.500,  5.000) = 226300 
    [ 5.000,  7.500) = 10629 
    [ 7.500, 10.000) = 1547 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     18.302 ms/op
     p(99.9900) =     33.623 ms/op
     p(99.9990) =     34.984 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 14.871 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.758 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.039 ±(99.9%) 0.017 ms/op
Iteration   1: 4.686 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  25.625 ms/op
                 listUser·p0.9999: 28.542 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 5.007 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  18.957 ms/op
                 listUser·p0.9999: 22.191 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.604 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  15.788 ms/op
                 listUser·p0.9999: 17.668 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201604
  mean =      4.759 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 165120 
    [ 5.000,  7.500) = 31134 
    [ 7.500, 10.000) = 3843 
    [10.000, 12.500) = 766 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     19.936 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     29.521 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.864 ± 1.419  ops/ms
ClientPb.existUser                       thrpt       3   8.340 ± 2.888  ops/ms
ClientPb.getUser                         thrpt       3   7.939 ± 2.773  ops/ms
ClientPb.listUser                        thrpt       3   6.692 ± 1.324  ops/ms
ClientPb.createUser                       avgt       3   4.022 ± 3.950   ms/op
ClientPb.existUser                        avgt       3   3.871 ± 0.449   ms/op
ClientPb.getUser                          avgt       3   3.991 ± 3.110   ms/op
ClientPb.listUser                         avgt       3   4.617 ± 2.692   ms/op
ClientPb.createUser                     sample  242109   3.963 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.229           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  251006   3.826 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.231           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.717           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.762           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  239477   4.008 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.623           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.455           ms/op
ClientPb.listUser                       sample  201604   4.759 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.565           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.936           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.754           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.819           ms/op
