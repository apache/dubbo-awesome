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
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 3.483 ops/ms
# Warmup Iteration   3: 6.817 ops/ms
Iteration   1: 7.614 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 7.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.884 ±(99.9%) 5.878 ops/ms [Average]
  (min, avg, max) = (7.614, 7.884, 8.240), stdev = 0.322
  CI (99.9%): [2.006, 13.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 6.866 ops/ms
# Warmup Iteration   3: 8.253 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.229 ±(99.9%) 2.956 ops/ms [Average]
  (min, avg, max) = (8.058, 8.229, 8.380), stdev = 0.162
  CI (99.9%): [5.273, 11.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 6.323 ops/ms
# Warmup Iteration   3: 7.542 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.273 ±(99.9%) 5.791 ops/ms [Average]
  (min, avg, max) = (7.937, 8.273, 8.568), stdev = 0.317
  CI (99.9%): [2.482, 14.064] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.050 ops/ms
# Warmup Iteration   2: 5.041 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 6.718 ops/ms
Iteration   2: 6.936 ops/ms
Iteration   3: 7.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.929 ±(99.9%) 3.781 ops/ms [Average]
  (min, avg, max) = (6.718, 6.929, 7.133), stdev = 0.207
  CI (99.9%): [3.149, 10.710] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.289 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.967 ±(99.9%) 0.004 ms/op
Iteration   2: 3.951 ±(99.9%) 0.012 ms/op
Iteration   3: 3.885 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.934 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.885, 3.934, 3.967), stdev = 0.044
  CI (99.9%): [3.135, 4.734] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.900 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.789 ±(99.9%) 0.011 ms/op
Iteration   2: 3.898 ±(99.9%) 0.008 ms/op
Iteration   3: 3.937 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.875 ±(99.9%) 1.393 ms/op [Average]
  (min, avg, max) = (3.789, 3.875, 3.937), stdev = 0.076
  CI (99.9%): [2.482, 5.268] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.229 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.736 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.011 ms/op
Iteration   1: 4.018 ±(99.9%) 0.010 ms/op
Iteration   2: 4.092 ±(99.9%) 0.008 ms/op
Iteration   3: 4.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.037 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (4.001, 4.037, 4.092), stdev = 0.048
  CI (99.9%): [3.157, 4.917] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.353 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.720 ±(99.9%) 0.013 ms/op
Iteration   1: 4.844 ±(99.9%) 0.010 ms/op
Iteration   2: 4.870 ±(99.9%) 0.007 ms/op
Iteration   3: 4.602 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.772 ±(99.9%) 2.697 ms/op [Average]
  (min, avg, max) = (4.602, 4.772, 4.870), stdev = 0.148
  CI (99.9%): [2.075, 7.469] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.820 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.020 ms/op
Iteration   1: 4.208 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.784 ms/op
                 createUser·p0.999:  13.697 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  25.974 ms/op
                 createUser·p0.9999: 29.367 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  18.483 ms/op
                 createUser·p0.9999: 29.590 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234796
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 345 
    [ 2.500,  5.000) = 220547 
    [ 5.000,  7.500) = 11712 
    [ 7.500, 10.000) = 1401 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     19.025 ms/op
     p(99.9900) =     29.279 ms/op
     p(99.9990) =     29.906 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.537 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.864 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  14.127 ms/op
                 existUser·p0.9999: 26.788 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  25.527 ms/op
                 existUser·p0.9999: 28.010 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.508 ms/op
                 existUser·p0.999:  14.497 ms/op
                 existUser·p0.9999: 30.429 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244458
  mean =      3.925 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 233964 
    [ 5.000,  7.500) = 8441 
    [ 7.500, 10.000) = 1169 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 134 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     31.009 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 13.946 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.502 ±(99.9%) 0.019 ms/op
Iteration   1: 4.116 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  23.364 ms/op
                 getUser·p0.9999: 35.666 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  12.501 ms/op
                 getUser·p0.9999: 27.331 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  24.936 ms/op
                 getUser·p0.9999: 27.263 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238578
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 224943 
    [ 5.000,  7.500) = 11009 
    [ 7.500, 10.000) = 1743 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 17.437 ±(99.9%) 0.270 ms/op
# Warmup Iteration   2: 5.968 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.998 ±(99.9%) 0.020 ms/op
Iteration   1: 4.770 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.922 ms/op
                 listUser·p0.999:  27.905 ms/op
                 listUser·p0.9999: 47.514 ms/op
                 listUser·p1.00:   49.152 ms/op

Iteration   2: 4.725 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 30.187 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   3: 4.754 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 24.823 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202216
  mean =      4.750 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 168785 
    [ 5.000, 10.000) = 32348 
    [10.000, 15.000) = 667 
    [15.000, 20.000) = 167 
    [20.000, 25.000) = 91 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     22.858 ms/op
     p(99.9900) =     45.715 ms/op
     p(99.9990) =     49.054 ms/op
     p(99.9999) =     49.152 ms/op
    p(100.0000) =     49.152 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.884 ± 5.878  ops/ms
ClientPb.existUser                       thrpt       3   8.229 ± 2.956  ops/ms
ClientPb.getUser                         thrpt       3   8.273 ± 5.791  ops/ms
ClientPb.listUser                        thrpt       3   6.929 ± 3.781  ops/ms
ClientPb.createUser                       avgt       3   3.934 ± 0.800   ms/op
ClientPb.existUser                        avgt       3   3.875 ± 1.393   ms/op
ClientPb.getUser                          avgt       3   4.037 ± 0.880   ms/op
ClientPb.listUser                         avgt       3   4.772 ± 2.697   ms/op
ClientPb.createUser                     sample  234796   4.087 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.381           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.025           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.279           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  244458   3.925 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.878           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.098           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  238578   4.021 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.323           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.970           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  202216   4.750 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.858           ms/op
ClientPb.listUser:listUser·p0.9999      sample          45.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          49.152           ms/op
