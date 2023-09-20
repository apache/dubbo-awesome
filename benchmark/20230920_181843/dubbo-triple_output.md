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
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.947 ops/ms
# Warmup Iteration   3: 8.715 ops/ms
Iteration   1: 9.232 ops/ms
Iteration   2: 9.339 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.415 ±(99.9%) 4.195 ops/ms [Average]
  (min, avg, max) = (9.232, 9.415, 9.673), stdev = 0.230
  CI (99.9%): [5.220, 13.610] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.331 ops/ms
# Warmup Iteration   2: 8.630 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 9.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.763 ±(99.9%) 3.180 ops/ms [Average]
  (min, avg, max) = (9.639, 9.763, 9.962), stdev = 0.174
  CI (99.9%): [6.583, 12.943] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 8.211 ops/ms
# Warmup Iteration   3: 9.270 ops/ms
Iteration   1: 9.173 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.342 ±(99.9%) 2.710 ops/ms [Average]
  (min, avg, max) = (9.173, 9.342, 9.452), stdev = 0.149
  CI (99.9%): [6.631, 12.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.000 ops/ms
# Warmup Iteration   2: 7.464 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.957 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (7.818, 7.957, 8.061), stdev = 0.125
  CI (99.9%): [5.678, 10.237] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.953 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.006 ms/op
Iteration   1: 3.335 ±(99.9%) 0.002 ms/op
Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
Iteration   3: 3.320 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.335 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.320, 3.335, 3.351), stdev = 0.015
  CI (99.9%): [3.053, 3.617] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.715 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.005 ms/op
Iteration   1: 3.295 ±(99.9%) 0.004 ms/op
Iteration   2: 3.260 ±(99.9%) 0.005 ms/op
Iteration   3: 3.264 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.273 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.260, 3.273, 3.295), stdev = 0.019
  CI (99.9%): [2.922, 3.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.317 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.001 ms/op
Iteration   1: 3.300 ±(99.9%) 0.002 ms/op
Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
Iteration   3: 3.246 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.313 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (3.246, 3.313, 3.392), stdev = 0.074
  CI (99.9%): [1.963, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 11.248 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.004 ms/op
Iteration   1: 3.963 ±(99.9%) 0.003 ms/op
Iteration   2: 3.949 ±(99.9%) 0.007 ms/op
Iteration   3: 3.965 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (3.949, 3.959, 3.965), stdev = 0.009
  CI (99.9%): [3.800, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.566 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
Iteration   1: 3.374 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  18.353 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.346 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.052 ms/op
                 createUser·p0.9999: 23.804 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287427
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14197 
    [ 2.500,  5.000) = 268343 
    [ 5.000,  7.500) = 3828 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     15.169 ms/op
     p(99.9900) =     23.438 ms/op
     p(99.9990) =     24.429 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 9.581 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
Iteration   1: 3.313 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 21.027 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  17.747 ms/op
                 existUser·p0.9999: 23.044 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  16.186 ms/op
                 existUser·p0.9999: 23.694 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293310
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14120 
    [ 2.500,  5.000) = 274668 
    [ 5.000,  7.500) = 3647 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.660 ms/op
     p(99.9000) =     15.691 ms/op
     p(99.9900) =     22.992 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 8.827 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.412 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  18.743 ms/op
                 getUser·p0.9999: 21.450 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  15.552 ms/op
                 getUser·p0.9999: 24.127 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.311 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  11.941 ms/op
                 getUser·p0.9999: 22.873 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287354
  mean =      3.339 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16690 
    [ 2.500,  5.000) = 263729 
    [ 5.000,  7.500) = 5491 
    [ 7.500, 10.000) = 645 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     25.215 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 9.336 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.011 ms/op
Iteration   1: 4.116 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.482 ms/op
                 listUser·p0.9999: 24.205 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.640 ms/op
                 listUser·p0.9999: 16.092 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 4.053 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.649 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236003
  mean =      4.066 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 228770 
    [ 5.000,  7.500) = 5549 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 395 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     22.230 ms/op
     p(99.9990) =     24.669 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.415 ± 4.195  ops/ms
ClientPb.existUser                       thrpt       3   9.763 ± 3.180  ops/ms
ClientPb.getUser                         thrpt       3   9.342 ± 2.710  ops/ms
ClientPb.listUser                        thrpt       3   7.957 ± 2.280  ops/ms
ClientPb.createUser                       avgt       3   3.335 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   3.273 ± 0.351   ms/op
ClientPb.getUser                          avgt       3   3.313 ± 1.350   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 0.159   ms/op
ClientPb.createUser                     sample  287427   3.340 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.041           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.169           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.438           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.838           ms/op
ClientPb.existUser                      sample  293310   3.271 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.660           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.691           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.992           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  287354   3.339 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.580           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.265           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.330           ms/op
ClientPb.listUser                       sample  236003   4.066 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.583           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
