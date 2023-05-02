# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.803 ops/ms
# Warmup Iteration   2: 4.254 ops/ms
# Warmup Iteration   3: 7.261 ops/ms
Iteration   1: 7.534 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.979 ±(99.9%) 7.367 ops/ms [Average]
  (min, avg, max) = (7.534, 7.979, 8.321), stdev = 0.404
  CI (99.9%): [0.612, 15.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 7.509 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 8.538 ops/ms
Iteration   2: 8.207 ops/ms
Iteration   3: 8.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.500 ±(99.9%) 5.043 ops/ms [Average]
  (min, avg, max) = (8.207, 8.500, 8.756), stdev = 0.276
  CI (99.9%): [3.457, 13.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 6.501 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 7.635 ops/ms
Iteration   2: 7.871 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.904 ±(99.9%) 5.243 ops/ms [Average]
  (min, avg, max) = (7.635, 7.904, 8.207), stdev = 0.287
  CI (99.9%): [2.662, 13.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 6.608 ops/ms
Iteration   1: 6.887 ops/ms
Iteration   2: 7.145 ops/ms
Iteration   3: 6.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.976 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (6.887, 6.976, 7.145), stdev = 0.146
  CI (99.9%): [4.313, 9.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.548 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.891 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.013 ms/op
Iteration   1: 3.884 ±(99.9%) 0.007 ms/op
Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
Iteration   3: 3.890 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.892 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.884, 3.892, 3.903), stdev = 0.010
  CI (99.9%): [3.718, 4.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.289 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.008 ms/op
Iteration   1: 3.759 ±(99.9%) 0.007 ms/op
Iteration   2: 3.827 ±(99.9%) 0.009 ms/op
Iteration   3: 3.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.812 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.759, 3.812, 3.850), stdev = 0.047
  CI (99.9%): [2.948, 4.676] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.384 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.005 ms/op
Iteration   1: 3.921 ±(99.9%) 0.007 ms/op
Iteration   2: 3.962 ±(99.9%) 0.007 ms/op
Iteration   3: 3.832 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.905 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (3.832, 3.905, 3.962), stdev = 0.067
  CI (99.9%): [2.687, 5.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.587 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.013 ms/op
Iteration   1: 4.619 ±(99.9%) 0.015 ms/op
Iteration   2: 4.657 ±(99.9%) 0.008 ms/op
Iteration   3: 4.496 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.591 ±(99.9%) 1.541 ms/op [Average]
  (min, avg, max) = (4.496, 4.591, 4.657), stdev = 0.084
  CI (99.9%): [3.050, 6.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.290 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.016 ms/op
Iteration   1: 3.863 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  23.090 ms/op
                 createUser·p0.9999: 25.943 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.329 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 26.615 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.909 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  28.493 ms/op
                 createUser·p0.9999: 31.806 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246551
  mean =      3.890 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 249 
    [ 2.500,  5.000) = 236913 
    [ 5.000,  7.500) = 7652 
    [ 7.500, 10.000) = 1027 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     24.427 ms/op
     p(99.9900) =     30.780 ms/op
     p(99.9990) =     32.999 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.620 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  22.000 ms/op
                 existUser·p0.9999: 24.541 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.761 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 26.067 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.813 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  24.433 ms/op
                 existUser·p0.9999: 28.450 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254294
  mean =      3.774 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 246448 
    [ 5.000,  7.500) = 6094 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     21.193 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.864 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
Iteration   1: 4.023 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  24.394 ms/op
                 getUser·p0.9999: 29.660 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 3.844 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  9.663 ms/op
                 getUser·p0.9999: 26.772 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  26.336 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246387
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 235578 
    [ 5.000,  7.500) = 9130 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     30.809 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.700 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.018 ms/op
Iteration   1: 4.708 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  24.428 ms/op
                 listUser·p0.9999: 29.367 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 4.610 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.705 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205230
  mean =      4.674 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 173306 
    [ 5.000,  7.500) = 27575 
    [ 7.500, 10.000) = 3484 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.457 ms/op
     p(99.9900) =     27.246 ms/op
     p(99.9990) =     29.683 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.979 ± 7.367  ops/ms
ClientPb.existUser                       thrpt       3   8.500 ± 5.043  ops/ms
ClientPb.getUser                         thrpt       3   7.904 ± 5.243  ops/ms
ClientPb.listUser                        thrpt       3   6.976 ± 2.663  ops/ms
ClientPb.createUser                       avgt       3   3.892 ± 0.174   ms/op
ClientPb.existUser                        avgt       3   3.812 ± 0.864   ms/op
ClientPb.getUser                          avgt       3   3.905 ± 1.218   ms/op
ClientPb.listUser                         avgt       3   4.591 ± 1.541   ms/op
ClientPb.createUser                     sample  246551   3.890 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.743           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.427           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  254294   3.774 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.608           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.193           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.903           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  246387   3.894 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  205230   4.674 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.457           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.246           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.688           ms/op
