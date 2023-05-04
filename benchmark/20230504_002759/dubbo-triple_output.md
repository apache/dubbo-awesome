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
# Warmup Iteration   1: 1.436 ops/ms
# Warmup Iteration   2: 3.114 ops/ms
# Warmup Iteration   3: 5.820 ops/ms
Iteration   1: 7.415 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 8.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.862 ±(99.9%) 7.405 ops/ms [Average]
  (min, avg, max) = (7.415, 7.862, 8.206), stdev = 0.406
  CI (99.9%): [0.458, 15.267] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.838 ops/ms
# Warmup Iteration   2: 5.206 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 8.244 ops/ms
Iteration   2: 8.283 ops/ms
Iteration   3: 8.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.369 ±(99.9%) 3.330 ops/ms [Average]
  (min, avg, max) = (8.244, 8.369, 8.578), stdev = 0.183
  CI (99.9%): [5.038, 11.699] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 6.400 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.846 ops/ms
Iteration   2: 8.244 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.993 ±(99.9%) 3.986 ops/ms [Average]
  (min, avg, max) = (7.846, 7.993, 8.244), stdev = 0.218
  CI (99.9%): [4.008, 11.979] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 5.214 ops/ms
# Warmup Iteration   3: 6.592 ops/ms
Iteration   1: 6.876 ops/ms
Iteration   2: 7.161 ops/ms
Iteration   3: 6.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.995 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (6.876, 6.995, 7.161), stdev = 0.148
  CI (99.9%): [4.296, 9.694] (assumes normal distribution)


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
# Warmup Iteration   1: 13.852 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.004 ms/op
Iteration   1: 3.918 ±(99.9%) 0.008 ms/op
Iteration   2: 3.850 ±(99.9%) 0.007 ms/op
Iteration   3: 3.803 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.857 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.803, 3.857, 3.918), stdev = 0.058
  CI (99.9%): [2.806, 4.908] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.715 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.008 ms/op
Iteration   1: 3.968 ±(99.9%) 0.004 ms/op
Iteration   2: 3.828 ±(99.9%) 0.005 ms/op
Iteration   3: 4.074 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.957 ±(99.9%) 2.243 ms/op [Average]
  (min, avg, max) = (3.828, 3.957, 4.074), stdev = 0.123
  CI (99.9%): [1.713, 6.200] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.971 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.008 ms/op
Iteration   1: 4.250 ±(99.9%) 0.009 ms/op
Iteration   2: 4.229 ±(99.9%) 0.006 ms/op
Iteration   3: 4.134 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.204 ±(99.9%) 1.124 ms/op [Average]
  (min, avg, max) = (4.134, 4.204, 4.250), stdev = 0.062
  CI (99.9%): [3.080, 5.328] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.933 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.767 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.636 ±(99.9%) 0.011 ms/op
Iteration   1: 4.671 ±(99.9%) 0.012 ms/op
Iteration   2: 5.016 ±(99.9%) 0.010 ms/op
Iteration   3: 4.897 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.861 ±(99.9%) 3.191 ms/op [Average]
  (min, avg, max) = (4.671, 4.861, 5.016), stdev = 0.175
  CI (99.9%): [1.670, 8.052] (assumes normal distribution)


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
# Warmup Iteration   1: 14.229 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.217 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.018 ms/op
Iteration   1: 4.267 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   6.160 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  24.083 ms/op
                 createUser·p0.9999: 28.262 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   2: 3.982 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  15.592 ms/op
                 createUser·p0.9999: 30.080 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 3.907 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  28.738 ms/op
                 createUser·p0.9999: 34.924 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237346
  mean =      4.046 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 435 
    [ 2.500,  5.000) = 219875 
    [ 5.000,  7.500) = 14118 
    [ 7.500, 10.000) = 2219 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     23.975 ms/op
     p(99.9900) =     33.408 ms/op
     p(99.9990) =     35.693 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 11.264 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.343 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  26.161 ms/op
                 existUser·p0.9999: 29.715 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 3.652 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.171 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  14.696 ms/op
                 existUser·p0.9999: 30.515 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   3: 3.721 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.964 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  27.429 ms/op
                 existUser·p0.9999: 32.683 ms/op
                 existUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255166
  mean =      3.760 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 383 
    [ 2.500,  5.000) = 245964 
    [ 5.000,  7.500) = 6954 
    [ 7.500, 10.000) = 1266 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     24.767 ms/op
     p(99.9900) =     31.275 ms/op
     p(99.9990) =     33.384 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 14.698 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.311 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.016 ms/op
Iteration   1: 4.333 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 26.730 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 4.081 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.697 ms/op
                 getUser·p0.999:  26.028 ms/op
                 getUser·p0.9999: 28.421 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   3: 3.934 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.134 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 30.376 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233406
  mean =      4.109 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 215661 
    [ 5.000,  7.500) = 13810 
    [ 7.500, 10.000) = 2943 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     29.644 ms/op
     p(99.9990) =     31.282 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 17.731 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.017 ms/op
Iteration   1: 4.738 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  29.308 ms/op
                 listUser·p0.9999: 32.293 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 4.648 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.709 ms/op
                 listUser·p0.999:  24.417 ms/op
                 listUser·p0.9999: 31.079 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   3: 4.770 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  19.247 ms/op
                 listUser·p0.9999: 30.077 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203479
  mean =      4.718 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 174049 
    [ 5.000,  7.500) = 24608 
    [ 7.500, 10.000) = 3785 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     25.216 ms/op
     p(99.9900) =     31.511 ms/op
     p(99.9990) =     32.797 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.862 ± 7.405  ops/ms
ClientPb.existUser                       thrpt       3   8.369 ± 3.330  ops/ms
ClientPb.getUser                         thrpt       3   7.993 ± 3.986  ops/ms
ClientPb.listUser                        thrpt       3   6.995 ± 2.699  ops/ms
ClientPb.createUser                       avgt       3   3.857 ± 1.051   ms/op
ClientPb.existUser                        avgt       3   3.957 ± 2.243   ms/op
ClientPb.getUser                          avgt       3   4.204 ± 1.124   ms/op
ClientPb.listUser                         avgt       3   4.861 ± 3.191   ms/op
ClientPb.createUser                     sample  237346   4.046 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.408           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.176           ms/op
ClientPb.existUser                      sample  255166   3.760 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.767           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.275           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.489           ms/op
ClientPb.getUser                        sample  233406   4.109 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.483           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.201           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.644           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  203479   4.718 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.056           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.216           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.511           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.932           ms/op
