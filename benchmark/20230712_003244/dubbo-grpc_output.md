# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ops/ms
# Warmup Iteration   2: 9.216 ops/ms
# Warmup Iteration   3: 9.863 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.188 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.172 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (10.118, 10.172, 10.209), stdev = 0.048
  CI (99.9%): [9.299, 11.044] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.825 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 11.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.861 ±(99.9%) 5.516 ops/ms [Average]
  (min, avg, max) = (10.683, 10.861, 11.210), stdev = 0.302
  CI (99.9%): [5.345, 16.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.495 ops/ms
# Warmup Iteration   2: 9.772 ops/ms
# Warmup Iteration   3: 10.186 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.241 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (10.204, 10.241, 10.312), stdev = 0.061
  CI (99.9%): [9.121, 11.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.264 ops/ms
# Warmup Iteration   2: 7.733 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.912 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (7.774, 7.912, 8.015), stdev = 0.124
  CI (99.9%): [5.645, 10.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.002 ms/op
Iteration   1: 3.090 ±(99.9%) 0.004 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.052 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.033, 3.052, 3.090), stdev = 0.033
  CI (99.9%): [2.452, 3.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.923 ±(99.9%) 0.002 ms/op
Iteration   2: 2.951 ±(99.9%) 0.004 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.923, 2.954, 2.989), stdev = 0.033
  CI (99.9%): [2.357, 3.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.002 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.036, 3.053, 3.074), stdev = 0.020
  CI (99.9%): [2.693, 3.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.016 ms/op
Iteration   1: 3.713 ±(99.9%) 0.014 ms/op
Iteration   2: 3.911 ±(99.9%) 0.039 ms/op
Iteration   3: 3.906 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.843 ±(99.9%) 2.058 ms/op [Average]
  (min, avg, max) = (3.713, 3.843, 3.911), stdev = 0.113
  CI (99.9%): [1.785, 5.902] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.349 ms/op
                 createUser·p0.9999: 14.712 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.799 ms/op
                 createUser·p0.9999: 21.971 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  12.889 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316984
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25842 
    [ 2.500,  5.000) = 289566 
    [ 5.000,  7.500) = 1090 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     21.231 ms/op
     p(99.9990) =     22.342 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
Iteration   1: 2.886 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  6.219 ms/op
                 existUser·p0.9999: 15.598 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   2: 2.845 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   3: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.267 ms/op
                 existUser·p0.999:  8.949 ms/op
                 existUser·p0.9999: 14.090 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334188
  mean =      2.872 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2704 
    [ 1.250,  2.500) = 34110 
    [ 2.500,  3.750) = 289145 
    [ 3.750,  5.000) = 7116 
    [ 5.000,  6.250) = 647 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     14.887 ms/op
     p(99.9990) =     15.772 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.402 ms/op
                 getUser·p0.9999: 16.343 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 14.079 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.889 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318083
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21092 
    [ 2.500,  5.000) = 295595 
    [ 5.000,  7.500) = 1095 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     26.352 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
Iteration   1: 3.776 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.658 ms/op
                 listUser·p0.9999: 16.898 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 3.969 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.318 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.783 ms/op
                 listUser·p0.9999: 18.530 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.692 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246721
  mean =      3.893 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3705 
    [ 2.500,  5.000) = 220554 
    [ 5.000,  7.500) = 21124 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     21.452 ms/op
     p(99.9990) =     23.873 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.172 ± 0.872  ops/ms
ClientGrpc.existUser                       thrpt       3  10.861 ± 5.516  ops/ms
ClientGrpc.getUser                         thrpt       3  10.241 ± 1.121  ops/ms
ClientGrpc.listUser                        thrpt       3   7.912 ± 2.267  ops/ms
ClientGrpc.createUser                       avgt       3   3.052 ± 0.601   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.597   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.360   ms/op
ClientGrpc.listUser                         avgt       3   3.843 ± 2.058   ms/op
ClientGrpc.createUser                     sample  316984   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.597           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.231           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  334188   2.872 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.456           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.887           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.794           ms/op
ClientGrpc.getUser                        sample  318083   3.017 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.365           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.352           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.672           ms/op
ClientGrpc.listUser                       sample  246721   3.893 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.318           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.452           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
