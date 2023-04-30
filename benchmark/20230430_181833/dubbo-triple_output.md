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
# Warmup Iteration   1: 2.462 ops/ms
# Warmup Iteration   2: 5.696 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 9.516 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.678 ±(99.9%) 4.663 ops/ms [Average]
  (min, avg, max) = (9.516, 9.678, 9.973), stdev = 0.256
  CI (99.9%): [5.015, 14.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ops/ms
# Warmup Iteration   2: 9.721 ops/ms
# Warmup Iteration   3: 9.999 ops/ms
Iteration   1: 10.300 ops/ms
Iteration   2: 10.071 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.207 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (10.071, 10.207, 10.300), stdev = 0.120
  CI (99.9%): [8.009, 12.405] (assumes normal distribution)


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
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 9.521 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 10.003 ops/ms
Iteration   3: 10.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.928 ±(99.9%) 6.251 ops/ms [Average]
  (min, avg, max) = (9.554, 9.928, 10.227), stdev = 0.343
  CI (99.9%): [3.677, 16.179] (assumes normal distribution)


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
# Warmup Iteration   1: 3.059 ops/ms
# Warmup Iteration   2: 7.577 ops/ms
# Warmup Iteration   3: 8.274 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.346 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.503 ±(99.9%) 2.542 ops/ms [Average]
  (min, avg, max) = (8.346, 8.503, 8.611), stdev = 0.139
  CI (99.9%): [5.961, 11.045] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.006 ms/op
Iteration   1: 3.137 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.006 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.137, 3.170, 3.229), stdev = 0.051
  CI (99.9%): [2.243, 4.097] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.261 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.026 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (2.976, 3.026, 3.059), stdev = 0.044
  CI (99.9%): [2.230, 3.822] (assumes normal distribution)


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
# Warmup Iteration   1: 7.398 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.261 ±(99.9%) 0.004 ms/op
Iteration   3: 3.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.169 ±(99.9%) 1.808 ms/op [Average]
  (min, avg, max) = (3.064, 3.169, 3.261), stdev = 0.099
  CI (99.9%): [1.362, 4.977] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.393 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.004 ms/op
Iteration   1: 3.670 ±(99.9%) 0.009 ms/op
Iteration   2: 3.683 ±(99.9%) 0.009 ms/op
Iteration   3: 3.777 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.710 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.670, 3.710, 3.777), stdev = 0.059
  CI (99.9%): [2.641, 4.778] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
Iteration   1: 3.146 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  19.045 ms/op
                 createUser·p0.9999: 20.900 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  11.266 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 25.851 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302186
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18643 
    [ 2.500,  5.000) = 278439 
    [ 5.000,  7.500) = 4295 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     17.453 ms/op
     p(99.9900) =     24.136 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.307 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 20.149 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  16.746 ms/op
                 existUser·p0.9999: 22.121 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307618
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15651 
    [ 2.500,  5.000) = 287337 
    [ 5.000,  7.500) = 3557 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     21.544 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.217 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.253 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  18.675 ms/op
                 getUser·p0.9999: 31.397 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   2: 3.170 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  19.699 ms/op
                 getUser·p0.9999: 23.492 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.428 ms/op
                 getUser·p0.9999: 18.612 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300128
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15083 
    [ 2.500,  5.000) = 277397 
    [ 5.000,  7.500) = 6573 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.076 ms/op
     p(99.9000) =     16.654 ms/op
     p(99.9900) =     28.851 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.513 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.013 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.610 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 20.195 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 15.892 ms/op
                 listUser·p1.00:   15.974 ms/op

Iteration   3: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255081
  mean =      3.763 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 246096 
    [ 5.000,  7.500) = 6954 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.531 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     20.798 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.678 ± 4.663  ops/ms
ClientPb.existUser                       thrpt       3  10.207 ± 2.198  ops/ms
ClientPb.getUser                         thrpt       3   9.928 ± 6.251  ops/ms
ClientPb.listUser                        thrpt       3   8.503 ± 2.542  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 0.927   ms/op
ClientPb.existUser                        avgt       3   3.026 ± 0.796   ms/op
ClientPb.getUser                          avgt       3   3.169 ± 1.808   ms/op
ClientPb.listUser                         avgt       3   3.710 ± 1.068   ms/op
ClientPb.createUser                     sample  302186   3.177 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.779           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.453           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.136           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  307618   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.713           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.544           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  300128   3.197 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.076           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.654           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.851           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.719           ms/op
ClientPb.listUser                       sample  255081   3.763 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.531           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.070           ms/op
